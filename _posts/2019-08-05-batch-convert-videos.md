---
layout: post
title: ffmpeg
---

1. download ffmpeg (windows build) from official websites
2. unzip it to an arbitrary category
3. add bin to system variables as a new path
4. batch: 
>for %%a in ("*.mkv") do ffmpeg -i "%%a" -vcodec copy -acodec copy "newfiles\%%~na.mp4"
pause
5. create a new folder: ffmpeg.exe; newfiles (folder); bat file; videos
6. click the batch file

------
Actually,
Python and other softwares could realize the same work.


-----
Another thing I found today is that Excel can scrape data from online pages.
> Data-From web pages


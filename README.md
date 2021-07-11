# BD-Slim-Server-Row
Better Discord Slim Server Row.

A bunch of code I put together from various sources, and modified drastically.

You can customize the size, the spacing and the padding of the Server Row.


# Disable Discord Smooth Scrolling Bat file:

@echo off

FOR /F "delims=" %%i IN ('dir /b /ad-h /t:c /od') DO SET a=%%i

start Update.exe

start %a%\Discord.exe --disable-smooth-scrolling


Thanks to r/u/Holycraplol

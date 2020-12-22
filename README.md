@echo off
mode con lines=40 cols=100
chcp 65001 >nul
:again
cls
color 5
title Ddos MACHINE BY Dej Viś for YT
echo Pls Login
echo.
echo ██████╗ ███████╗     ██╗    ██╗   ██╗██╗██████╗ ███████╗ ██████╗ ███╗   ██╗
echo ██╔══██╗██╔════╝     ██║    ██║   ██║██║██╔══██╗██╔════╝██╔═══██╗████╗  ██║
echo ██║  ██║█████╗       ██║    ██║   ██║██║██║  ██║███████╗██║   ██║██╔██╗ ██║
echo ██║  ██║██╔══╝  ██   ██║    ╚██╗ ██╔╝██║██║  ██║╚════██║██║   ██║██║╚██╗██║
echo ██████╔╝███████╗╚█████╔╝     ╚████╔╝ ██║██████╔╝███████║╚██████╔╝██║ ╚████║
echo ╚═════╝ ╚══════╝ ╚════╝       ╚═══╝  ╚═╝╚═════╝ ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
echo.
set /p user=Enter Username:
echo.
set /p pass=Enter Pass:
if %user% == root if %pass% == root goto main                                                                   
echo Wrong Login, try again...
timeout 3 >nul
goto again
:main
cls
echo. Welcome %USERNAME%
echo ██████╗ ███████╗     ██╗    ██╗   ██╗██╗██████╗ ███████╗ ██████╗ ███╗   ██╗
echo ██╔══██╗██╔════╝     ██║    ██║   ██║██║██╔══██╗██╔════╝██╔═══██╗████╗  ██║
echo ██║  ██║█████╗       ██║    ██║   ██║██║██║  ██║███████╗██║   ██║██╔██╗ ██║
echo ██║  ██║██╔══╝  ██   ██║    ╚██╗ ██╔╝██║██║  ██║╚════██║██║   ██║██║╚██╗██║
echo ██████╔╝███████╗╚█████╔╝     ╚████╔╝ ██║██████╔╝███████║╚██████╔╝██║ ╚████║
echo ╚═════╝ ╚══════╝ ╚════╝       ╚═══╝  ╚═╝╚═════╝ ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
echo Welcome to Ddos MACHINE
echo 1 - gen 2 - google  
echo 3 - youtube
echo.
:mainlogo
set /p main=Choose your number:
if %main% == 1 goto gen
if %main% == 2 goto google
if %main% == 3 goto goto youtube
echo Wrong Number...
pause
timeout 2 >nul
:gen
start gen.bat
goto mainlogo
:google
start https://www.google.com/
goto mainlogo
:youtube
start https://www.youtube.com/
goto mainlogo

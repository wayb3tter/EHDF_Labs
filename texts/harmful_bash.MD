@echo off
:: vuln_demo.bat - LAB DEMO (harmless)
:: Demonstrates command injection by executing user input directly.

echo #### VULNERABLE BATCH DEMO ####
echo This script asks for a filename and runs: type %userinput%
echo You can append commands with & or && to demonstrate injection.
echo.

set /p userinput=Enter a filename to display (eg. notes.txt):

echo.
echo Running: type %userinput%
type %userinput%

echo.
echo DONE. Press any key to exit.
pause >nul

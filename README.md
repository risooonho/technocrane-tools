# Technocrane Tools
 Tools that help to emulate data packets or analyze incoming packets data
The binaries could be found in Release section of the repository.

<p align="left">
  <a href="https://github.com/technocranes/technocrane-tools/Projects"><img alt="GitHub Actions status" src="https://github.com/technocranes/technocrane-tools/workflows/Main%20workflow/badge.svg"></a>
</p>

## Data Display

 This is a tiny COM trace application that could help to see what data is receving on a specified com port.

Usage example from command line
datadisplay.exe -d COM1

## Data Generator

 This is a console application that could be used to stream generated or source file data packets.

Usage example to stream packets from *.cgi file
datagenerator.exe --open "D:\\Work\\Technocrane\\Result\\test-cgi.cgi" --timecode

## Sources

  There are VS 2013 project files to compile application for windows. Original applications has been made for Linux and to make them work on Windows I added open source analog libraries.

# Contact

Please post issues and feature requests to this [github repository issues section](https://github.com/technocranes/technocrane-unreal/issues)

# X Server Launcher Script

A simple interactive bash script that detects installed video cards and allows the user to choose a startup option for the X server interactively or via numbered input.

## Description

Detects installed video cards and allows the user to choose a startup option for the X server interactively or via numbered input.

## Version

1.0

## Author

Maksym Nazar  
Copyright (C) 2025–2026  
Created with the assistance of ChatGPT, and Grok.

## Installation

To install the script system-wide so you can run it simply by typing `startxx` from anywhere:

### Using curl
```bash
sudo curl -L -o /usr/local/bin/startxx https://raw.githubusercontent.com/Maxym-N/X-Server-Launcher-Script/main/startxx
sudo chmod +x /usr/local/bin/startxx
```

### Using wget
```bash
sudo wget -O /usr/local/bin/startxx https://raw.githubusercontent.com/Maxym-N/X-Server-Launcher-Script/main/startxx
sudo chmod +x /usr/local/bin/startxx
```

## Usage

After installation, run:

```bash
startxx
```

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see https://www.gnu.org/licenses/.

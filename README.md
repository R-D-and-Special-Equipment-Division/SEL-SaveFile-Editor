# SEL-SaveFile-Editor
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

 
Editor of the savefile created by the game Serial Experiments Lain.
Before proceeding, please make yourself knowledgeable of the license used by this Python program. 

-- How it works --

Three separate scripts are to be used, and have to remain in the same repository. 
The first script to be used it the script that converts the raw savefile into a JSON file.
The second script to be used is the main one, that will read the JSON file, and will print out a JSON file according to a file you have to create yourself. In short, you have to write a file, a .txt, separated by "," - that has all the chapters of the game you have completed. 

In conclusion, this serves as an editor of the savefile whereas your .txt file means you have completed each chapter appearing in this txt file, and thus, can edit the savefile. 


NEW VERSION WILL BE CONTINUED LATER

----

# SEL SaveFile Editor
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
Works partially

## Overview

The **SEL-SaveFile-Editor** is a set of scripts for editing and converting save files for the Serial Experiments Game (SEL) PSX, that can be played here: [Serial Experiments Lain PSX game](https://3d.laingame.net/#/).
This tool allow you to modify the save file data, convert save files to and from JSON format, and modify it all with these operations through a main script that orchestrates it all.

## Features

- **Save File Editing:** Edit the contents of SEL save files using `SSFE.py`.
- **Format Conversion:** Convert save files to JSON format and vice versa with `SSFE_JSON_Convert.py`.
- **Main Interface:** Use `SSFE_main.py` to access and utilize the editing and conversion functions in a unified script.
- **Command-Line Interface:** All functionalities are accessible via the command line.

## Installation

### Prerequisites

- **Python 3 and above** is required to run these scripts.
- Required Python libraries can be installed using: (will be added later, you can see them in the scripts here on GitHub)

  ```bash
  pip install -r requirements.txt

### Setup
  ```bash
git clone https://github.com/R-D-and-Special-Equipment-Division/SEL-SaveFile-Editor.git


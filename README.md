# Easy Moss

A Wrapper for MOSS to make submissions downloaded from Prairie Learn easy.

* You must download the shell script from Stanford's Moss project to use this program.
Adjust all values in moss.json according to how your homework directories are set up. Then, simply call "python3.10 easy-moss.py <directory of moss.json>".

## Issues/Notes:

Listed are the current issues with the code, along with notes on how to fix them.

### Zip files not accounted for

- Unzip before going through files, this will create a new file.
- -d might require all folders to be flattened (give different names to files w/ same name)
- -d might require all files to be in one folder. (shutil)
- chain maps: if not in child, looks in parent.

#### -----GLOBAL-----

starting path: Required in one or the other
comment: Not required
number of matches to show: Not required
language: Required in one or the other
max appearances: Not Required
assignment info: Required

#### -----WITHIN ASSIGNMENT-----

question name: Required
starting path: Required in one or the other
comment: Not required
number of matches to show: Not required
language: Required in one or the other
max appearances: Not Required
submitted files: Required
base files: Not Required
are submissions by directory: not required

### List Supported Langauges with JSON Schema

- Sort alphabetically
- Put in external file

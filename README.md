nokiasanitizer
==============

A tool for preparing MP3 files for use with non-POPM Nokia music players. Possibly compatible with other players too.

##Usage

* `-d` - Sanitize all MP3 files in current directory."
* `-f` - Sanitize <file>."
* `-h` - Display this help message."
* `-p` - Purge the music player database in your phone's directory.

##Requirements

`nokiasanitize` requires the `mid3v2` Python script bundled above.

`mid3v2` is also available in the `mid3v2` package (Ubuntu < 10.04)
or in the `python-mutagen` package (Ubuntu >= 10.04).

Of course, to run Python scripts, you would need to have Python installed
on your computer.
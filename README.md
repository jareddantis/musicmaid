musicmaid
==============

This is a set of scripts for working with MP3 files.

## What's included?

1. `nokiasanitizer` - A script for removing Popularimeter data from MP3 files, which might cause some old Nokia music players to malfunction.
2. `embedart` - A script for embedding album art in a file or a group of files, while preserving their original metadata.

## Requirements

`nokiasanitize` requires the `mid3v2` Python script.

`mid3v2` is also available in the `mid3v2` package (Ubuntu < 10.04)
or in the `python-mutagen` package (Ubuntu >= 10.04).
An alternative, `id3v2`, is available for Mac OS X through `brew install id3v2`.

`embedart` requires the above and also the `lame` MP3 command-line encoder.

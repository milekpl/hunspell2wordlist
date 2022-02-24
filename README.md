# hunspell2wordlist
A bash script to print all dictionary words from hunspell files

### Requirements

- awk
- hunspell
- bash

### Running

Simply run:

`LC_ALL=C ./hunspell2wordlist <dictionary>`

where `<dictionary>` stands for the filename (without any extension) of your hunspell dictionary file.

The script can be run also under Cygwin.

### Notes

* The script is very slow. Expect it to run for at least several hours for complex dictionaries.

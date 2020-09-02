# xkcdpwgen

Generates more memorable passwords.


### Usage
```
$ chmod u+x xkcdpwgen
$ ./xkcdpwgen -h
usage: xkcdpwgen [-h] [-w WORDS] [-c CAPS] [-n NUMBERS] [-s SYMBOLS]

Generate a secure, memorable password using the XKCD method

optional arguments:
  -h, --help            show this help message and exit
  -w WORDS, --words WORDS
                        include WORDS words in the password (default=4)
  -c CAPS, --caps CAPS  capitalize the first letter of CAPS random words (default=0)
  -n NUMBERS, --numbers NUMBERS
                        insert NUMBERS random numbers in the password (default=0)
  -s SYMBOLS, --symbols SYMBOLS
                        insert SYMBOLS random symbols in the password (default=0)

https://www.xkcd.com/936/
```


```
$ ./xkcdpwgen
gushesvisionarydrippingbidder

$ ./xkcdpwgen -w 2
kernedknockout

$ ./xkcdpwgen -w 3 -s 2 -n 1 -c 2
IncubationPouches;:inte2grally
```

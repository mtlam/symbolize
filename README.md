## symbolize

A small command-line script to generate a unicode symbols easily for copying.


#### Example usage:

```shell
user@computer: ./symbolize lambda pi gamma Gamma \'E accent-o umlaut-u carat-o hat-o tilde-n angstrom pm

λπγΓÉóüôôñÅ±
```

#### Help:

~~~~
usage: symbolize [-h] [-q] [-c] [-ex] [symbols [symbols ...]]

A simple utility for printing a variety of common unicode characters. For accents, can take either LaTeX style or attached to the letter with a hyphen. Some mathematical symbols are available.

positional arguments:
  symbols     symbol(s) to process

optional arguments:
  -h, --help  show this help message and exit
  -q          suppress warnings
  -c          copy output to clipboard (requires pyperclip)
  -ex         Show a list of examples
~~~~               
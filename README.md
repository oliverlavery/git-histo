# git-histo
Git command for displaying histograms of how recently source code was modified.

![Screenshot](/screenshot.png?raw=true "git histo screenshot")

# Installation

Python3 is required.

Currently you just need to:
```
pip3 install isodate
```

# Usage 

```
Usage: git-histo [options]

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -r, --recursive       recurse through sub-directories
  -s, --sort            sort output by most recent commits
  -m MAXAGE, --maxage=MAXAGE
                        maximum age of commits, in iso8601 format (e.g.:
                        'P1Y3M1W' for 1 year, 3 months, 1 week)
  -a AGE, --age=AGE     age range for histogram, in iso8601 format. Default is
                        1 year.
  -p PATH, --path=PATH  path to search, defaults to current directory
  -c, --csv             CSV format output
```

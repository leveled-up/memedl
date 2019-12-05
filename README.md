# memedl

Memedl is a very simple tool to download the latest images from a specific sub reddit.

**Installation:**

- Install Node.js version 12 or higher (https://nodejs.org/en/download/)
- Clone or download this repository
- Run `npm install` inside the program directory

**Usage:**

Example: `node memedl.js --limit 100 --sub historymemes`

```
Usage: node memedl.js [--help] [--dump] [--output OUTPATH] --limit NUMBER --sub SUBNAME
A tool to download the latest images from a sub reddit.

        --limit NUMBER, -n NUMBER       Download the latest NUMBER images from SUBNAME. (required)
        --sub SUBNAME, -s SUBNAME       The name of the sub reddit you want to download: /r/SUBNAME (required)
        --help, -h                      Print this help message and exit. (optional)
        --dump, -v                      Save downloaded HTML pages to target directory. (optional)
        --output OUTPATH, -o OUTPATH    Save downloaded files to a sub directory of OUTPATH named by the SUBNAME. (optional)
```

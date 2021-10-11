# xelatex
Private xelatex style files

This is simply a place for my private XeLaTeX style files.  The contain standard setup macros for the things I always do, plus a few utilities like `\q{}` for marginal queries, etc.  One day, I might even document these macros.

## Installation
Do a `git pull` to fetch these files to your disk.  Place the files in your "local texmf" directory.  To find out what your local texmf directory is, issue this command in a terminal:
```
 kpsewhich --var-value TEXMFHOME
```
Once your files are in the right place, rebuild your TeX indexes.  For Linux, the command is:
```
sudo mktexlsr
```
For other systems, try `sudo texhash` or similar.  Your TeXlive installation manager also has a button under Actions for doing this (`tlmgr`: "update filename database"; `tlshell`: "regenerate filename database").

That's all, folks!

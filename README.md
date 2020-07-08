# My Brew List

Since I'm setting up a new MacBook, here's my lists of things I typically install from 
beginning with `homebrew`. I'll try to keep this up to date.

# How I use it.

I do a simple `for` loop.

```
for i in `cat brew_list.txt` ; do
echo $i
brew install $i
done
```

# Requirements

Make sure you have `homebrew` installed. 


# Files
```
.
├── README.md
├── brew_casks.txt
└── brew_list.txt

0 directories, 3 files
```

Download All Firmwares
======================
A utility to download all (or specific sets of) Apple's iOS firmware using the [IPSW Downloads API](https://api.ipsw.me/)

![Download all the firmwares!](https://dl.dropboxusercontent.com/u/38032597/content/blogs/BsyVbxlCIAAiBtC.jpg)

Usage

```
$ ./allthefirmwares --help
Usage of ./allthefirmwares:
  -c	just check the integrity of the currently downloaded files
  -d string
    	the location to save/check IPSW files.
	 Can include templates e.g. {{.Identifier}} or {{.BuildID}} (default "./")
  -i string
    	only download for the specified device
  -r	redownload the file if it fails verification (w/ -c)
  -s	only download signed firmwares
```

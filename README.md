# Inkscape Extension pathpoints2dots

This repository contains an inkscape extension which puts elements on the nodes of a path.


## Requirements

- Inkscape 1.0
- Python 3.8


## Installation

Put the files
```
pathpoints2dots.inx
pathpoints2dots.py
```
into your user extensions directory. You will find the directory under `Edit -> Preferences -> System: User extensions`.


## Usage

- Select two elements. The first element represents the path, the second element represents the symbol.
- Choose the pathpoints2dots extension under `Extensions -> Render`.


## Hints

The symbols on the path are clones (`<use>` elements) linked to the original object. So you can change the
original object, and all the linked clones will update automatically.

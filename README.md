# Inkscape-Extension pathpoints2dots
This repository contains an inkscape-extensions which puts elements on the endpoints of a path.

## Requirements
- Inkscape 1.0
- Python 3.8

## Installation
Put the files
```
pathpoints2dots.inx
pathpoints2dots.py
```
into your extension-directory. You will find the directory under `Edit -> Settings -> System`.

## Usage
- Select to elements. The first element represents the path, the second element represents the symbol.
- Choose the pathpoints2dots extension under `Extensions -> Render`.

## Hints
The symbols on the path are use-elements linked to the original element. So you can change the
original Element and all the linked elements will be changed too.

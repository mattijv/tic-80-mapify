# TIC-80 Mapify

This is a Python (3) script that will read the data sections
of a [TIC-80](https://tic.computer/) .lua cart, extracts the
relevant data sections (MAP, TILES and PALETTE) and renders
a PNG file of the MAP.

## Install

```shell
git clone https://github.com/mattijv/tic-80-mapify
cd tic-80-mapify
pip3 install -r requirements.txt
```

## Usage

```shell
python3 mapify.py cart.lua
```

The script will output a file in the same folder with the name
`map.png`.

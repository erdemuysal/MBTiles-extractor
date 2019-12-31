
# MBTiles Extractor

### Usage

1) Save convert.py into the same folder as your .mbtiles file
2) Make sure python is installed
3) In terminal, cd into that folder
4) Run this:

```python
    python convert.py filename.mbtiles
```

5) If you prefer XYZ schema instead of TMS run this:

```python
    python convert.py filename.mbtiles XYZ
```

That's it! It should generate a folder called filename filled with PNGs that contain the data in the mbtiles archive.
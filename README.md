# rblx-cache-extractor
A quick and dirty cross-platform Python script that allows you to extract embedded PNGs, OGGs, MP3s, and KTX from Roblox binary cache files.

## Requirements
Python 3

## Usage
### macOS
``` console
./embedded-png-extract /Applications/testbin.app/Contents/MacOS/testbin /Users/noone/Desktop/CarvedImages
Wrote carved_1.png
Wrote carved_2.png
Wrote carved_3.png
Done! Total extracted: 3
```
### Windows
``` console
python embedded-png-extract C:\Users\noone\Desktop\testbin C:\Users\noone\Desktop\CarvedImages
Wrote carved_1.png
Wrote carved_2.png
Wrote carved_3.png
Done! Total extracted: 3
```

## Licence
MIT

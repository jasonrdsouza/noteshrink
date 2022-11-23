noteshrink
==========

Convert scans of handwritten notes to beautiful, compact PDFs

## Requirements

 - Python 2 or 3
 - NumPy 1.10 or later
 - SciPy
 - ImageMagick
 - Image module from PIL or Pillow
 - OpenCV

## Usage

Noteshrink:
```
./noteshrink.py IMAGE1 [IMAGE2 ...]

# example with params
./noteshrink.py -g -w -s 20 -v 30 -p 20 -o recipebook.pdf recipebook.jpg
```

Adaptive Threshold:
```
./adaptiveThreshold.py -i recipe.jpg
```

## References

- Original writeup: https://mzucker.github.io/2016/09/20/noteshrink.html
- Original noteshrink code: https://github.com/mzucker/noteshrink
- Original image thresholding code: https://github.com/pedrofrodenas/image-thresholding-OCR


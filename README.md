# Image Resize
Script to batch resize images through command line (cmd - Win x64)

# Requirements
Get a copy of ImageMagick : https://www.imagemagick.org/script/download.php#windows and install it for using `magick.exe`. For usage with Gimp get and download the latest Gimp : https://download.gimp.org/pub/gimp/v2.10/windows/ and resize with the Gimp GUI and export the file.

# Usage
With ImageMagick use : `magick.exe mogrify -resize AxB -path / input.ext output.ext` where AxB is the target resolution and input and output for batch conversion can be as such - `*.jpg` or `*.png`

# Image Resize
A script to batch resize images through the Windows command line (cmd)

# Requirements
Get a copy of ImageMagick : https://www.imagemagick.org/script/download.php#windows and install it for using `magick.exe` include the excecutable in your `PATH` in case the script doesn't work
 
# Usage
Do `magick.exe mogrify -resize AxB -path / input.ext output.ext` where (A, B) is the target resolution and input output for batch conversion can be any image format `*.png` `*.jpg` etc.

# Alternative
Alternatively get Gimp use it : https://download.gimp.org/pub/gimp/v2.10/windows/

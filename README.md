# AsciiArt
Converts images and videos to ascii characters and displays to terminal

usage: ascii.py image_name [OPTIONS]

optional arguments:
  -h, --help            show this help message and exit
  --size SIZE, -s SIZE  Set size which image is scaled down to
  --output OUTPUT, -o OUTPUT
                        Save ascii image to text file
  --strategy {filled-ascii,just-ascii,ascii-color}, -S {filled-ascii,just-ascii,ascii-color}
                        Set strategy to use for rendering
  --invert, -i          Invert image brightness
  --luminosity, -l      Set brightness mode to luminosity
  --average, -a         Set brightness mode to average
  --color, -c           Print in full color
  --video, -v           Set to video mode

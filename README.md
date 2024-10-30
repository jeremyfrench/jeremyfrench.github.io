# Jeremyfrench.github.io
github repository for building my [personal website](https://www.Jeremyfrench.co.uk)

Should build with Jekyll and automatically on push

Theme is a customised version of the [Hacker Theme](https://github.com/pages-themes/hacker)

## Converting images
To keep images small enough to inline use ImageMagick convert to a 1 bit per pixel monochrome image and then fix the colours

```
convert g.jpg -monochrome -negate -depth 1 -resize 50% -type bilevel -background none -define png:color-type=3 -define png:bit-depth=1 g.png
convert g.png  -background none -define png:color-type=3 -define png:bit-depth=1 g2.png
convert g2.png +level-colors "#151515","#b5e853" g3.png
```

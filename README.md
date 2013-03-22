# SoLaWiS graphics collection

## Software

- [Inkscape](http://inkscape.org/)
- [Scribus](http://scribus.net/)
- [Gimp](http://www.gimp.org/)
- [Krita](http://www.krita.org/)
- [ImageMagic](http://www.imagemagick.org)
- [LittleCMS](http://www.littlecms.com/)

## Colors

- Black:       `r0   g0   b0`   / `#000000` / `c0   m0   y0   k100`
- Gray:        `r77  g77  b77`  / `#4d4d4d` / `c0   m0   y0   k70`
- Light Green: `r82  g132 b28`  / `#52841c` / `c62  m0   y100 k36`
- Dark Green:  `r22  g83  b23`  / `#165317` / `c74  m0   y100 k66`

### ICC-Profiles

[eci_offset_2008.zip](http://www.eci.org/_media/downloads/icc_profiles_from_eci/eci_offset_2008.zip)

### Convert RGB JPGs to CMYK

If the JPG file already includes a profile you can convert it with the following
command:

    convert  rgb.jpg -profile /path/to/target/cmyk/profile.icc cmyk.jpg

otherwise you have to use an RGB profile:

    convert  rgb.jpg -profile /path/to/source/rgb/profile.icm -profile /path/to/target/cmyk/profile.icc cmyk.jpg

## License

[Creative Commons BY-NC-SA](http://creativecommons.org/licenses/by-nc-sa/3.0/de/)

# SoLaWiS graphics collection

## Software

- [Inkscape](http://inkscape.org/)
- [Scribus](http://scribus.net/)
- [Gimp](http://www.gimp.org/)
- [ImageMagic](http://www.imagemagick.org)
- [LittleCMS](http://www.littlecms.com/)
- [Krita](http://www.krita.org/)

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

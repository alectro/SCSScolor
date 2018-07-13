# SCSScolor
A SCSS starter to create harmonic color palettes based on color wheel schemes.

## HSLA
Hue: 0 to 360 degrees. **0** is **Red**, **120** is **Green**, **240** is **Blue**.
Saturation: 0 to 100 percent. **0** equals **total desaturation**, **100** is **fully saturated**.
Lightness: 0 to 100 percent. **0** equals **Black**, **100** equals **White**.
Alpha: 0 to 1. Fractions will output **rgba** colors while 1 will output **HEX**.

## How to
1. Open **scss/_setup.scss**.
2. Edit the values for **$hue**, **$saturation**, **$lightness**, **$alpha**.
3. Save and compile.

## Color Schemes

### Complementary
Complementary schemes are created by combining colors from opposite sides of the color wheel.
Colors are **180 degrees** separated in the color wheel.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-complimentary.png)

### Split Complementary
Split complementary schemes use colors that are on either side of the hue opposite your base hue.
Colors are **150 degrees** separated in the color wheel in each direction.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-split-complimentary.png)

### Analogous
Analogous color schemes are the next easiest to create. Analogous schemes are created by using three colors that are next to each other on the 12-spoke color wheel.
Colors are **30 degrees** separated in the color wheel in each direction.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-analogous.png)

### Triadic
Triadic schemes are made up of hues equally spaced around the 12-spoke color wheel.
Colors are **120 degrees** separated in the color wheel in each direction.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-triadic.png)

### Tetradic Rectangle
Four colors arranged into two complementary color pairs.
A set of complimentary colors plus their **60 degrees** separated in the color wheel.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-tetradic-60.png)

### Tetradic Square
Four colors arranged into two complementary color pairs.
A set of complimentary colors plus their **90 degrees** separated in the color wheel.

![](https://github.com/alectro/Sketch-Color-Harmony/blob/master/docs/images/color-harmony-tetradic-90.png)

## Source
[Basic color schemes - Introduction to Color Theory](http://www.tigercolor.com/color-lab/color-theory/color-theory-intro.htm)

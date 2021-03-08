# HTML & CSS : COLOR  
- There are three common ways to specify colors  in
which you can indicate your choice of colors (plus extra
ways made available in CSS3) .
1. Color terminology 
2. Contrast, and ensuring
3. Background colors 

### Foreground Color 
 - The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways: 
1. rgb values
2. hex codes 
3. color names 

### background-color 
- You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names. 
 - If you do not specify a
background color, then the
background is transparent. 
- By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the <body> element. 

### Understanding Color  
- Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker .
- Computer monitors are made
up of thousands of tiny squares
called pixels .
- Color picking tools are available
in image editing programs like
Photoshop and GIMP. You can
see the RGB values specified
next to the radio buttons that
say R, G, B . 

1. RGB Values 
-  Values for red, green, and blue
are expressed as numbers
between 0 and 255 . 

2. Hex Codes
-  Hex values represent values
for red, green, and blue in
hexadecimal code.
3. Color Names
- Colors are represented by
predefined names. However,
they are very limited in number. 
4. Hue 
- Hue is near to the colloquial idea
of color. Technically speaking
however, a color can also have
saturation and brightness as
well as hue. 
5. Saturation 
- Saturation refers to the amount
of gray in a color. At maximum
saturation, there would be no
gray in the color. At minimum
saturation, the color would be
mostly gray. 
6. Brightness 
-  Brightness (or "value") refers
to how much black is in a color.
At maximum brightness, there
would be no black in the color.
At minimum brightness, the
color would be very dark. 
 
 ### Contrast 
  - When picking foreground and background
colors, it is important to ensure that there is
enough contrast for the text to be legible.
1. Low Contrast 
- Text is harder to read when
there is low contrast between
background and foreground
colors.
- A lack of contrast is particularly
a problem for those with
visual impairments and color
blindness.
-  It also affects those with poor
monitors and sunlight on their
screens (which is increasingly
common as people use handheld
devices outdoors). 
2. High Contrast 
- Text is easier to read when
there is higher contrast between
background and foreground
colors.
- If you want people to read a lot
of text on your page, however,
then too much contrast can
make it harder to read, too 
3. Medium Contrast 
- For long spans of text, reducing
the contrast a little bit improves
readability. 
-  You can reduce contrast by
using dark gray text on a white
background or an off-white text
on a dark background. 

## CSS 3: Opacity
 - CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).
- The CSS3 rgba property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. This value is
known as an alpha value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).
- Because some browsers will
not recognize RGBA colors, you
can offer a fallback so that they
display a solid color. If there are
two rules that apply to the same
element, the latter of the two
will take priority. To create the
fallback, you can specify a color
as a hex code, color name or
RGB value, followed by the rule
that specifies an RGBA value. If
the browser understands RGBA
colors it will use that rule. If it
doesn't, it will use the RGB value.

### CSS 3: HSL Colors 
- CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values. 
1. hue
- Hue is the colloquial idea of
color. In HSL colors, hue is often
represented as a color circle
where the angle represents the
color, although it may also be
shown as a slider with values
from 0 to 360. 
2. saturation
- Saturation is the amount of
gray in a color. Saturation is
represented as a percentage.
100% is full saturation and 0%
is a shade of gray.
3. ligh tness
- Lightness is the amount of
white (lightness) or black
(darkness) in a color. Lightness
is represented as a percentage.
0% lightness is black, 100%
lightness is white, and 50%
lightness is normal. Lightness
is sometimes referred to as
luminosity. 

### CSS 3: HSL & HSLA

- The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for:
1. hue
- This is expressed as an angle
(between 0 and 360 degrees).
2. saturation
- This is expressed as a
percentage.
3. lightness
- This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
- The hsla color property allows
you to specify color properties
using hue, saturation, and
lightness as above, and adds a
fourth value which represents
transparency
4. alpha
- This is expressed as a
number between 0 and 1.0.
For example, 0.5 represents
50% transparency, and 0.75
represents 75% transparency 

# Learn Color Design

Color is essential to the overall aesthetics and usability of your websites.

With 16.8 million colors to choose from, the possibilities are endless. Understanding how to select and use colors properly 
and effectively can impact the quality as well as how users comprehend and use your website.

Before selecting and applying color to your projects, it’s essential to gain an understanding of:

## Which colors pair well with others
## What color schemes are available to produce effective designs
## Which emotions each color evokes and communicates
## How contrast plays a vital role
## What color combinations you should avoid

# The Color Wheel
If you’ve taken an art class, it’s likely that you’ve been introduced to the color wheel. This is a tool
used by artists and designers to visualize the relationship between colors.

It’s comprised of three color groups: primary, secondary and tertiary.

Primary colors are comprised of red, blue and yellow. These are equidistant to each other on the wheel, forming a triangle. 
They are also the basis for all other colors on the wheel.

Secondary colors are created by mixing two primary colors, forming green, orange and purple.

The third and final group of colors are considered to be tertiary and are formed when mixing a secondary and primary. 
These usually result in a two-word name, such as:

Red-orange (Vermillion)
Yellow-orange (Amber)
Yellow-green (Chartreuse)
Blue-green (Teal)
Blue-purple (Violet)
Red-purple (Magenta)

# The Color Wheel and HSLA
There are a few different options for setting colors in CSS that we covered in Learn CSS: Color. Take a look at the code below to refresh yourself on the different ways of setting color in CSS.


h1 {
    color: Yellow; /*Keyword */
}
h2 {
    color: #8FBC8F; /* Hex Code */
}
h3 {
    color: rgb(23, 45, 23); /* RGB*/
}
p {
    color: hsla(34, 100%, 50%, 0.1); /* HSLA*/
}
When thinking like a designer, # HSLA is the preferred syntax for setting colors. Why?

The CSS color keywords only give us a few options.
Hex Codes and RGB values cannot be intuitively adjusted. For example, you get feedback on your design that 
one color needs to be a little brighter, that does not translate to intuitive changes within Hexadecimal codes or RGB values.
HSLA is the most semantic system of setting colors with CSS.
Let’s review what each value means:

The “pure” color is set with the Hue. This is expressed as the angle in degrees around the color wheel.
Saturation refers to the intensity or purity of that hue. Colors with full saturation (100%) are the color itself, colors
with no saturation (0%) are completely grayscale.
Lightness refers to the lightness of the color. 0% is black, 100% is white.
A, or alpha, refers to the opacity. 0% is fully transparent, 100% is fully opaque.
Using values that have semantic meaning gives the designer more direct control over the color scheme, and more direct 
ability to manage contrast and create related color schemes.



# Read 05

## HTML Ch 5 (94-125)
**Images for your site**
- When choosing your images you will want something that will make your site engaging. When looking for pictures, it's good to use stock images. Once you have your images, you can store them directly on your site. It's good practice to have a seperate folder for images only.

You should place your image before a paragraph, inside the start of a paragraph, or in the middle of a paragraph. Images can be aligned horizontally left, right, and center. Images can also be aligned vertically top, middle, bottom.

- ```<img>``` is the element to add an image.
- ```width="600"``` and ```height="600"``` is the way to adjust the width and/or height of the image.
- JPEG is best for photographs, GIF is best for illustrations, logos, and flat colors

**Three rules for creating images**
1. Save images in the right format
1. Save images at the right size
1. Measure images in pixels

**Figure and Figure Caption**
- ```<figure>``` This element contains images and their caption so that the two are associated. You can have more than one image inside this tag but they will share the same caption.
- ```<figcaption>``` This allows authors to add a caption to an image.

### Keywords
- **Vector images** Images that are typically created in Adobe Illustrator. Scalable Vector Graphics (SVG) is a new format to display vector images.
- **Animated GIFs** GIFs show an animated picture that show several frames to create the animation.
- **Transparency** If you want your image to have transparency, you will want to save it as a transparent gif or a png.

## HTML CH 11 (246-263)
There are three options for using color. RGB values ```rgb(100.100.90)```, hex codes ```#ee3e80```, and color names ```DarkBlue```. 

When desiging your webpage, you want to think about contrast and opacity. It will change your look and feel of the site. A high contrasted background and foreground will make your page more legible. Avoid low contrast because it will be hard on your eyes.

CSS3 has a new way to specify colors (HSL and HSLA) using hue, saturation, and lightness. There is also the alpha which is expressed as a number between 0 and 1.0. Old browser do not recognize HSL and HSLA.

## HTML Ch 12 (264-299)
There are 3 kinds of main typeface fonts. Serif has extra little details. This is a more traditional font for print. Sans-serif have a cleaner design. It's great for lower resolution as it's more clear to read. Monospace is a fixed-width font where it's the same width. This is more common for code. An few extra fonts are cursive and fantasy.

**Weight** ```font-weight```
- light
- medium
- bold
- black

**Style** ```font-style```
- Normal
- *Italic*
- Oblique

**Stretch**
- Condensed
- Regular
- Extended

**Alignment**
- ```text-align```
    - left
    - right
    - center
    - justify
- ```vertical-align```
    - baseline
    - sub
    - super
    - top
    - text-top
    - middle
    - bottom
    - text-bottom

**There are multiple ways to use fonts** (HTML & CSS, Duckett pg 271, 272.)
1. **font-family** CSS used to specify the typeface
1. **font-face** CSS specifies where a font can be downloaded
    - ```font-family: 'ChunkFiveRegular':```
    - ```src: url('fonts/chunkfive.eot');```
1. **service-based font-face** Commercial services give users access to a wide range of fonts using ```@font-face```.
1. **images** You can create graphics that have text
1. **SIFR** the font is embedded into a Flash movie, and JavaScript replaces specified HTML text with a flash version of it.
1. **CUFON** uses JavaScript to create either an SVG or VML version of the text.

- **uppercase and lowercase** ```text-transform```
    - uppercase
    - lowercase
    - capitalize
- **underline and strike**```text-decoration```
    - none
    - underline
    - overline
    - line-through
    - blink
- **leading** ```line-height```
- **letter and word spacing** ```letter-spacing && word-spacing```
- **indenting text** ```text-indent```
- **drop shadow** ```text-shadow```
- **first letter or line** ```:first-letter || :first-line```
- **styling links** ```:link && :visited```
- **responding to users** ```:hover && :active && :focus```

[<== Back](https://simoneodegard.github.io/reading-notes/)
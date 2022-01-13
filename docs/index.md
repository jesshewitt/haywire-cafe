
## Overview
Haywire Café is a long-form generative art project designed by Jess Hewitt for Art Blocks. The combination of bold colors, distorted patterns, and dramatic shadows create a surreal, nostalgic vibe.  

![Test Mint 5](./images/test5.png)
![Test Mint 29](./images/test29.png)
![Test Mint 49](./images/test49.png)

## Inspiration
This series is inspired by classic mind-bending mid century cartoons by the likes of Chuck Jones, Maurice Noble, and Dr. Seuss. These cartoons shaped my sense of style with their exaggerated perspective, smart humor, and breaking of the fourth wall.

![Duck Dodgers](./images/inspiration/9c8087b79ac0946d9e678c36021ac64b.png)
![Duck Dodgers](./images/inspiration/bceee32a3de89184613aa226334a32ec--warner-brothers-warner-bros.jpg)
![Road Runner](./images/inspiration/mauricenoblebackground.jpg) 
![The Dot and the Line](./images/inspiration/The_dot_and_the_line.jpg) 
![Duck Dodgers](./images/inspiration/tumblr_08d3548ae6d7ba5541effe68d9e427f4_674a518c_540.jpg)
![The Phantom Tollbooth](./images/inspiration/tumblr_oxf2keO01U1rsovmko1_r1_1280.jpg)

## Process
My creative process often involves an element of discovery and intuitive curation. I've co-written a generative art app that I sometimes use to find that beginning direction. I'll randomize its settings and look for interesting output, which I will then develop and refine.  

Haywire Café was conceived in this way, and then replicated in standalone form and fine-tuned.  

The process of generating these works is described below. The steps are seemingly simple, but the magic happens in the pattern mixing and in the order of operations.  

You'll notice that it looks quite different before the palette is applied!

### Generate a distorted background pattern  

The pattern can be one of bubbles, checkers, circle, dots, grid, rings or stripes and is controlled by the `Pattern` feature. The distortion is affected by the `Pattern Rotation` and `Pattern Skew` features.

![Step 1](./images/process/1-pattern.png)

### Generate some curl noise  

The curl noise creates the loopy, bandy foreground forms. It's controlled by the `Loop Scale` feature (smaller is more noodly) as well as a few hidden variables.

![Step 2](./images/process/2-curlnoise.png)

### Mix the two together  

When the two are combined, the curl noise develops a hard edge and outline which will become more visible later. This process also creates the appearance of dramatic shadows after the palette is applied.

![Step 3](./images/process/3-mix.png)

### Add some post processing  

Technically, this is pre-processing...scanlines and an inverted vignette are applied before the palette instead of at the end.

![Step 4](./images/process/4-scanlinesvignette.png)

### Apply a palette  

One of 21 palettes is applied, controlled by the `Palette` feature. 

![Step 5](./images/process/5-palette.png)

### Apply dithering  

Bayer 8x8 dithering is applied to create an interesting regular yet grainy look. Rarely, dust speckles are also applied, controlled by the `Dusty` feature.

![Step 6](./images/process/6-dither.png)

## 
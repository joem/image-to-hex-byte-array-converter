# Image To Hex Byte Array Converter

This is a fork of [Andrew Lowndes's Arduboy Image Converter (hosted)](http://www.andrewlowndes.co.uk/blog/graphics/arduboy-image-converter) ([github](https://github.com/andrewlowndes/Arduboy.js/tree/master/image_converter)) (note: his converter was part of his [Arduboy.js](https://github.com/andrewlowndes/Arduboy.js) project). This fork has a few changes to make it less specific to Arduboy and more useful to the AVML project (and hopefully other projects too).

You can convert an image (jpg/gif/png) into a hex byte array, ready for rendering in the Arduboy. Note: no images are uploaded, they are only converted locally in your browser.

# Getting Started

(insert instructions and link for the hosted version here)

Clone the repo onto a local web server and open 'index.html' in a browser to run the converter.

# TODOs

- Figure out how to remove the whole Arduboy.js as a requirement
- Set the preview screen size to 136x96
  - Let user define size of preview screen
  - Have a radio button for arduboy, avml, and custom where they can input their own?
- Let user define a size to scale image to, instead of only fit/fill/no-scaling
- Add it to my github
  - Can I host it via github pages or whatever?



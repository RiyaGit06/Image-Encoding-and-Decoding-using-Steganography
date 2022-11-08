# Image Veiling 

The project enables users to veil images by encoding them into a subset of pixels in another image's least significant bit positions. Without losing any information, the encoded image may then be decoded and restored.

## Encoding 

Two images are used as input for the encoding. The first image is the one we want to utilise to conceal the other.

The second image is the one we wish to disguise and camouflage in the first.

The initial picture used for concealing must meet the criterion that its pixel count is at least twice that of the image we want to hide.

The end result of the encoding is a picture that, on the surface, shouldn't seem very different from the original image, but the pixel information of the image that we wish to conceal is substituted for the least significant bits of a subset of pixels.

## Decoding

An image that has another image encoded inside it serves as the input for decoding.

The picture that was concealed and encoded in another image is identical to the output image that has been decoded.

## Getting Started
For encoding an image, provide two images: one that is to concealed, and other that will hide it in.
Command: python encode.py

For decoding an image, provide the encoded image as input.
Command: python decode.py
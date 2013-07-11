FontCreator
===========

Example swing app for someone needing font generation for arduino libraries

The default font file created right now is in the format i need it to be but you can modify for your own library.

Currently the code is for taking a char pixels left-> right for each row and then dividing them into bytes and writing to the font.
All bytes are reversed before writing as it is easier to read in arduino code.

The IL9225 lcd has a rectangle fill mode which I use to output each character as a rectangle bitmap hence the format.

Also I only use mono-spaced fonts for my project so you will need to modify the code if you use a font which is not mono-spaced.

I may add more functionality if someone requires but my requirement from this is already complete.

Feel free to CTRL-C,CTRL-V to use as you see fit.

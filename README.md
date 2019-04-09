# HaskRiptLig

A font mashup to be used in code editors and shell, displaying a script typeface for the bold-italic font style (à la Operator Mono).

The Regular, Bold, and Italic face styles are taken from [Hasklug](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hasklig#why-hasklug-and-not-hasklig), the Powerline/Font-Awesome/Devicons UTF-8 patch of [Hasklig](https://github.com/i-tu/Hasklig) by NerdFonts. The Bold Italic face is also from Hasklug, but with the roman characters patched mostly from [Script12](https://www.myfontsfree.com/134618/script12pitchbt.htm) modified for better monospace behavior and some specific adjustments/substitutions.

Unlike similar mashups I've seen, this one allows you to get 'normal' Italic typeface from the primary font (Hasklig) by using just the 'Italic' face. The Bold Italic face was chosen to receive the cursive/script patch, as this results in fewer instances where the cursive script is appearing much more frequently than may be desired.

I have my themes set up so the different faces are tied to very specific things - 
Bold - Type, Class or Typeclass names
Italic - Functions, as well as object properties/methods
Bold Italic (Cursive) - variables and parameters - this is intuitive to me because the handwritten letter or name for a variable feels like a variable name in mathematical/technical writing, or a written name in a form.

Being based on NerdFont means it can be used for Powerline and instances where unicode/emoji are desired.

And of course, with the original ancestor being Hasklig, you get all the great ligatures for arrows and all the Haskell infix operators.

<img src="Capture.JPG" alt="drawing" width="80%"/>

## Install

Download or clone this repository and install the fonts on your system.

In your editor of choice set the font to `HaskRiptLig`.  Also, ensure that the current theme and syntax highlighting utilize italic, or better yet italic and bold-italic.

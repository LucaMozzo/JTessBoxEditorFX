## JTessBoxEditorFX

This project is a fork of the original JTessBoxEditorFX v1.0.1
I will add improvements and fixes based on my needs, however you're more than welcome to suggest your own.

A box editor and trainer for Tesseract OCR, providing editing of box data of both Tesseract 2.0x and 3.0x formats and full automation of Tesseract training. It can read images of common image formats, including multi-page TIFF.
jTessBoxEditorFX is jTessBoxEditor rewritten in JavaFX to address the current issue of rendering complex scripts existing in Java Swing. The program requires Java Runtime Environment 8u40 or later.

JTessBoxEditorFX is released and distributed under the [Apache License, v2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Features
- Capable of rendering complex scripts
- Tesseract training executable 3.05dev
- Full box editor
- Automatic training

## Improvements
- ![Improvement Type](https://img.shields.io/badge/improvement-fix-yellow.svg?style=flat-square) Prompt to save changes in box editor discarded the changes regardless of user input
- ![Improvement Type](https://img.shields.io/badge/improvement-feature-green.svg?style=flat-square) When opening an image with no .box file in the box editor, it now asks if you want it to be automatically generated
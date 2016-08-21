# FolderGallery
Extremely simple gallery webpage for a folder of images

## Installation

* For your web server of choice, make sure PHP works properly
* Make sure PHP index pages are understood by your webserver
* Under your webroot in any folder, place your images (JPG, PNG, or any format if you change the code)
* Place all the files in this repository in the same folder as the images
* Go in yourserver.com/some_folder_with_images

## Motivation

I googled around for a gallery tool that was short enough to read through in a few minutes without any external dependencies (excluding jquery). Most of them were overly engineering massive web apps with bells and whistles. Frustrated, I figured the only way is to spend a couple of hours coding my own.

This gallery works as follows:

* The PHP index is executed
* The PHP file finds all image files in the same directory as the PHP file
* The PHP file loads page.html and adds the array of found images in the javascript code by smacking it right in
* The modified page.html is served by PHP echo
* Javascript changes the image on page load and previous / next button presses

## License

The MIT License (MIT)
Copyright (c) 2016 Jesse Kaukonen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



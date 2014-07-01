# _Project_

_FrameScrub is a plugin that mimics the iPhoto album/event mouseover functionality for the web._

## Project Setup

_Setup is pretty easy..._ 

1. _Download or clone the project._
2. _Include the project in your code. Make sure you have jQuery included also. It is in the project files or you can include the latest from Google._
```
<script src="js/jquery.1.11.0.min.js"></script>
<script src="js/frameScrub.min.js"></script>
```
_Target an element like so..._
```
$('#element').frameScrub({options});
```
_Here are the options..._

| Option  | What it do! | Possible Values          |
|------------- | ------------- | -----------------|
|`defaultImage`  | Takes the 'id' attribute of an image. On page load and mouseOut, the defaultImage will be what is displayed inside the frameScrub.  | _"Element Id" : String_|
|`verticalAlignment`  | Obviously, this will align the images vertically inside the frameScrub container. Align to the top, middle, or bottom. The default is top.  | _"top|middle|bottom": String_|
|`showTitles`  | If you'd like to show titles of your images, you can do that. Just pass in the "ID" of the element you want to house the titles. Make sure your images have titles on them.  | _"Element Id": String_|
|`frameWidth`  | If you want to specify a width for your images, pass in this option. If you don't, the images will stretch to fit the container. Either way, the height will be calculated to preserve the image's aspect ratio. Also, if you don't pass any width, the frameScrub is responsive to widths  | _"width": String_|

## What's Next
I wanted to release this and see if it gains any traction. Here is what is on my docket for improvements...

-_Mobile friendliness very soon_-

I am anxious to hear if people use it and want to see it improved. Also I welcome any bug reports.

## License

The MIT License (MIT)

_Copyright (c) 2014 Mike Cross_

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

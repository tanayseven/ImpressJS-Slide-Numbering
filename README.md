Impress JS Slide Numbering Plugin
=================================

This is a very simple plugin which can be copied and pasted into your Impress.JS presentation and then used directly to display the slide numbers and navigate slides using numbers on the keyboard.

**Caution**

This project is a very quick and dirty hack, it can be very buggy and done in a completely bad way.


HOW TO USE IT
---------------

Just copy the ```impress-slide-num.js``` file and the ```impress-slide-num.css``` files into your project include the files into your presentation document and do the following in your JavaScript:

```
<script src="js/impress.js"></script>
<script src="js/impress-slide-num.js"></script>
<script>
  var obj = impress();
  obj.init();
  initSlideNo(obj);
</script>
```


Motivation behind this:
-----------------------

This plugin was developed for my personal use and is based on a presentation tool (or a JavaScript library) called Impress.JS by [Bartek Szopka](https://github.com/bartaz).

It is a very dirty and a quick hack so you are most welcome to contribute, by cleaning the code, fixing bugs and adding new features.

LICENSE (MIT):
--------------

Copyright (c) 2016 Tanay PrabhuDesai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

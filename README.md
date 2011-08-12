rebase.css
==========

A combination of YUI's reset.css, base.css and my own CSS rules.

Usage
-----

To use rebase.css just include it in between the `<head>` tags
of your site before any other stylsheet includes.

**Example:**

```html
<head>
    <title>Site Title</title>
    
    <link rel="stylesheet" type="text/css" href="/css/rebase-min.css" />
    <link rel="stylesheet" type="text/css" href="/css/style.css" />
</head>
```


Modifying
---------

When modifying rebase.css it is recommended you make changes to the uncompressed
file first, then recompressing it after your changes are made and using the
compressed version on your web page.

First, download [YUI Compressor](http://yuilibrary.com/downloads/#yuicompressor)
and extract the contents.  Next, navigate to the `build` directory within the
extracted folder and run the following to compress rebase.css:
 
```bash
java -jar yuicompressor-2.4.6.jar -v -o /path/to/rebase-min.css /path/to/rebase.css
```

**NOTE:** You will need the [Java JDK](http://java.com/en/download/index.jsp) or
[OpenJDK](http://openjdk.java.net/) to run the YUI Compressor.

-----

**Copyright (c) 2011 Chris Kankewicz <Chris@ChrisKankiewicz.com>**

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

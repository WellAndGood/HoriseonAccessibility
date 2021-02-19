# Horiseon - Accessibility Project

The following is a webpage of HoriSEOn, subjected to a variety of accessibility measures, such as:

* Ran accessibility test through: https://wave.webaim.org/report#/https://f34rth3r34p3r.github.io/HoriseonAccessibility/ and determined that there was low contrast in the `<aside>` element. Changed color of `"benefits"` div to #0072bb, darkening it to increase contrast ratio. 
* Added accessibility links to top of page, invisible to sighted visiters but accessible to keyboard-only users and screen-readers.
* Collaped and consolidated multiple CSS selectors into more concise terms; updated `<div>` ids accordingly.
* Adding alt-text for all large or meaningful images.
* Adding empty alt-text brackets `alt=""` for small icons to prevent the screen-reader from reading it and to avoid confusing the person using it.
* Changing `<div>` elements to more semantic and human/SEO-friendly tags, such as `<nav>`, `<footer>`, `<section>`, and `<aside>`.



# File Architecture

File name | Function
------------ | -------------
index.html | HTML
assets/style/style.css | CSS stylesheet
assets/images | stock images in webpage
<pre>

</pre>
# Website Appearance 
Once loaded, the website should look like this:  
[Appearance Upon Deployment](assets/images/screenshot.png)

This website is available at the following URL:   https://github.com/F34rTh3R34p3r/HoriseonAccessibility/  


# Contributor(s)
Daniel Pisani (F34rTh3R34p3r)
Received helpful advice from Anastasia Sorkin.

# MIT License

Copyright (c) 2021 Daniel Pisani (F34rTh3R34p3r) 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
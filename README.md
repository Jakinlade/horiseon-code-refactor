# Horiseon-code-refactor

### Code repository: 
https://github.com/Jakinlade/horiseon-code-refactor 

### Deployed application: 
https://jakinlade.github.io/horiseon-code-refactor/

<br>

## Description

For this project, I was provided with existing HTML and CSS code for a digital marketing companies website. However, the codebase didn't meet current accessibility standards and had poor search engine optimisation.

In refactoring the codebase, I made the following changes:
- Added semantic HMTL elements where appropriate.
- Reorganised the code to give it a more logical overall structure, such as ensuring heading attributes are in a sequential order.
- Changed the title element to be clear and concise.
- added accessible alt attributes for image and icon elements.

<br>

## Website Screenshot

![screenshot of website](./assets/images/screencapture-file-C-Users-compa-bootcamp-horiseon-code-refactor-index-html-2022-11-22-19_46_11.png)

<br>

## Code Examples


- Adjusted HTML to include semantic tags in the header and nav.
```html
 <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```

- Consolidated CSS tags to reduce repetition in the code.
```css
.services {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.services img {
    max-height: 200px;
}

.services h2  {
    margin-bottom: 20px;
    font-size: 36px;
}
```
<br> 

## Technologies used

![HTML badge](https://img.shields.io/badge/Language-HTML-green)

![CSS badge](https://img.shields.io/badge/Language-CSS-blue)

<br>

## License

MIT License

Copyright (c) 2022 Jakinlade

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


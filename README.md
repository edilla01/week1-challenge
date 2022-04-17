# Horiseon Code Refactor for Accessibility

## Description

The good folks at Horiseon tasked me to refactor their homepage to include enhancements for accessibility and best practices. I updated the starter code to include semantic HTML and add features to enable screen reading technology. I also refactored code to remove redundencies and make it more efficient.

-I changed the file structure so that the index.html file was at the highest level. 
-I replaced <div> elements with semantic HTML elements such as <header>, <footer>, <section>, <article>, and <nav> where appropriate.
-I added meta information to the head 
-I added <alt> attributes to pictures for acecssibility purposes. 
-I combined CSS for elements in the content and benefits classes to decrease the amount of code needed
-I added font families and font color to the universal selector and removed those properties from later selectors to reduce repetitiveness
-I added comments and made sure indentation was uniform. 
-I changed the background color of the benefits section to increase the contrast for readability. 
-I changed the order of the CSS file so that declarations for similar elements were near eachother 

## Installation

You can view the production website at https://edilla01.github.io/week1-challenge/


## Usage

To use the website, navigate to the previously mentioned URL and verify it looks like the screenshot below.
![alt text](assets/images/screenshot.png)

## Credits

Thank you to Github user @Xandromus for providing the starter code. 

## License

MIT License

Copyright (c) [2022] [Eliza Dillaway]

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

## Tests

Test 1: Verify content is aligned properly 
    - Load website and scroll down page, making sure all content is still visible
    - Change width of broswer window and scroll, making sure all content is still visible

Test 2: Verify links are functioning
    -In the navigation bar on the top right, click each link and verify it takes you to the correct section

Test 3: Verify website meets accessibility standards
    -Download a screenreading software and open website and close your eyes. Verify that purpose of website and layout is comprehendable 



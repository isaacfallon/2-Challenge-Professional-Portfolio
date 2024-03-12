# 2-Challenge-Professional-Portfolio

## Description

This project is a personal porfolio webpage to host information about myself and my web development projects.

- My motivation to complete this project was to ensure that I would have a live location to house information about myself and my projects.
- Building this project now gives me a way to showcase my work in an interesting way for potential employers and connections to see.
- Previously, my digital footprint was quite minimal, so this project solives the problem of not having work online to be reviewed easily.
- Completing this project taught me several design tricks to accomodate text and graphics without breaking the overall layout of the site. Specifically, I learned some new flexbox commands like 'flex-basis' and 'flex-grow' to ensure my content fit in the correct areas - especially when the page window changed to accomodate smaller devices.

### Screenshots of deployed application at different screen resolutions

#### No media query applied (ideal for standard computer screens):

![Screenshot showing completed webpage for the week 2 portfolio page challenge in full resolution view.](./assets/images/IF_PortfolioScreenshot_FullResolution.png)

#### Media query applied when the viewport is less than 1450px (ideal for tablet screens):

![Screenshot showing completed webpage for the week 2 portfolio page challenge when the viewport is less than 1450px.](./assets/images/IF_PortfolioScreenshot_MaxWidth-1450px.png)

#### Media query applied when the viewport is less than 800px (ideal for phone screens):

![Screenshot showing completed webpage for the week 2 portfolio page challenge when the viewport is less than 800px.](./assets/images/IF_PortfolioScreenshot_MaxWidth-800px.png)

## Installation

N/A

## Usage

### Usage Method 1: Access the website via GitHub Pages

If you want to simply access the page easily and without hassle, [visit the working GitHub Pages link here](https://isaacfallon.github.io/2-Challenge-Professional-Portfolio/) or by accessing the full link below:

https://isaacfallon.github.io/2-Challenge-Professional-Portfolio/

### Usage Method 2: Clone the project locally

Alternatively, you can clone the repository and run the project locally by following these steps:

1. Ensure Git is installed on your computer and/or download the latest version.
   [View this git install guide if you need help.](https://github.com/git-guides/install-git/)
2. Clone the [repository](https://github.com/isaacfallon/2-Challenge-Professional-Portfolio) by pressing the green 'code' button and select either HTTPS or SSH depending on your preferences.
3. Open your command line of choice and enter the following code:

   ```md
   git clone [HTTPS or SSH key copied here]
   ```

4. Navigate to the cloned folder and access the website by either opening the index.html file in your browser of choice or opening the codebase in your code editor of choice and opening the index.html file in a live window.

## Credits

### Code sourced

My codebase uses two CSS flex properties sourced from external locations.

- The first is the use of 'flex-basis' on line 98 of my styles.css. The purpose of using flex basis was to ensure that the .std-content-box-heading class filled out more space so the subheading could fit on one line. Specifically, this line makes sure that the class takes up 50% of the initial main size as a flex item.

I sourced this idea for using this code from an mdn web docs page linked here:
https://developer.mozilla.org/en-US/docs/Web/CSS/flex-basis

- The second is the use of 'flex-grow' on line 141 and 170 of my styles.css. The purpose of the grow factor is to expand the image within the parent div container to completley fill the space. By setting the height to '0' in the line above, the image fills the div container completley, even if the viewport is changed unexpectedly.

I sourced this code from a Stack Overflow answer linked here:
https://stackoverflow.com/questions/74477930/how-to-build-a-figure-with-a-fixed-height-and-an-img-and-figcaption-that-flex-to

### Images/Graphics sourced

The secondary projects use a placeholder image sourced from Wikipedia here:
https://en.m.wikipedia.org/wiki/File:Comingsoon.png

According to the Wikipedia licencing listed:

This file is made available under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [CC0 1.0 Universal Public Domain Dedication.](https://creativecommons.org/publicdomain/zero/1.0/deed.en)
The person who associated a work with this deed has dedicated the work to the public domain by waiving all of their rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission."

## License

MIT License

Copyright (c) 2024 isaacfallon

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

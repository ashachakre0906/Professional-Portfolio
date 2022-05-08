## Name of the project
Professional Portfolio
## The Challenge
Creating a web application(My professional portfolio) from scratch!
We don't have enough web applications to showcase at this point, using placeholder images and names.
## User Story
```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```
## Acceptance Criteria
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```
## Links  
[Github URL](https://github.com/ashachakre0906/Professional-Portfolio)<br>
[Live URL](https://ashachakre0906.github.io/Professional-Portfolio/)<br>

## Built with
- Semantic HTML5 markup
- CSS

## What I learned
- How to write code from scratch.
- Advanced CSS which includes Media queries,Flexbox,Reponsive design,CSS positioning,Psuedo Selectors,Psuedo-elements,CSS variables.

***Some HTML code which I'm proud of***
- Declaring CSS variable globally inside the :root selector so that I can reuse throughout the document in CSS styling sheets.
```
:root {
--secondarybackground-color:dimgrey;
--primarybackgroundcolor:rgb(145, 109, 115);
--navheader:whitesmoke;
--boxshadow: 0 3px 5px rgba(227, 184, 184, 0.1);
--fontfamily: "Trirong", serif;
--paracolor:cornsilk;
--textshadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;
--hovershadow:0 0 2px 2px #8b8eaf , inset 0 0 5px 5px #8b8eaf;
}
```
- Media query for max-width: 576px
```
@media screen and (max-width: 576px){
.nav-bar li a{
  font-size:0.8em;
}
```
- Psuedo selector used and provided margin which creates the gap between the anchor links 
for each section.
```
.projectlinks a:not(:last-child){
margin-right:10px;
}
```
### Useful resources
- [w3schools](https://w3schools.com)
- [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Advanced_styling_effects)
-[CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Github Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings)

## Author
- Linkedin - [@ashachakre](https://www.linkedin.com/in/ashachakre/)

## License
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.

Copyright (c) [2022] [Asha Chakre]

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


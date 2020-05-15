# Responsive Web Design

1. `*, *::before, *::after { box-sizing: inherit; } html { box-sizing: border-box; }` to ensure a consistent look-and-feel of all elements.
2. Using percentages for 'widths', avoid setting 'height', and using 'max-width'.
3. BEM, Block Element Modifier for CSS clarity and less need for nested CSS: `<div class="card"><p class="card__p"></p></div>`
4. '.btn { display: inline-block; text-decoration: none; border-radius: 100px }', '.btn:hover, .btn:focus { opacity: .75 }
5. `<div class="container"><div class="row"><div class="col"><div class="col"><div class="col"></div></div></div></div>`, `.row { display:flex; }`, and block__element--modifier.
6. `.col + col { margin-left: 30px; }`
7. Avoid descendants, give everything a class instead.
8. `justify-content: space-between;`, `align-self: flex-start`
9. Responsive Images: `img { max-width:100 }`
10. [Semantic Web (HTML)] <https://www.w3schools.com/html/img_sem_elements.gif>
11. `flex-grow: 1; flex-shrink: 1;` or `width: 100%`
12. 'min()', 'max()', and 'clamp()'. 'width: max(600px, 70%)' using the smallest of the values. 'width: max(100px, 20%, 50vh)'. 'width: clamp(200px, 50%, 20rem)' => smallest, ideal, max. Use 'clamp()' for flexible font-sizes, for example 'font-size: clamp(2rem, 5vw, 5rem)'.
13. Media-queries: '@media () {}'
14. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
15. 'height', using 'min-height: 660px;', 'display: flex;', 'align-items: center;'.
16. Responsive Web Design - Summary: Websites are responsive before we write any CSS; When our layouts run into issues, we're at fault; Usually, a desktop-first approach is the issue; Writing mobile-first CSS tends to be the easier way to approach it as well, even if you only have a desktop layout to base things off of; Flexbox is flexible :-) ; Grid layout is another choice, and both work well together;  

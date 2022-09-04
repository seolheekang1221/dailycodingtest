.button {
    padding: 0.5rem; // space between the text and the edges of my button
    border-radius: 5px; //corner
}


// Navbar Responsive

@media (min-width: 850px) {
    nav {
        max-width: 1200px;
        margin: 0 auto;
    }
    nav li:first-child {
        flex-basis: auto;
        text-align: left;
        margin-right: auto;
    }
}

.gradient {
    background: linear-gradient(90deg, rgba(255, 23, 228, 1) 0%, rgba(134, 251, 251, 1) 100%);
    height: 2px;
}

.projects ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-flow: row wrap;
    justify-content: flex-start;
    gap: 1rem;
}

//Grid(Layout)
1. display:grid
    1)grid-template-row
    2)gird-template-columns

2. Gap between Block Elements(no needed margin)
3. overlap


//Flexbox(Alignmnet)
1. For responsive web page, page element
2. display:flex in Container
    1)flex-direction : column
    2)flex: row

.main-menu li {
    display: inline-block;
}

// Block Element
1. block element in block element
div p ul ol li dl dt dd h1~h6
pre noscript table hr form
blockquote address fieldset

2. inline element in block element
inline element: span, img

3. some block elements can't include some block elements
<address>, <h1>~<h6>, <p>

4. Block element is 100% width.

*padding :  in
 margin : out


// Inline Element
a span img input strong samp b em u i select

1. right, left (0)
2. width, height (x) 
(but, input, textarea, select, img -> width, height (0))
3. inline element can only include inline element
4. If children element width is more bigger than width, it will move on the next line.



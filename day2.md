<CSS Concept>

- text-decoration: none;
- display: block;
=> By default, the a element is an inline element.

- nav li:first-child {
    flex-basis: 100%;
    flex: 0 0 100%; 
    //flex-glow, flex-shrink, flex-basis
    border: 1px solid red;
}

- nav a:hover {
    color: var(--magenta);
}

- flex-box -> all about parents and children
=> flex-basis only in flex-box


<HTML Concept>

- aria-hidden="true"  on the icon and then
make sure the words are either there for everyone depending on the kind of icon that you are using or add that class
-> - nav [class*="fa-"]

# CSS 
## General

One must understand something like the definition below ([source](https://www.w3.org/TR/css-flexbox-1/#visibility-collapse)):
```
@media (min-width: 60em) {
  /* [two column layout only when enough room](https://www.w3.org/TR/css3-mediaqueries/#width) (relative to default text size) */
  div { display: flex; }
  #main {
    flex: 1;         /* [Main takes up all remaining space](https://www.w3.org/TR/css-flexbox-1/#flexibility) */
    order: 1;        /* [Place it after (to the right of) the navigation](https://www.w3.org/TR/css-flexbox-1/#order-property) */
    min-width: 12em; /* Optimize main content area sizing */
  }
}
/* menu items use flex layout so that visibility:collapse will work */
nav > ul > li {
  display: flex;
  flex-flow: column;
}
/* dynamically collapse submenus when not targetted */
nav > ul > li:not(:target):not(:hover) > ul {
  visibility: collapse;
}

<div>
  <article id="main">
    Interesting Stuff to Read
  </article>
  <nav>
    <ul>
      <li id="nav-about"><a href="#nav-about">About</a>
        …
      <li id="nav-projects"><a href="#nav-projects">Projects</a>
        <ul>
          <li><a href="…">Art</a>
          <li><a href="…">Architecture</a>
          <li><a href="…">Music</a>
        </ul>
      <li id="nav-interact"><a href="#nav-interact">Interact</a>
        …
    </ul>
  </nav>
</div>
<footer>
```


## Layouts
- Mozilla Forum with "Assessment wanteds": https://discourse.mozilla.org/t/assessment-wanted-for-structuring-a-page-of-content-mdns/122098 -- an opportunity for finding assignments


# HTML
- [HTML5 specific tags](https://www.geeksforgeeks.org/html5-new-tags/) including `<article>` and `<nav>`
- [Custom tags](https://matthewjamestaylor.com/custom-tags) 
- `rem` vs. `em` - [an article](https://blog.logrocket.com/using-em-vs-rem-css/) - one is relative to the root font size of the page, the other to the current font



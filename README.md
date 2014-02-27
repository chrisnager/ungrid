![ungrid logo](favicon.png "ungrid logo")

# ungrid

the simplest responsive css grid

---

ungrid is a responsive, (`display:`)`table`-based css grid system. the entire `ungrid.css` file is 97 bytes minified.

```css
@media (min-width: 30em) {
    .row { width: 100%; display: table; table-layout: fixed; }
    .col { display: table-cell; }
}
```

![ungrid grid system](ungrid-screenshot.png "ungrid grid system")

---

&copy; 2014 Chris Nager

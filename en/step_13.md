<h2 class="c-project-heading--task">Style your nav bar</h2>

You can style your nav bar using CSS.

--- task ---

Open the style sheet file `styles.css` and add these CSS rules.

- The first one changes the colours.
- The second one changes:
  - `list-style-type` to remove bullet points
  - `display` to make the list horizontal (across) instead of vertical (down)
  - `margin-right` and `margin-left` to space them out.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: css
filename: styles.css
line_numbers: false
line_number_start: 12
line_highlights:
---
nav ul {
  background-color: tomato;
}

nav ul li {
  list-style-type: none;
  display: inline;
  margin-right: 10px;
  margin-left: 10px;
}

--- /code ---
</div>

--- task ---

**Run** your code to see your nav bar. 

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

- `10px` means ten pixels.

- Notice how you used more than one selector? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags.

</div>
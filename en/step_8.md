<h2 class="c-project-heading--task">Add images</h2>

For `<h1>` headings, you use the `h1` selector.

--- task ---

Open `index.html` then add an image.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 12
line_highlights: 21
---
	  <main>
	    
	    <h1>Bird Conservation</h1>
	    
	    <p>
	      <em>This website</em> is about <strong>bird conservation</strong>. 
	    </p>

      <img src="barn-owl.jpg" alt="A barn owl" width="200px" />

--- /code ---
</div>

--- task ---

**Run** your code.

- Your heading text should be orange now, with the paragraph in purple as before. 

--- /task ---

--- task ---

Experiment with different numbers to see what the `width="200px"` attribute does.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

- Notice that the `<img>` tag is different from the other tags you've used so far — there is no closing `</img>` tag. Instead, this tag is **self-closing**: it has `/>` at the end. This is because there is no 'start' and 'end' to an image element like there is for text on the page. 

The tag contains **attributes** with extra information:
- The `src` attribute tells the browser what file to use for the picture. 
- The `alt` attribute is a short description that the browser will show if it cannot display the picture. 'alt' is short for 'alternative'. This text also helps people using a screen reader to know what the picture is.
- The `width` attribute tells the browser how wide to make the picture. `100px` means one hundred **pixels**, which are the tiny dots that make up what you're seeing on your screen. If you don't include this attribute, the picture will be displayed in its original size.
</div>
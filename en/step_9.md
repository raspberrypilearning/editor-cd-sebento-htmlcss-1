<h2 class="c-project-heading--task">Change the image</h2>

Open the image gallery and to see the image files available for you to use in your project.

Note the name of one of the image files.

--- task ---

Change the text `barn-owl.jpg` so that it exactly matches the name of the image file you've chosen.

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

- Your image should change. 

--- /task ---

--- task ---

Add new alt text to correctly describe the new image.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

- You changed the attribute called `src`, which tells the browser which file to display.

- The value you type for an attribute must have quotation marks `""` around it.
</div>
CSS Pseudo-Elements Example
This HTML document showcases the use of CSS pseudo-elements to style specific parts of the content.

Files
index.html: The main HTML file.
style.css: The CSS file containing the styling for pseudo-elements.
Description
The HTML file (index.html) contains various heading (<h1>, <h2>, <h3>, <h4>, <h5>, <h6>) and paragraph (<p>) elements. The CSS file (style.css) is linked to the HTML file and utilizes CSS pseudo-elements to style specific parts of the content.

CSS Pseudo-Elements Used
::first-line: Styles the first line of the paragraph (<p>).
::first-letter: Styles the first letter of the paragraph (<p>).
::after: Inserts content after the paragraph (<p>).
::before: Inserts content before the paragraph (<p>) and specific headings (<h1>).
::first-line (h2): Styles the first line of the <h2> element.
Usage
Open index.html in a web browser to view the styled webpage.
CSS Styling
css
Copy code
p::first-line {
    color: rebeccapurple;
    font-size: larger;
    font-family: Arial, Helvetica, sans-serif;
    font-style: italic;
    font-weight: bolder;
}

p::first-letter {
    color: red;
}

p::after {
    content: " Ending Here";
}

p::before {
    content: " Selection";
}

h1::before {
    content: "Aqua Marmaid";
}

h2::first-line {
    color: burlywood;
}

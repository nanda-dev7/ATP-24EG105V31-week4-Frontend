


// Frontend Basics Notes
1. HTML Basics

HTML (HyperText Markup Language) is a markup language, not a programming language.
It is used to structure content on a webpage.

Creating a Basic HTML Document

You can quickly generate an HTML template in editors like VS Code:

Type html:5 and press Enter

Or press Shift + ! then Enter

Both generate a basic HTML structure.

Basic HTML Structure
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
HTML Main Parts

1. Head Section
Contains metadata about the page.

Important meta tags:

charset → Defines character encoding

<meta charset="UTF-8">

viewport → Makes the page responsive on mobile devices

<meta name="viewport" content="width=device-width, initial-scale=1.0">

2. Body Section
Contains the actual visible content like:

text

images

links

headings

buttons

2. HTML Styling Behavior

HTML itself does not focus on presentation (design).
Browsers apply default styles.

User Agent Stylesheet

Every browser has a default stylesheet called a User Agent Stylesheet.

Because of this:

Different browsers may display elements slightly differently.

Example:

Unvisited link → Blue

Visited link → Purple (sometimes appears red depending on styles)

3. HTML Tags

Most HTML elements have:

Opening Tag

Content

Closing Tag

Example:

<p>This is a paragraph</p>
4. Block vs Inline Elements
Block Level Elements

Always start on a new line

Take the full width

Examples:

<h1> – <h6>

<p>

<div>

Example:

<h1>Hello</h1>
<h2>World</h2>

They appear on separate lines.

Inline Elements

Take only the space they need

Stay in the same line

Examples:

<img>

<a>

<span>

Example:

<a href="#">Link</a>
<img src="image.png">
CSS Basics

CSS (Cascading Style Sheets) is used to style HTML elements.

Example:

h1 {
  color: red;
}

Here:

h1 → Selector

color: red → CSS rule

CSS Box Model

In CSS, every HTML element is considered as a box.

Structure of Box Model

Content

Padding

Border

Margin

Margin
 └ Border
    └ Padding
       └ Content
Padding

Padding = space between content and border

Example:

div {
  padding: 10px;
}

Padding has four sides:

top

right

bottom

left

Margin

Margin = space outside the border

Example:

div {
  margin: 20px;
}

Margin also has four sides.

Aligning Elements

Elements can be aligned:

Left

Right

Center

Example (center alignment):

div {
  margin: auto;
  width: 200px;
}

margin: auto helps center block elements horizontally.

💡 Important Tip

You can convert inline elements to block using CSS:

display: block;

Example:

a {
  display: block;
}

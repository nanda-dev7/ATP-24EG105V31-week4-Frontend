Frontend Basics Notes

This repository contains beginner-friendly notes on HTML and CSS fundamentals. The goal is to help anyone quickly understand the core concepts of frontend development.

1. HTML Basics

HTML (HyperText Markup Language) is a markup language used to structure web pages.
It is not a programming language. Instead, it defines the structure and organization of content on a webpage.

Using HTML, developers can add:

Text

Headings

Images

Links

Buttons

Other webpage elements

2. Creating an HTML Document

Most modern code editors provide shortcuts that automatically generate a basic HTML document structure. This allows developers to start building webpages quickly without writing the entire structure manually.

3. Structure of an HTML Document

A standard HTML document mainly contains two important sections.

3.1 Head Section

The head section contains metadata about the webpage. Metadata helps browsers understand how to display the page.

Common metadata includes:

Character encoding (charset) which defines how text characters are stored and displayed.

Viewport settings which help make the webpage responsive on different screen sizes such as mobile devices and tablets.

3.2 Body Section

The body section contains the actual visible content of the webpage.

Examples of content placed in the body include:

Text

Headings

Images

Links

Buttons

Other webpage components

Everything that appears on the webpage is placed inside the body.

4. HTML and Presentation

HTML focuses on structure rather than visual design.

Web browsers apply their own default styling to HTML elements using something called a User Agent Stylesheet.

Because each browser has its own default stylesheet, the appearance of elements may vary slightly between browsers.

For example:

Unvisited links usually appear blue.

Visited links may appear purple or another color depending on the browser.

5. HTML Tags

Most HTML elements consist of three parts:

Opening tag

Content inside the element

Closing tag

If an element contains data or content, it usually requires a closing tag.

6. Block-Level Elements

Block-level elements have the following characteristics:

They start on a new line.

They occupy the full available width.

They push the next element to the next line.

Because of this behavior, heading elements automatically appear on a new line.

7. Inline Elements

Inline elements behave differently from block-level elements.

Their characteristics include:

They occupy only the space required by their content.

They do not start on a new line.

Multiple inline elements can appear on the same line.

Images and links are common examples of inline elements.

8. CSS Basics

CSS (Cascading Style Sheets) is used to style and design HTML elements.

While HTML creates the structure of a webpage, CSS is responsible for controlling the appearance and layout.

CSS works using rules, and each rule targets specific HTML elements using a selector.

9. CSS Box Model

In CSS, every HTML element is treated as a box.

Understanding the Box Model is very important because it controls spacing and layout on a webpage.

The box model consists of four main parts:

Content

Padding

Border

Margin

9.1 Content

Content is the actual information inside the element, such as text, images, or other elements.

9.2 Padding

Padding is the space between the content and the border.

Padding exists on four sides:

Top

Right

Bottom

Left

Padding increases the internal spacing of the element.

9.3 Border

The border is the boundary that surrounds the padding and content of the element.

It visually separates the element from other elements on the webpage.

9.4 Margin

Margin is the space outside the border.

Margin is used to create spacing between different elements on a webpage.

Like padding, margin also exists on four sides:

Top

Right

Bottom

Left

10. Element Alignment

Elements on a webpage can be aligned in different ways.

Common alignment options include:

Left alignment

Right alignment

Center alignment

Margins are often used to help center elements on the page.

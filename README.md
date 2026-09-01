# Day 01: Introduction to HTML & Basic Elements

## What I Learned Today
Today was Day 1 of my becoming a full stack developer journey. 
Started with the basics of Web Development.

### Topics Covered
1.  **What is HTML?**  
    HTML = HyperText Markup Language.  
    It is the skeleton/structure of every website.
3.  **Heading Tags**  
    `<h1>` to `<h6>` - Used for titles and subtitles. h1 is biggest.
4.  **Paragraph Tag**  
    `<p>` - Used to write paragraphs and normal text.

### Code I Wrote
Created a simple webpage with heading and paragraph.
File: `index.html`

### Key Takeaway
Every website starts with HTML. Without structure, CSS and JS are useless.
# Day 02: Link Tag & Image Tag

## What I Learned Today
Learned how to connect pages and add media to a website.

### Topics Covered
1.  **Anchor Tag `<a>`**  
    Used to create clickable links.  
    Syntax: `<a href="https://example.com">Click Me</a>`
    `href` = where the link goes
2.  **Image Tag `<img>`**  
    Used to display images on a webpage.  
    Syntax: `<img src="image.jpg" alt="description">`
    `src` = image source/path
    `alt` = text shown if image doesn't load. Important for SEO.

### Code I Wrote
Added a link to freeCodeCamp and added an image to my Day 1 page.
File: `day 02.html`

### Key Takeaway
Links connect the web. Images make websites beautiful. 
Both tags are self-closing and most used in HTML.
# Day 03: HTML Sections, Figure & Attributes

## What I Learned
Learned how to structure a webpage semantically.

### Topics Covered
1.  **HTML Boilerplate**  
    The basic structure every HTML page starts with:  
    `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
2.  **Section Tag `<section>`**  
    Used to group related content. Makes code organized.
3.  **Figure & Figcaption `<figure> <figcaption>`**  
    Used to display images with a caption.  
    Example: `<figure><img><figcaption>Text</figcaption></figure>`
4.  **Attributes**  
    Extra info added to tags. Format: `name="value"`  
    Examples: `href`, `src`, `alt`, `charset`

### Key Takeaway
Boilerplate gives structure. Sections + Figure make it semantic. 
Attributes give tags meaning.

# Day 4: HTML Fundamentals

This is Day 4 of my learning journey.  
Today we covered core HTML building blocks: elements, tags, and how content is structured on a webpage.

## Topics Covered

### 1. Tags vs Elements
Understanding the difference is key in HTML.

**Tags**  
Labels wrapped in angle brackets `<>` that mark the start and end of an element.  
Example: `<p>`, `</p>`, `<img>`

**Elements**  
The complete package consisting of the opening tag, the content inside, and the closing tag.  
Example: `<p>This is a paragraph</p>`

### 2. Types of Elements

**Empty Elements**  
Elements that do not need a closing tag. They only have an opening tag.  
Examples: `<img>`, `<br>`, `<hr>`, `<input>`

**Inline Elements**  
Do not start on a new line. Only take up as much width as their content requires.  
Examples: `<a>`, `<strong>`, `<em>`, `<span>`, `<img>`

**Block Elements**  
Always start on a new line and occupy the full width available within their parent.  
Examples: `<p>`, `<h1> - <h6>`, `<div>`, `<ul>`, `<li>`

### 3. Text Formatting Tags

**`<strong>` tag**  
Renders text in bold to signal importance.  
Example: `<strong>Important Notice</strong>`

**`<em>` tag**  
Renders text in italic for emphasis.  
Example: `<em>This is emphasized</em>`

### 4. Structural Tags

**`<div>` tag**  
A generic block-level container used to group elements together for styling with CSS later.  
Example: `<div>All content goes here</div>`

### 5. Comments
You can add notes to your code that browsers will completely ignore.  
Comments are helpful for documentation and remembering code.

Syntax:
```html
<!-- This is a comment -->

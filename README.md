# Lab 4.1: Practice with CSS Selectors and Effects

**Course:** Foundations of Web Development
**Student:** Ramon
**Chapter:** 4

## Objective
Write a standalone set of CSS rules practicing the selector types and properties introduced in Chapters 3 and 4, without wiring them into a full page yet.

## File
- `ch4lab.css` — contains all five CSS rules for this lab

## Rules Included

| # | Selector | Type | What It Does |
|---|----------|------|--------------|
| 1 | `footer` | HTML element selector | Light blue background, Arial font, dark blue text, 10px padding, and a narrow dashed dark blue border |
| 2 | `#notice` | id selector | 80% width, centered on the page using `margin-left: auto` and `margin-right: auto` |
| 3 | `.dotted-headline` | class selector | Headline text with a dotted line underneath, created with `border-bottom` |
| 4 | `h1` | HTML element selector | Text drop shadow (`text-shadow`), 50% transparent background using `rgba()`, sans-serif font at 4em |
| 5 | `#section` | id selector | Small red Arial font, white background, 80% width, and a drop shadow (`box-shadow`) |

## Concepts Practiced
- Element, id, and class selectors
- Color values (hex, color names, and `rgba()` for transparency)
- Font properties (`font-family`, `font-size`)
- Box model properties (`padding`, `border`, `margin`, `width`)
- Centering a block element with automatic margins
- Visual effects with `text-shadow` and `box-shadow`

## How to Use
To apply these styles to a page, link the stylesheet in the `<head>` of an HTML file:

    <link rel="stylesheet" href="ch4lab.css">

    # Lab 4.2: Design a Web Page About You

**Course:** Foundations of Web Development
**Student:** Ramon
**Chapter:** 4

## Objective
Design a standalone web page about myself, styled with the CSS from Lab 4.1, that includes an optimized photo with a caption and an HTML5 progress element.

## Files
- `yourlastname.html` — the "About Me" page
- `ch4lab.css` — stylesheet from Lab 4.1, updated with a `body` rule for background and text color plus styles for the figure and progress bar
- `images/yourlastname.jpg` — photo resized to about 400px wide and compressed for the web

## Requirements Checklist
- [x] Page linked to `ch4lab.css` using `<link rel="stylesheet">`
- [x] Background and text color set by the stylesheet (`body` rule)
- [x] Name inside an `<h1>` tag
- [x] Paragraphs describing hobbies and activities
- [x] Optimized photo in a `<figure>` with a `<figcaption>`
- [x] Image stored in a child `images` folder
- [x] `<progress>` element showing class standing (Senior, `value="95" max="100"`)
- [x] `<footer>` with copyright info using the `&copy;` entity

## Selectors from Lab 4.1 Used on This Page
| Selector | Where It's Used |
|----------|-----------------|
| `h1` | My name at the top of the page |
| `#notice` | Wrapper that centers the page content at 80% width |
| `.dotted-headline` | Section headings for hobbies and class standing |
| `#section` | Box around the class standing progress bar |
| `footer` | Copyright footer |

Then use the selectors in your markup, for example:

    <h2 class="dotted-headline">My Headline</h2>
    <div id="notice">Notice text</div>
    <div id="section">Section content</div>

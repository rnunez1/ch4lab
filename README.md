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

Then use the selectors in your markup, for example:

    <h2 class="dotted-headline">My Headline</h2>
    <div id="notice">Notice text</div>
    <div id="section">Section content</div>

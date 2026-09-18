# HTML Basics

## What I learned

### Basic HTML document structure

- `<!DOCTYPE html>` tells the browser that the document uses HTML5.
- `<html>` contains the whole HTML document.
- `<head>` contains information about the webpage.
- `<title>` sets the name shown in the browser tab.
- `<body>` contains the content the user sees on the webpage.

The basic structure is:

`<!DOCTYPE html>` → `<html>` → `<head>` and `<body>`

### Headings

- `<h1>` is the main heading of the page.
- `<h2>` is a major section heading.
- `<h3>` is a subsection inside an `<h2>`.
- `<h4>` is a deeper subsection inside an `<h3>`.
- `<h5>` comes after `<h4>` in the heading hierarchy.
- `<h6>` is the deepest heading level.
- The heading hierarchy is `h1 → h2 → h3 → h4 → h5 → h6`.
- Heading levels describe the structure and importance of sections, not just text size.

### Text

- `<p>` creates a paragraph.
- `<strong>` marks important text, usually shown in bold.
- `<em>` adds emphasis, usually shown in italic.
- `<span>` is a small container for a piece of text. It has no special meaning or visual change by itself.

### Line breaks and dividers

- `<br>` forces a line break.
- `<hr>` creates a horizontal divider between sections.
- There is no standard `<vr>` tag for a vertical line. Vertical lines are normally made with CSS.

## My understanding

The `<head>` and `<body>` are both inside `<html>`.

The head is where we put information about the HTML page, while the body is where we put the content the user sees.

`<title>` is for the browser tab, while headings such as `<h1>` are visible page content.

Headings should follow a logical hierarchy: `h1 → h2 → h3 → h4 → h5 → h6`. If I am inside an `<h3>` section and need a deeper subsection, I can use `<h4>`.

`<strong>` and `<em>` give text meaning, while `<span>` is mainly a small wrapper that can be targeted later with CSS or JavaScript. A `<span>` does not normally change how text looks by itself.

`<br>` moves content to a new line, while `<hr>` separates content with a horizontal line.

## Practice

I created a basic Himma Academy page with a browser tab title and a visible main heading.

I practiced using `<p>`, `<strong>`, `<em>`, `<span>`, `<br>`, and `<hr>`.

I also practiced understanding the heading hierarchy through `<h1>` to `<h6>`, including using `<h4>` for a deeper subsection.


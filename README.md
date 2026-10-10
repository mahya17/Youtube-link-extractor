# YouTube Link Extractor

## About
A Python program that extracts YouTube video URLs from HTML embedded iframe elements and converts them into shorter, shareable links using the `youtu.be` domain.

## How It Works
- Accepts an HTML string as input.
- Searches for a YouTube video URL in an iframe's `src` attribute.
- Supports common YouTube embed URL formats with HTTP or HTTPS.
- Converts the extracted video URL into a shortened `https://youtu.be/` link.
- Returns `None` if no matching YouTube embed URL is found.

## Example
**Input:**
```html
<iframe src="https://www.youtube.com/embed/xvFZjo5PgG0"></iframe>
```

**Output:**
```text
https://youtu.be/xvFZjo5PgG0
```

## What I Practiced
- Working with strings and HTML snippets
- Using regular expressions with Python's `re` module
- Extracting matching groups from a pattern
- Defining functions that return values
- Handling inputs that do not match the expected pattern

## Technologies
- Python
- Regular Expressions (`re`)

## Course
Developed as part of Harvard University's CS50 Introduction to Programming with Python.

# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**
The <head> section contains information about the webpage that is not displayed directly to the user, such as the title, metadata, and links to CSS files. The <body> section contains all the visible content of the page, like headings, images, text, and links. Browsers use the <head> to set up the page, while users interact with what is inside the <body>.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:**
Semantic elements like <header>, <main>, and <footer> clearly describe the purpose of the content they contain. This makes the code easier to read and understand for developers, screen readers, and search engines. Using semantic HTML also improves accessibility and helps organize the structure of a webpage more meaningfully than using <div> tags everywhere.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:
1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
/* 1. All list items have a yellow background */
li {
  background-color: yellow;
}

/* 2. Only vegetables have green text */
.vegetable {
  color: green;
}

/* 3. Only Mango is bold */
#favorite {
  font-weight: bold;
}

```


## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**
The content is the actual text or image inside an element. Padding adds space between the content and the border, while the border wraps around the padding and content. Margin creates space outside the element, separating it from other elements. Together, these parts control spacing and layout on the page.

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**
box-sizing: border-box makes the width and height of an element include padding and borders, instead of adding them on afterward. This prevents elements from unexpectedly growing larger than intended. We include it in a CSS reset to make sizing more predictable and consistent across the entire page.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**
display: block elements take up the full width and start on a new line.
display: inline elements stay on the same line and ignore width and height.
display: inline-block allows elements to sit on the same line while still respecting width, height, and padding. Inline-block is useful for styling navigation links or buttons side by side.

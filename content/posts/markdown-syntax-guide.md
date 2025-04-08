---
title: "Markdown Syntax Guide"
date: 2024-03-15
categories: ["Markdown"]
---

This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also showing how these elements look in HTML.

## Headings

The following HTML `<h2>`—`<h6>` elements represent six levels of section headings. `<h1>` is reserved for the page title.

## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur?

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element.

> Simple blockquote example that looks fancy

> This is another blockquote with citation.
>
> — <cite>Famous Person</cite>

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports them.

| Name  | Age |
|-------|-----|
| Bob   | 27  |
| Alice | 23  |

## Code Blocks

Hugo's built-in code highlighter with Chroma.

```javascript
// Example JavaScript code
const greeting = 'Hello, World!';
console.log(greeting);

function multiply(a, b) {
  return a * b;
}

// Some ES6 features
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2);
```

```css
/* Example CSS */
body {
  font-family: system-ui, sans-serif;
  line-height: 1.5;
  color: #333;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 1rem;
}

@media (max-width: 768px) {
  .container {
    padding: 0.5rem;
  }
}
```

## Lists

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

* List item
* Another item
* And another item

## Images

Here's our logo (hover to see the title text):

![Hugo Logo](/images/sample-image.jpg "Hugo logo")

## Using the Figure Shortcode

Hugo has a `figure` shortcode built in, so you can easily add captions and more to your images.

{{< figure src="/images/garden.jpg" alt="Sample image" caption="This is a caption for the sample image." >}}

---
title: Markdown Formatting Showcase
date: 2023-04-08T10:00:00-05:00
draft: true
categories: [Markdown]
tags: []
---

# Markdown Formatting Showcase

This post demonstrates various formatting options available in Markdown to help preview your Hugo theme.

## Text Formatting

Regular paragraph text looks like this. You can make text **bold**, *italic*, or ***bold and italic***. You can also add ~~strikethrough~~ to text.

## Headers

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

## Lists

### Unordered Lists

* Item 1
* Item 2
  * Nested item 1
  * Nested item 2
* Item 3

### Ordered Lists

1. First item
2. Second item
   1. Nested item 1
   2. Nested item 2
3. Third item

## Blockquotes

> This is a blockquote.
> 
> It can span multiple paragraphs.
>
> > This is a nested blockquote.

## Code

Inline code: `const greeting = "Hello, world!";`

Code block with syntax highlighting:

```javascript
function calculateFactorial(n) {
  if (n === 0 || n === 1) {
    return 1;
  }
  return n * calculateFactorial(n - 1);
}

console.log(calculateFactorial(5)); // 120
```

Python example:

```python
def fibonacci(n):
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)
        
# Print the first 10 Fibonacci numbers
for i in range(10):
    print(fibonacci(i))
```

## Links and Images

[Link to Hugo website](https://gohugo.io/)

![Sample Image](https://example.com/sample-image.jpg)

## Tables

| Name    | Age | Occupation     |
|---------|-----|----------------|
| John    | 28  | Developer      |
| Sarah   | 32  | Designer       |
| Michael | 45  | Project Manager|

## Horizontal Rule

---

## Definition Lists

Term 1
: Definition 1

Term 2
: Definition 2a
: Definition 2b

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task

## Footnotes

Here's a sentence with a footnote[^1].

[^1]: This is the footnote content.

## Mathematical Formulas

Inline formula: $E = mc^2$

Block formula:

$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

## Embedded HTML

<div style="padding: 20px; background-color: #f8f9fa; border-radius: 5px;">
  <h3>HTML Example</h3>
  <p>This is an example of embedded HTML in Markdown.</p>
</div>

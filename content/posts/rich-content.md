---
title: Rich Content Examples
date: 2024-03-20T10:00:00-05:00
draft: true
categories: [Markdown]
summary: Hugo ships with several Built-in Shortcodes for rich content, along with a Privacy Config and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.
---

Hugo ships with several Built-in Shortcodes for rich content, along with a Privacy Config and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.

## Syntax Highlighting Examples

Here are more examples of syntax highlighting with different languages:

### Python

```python {linenos=inline}
def fibonacci(n):
    """Generate the Fibonacci sequence up to n"""
    a, b = 0, 1
    while a < n:
        yield a
        a, b = b, a + b

# Example usage
for num in fibonacci(100):
    print(num)
```

### Go

```go {linenos=inline}
package main

import "fmt"

func main() {
    fmt.Println("Hello, Hugo!")
    
    // Define variables
    var x int = 10
    y := 20
    
    // Control flow
    if x < y {
        fmt.Println("x is less than y")
    }
    
    // Loop
    for i := 0; i < 5; i++ {
        fmt.Printf("Iteration %d\n", i)
    }
}
```

### HTML/CSS/JS

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Hugo Site</title>
    <style>
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }
        .container {
            border: 1px solid #eaeaea;
            border-radius: 4px;
            padding: 1.5rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Hugo Site</h1>
        <p>This is a simple HTML example.</p>
        <button id="clickMe">Click Me</button>
    </div>
    
    <script>
        document.getElementById('clickMe').addEventListener('click', function() {
            alert('Button clicked!');
        });
    </script>
</body>
</html>
```

## YouTube

Below is an example of embedding a YouTube video using Hugo's built-in `youtube` shortcode:

{{< youtube w7Ft2ymGmfc >}}

## Figure Shortcode

Hugo has a `figure` shortcode built in, so you can easily add captions and more to your images.

{{< figure src="/images/garden.jpg" alt="Sample image" caption="This is a caption for the sample image." >}}
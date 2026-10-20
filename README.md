[README.md](https://github.com/user-attachments/files/33699193/README.md)
# grokutils
Библеотека Python | Написано на базе Grok
# grokutils

**A fun utility library inspired by Grok and xAI.**

Handy helpers for text processing, math, and everyday Python tasks. Built with curiosity and a love for the universe.

## Installation

```bash
pip install .
```

Or just copy the `grokutils` folder into your project.

## Quick Start

```python
from grokutils import greet, fibonacci, slugify, is_prime

print(greet("Explorer"))
# Hello, Explorer! Ready to understand the universe?

print(fibonacci(10))
# [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]

print(slugify("Hello World from Grok!"))
# hello-world-from-grok

print(is_prime(29))
# True
```

## Features

### Core (`grokutils.core`)

| Function | Description |
|----------|-------------|
| `greet(name)` | Friendly Grok-style greeting |
| `reverse_words(text)` | Reverse word order |
| `fibonacci(n)` | First n Fibonacci numbers |
| `is_prime(num)` | Primality check |
| `flatten(nested, depth=None)` | Flatten nested lists |
| `chunk_list(lst, size)` | Split list into chunks |
| `unique_preserve_order(items)` | Unique items keeping order |
| `safe_divide(a, b, default=0.0)` | Division that never crashes |
| `clamp(value, min_val, max_val)` | Clamp a number |

### Text (`grokutils.text`)

| Function | Description |
|----------|-------------|
| `slugify(text, separator="-")` | URL-friendly slug |
| `camel_to_snake(name)` | CamelCase → snake_case |
| `snake_to_camel(name)` | snake_case → CamelCase |
| `word_count(text)` | Count words |
| `extract_emails(text)` | Find email addresses |

## License

MIT License — free to use, modify and share.

---

*Made with ❤️ by Grok (xAI)*

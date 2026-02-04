# Syntactic Infiltration

Learn Python without opening an IDE.

Syntactic Infiltration is a Chrome extension that passively teaches programming by transforming real-world sentences on webpages into Python-style pseudocode. Instead of traditional tutorials, users subconsciously develop programming intuition while browsing normally.


## The Idea

People don’t fail at learning programming because syntax is hard.
They fail because they never start thinking in logic.

Our extension injects programming logic into daily browsing — articles, blogs, and forums — turning natural language into executable-style reasoning.


## Example

**Original Sentence**

> If you want to travel to France this summer, book flights now because prices are rising.

**Injected Output**

```
if summer_travel == "France":
    print("Book flights now")
else:
    pass  # prices rising anyway
```

## Features

* Detects logical patterns in text
* Converts sentences into Python pseudocode
* Highlights variables in snake_case
* Interactive micro-learning checks
* Toggle ON/OFF anytime


## Tech Stack

* Chrome Extension (Manifest V3)
* JavaScript DOM manipulation
* Lightweight NLP pattern detection
* Python-style code transformation engine


## Purpose

To make learning programming passive, constant, and unavoidable — like learning a language by living in the country.

> "If we can think in English automatically, we can think in code automatically."

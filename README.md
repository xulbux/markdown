<div align="center">
  <br><br>
  <h1>
    <a href="https://github.com/xulbux/markdown"><img height="96" src="https://raw.githubusercontent.com/xulbux/markdown/main/assets/md-mark.svg"></a>
    <br>
    Ultimate Markdown Cheat Sheet
    <br><br>
    <a href="https://github.com/xulbux/markdown/blob/main/LICENSE"><img src="https://svg.xul.is/badge/gh/xulbux/markdown/license?variant=3&color=neutral" /></a>
    <a href="https://github.com/xulbux/markdown/commits"><img src="https://svg.xul.is/badge/gh/xulbux/markdown/commit?variant=3&color=neutral"/></a>
    <a href="https://github.com/sponsors/xulbux"><img src="https://svg.xul.is/badge/Sponsor?variant=2&color=rose&icon=heart&anim=pulse"/></a>
  </h1>
  <h3>Your friendly, comprehensive, and beautiful guide to Markdown syntax.</h3>
  <br><br>
</div>

## <a href="#table-of-contents"><img src="https://svg.xul.is/icon/list?size=32&stroke=2" align="left" /></a>Table of Contents

-   [**Basic Formatting**](#basic-formatting) – Headings, Bold, Italic, etc.
-   [**Lists & Tasks**](#lists-tasks) – Unordered, Ordered, Task Lists
-   [**Links & Media**](#links-media) – URLs, Images, Anchors
-   [**Quotes & Code**](#quotes-code) – Blockquotes, Inline Code, Code Blocks, Escaping
-   [**Structure**](#structure) – Tables, Horizontal Rules
-   [**Advanced & GFM Features**](#advanced-gfm-features) – Alerts, Mermaid, Math, HTML

<span id="limited-support"></span>

> Features with limited support across different Markdown parsers are marked with **[[L]](#limited-support)**.

<br>
<br>
<br>

## <a href="#basic-formatting"><img src="https://svg.xul.is/icon/pen-tool?size=32&stroke=2" align="left" /></a>Basic Formatting

<br>

### Headings

Headings help structure your document. Use `#` for levels 1-6.

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

<br>

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

<br>

### Emphasis & Styling

Make your text stand out with basic formatting.

**Bold Text**: Space is **vast and empty**.<br>
*Italic Text*: The stars are *beautifully bright*.<br>
***Bold & Italic***: The universe is ***constantly expanding***!<br>
~~Strikethrough~~: Pluto is ~~a major planet~~ a dwarf planet.

```markdown
**Bold Text**: Space is **vast and empty**.
*Italic Text*: The stars are *beautifully bright*.
***Bold & Italic***: The universe is ***constantly expanding***!
~~Strikethrough~~: Pluto is ~~a major planet~~ a dwarf planet.
```

<br>

### Escaping Characters

If you want to type symbols like `*` or `_` without triggering formatting, use a backslash `\`.

\*This text will not be italicized.\*

```markdown
\*This text will not be italicized.\*
```

<br>
<br>
<br>

<span id="lists-tasks"></span>

## <a href="#lists-tasks"><img src="https://svg.xul.is/icon/list-todo?size=32&stroke=2" align="left" /></a>Lists & Tasks

<br>

### Unordered Lists

Use `*`, `-`, or `+` for bullet points.

*   Launch preparations
*   Engine check
    -   Fuel levels nominal
    -   Thrusters engaged
*   Liftoff!

```markdown
*   Launch preparations
*   Engine check
    -   Fuel levels nominal
    -   Thrusters engaged
*   Liftoff!
```

<br>

### Ordered Lists

Use numbers followed by periods.

1.  Learn Markdown
2.  Write awesome documentation
3.  Profit!
    1.  Celebrate with coffee
    2.  Share with friends

```markdown
1.  Learn Markdown
2.  Write awesome documentation
3.  Profit!
    1.  Celebrate with coffee
    2.  Share with friends
```

<br>

### [[L]](#limited-support) Task Lists

Keep track of your to-dos.

-   [x] Write cheat sheet
-   [x] Add friendly examples
-   [ ] Conquer the galaxy

```markdown
-   [x] Write cheat sheet
-   [x] Add friendly examples
-   [ ] Conquer the galaxy
```

<br>
<br>
<br>

<span id="links-media"></span>

## <a href="#links-media"><img src="https://svg.xul.is/icon/link?size=32&stroke=2" align="left" /></a>Links & Media

<br>

### Links

A simple automatic link: <https://www.markdownguide.org><br>
An email link: <hello@universe.com><br>
A formatted [link to GitHub](https://github.com "Visit GitHub") with hover text.

```markdown
A simple automatic link: <https://www.markdownguide.org>
An email link: <hello@universe.com>
A formatted [link to GitHub](https://github.com "Visit GitHub") with hover text.
```

<br>

### Anchor Links

Jump to [Basic Formatting](#basic-formatting) or jump to a <span id="custom-anchor">custom hidden anchor</span>.

```markdown
Jump to [Basic Formatting](#basic-formatting) or jump to a <span id="custom-anchor">custom hidden anchor</span>.
```

<br>

### Images

![MD Mark](https://raw.githubusercontent.com/xulbux/markdown/main/assets/md-mark.svg "This is the MD Mark logo")

```markdown
![MD Mark](https://raw.githubusercontent.com/xulbux/markdown/main/assets/md-mark.svg "This is the MD Mark logo")
```

For a specific size, you can use HTML:

<img src="https://raw.githubusercontent.com/xulbux/markdown/main/assets/md-mark.svg" height="64" alt="MD Mark" title="Fixed Height Image" />

```markdown
<img src="https://raw.githubusercontent.com/xulbux/markdown/main/assets/md-mark.svg" height="64" alt="MD Mark" title="Fixed Height Image" />
```

<br>
<br>
<br>

<span id="quotes-code"></span>

## <a href="#quotes-code"><img src="https://svg.xul.is/icon/code?size=32&stroke=2" align="left" /></a>Quotes & Code

<br>

### Block Quotes

Great for citing text or drawing attention.

> "To infinity, and beyond!"<br>
> — Buzz Lightyear

Nested quotes:
> First level of quoting
> > Second level of quoting

```markdown
> "To infinity, and beyond!"
> — Buzz Lightyear

Nested quotes:
> First level of quoting
> > Second level of quoting
```

<br>

### Inline Code

Use backticks for inline code, like `print("Hello!")` or representing keystrokes.

```markdown
Use backticks for inline code, like `print("Hello!")` or representing keystrokes.
```

<br>

### Code Blocks

Use triple backticks for syntax highlighting.

```python
def greet_user(name: str):
    """A friendly greeting function."""
    print(f"Hello, {name}! Welcome aboard.")
```

````markdown
```python
def greet_user(name: str):
    """A friendly greeting function."""
    print(f"Hello, {name}! Welcome aboard.")
```
````

<br>

### Escaping Backticks

To include backticks inside code formatting, wrap the code with more backticks than it contains.

Inline escaping: `` `inline` ``

Block escaping:

````markdown
```python
print("Hello")
```
````

<br>

`````markdown
Inline escaping: `` `inline` ``

Block escaping:

````markdown
```python
print("Hello")
```
````
`````

<br>
<br>
<br>

## <a href="#structure"><img src="https://svg.xul.is/icon/table?size=32&stroke=2" align="left" /></a>Structure

<br>

### Tables

Organize data easily. Colons `:` dictate alignment.

| Feature       | Status     | Alignment |
| :------------ | :--------: | --------: |
| Markdown      | Awesome    | Left      |
| Tables        | Useful     | Center    |
| Formatting    | Clean      | Right     |

```markdown
| Feature       | Status     | Alignment |
| :------------ | :--------: | --------: |
| Markdown      | Awesome    | Left      |
| Tables        | Useful     | Center    |
| Formatting    | Clean      | Right     |
```

<br>

### Horizontal Rules

Separate content using three or more hyphens, asterisks, or underscores.

---

***

___

<br>

```markdown
---

***

___
```

<br>
<br>
<br>

<span id="advanced-gfm-features"></span>

## <a href="#advanced-gfm-features"><img src="https://svg.xul.is/icon/rocket?size=32&stroke=2" align="left" /></a>[[L]](#limited-support) Advanced & GFM Features

<br>

### Alerts / Callouts

> [!NOTE]<br>
> Markdown is incredibly versatile for daily documentation.

> [!TIP]<br>
> Use a good editor with preview mode to spot formatting errors early!

> [!IMPORTANT]<br>
> The exact rendering of these alerts depends entirely on the platform (e.g., GitHub).

> [!WARNING]<br>
> Too much styling can make raw markdown hard to read.

> [!CAUTION]<br>
> Deleting your documentation might lead to sad developers.

```markdown
> [!NOTE]
> Markdown is incredibly versatile for daily documentation.

> [!TIP]
> Use a good editor with preview mode to spot formatting errors early!

> [!IMPORTANT]
> The exact rendering of these alerts depends entirely on the platform (e.g., GitHub).

> [!WARNING]
> Too much styling can make raw markdown hard to read.

> [!CAUTION]
> Deleting your documentation might lead to sad developers.
```

<br>

### Collapsible Sections

Keep large chunks of info hidden until needed.

<details>
  <summary>Click to reveal secret coordinates</summary>
  
  42° 21' 36" N, 71° 3' 35" W
</details>

<br>

```markdown
<details>
  <summary>Click to reveal secret coordinates</summary>
  
  42° 21' 36" N, 71° 3' 35" W
</details>
```

<br>

### Footnotes

Add references or extra context without cluttering the text.

Here is a statement that needs clarification[^1].

[^1]: This is the clarification, tucked away neatly at the bottom.

```markdown
Here is a statement that needs clarification[^1].

[^1]: This is the clarification, tucked away neatly at the bottom.
```

<br>

### Keyboard Input

Press <kbd>Ctrl</kbd>+<kbd>S</kbd> to save your work.

```markdown
Press <kbd>Ctrl</kbd>+<kbd>S</kbd> to save your work.
```

<br>

### Subscript & Superscript

Water is H<sub>2</sub>O and E = mc<sup>2</sup>.

```markdown
Water is H<sub>2</sub>O and E = mc<sup>2</sup>.
```

<br>

### Ruby Text

<ruby>漢字<rt>Kanji</rt></ruby>

```markdown
<ruby>漢字<rt>Kanji</rt></ruby>
```

<br>

### Math Equations

For platforms supporting KaTeX/MathJax.

Inline math: $E = mc^2$

Block math:
$$ \int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi} $$

<br>

```markdown
Inline math: $E = mc^2$

Block math:
$$ \int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi} $$
```

<br>

### Mermaid Diagrams

Generate charts right from code!

```mermaid
graph LR
    A[Idea] --> B(Write Markdown)
    B --> C{Review}
    C -->|Looks Good| D[Publish]
    C -->|Needs Work| B
```

````markdown
```mermaid
graph LR
    A[Idea] --> B(Write Markdown)
    B --> C{Review}
    C -->|Looks Good| D[Publish]
    C -->|Needs Work| B
```
````

<br>

### CSS Styling

You can inject raw HTML/CSS into Markdown if supported.

<span style="font-size: 2em; font-weight: bold; background: linear-gradient(90deg, #F76, #F67, #F7A, #A7F, #67F); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">Rainbow Text!</span>

```markdown
<span style="font-size: 2em; font-weight: bold; background: linear-gradient(90deg, #F76, #F67, #F7A, #A7F, #67F); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">Rainbow Text!</span>
```

<br>

### Definition Lists

Some parsers support definition lists.

Markdown<br>
: A lightweight markup language with plain-text-formatting syntax.<br>
HTML<br>
: The standard markup language for documents designed to be displayed in a web browser.

```markdown
Markdown
: A lightweight markup language with plain-text-formatting syntax.
HTML
: The standard markup language for documents designed to be displayed in a web browser.
```

<br><br>
<br><br>
<br><br>
<br><br>

## Enjoying this cheat sheet?&numsp;Have suggestions?

Please consider giving a [![star](https://svg.xul.is/icon/star?size=20&anim=shake)](https://github.com/xulbux/markdown) on [**GitHub**](https://github.com/xulbux/markdown) or [**opening an issue**](https://github.com/xulbux/markdown/issues) with suggestions.

<br>
<br>
<br>

---

[![](https://svg.xul.is/icon/sparkles?size=20)](https://xulbux.com) Always creating more cool stuff for you! [![](https://svg.xul.is/icon/sparkles?size=20)](https://xulbux.com)&emsp;—&numsp;[**XulbuX**](https://xulbux.com)

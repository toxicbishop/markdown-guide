<p align="center">
  <img src="assets/banner.svg" alt="Markdown Guide Banner" width="800" />
</p>

<p align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=32&duration=3000&pause=500&color=22C55E&center=true&vCenter=true&width=650&height=80&lines=%F0%9F%93%9D+MARKDOWN+GUIDE;Master+the+Art+of+Documentation" alt="Typing SVG" />
  
</p>

<p align = center>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=ReadMe&logoColor=white" alt="License: MIT" />
    </a>
    <a href="CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/Contributions-Welcome-green?style=for-the-badge&logo=github&logoColor=white" alt="PRs Welcome" />
    </a>
    <a href="https://github.com/toxicbishop/markdown-guide/stargazers">
      <img src="https://img.shields.io/github/stars/toxicbishop/markdown-guide?style=for-the-badge&logo=github&color=red" alt="GitHub stars" />
    </a>
    <a href="https://github.com/toxicbishop/markdown-guide/network/members">
      <img src="https://img.shields.io/github/forks/toxicbishop/markdown-guide?style=for-the-badge&logo=github&color=orange" alt="GitHub forks" />
    </a>
  </p>

<p align="center">
  <strong>English</strong> |
  <a href="README.hi.md">हिन्दी</a> |
  <a href="README.kn.md">ಕನ್ನಡ</a> |
  <a href="README.te.md">తెలుగు</a>
</p>
  
<p align="center"> A clean, complete guide for anyone writing better README files. </p>

---

## Table of Contents

- [What is Markdown?](#what-is-markdown)
- [Headings](#headings)
- [Text Formatting](#text-formatting)
- [Lists](#lists)
- [Code Blocks](#code-blocks)
- [Diff Code Blocks](#diff-code-blocks)
- [Mermaid Diagrams](#mermaid-diagrams)
- [Tables](#tables)Expand the Project

Add .github/ISSUE_TEMPLATE/ - issue templates for bug reports, feature requests
Add .github/PULL_REQUEST_TEMPLATE.md - PR template
Create a GitHub Pages site to host an interactive version
Add translations in separate files (e.g., README.zh.md, README.es.md)
- [Blockquotes](#blockquotes)
- [Horizontal Line](#horizontal-line)
- [Links](#links)
- [Relative Links](#relative-links)
- [Images](#images)
- [Image Positioning](#image-positioning)
- [Video Embedding](#video-embedding)
- [Alerts](#alerts)
- [Emojis](#emojis)
- [Footnotes](#footnotes)
- [Math Expressions](#math-expressions)
- [Escape Characters](#escape-characters)
- [Badges](#badges)
- [GitHub-Specific Features](#github-specific-features)
- [HTML in Markdown](#html-in-markdown)
- [Anchors](#anchors)
- [Keyboard Keys](#keyboard-keys)
- [README Templates](#readme-templates)
- [Quick Reference Card](#quick-reference-card)
- [Some Useful Tips](#some-useful-tips)

---

## What is Markdown?
> Markdown is a lightweight markup language that lets you format text using simple symbols.
> It’s widely used in GitHub READMEs, documentation, wikis, blogs, and notes.
<br>

<!-- Heading -->
# Headings
Headings help structure your README into clear, readable sections. Simply it makes the document easy to scan.

> # This is a Heading
> ```md
> # This is a Heading
> ```
> ## This is a Heading
> ```md
> ## This is a Heading
> ```
> ### This is a Heading
> ```md
> ### This is a Heading
> ```

<!-- Text Formatting -->
# Text Formatting
Formatting helps you highlight important info, emphasize details, or organize explanations. It makes your README clearer, more readable, and more professional.

**Bold Text**
```md
**Bold Text** or __Bold Text__
```

*Italic Text*
```md
*Italic Text* or _Italic Text_
```

***Bold + Italic***
```md
***Bold + Italic***
```

~Strikethrough~
```md
`~~Strikethrough~~` or `~Strikethrough~`
```

<ins>Underline<ins>
```md
<ins>Underline<ins>
```

Here's is a <sub>subscript<sub>
```md
<sub>subscript<sub>
```

Here's is a <sup>superscript<sup>
```md
<sup>superscript<sup>
```

`inline code`
```md
`inline code`
```

<!-- Lists -->

# Lists
Lists help you present information cleanly and quickly, making complex steps or features easy to digest.

> ## Unordered List
> - Item 1
> - Item 2
> ```md
> - Item 1
> - Item 2
> ```


> ## Ordered List
> 1. Item 1
> 2. Item 2
> ```md
> 1. Item 1
> 2. Item 2
> ```

> ## Nested Lists
> - Item 1
>   - Sub Item 1
>     - Sub item a
> ```md
> - Item 1
>   - Sub Item 1
>     - Sub item a
> ```


> ## Task List
> - [x] Completed task
> - [ ] Pending task
> ```md
> - [x] Completed task
> - [ ] Pending task
> ```

<!-- Code -->
# Code Blocks
Code blocks make your README **developer‑friendly**, giving users clean, formatted examples they can copy and run.

### Inline Code
Use `npm install` to install packages.
```
`npm install`
```
### Code Block
```python
print("Hello World")
```

````
```python
print("Hello World")
```
````
Syntax highlighting available for Python, JavaScript, Java, Bash, JSON, YAML etc.
````
```<syntax>
<code>
```
````

# Diff Code Blocks
Use diff syntax highlighting to show code changes with additions and deletions. Very useful for showing what changed in code reviews or tutorials.

```diff
- const oldValue = "remove this";
+ const newValue = "add this";
  const unchanged = "stays the same";
```

````
```diff
- const oldValue = "remove this";
+ const newValue = "add this";
  const unchanged = "stays the same";
```
````

Lines starting with `-` are shown in red (removed), `+` in green (added), and no prefix means unchanged.

# Mermaid Diagrams
GitHub supports Mermaid for diagrams. Very useful for architecture diagrams, flowcharts, and explaining project structure: essential for technical documentation.


```mermaid
flowchart TD
    A --> B
```
Syntax:
````
```mermaid
flowchart TD
    A --> B
```
````

<!-- Tables -->
# Tables
Tables allow you to show structured information such as configurations, comparisons, or fields. It turns messy text into a clean, organized layout, especially useful for feature lists, API data, and documentation.

| Name   | Role      | Level  |
|--------|-----------|--------|
| John   | Developer | Senior |
| Bob    | Tester    | Junior |

```md
| Name   | Role      | Level  |
|--------|-----------|--------|
| John   | Developer | Senior |
| Bob    | Tester    | Junior |
```
or
```md
|Name|Role|Level|
|-|-|-|
|John|Developer|Senior|
|Bob|Tester|Junior|
```
We can also align text to the left, right, or center of a column by including colons ':' to the left, right, or on both sides of the hyphens within the header row.
|Left Aligned| Centered |Right Aligned|
|:---        |   :---:  |         ---:|
| name1      |   role1  |       level1|
| name2      |   role2  |       level2|

```md
|Left Aligned| Centered |Right Aligned|
|:---        |   :---:  |         ---:|
| name1      |   role1  |       level1|
| name2      |   role2  |       level2|
```

<!-- Blockquotes -->
# Blockquotes
Used for notes, warnings, tips, or important messages.

> This is a quoted line.
>> Nested quote
```md
> This is a quoted line.
>> Nested quote
```

# Horizontal Line

---
```md
---
```

# Links
Links lets us connect users to installation guides, docs, external pages, or related repositories.

[GitHub](https://github.com)

Syntax:
```
[GitHub](https://github.com)
```

# Relative Links
Link to other files within your repository using relative paths. This keeps links working even if the repo is forked.

[Read the Contributing Guide](./CONTRIBUTING.md)

```md
[Read the Contributing Guide](./CONTRIBUTING.md)
```

Link to specific sections in other files:
```md
[Setup Instructions](./docs/setup.md#installation)
```

Link to parent directories:
```md
[Back to Main](../README.md)
```

# Images
Images help make your README visually appealing, making your README more engaging and easier to understand.

Syntax:
```
![Alt text](image_url)
````
![cat](https://github.com/user-attachments/assets/ba594416-cd49-4231-837b-fc4b742b876f)

```
![cat](https://github.com/user-attachments/assets/ba594416-cd49-4231-837b-fc4b742b876f)
```

# Image Positioning
Use HTML tables to position images side by side or in grids.

<table>
  <tr>
    <td><img src="https://via.placeholder.com/150" alt="Image 1" /></td>
    <td><img src="https://via.placeholder.com/150" alt="Image 2" /></td>
    <td><img src="https://via.placeholder.com/150" alt="Image 3" /></td>
  </tr>
</table>

```md
<table>
  <tr>
    <td><img src="image1.png" alt="Image 1" /></td>
    <td><img src="image2.png" alt="Image 2" /></td>
    <td><img src="image3.png" alt="Image 3" /></td>
  </tr>
</table>
```

Center a single image with specific width:
```md
<p align="center">
  <img src="image.png" alt="Description" width="400" />
</p>
```

# Video Embedding
GitHub READMEs don't support direct video embeds, but you can use these approaches:

### Link to Video
[Watch the Demo Video](https://youtube.com/watch?v=example)
```md
[Watch the Demo Video](https://youtube.com/watch?v=example)
```

### GIF as Video Preview
Convert short clips to GIFs for inline playback:
```md
![Demo](assets/demo.gif)
```

### Video Thumbnail with Link
[![Video Title](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)
```md
[![Video Title](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)
```

### Uploaded Videos (GitHub Issues/Discussions)
You can drag and drop `.mp4` files into GitHub Issues or Discussions, then copy the generated link to your README.

<!-- HTML -->
# Alerts
Alerts are use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

### NOTE
> [!NOTE]
> Useful information that users should know, even when skimming content.
```
> [!NOTE]
> Useful information that users should know, even when skimming content.
```

> [!TIP]
> Helpful advice for doing things better or more easily.
```
> [!TIP]
> Helpful advice for doing things better or more easily.
```

> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

# Emojis
GitHub supports emoji shortcodes. Use them sparingly for visual emphasis.

| Shortcode | Result |
|-----------|--------|
| `:star:` | :star: |
| `:rocket:` | :rocket: |
| `:white_check_mark:` | :white_check_mark: |
| `:warning:` | :warning: |
| `:bug:` | :bug: |
| `:bulb:` | :bulb: |
| `:memo:` | :memo: |
| `:hammer:` | :hammer: |

```md
:star: Star this repo!
:rocket: Getting Started
:warning: Important Notice
```

Full list: [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)

# Footnotes
Footnotes let you add references without cluttering the main text.

Here is a statement that needs a citation[^1].

Another point worth noting[^2].

[^1]: This is the first footnote with more details.
[^2]: This is the second footnote.

```md
Here is a statement that needs a citation[^1].

Another point worth noting[^2].

[^1]: This is the first footnote with more details.
[^2]: This is the second footnote.
```

Footnotes automatically appear at the bottom of the rendered document.

# Math Expressions
GitHub supports LaTeX math syntax for inline and block equations.

### Inline Math
The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ for any quadratic equation.

```md
The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
```

### Block Math
$$
E = mc^2
$$

```md
$$
E = mc^2
$$
```

### Complex Equations
$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

```md
$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$
```

# Escape Characters
To display characters that have special meaning in Markdown, use a backslash.

| Character | Escaped | Result |
|-----------|---------|--------|
| `*` | `\*` | \* |
| `#` | `\#` | \# |
| `_` | `\_` | \_ |
| `` ` `` | `` \` `` | \` |
| `[` | `\[` | \[ |
| `]` | `\]` | \] |
| `(` | `\(` | \( |
| `)` | `\)` | \) |
| `|` | `\|` | \| |

```md
\*This won't be italic\*
\# This won't be a heading
```

# Badges
Badges provide quick visual information about your project. Use shields.io to generate them.

### Basic Badge Syntax
```md
![Badge](https://img.shields.io/badge/LABEL-MESSAGE-COLOR)
```

### Common Badge Examples

| Badge | Code |
|-------|------|
| ![Version](https://img.shields.io/badge/version-1.0.0-blue) | `![Version](https://img.shields.io/badge/version-1.0.0-blue)` |
| ![Build](https://img.shields.io/badge/build-passing-brightgreen) | `![Build](https://img.shields.io/badge/build-passing-brightgreen)` |
| ![License](https://img.shields.io/badge/license-MIT-green) | `![License](https://img.shields.io/badge/license-MIT-green)` |

### Dynamic Badges
Link to real data from your repo:
```md
![GitHub stars](https://img.shields.io/github/stars/username/repo)
![npm version](https://img.shields.io/npm/v/package-name)
![GitHub issues](https://img.shields.io/github/issues/username/repo)
```

### Badge with Link
```md
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
```

### Style Options
- `?style=flat` (default)
- `?style=flat-square`
- `?style=for-the-badge`
- `?style=plastic`

More options: [shields.io](https://shields.io)

# GitHub-Specific Features
GitHub Markdown has special autolink features that work only on GitHub.

### Issue and PR References
| Syntax | Description |
|--------|-------------|
| `#123` | Links to issue/PR #123 in current repo |
| `user/repo#123` | Links to issue/PR in another repo |
| `GH-123` | Alternative issue reference |

### User and Team Mentions
```md
@username - mentions a user
@org/team-name - mentions a team
```

### Commit References
| Syntax | Description |
|--------|-------------|
| `a1b2c3d` | Short SHA links to commit |
| `user/repo@a1b2c3d` | Commit in another repo |

### Compare Links
```md
https://github.com/user/repo/compare/v1.0...v2.0
```

### Task Lists in Issues
Task lists in issues show progress:
```md
- [x] Completed task
- [ ] Incomplete task
```

### Auto-linked URLs
URLs are automatically converted to clickable links:
```
https://github.com
```

# HTML in Markdown
Markdown is powerful, but it has limits. GitHub supports HTML inside Markdown, letting you do layout tricks that plain Markdown cannot achieve. Below is the full detailed explanation of how HTML can enhance Markdown.

## HTML Headings
Markdown headings are good, but HTML headings gives more control. Useful when you want alignment or mixed layout at the top.

> <h1>Heading 1</h1>
> <h2>Heading 2</h2>
> <h3>Heading 3</h3>
```md
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

> <h2 align="left">Left Aligned</h1>
> <h2 align="center">Centered</h2>
> <h2 align="right">Right Aligned</h3>
```md
<h2 align="left">Left Aligned</h1>
<h2 align="center">Centered</h2>
<h2 align="right">Right Aligned</h3>
```

## Paragraphs & Line Breaks
Markdown sometimes collapses line breaks. HTML fixes that.

### Paragraph
<p>This is a paragraph with controlled spacing.</p>

```md
<p>This is a paragraph with controlled spacing.</p>
```

### Line Break
Line 1 <br>
Line 2

```md
Line 1 <br>
Line 2
```

## Comments
Comments are notes that won't render on the markdown, useful in add info without showing them publicly.
```md
<!-- This is a Comment -->

<!--
This is
also a
Comment
-->
```

## Alignment and Centered Sections
We can tweak the alignment of elements using the 'align' attribute on some tags. It is very useful to get a clean professional look for README's top section.


> <div align="center">
>   <img src="assets/devdebug.png" title = "DevDebug Logo" alt="Logo" width="120" />
>   <h1>Project Name</h1>
>   <p>A short one‑line description of what your project does.</p>
> </div>

> ```md
> <div align="center">
>   <img src="assets/logo.png" alt="Logo" width="120" />
>   <h1>Project Name</h1>
>   <p>A short one‑line description of what your project does.</p>
> </div>
> ```

## Links
Using `<a>` tag we can add links inside centered blocks, badge rows, or custom layouts where Markdown links get messy.

<a href="https://example.com" title="Example">Example Site</a>

```md
<a href="https://example.com" title="Example">Example Site</a>
```

## Lists
Markdown lists are usually enough, but HTML lists help when you’re mixing complex blocks or alignment. We use `<ul>` ` <li>` for unordered lists, `<ol>` `<li>` for ordered lists.

<ul>
  <li>list 1</li>
  <li>list 2</li>
</ul>

```md
<ul>
  <li>list 1</li>
  <li>list 2</li>
</ul>
```

<ol>
  <li>list 1</li>
  <li>list 2</li>
</ol>

```md
<ol>
  <li>list 1</li>
  <li>list 2</li>
</ol>
```


## Tables
HTML tables are more flexible than Markdown tables. These are great for side‑by‑side layouts and for content that breaks Markdown table formatting.

<table align='center'>
  <tr>
    <td>Column 1</td>
    <td>Column 2</td>
  </tr>
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
</table>

```md
<table align='center'>
  <tr>
    <td>Column 1</td>
    <td>Column 2</td>
  </tr>
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
</table>
```


## Collapsible sections
Within our README we can use  `<details>` and  `summary>` tag to create expandable sections. These collapsible sections are perfect for FAQ, advanced setup, more screenshots, or extended configuration without making the README huge.

<details>
<summary>Show advanced setup</summary>
  
- Step 1: Do this  
- Step 2: Do that
</details>

```md
<details>
  <summary>Show advanced setup</summary>
  - Step 1: Do this  
  - Step 2: Do that  
</details>
```


# Anchors
Anchors helps navigation in long READMEs. GitHub supports TOC linking behavior as part of common README practice.

> ## Table of Contents
> - [Section1](#section1)
> - [Section2](#section2)
> ## Section1
> ## Section2

```md
[Section1](#section1)
[Section2](#section2)
```



# Keyboard keys
We can use `<kbd>` to display keyboard keys nicely. It is useful for shortcuts or commands in guides.

> Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to Copy.<br>
> Press <kbd>Ctrl</kbd> + <kbd>V</kbd> to Paste.
> ```md
> Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to Copy.
> Press <kbd>Ctrl</kbd> + <kbd>V</kbd> to Paste.
> ```

# README Templates

Below are minimal templates for different project types.

<details>
<summary>Web Application Template</summary>

```md
# Project Name

Brief description of the web application.

## Demo

[Live Demo](https://your-demo-url.com)

## Tech Stack

- Frontend: React / Vue / Angular
- Backend: Node.js / Python / Go
- Database: PostgreSQL / MongoDB

## Installation

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables (see `.env.example`)
4. Run the development server: `npm run dev`

## Environment Variables

| Variable | Description |
|----------|-------------|
| `DATABASE_URL` | Database connection string |
| `API_KEY` | External API key |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## License

MIT
```
</details>

<details>
<summary>CLI Tool Template</summary>

```md
# tool-name

One-line description of what the CLI does.

## Installation

```bash
npm install -g tool-name
```

## Usage

```bash
tool-name [options] <input>
```

## Options

| Option | Description |
|--------|-------------|
| `-o, --output` | Output file path |
| `-v, --verbose` | Enable verbose output |
| `-h, --help` | Show help |

## Examples

```bash
tool-name -o result.txt input.txt
tool-name --verbose data.json
```

## License

MIT
```
</details>

<details>
<summary>Library/Package Template</summary>

```md
# library-name

Brief description of the library.

## Installation

```bash
npm install library-name
```

## Quick Start

```javascript
const lib = require('library-name');

lib.doSomething();
```

## API Reference

### `methodName(param)`

Description of the method.

**Parameters:**
- `param` (string): Description

**Returns:** Description of return value

**Example:**
```javascript
lib.methodName('value');
```

## Contributing

PRs welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT
```
</details>

<details>
<summary>API Documentation Template</summary>

```md
# API Name

Base URL: `https://api.example.com/v1`

## Authentication

All requests require an API key in the header:
```
Authorization: Bearer YOUR_API_KEY
```

## Endpoints

### GET /resource

Retrieve all resources.

**Response:**
```json
{
  "data": [],
  "count": 0
}
```

### POST /resource

Create a new resource.

**Request Body:**
```json
{
  "name": "string",
  "value": "number"
}
```

## Error Codes

| Code | Description |
|------|-------------|
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |
| 500 | Server Error |
```
</details>

# Quick Reference Card

A condensed cheat sheet for common Markdown syntax.

| Element | Syntax |
|---------|--------|
| **Heading** | `# H1` `## H2` `### H3` |
| **Bold** | `**text**` |
| **Italic** | `*text*` |
| **Bold + Italic** | `***text***` |
| **Strikethrough** | `~~text~~` |
| **Code** | `` `code` `` |
| **Link** | `[text](url)` |
| **Image** | `![alt](url)` |
| **Blockquote** | `> quote` |
| **Unordered List** | `- item` |
| **Ordered List** | `1. item` |
| **Task List** | `- [x] done` `- [ ] todo` |
| **Horizontal Rule** | `---` |
| **Table** | `\| a \| b \|` |
| **Footnote** | `text[^1]` `[^1]: note` |
| **Inline Math** | `$equation$` |
| **Block Math** | `$$equation$$` |
| **Escape** | `\*` `\#` `\_` |

### Code Block
````
```language
code here
```
````

### Alerts
```md
> [!NOTE]
> [!TIP]
> [!IMPORTANT]
> [!WARNING]
> [!CAUTION]
```

### HTML Shortcuts
```md
<details><summary>Title</summary>Content</details>
<kbd>Key</kbd>
<sub>subscript</sub>
<sup>superscript</sup>
```

---

 <h1>Some Useful Tips</h1>
 
> [!TIP]
> - [x] Start with a 1–2 line summary explaining what the project does and who it’s for.
> - [x] Add a clear title + short tagline (people decide in 5 seconds).
> - [x] Show a screenshot/GIF early (especially for UI tools, dashboards, web apps).
> - [x] Include a “Features” section with 4–6 bullets (what makes it useful).
> - [x] Add a “Tech Stack” section (helps recruiters + contributors instantly).
> - [x] Provide quick install steps that work copy‑paste (no long paragraphs).
> - [x] Add a minimal “Usage” example (command/API snippet + expected output).
> - [x] Document configuration: env vars, keys, ports, config files (brief + clear).
> - [x] Include a simple folder structure so readers understand the codebase fast.
> - [x] Add a “Roadmap / TODO” (shows direction and ongoing development).
> - [x] Mention prerequisites (versions, OS, tools) to reduce setup friction.
> - [x] Link to important docs (CONTRIBUTING, LICENSE, SECURITY, wiki, demo).
> - [x] Use consistent headings and formatting (makes it readable + professional).
> - [x] Add “How to Contribute” (even 3 steps: fork → branch → PR).
> - [x] End with “License + Contact” (makes the project feel complete and credible).

---

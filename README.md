# Markdown to HTML Converter

## Description
This is a simple, static web application that converts Markdown text into HTML. It allows users to input Markdown in a text area, which is then rendered as HTML in a designated output area. The application also supports syntax highlighting for code blocks using highlight.js.

## Features
- **Real-time Conversion:** Converts Markdown to HTML as you type.
- **Syntax Highlighting:** Highlights code blocks within the Markdown input.
- **Responsive Design:** Works well on different screen sizes.
- **Word Count:** Displays a live word count of the Markdown input, updated after every render, and formatted with Intl.NumberFormat.

## Usage
1.  Open `index.html` in your browser.
2.  Type Markdown into the text area.
3.  The converted HTML will be displayed in the output area below.
4.  Code blocks are automatically highlighted.
5.  The word count is displayed below the input area.

## Technologies Used
- HTML
- CSS
- JavaScript
- [marked.js](https://github.com/markedjs/marked) for Markdown parsing.
- [highlight.js](https://highlightjs.org/) for syntax highlighting.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
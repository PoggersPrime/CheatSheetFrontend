**HTML Cheat Sheet**

<h1> Document Structure </h1>

- `<!DOCTYPE html>`:

  - Declaration that specifies the document type and version of HTML being used.

- `<html>`:

  - Root element that wraps all content on the webpage.
  - **Attributes:**
    - `lang`: Specifies the language of the document.

- `<head>`:

  - Container for metadata and links to external resources such as CSS stylesheets and JavaScript files.

- `<title>`:

  - Sets the title of the webpage, displayed in the browser's title bar or tab.

- `<meta>`:

  - Provides metadata about the HTML document such as character set, viewport settings, and description.
  - **Attributes:**
    - `charset`: Specifies the character encoding for the document.
    - `name`: Specifies metadata such as description, keywords, author, etc.
    - `content`: Provides the value for the metadata.

- `<body>`:
  - Contains the main content of the webpage, including text, images, links, and other elements.

# <h2> Text Content </h2>

- `<h1> to <h6>`:

  - Defines headings of varying sizes, with `<h1>` being the largest and `<h6>` being the smallest.

- `<p>`:

  - Defines a paragraph of text.

- `<a>`:

  - Creates a hyperlink to another webpage or resource.
  - **Attributes:**
    - `href`: Specifies the URL of the linked page or resource.
    - `target`: Specifies where to open the linked document (e.g., `_blank` for a new tab).

- `<img>`:

  - Embeds an image in the webpage.
  - **Attributes:**
    - `src`: Specifies the URL of the image.
    - `alt`: Provides alternative text for the image (for accessibility and SEO).

- `<ul>` and `<ol>`:

  - Defines unordered and ordered lists, respectively.

- `<li>`:

  - Defines a list item within an `<ul>` or `<ol>`.

- `<br>`:

  - Inserts a line break within text.

- `<hr>`:
  - Inserts a horizontal rule, commonly used to separate sections of content.

# <h2> Structural Elements </h2>

- `<div>`:

  - Defines a division or section of content, often used for styling with CSS.

- `<span>`:

  - Inline element used to apply styles or manipulate text within a larger block of content.

- `<header>`, `<footer>`, `<nav>`, `<section>`, `<article>`, `<aside>`:
  - HTML5 semantic elements used to define different sections of a webpage for improved structure and accessibility.

# <h2> Form Elements </h2>

- `<form>`:

  - Container for form elements such as input fields, buttons, and dropdowns.
  - **Attributes:**
    - `action`: Specifies the URL where the form data will be sent.
    - `method`: Specifies the HTTP method used to submit the form (e.g., GET or POST).

- `<input>`:

  - Creates an input field for accepting user input, with various types such as text, password, checkbox, radio, etc.
  - **Attributes:**
    - `type`: Specifies the type of input field.
    - `name`: Specifies the name of the input field.
    - `value`: Specifies the initial value of the input field.

- `<label>`:

  - Associates a label with an input field for improved accessibility and usability.
  - **Attributes:**
    - `for`: Specifies which input element the label is bound to.

- `<textarea>`:

  - Creates a multiline text input field.
  - **Attributes:**
    - `rows`: Specifies the visible number of rows in the textarea.
    - `cols`: Specifies the visible number of columns in the textarea.

- `<button>`:

  - Defines a clickable button.
  - **Attributes:**
    - `type`: Specifies the type of button.

- `<select>` and `<option>`:
  - Creates a dropdown menu with selectable options.
  - **Attributes:**
    - `value`: Specifies the value of each option.
    - `selected`: Specifies that an option should be pre-selected.

# <h2> Media Elements </h2>

- `<audio>`:

  - Embeds audio content in the webpage.
  - **Attributes:**
    - `src`: Specifies the URL of the audio file.
    - `controls`: Specifies whether the browser should provide controls for audio playback.

- `<video>`:

  - Embeds video content in the webpage.
  - **Attributes:**
    - `src`: Specifies the URL of the video file.
    - `controls`: Specifies whether the browser should provide controls for video playback.

- `<iframe>`:
  - Embeds a webpage or external content within the current webpage.
  - **Attributes:**
    - `src`: Specifies the URL of the content to embed.
    - `width` and `height`: Specifies the dimensions of the iframe.

# <h2> Miscellaneous </h2>

- `<!-- -->`:

  - Defines a comment within the HTML code, not visible to users but useful for documenting code or adding notes.

- `<script>`:
  - Embeds JavaScript code within the webpage for dynamic behavior and interactivity.
  - **Attributes:**
    - `src`: Specifies the URL of the external script file.
    - `type`: Specifies the MIME type of the script.

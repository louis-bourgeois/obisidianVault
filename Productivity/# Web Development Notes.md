# Web Development Notes

## How the Web Works
- DNS servers act as a directory, converting requests into IP addresses.
- Clients send requests to DNS servers and receive responses from company servers.
- Company servers host websites and send necessary files (CSS, HTML, JavaScript) to clients.
- ISPs (Internet Service Providers) transmit client requests to DNS servers.

## HTML

### Tags and Formatting
- An element (content + tags) is not equal to a tag.
- HTML tags structure and format web content.
- **Nested lists**: A list within a list.
- **Alignment and Breaks**: Tags like `<center>` and `<br>` are used for alignment and creating line breaks.
- **Headings**: `<hx>` tags represent headings, with the number determining the level of hierarchy.
- **Div Element**: `<div> content </div>` allows creating a box that gathers multiple elements (useful for CSS).
- **Lists**: 
  - `<ul>` creates unordered lists (bullets, etc.).
  - `<ol>` creates ordered lists (numbers, letters, etc.).
  - `<li>` acts as a list item.
- **Hyperlinks**: `<a>` is the tag for hyperlinking. Using `target="_blank"` will open the link in a new page.
- Tags can have attributes for size, color, alignment, etc.
- Some tags are self-closing and don't require a separate closing tag.

### Meta Elements
- Provide additional metadata within HTML files, such as site descriptions and character encoding.
- HTML files often start with a meta element to specify metadata.
- Contribute to enhancing the browsing experience and search engine optimization (SEO).

### Tables
- Created using the `<table>` tag.
- A table consists of a head, body, and footer:
  - **Head**: `<thead>` contains header cells (`<th>`).
  - **Body**: `<tbody>` contains rows added using the `<tr>` tag, with cells (`<td>`).
  - **Footer**: `<tfoot>`.
- Recommended to use CSS for styling instead of inline styles.
- Attributes such as `cellspacing` and `cellpadding` allow adjusting the space between cells.
- Tables can be used for text layout without borders for specific visual effects.
- Cells are placed horizontally one after the other; there are no table columns.

## Relative File Paths
- Based on the project's location and independent of the computer's root or computer name.
- `..` before the path allows moving up a level in the file hierarchy.
- `./` represents the current directory, but often it is not necessary to include it.

## CSS

### Structure
- CSS is structured with properties and values, similar to a JSON file.
- There are three ways to add CSS to an HTML file:
  - **Inline**: `<element style="css"/>` (useful for single changes).
  - **Internal**: CSS added within the `<style>` tags (useful for single-page sites).
  - **External**: `<link href="style.css" rel="stylesheet"/>` (commonly used).

### Selectors
- CSS rules consist of a selector and the corresponding properties and values.
- Types of selectors:
  - **Element Selector**: `element { property: value; }`.
  - **Class Selector**: `.classname { property: value; }`.
  - **ID Selector**: `#id_name { property: value; }`.
  - **Attribute Selector**: `element[attribute='value'] { property: value; }`.
  - **Universal Selector**: `* { property: value; }`.

### Properties

#### Text Properties
- `text-align`: values include center, left, right, start, end.

#### Font Properties


- `font-weight`: values include bold, normal, numeric values (100 to 900), or relative units (lighter, bolder).
- `font-family`: specify font names or generic types (serif, sans-serif).
- `font-size`: specify in absolute units (px, pt) or relative units (em, rem).

#### Layout and Box Model
- `width` and `height`: specify dimensions using units like px, pt, %.
- **Borders**:
  - `border`: define thickness (px), style (dashed, solid), and color.
  - `border-top` (or left, right, bottom): change specific border sides (must have a `border` attribute before).
  - `border-width`: takes 4 values (top, right, bottom, left) or 2 values (horizontal, vertical) in units like px.
- **Margin**: defines the space outside of the border. Can also take 2 or 4 values (similar to `border-width`).
- **Padding**: pushes the content out from the inside of the border. Also takes 2 or 4 values (similar to `border-width`).
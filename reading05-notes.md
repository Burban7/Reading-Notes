# Design Web Pages with CSS


### ***What is CSS?***

**********************

- **CSS (Cascading Style Sheets)** allows you to create great-looking wepages by controlling how HTML elements look in the browser.

- A **document** is usually a text file structured using a markup language like HTML.

- **Presenting** a document to a user means converting it into a form usable by your audience.

- CSS can be used for a number of things:
  - **Basic document text styling**: such as changing the color and size of headings and links.
  - **Creating a layout**: Such as turning a single column of text into a layout with a main content area and a sidebar for related information.
  - **Creating effects**: Such as animations.

- CSS is a rule-based language - you define rules specifying groups of stles that should be applied to particuar elements or groups of elements on your web page.

- CSS rules open with a **selector** which is used to select the HTML element you are going to style.

- CSS rules have a set of curly braces inside of which will be one or more **declarations**, which take the form of **property** and **value** pairs.

- The CSS language is broken down into **modules**


### ***How to add CSS***

***********************

- Using an **external** CSS, you can change the entire look of a website by changing a single file.
  - Each HTML page must include a reference to the external style sheet file inside the **`<link>`** element, inside the head section.
  - An external style sheet can be written in any text editor, and must be saved with a **.css** extension.
  - The external .css file should not contain any HTML tags.

- An **internal** CSS may be used if a single HTML page has a unique style.
  - The internal style is defined inside the **`<style>`** element, inside the head section.

- An **inline** CSS may be used to apply a unique style for a single element.
  - To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
  - An inline style loses many of the advantages of a style sheet.

- If there is more than one style specified for an HTML element, all styles in the page will "cascade" into a new "virtual" style sheet in the following order:
  1. Inline Style
  2. External and Internal style sheets
  3. Browser Default

- An inline style has the highest priority and will override external/internal styles and the browser defaults.


### ***Repository Directory***

************************

- [Growth Mindset](https://burban7.github.io/Reading-Notes)
- [Learning Markdown](https://burban7.github.io/Reading-Notes/reading01-notes)
- [The Coder's Computer](https://burban7.github.io/Reading-Notes/reading02-notes)
- [Revisions and the Cloud](https://burban7.github.io/Reading-Notes/reading03-notes)
- [Structuring Web Pages with HTML](https://burban7.github.io/Reading-Notes/reading04-notes)
- [Dynamic Web Pages with JavaScript](https://burban7.github.io/Reading-Notes/reading06-notes)

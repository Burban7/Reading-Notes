# Learning Markdown


### ***What is Markdown?***

Markdown is a lightweght markup language used to generate HTML files. While HTML offers you more control, Markdown is much faster at authoring.

For more information on the general description of Markdown check out [What is Markdown?](https://becomeawritertoday.com/what-is-markdown/)

**********

### ***Commands used in Markdown***

- To create a **Header**, use the command `# Text`
  - The size of your headers can range from one \# (biggest) to six \# (smallest)
  - This command can be translated into the HTML command `<h1> Text </h1>`
  - Alternatively, you can use the commands `----` or `====` placed a line below the desired text
  - Be sure to leave a line of space above and below your header

- To create **individual paragraphs**, leave a  line of space between groups of text
  - When writing in HTML, use the command `<p> Text </p>`
  - Unless paragraphs are part of a list, keep text left-aligned

- To create **line breaks** or a new line, end a text line with two or more spaces before hitting return
  - This can be translated into the HTML command `<p> Text <br> Text </p>`

- To make a selected text **Bold**, use the commands `**Text**` or `__Text__`
  - When writing in HTML, use the command `<strong>Text</strong>`
  - When making the middle of a word bold, always use the asterisks for the sake of compatability

- To ***italicize*** a desired text, use the commands `*Text*` or `_Text_`
  - When writing in HTML, use the command `<em>Text</em>`
  - Follow the same asterisks rule as mentioned above when italicizing the middle of a word

- To both **Bold** and ***Italicize*** a desired text, use the command `***Text***` or `___Text___`
  - When writing in HTML, use the commands `<strong><em>Text</em></strong>`

- To create a **blockquote**, use the command `> Text`
  - To **nest a paragraph inside of a blockquote**, use the command `>> Text`
  - Not all elements can be used inside of a blackquote
  - Make sure to leave a line of space above and below a blockquote

- To create **ordered lists**, use the command `1. Text`
  - You can select any number you want before each line of text and it will render in the correct order
  - When writing in HTML, use the commands `<ol> <li> Text </li> </ol>`

- To create **unordered lists**, use the commands `* Text`, `- Text`, or `+ Text`
  - When writing in HTML, use the commands `<ul> <li> Text </li> </ul>`
  - You can create **nested lists** by indenting lines of text
  - Make sure to use the same delimeters throughout your list

- To create a **codeblock**, indent every line by atleast four spaces or one tab
  - To avoid indenting, you can use **fenced code blocks** by using the command ` ``` ` on the lines before and after the codeblock

- To add an **image**, use the command `![Text](IMG Src)`
  - You can add a **link to an image** by using the command `![Text](IMG Src)](url)`
  - To **add an image to a list**, indent atleast four spaces or one tab before using the command above

- To denote a word or phrase as **code**, use a the command `` `Text` ``
  - When writing in HTML, use the command `<code>Text</code>`

- To create a **horizontal rule**, use the commands `***`, `---`, or `___` 
  - Leave a line of space before and after a horizontal rule

- To create a **link**, use the command `[Text](url)`
  - To add a title to a link, you can use the command `[Text](url "Text")`

- To quickly turn a **url or email address into a link**, use the command `<Text>`

- You can mention a person or team by using the commands `@Username` and/or `@Team`

- You can add an emoji by using the command `:Emojicode:`
  - Typing the command `:` will bring up a list of suggested emoji

- To add a **footnote**, use the command `^Note` or `^1`
  - The footnote will render at the bottom of the page regadless of where it is placed in markdown

- To ignore or bypass markdown formatting, use the command `\` before the desired character

**********

### ***What is GitHub Pages?***

[GitHub Pages](https://pages.github.com/) is an online tool that allows you to turn your GitHub repositories into rendered websites, which you can use to showcase your portfolio, projects, and more. Github Pages is the most direct path to turning your projects into websites, automatically building and deploying your work. It offers a straight-forward, quick and easy publishing experience through the help of [Jekyll](http://jekyllrb.com/), an open-source tool that transforms your text files into completed webpages. If GitHub is where you create, GitHub pages is where you share those creations.

**********

### ***Repository Directory***

- [Growth Mindset](https://burban7.github.io/Reading-Notes/)

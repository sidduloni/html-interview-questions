# html-interview-questions
Html interview questions with answers

Sure, I'd be happy to provide answers to your HTML-related questions:

## S.No 1: What is `<!Doctype html>` in HTML5?
**Ans:** `<!DOCTYPE html>` is an HTML5 declaration that is used at the beginning of an HTML document to specify the document type and version. It tells the browser that the document is written in HTML5. This declaration is necessary for the browser to interpret the page correctly.

## S.No 2: What is the difference between `div` and `span` in HTML?
**Ans:** `div` and `span` are both HTML elements used for structuring and styling content, but they have different purposes. 

- `<div>` is a block-level element used for grouping and structuring larger sections of content. It typically creates a line break before and after its content, making it suitable for creating divisions or containers for various elements.

- `<span>` is an inline element used for applying styles or scripting to smaller portions of text or elements within a larger block of content. It doesn't create line breaks, so it's useful for applying styles to individual words or elements within a sentence or paragraph.

## S.No 3: What are semantic tags and non-semantic tags in HTML?
**Ans:** Semantic tags in HTML are elements that carry meaning about the structure of the document's content. They provide information about the type of content they enclose. Examples of semantic tags include `<header>`, `<nav>`, `<article>`, and `<footer`. They make the HTML document more structured and understandable.

Non-semantic tags, on the other hand, do not convey any specific meaning about the content. Examples of non-semantic tags include `<div>` and `<span>.` They are used primarily for layout and styling purposes and do not provide information about the document's structure.

## S.No 4: What is the difference between HTML and HTML5?
**Ans:** HTML (Hypertext Markup Language) is a standard markup language for creating web pages. HTML5 is the fifth major revision of HTML. The main differences between HTML and HTML5 include:

- **New Elements:** HTML5 introduced several new elements like `<nav>`, `<section>`, and `<header>` for better structuring web content.

- **Multimedia Support:** HTML5 added native support for audio and video elements, reducing the need for external plugins like Flash.

- **Canvas and SVG:** HTML5 includes the `<canvas>` element for drawing graphics and the ability to embed scalable vector graphics (SVG).

- **Improved Form Elements:** HTML5 introduced new form input types like email, date, and number, along with form validation features.

- **Local Storage:** HTML5 introduced the `localStorage` and `sessionStorage` for client-side data storage.

- **Improved Accessibility:** HTML5 includes features to enhance web accessibility, such as ARIA roles and attributes.

- **APIs:** HTML5 comes with new JavaScript APIs for geolocation, drag and drop, and more.

## S.No 5: What is the `<iframe>` tag in HTML5?
**Ans:** The `<iframe>` (Inline Frame) tag in HTML5 is used to embed another HTML document within the current document. It is often used to display content from other websites or include external content like videos, maps, or widgets on a web page. The content within the `<iframe>` is sandboxed, which means it operates independently from the parent document to enhance security.

## S.No 6: What are the formatting tags in HTML?
**Ans:** Formatting tags in HTML are used to apply various styles and formatting to text and elements. Some common formatting tags include:

- `<b>`: Used to make text bold.
- `<i>`: Used to italicize text.
- `<u>`: Used to underline text (although not recommended for semantic reasons).
- `<strong>`: Used to indicate strong importance, typically displayed as bold.
- `<em>`: Used to emphasize text, typically displayed as italic.

It's worth noting that HTML5 promotes the use of semantic tags and CSS for styling, making these formatting tags somewhat outdated.

## S.No 7: What is the difference between `<b>` and `<strong>` in HTML?
**Ans:** Both `<b>` and `<strong>` are used to make text bold, but they have different semantic meanings:

- `<b>` is a non-semantic tag used for applying bold styling to text. It doesn't convey any specific meaning about the content's importance or significance.

- `<strong>` is a semantic tag used to indicate that the enclosed text is of strong importance or emphasis. Browsers typically render the text as bold, but the primary purpose is to provide semantic meaning to the content, making it more accessible for screen readers and search engines.

## S.No 8: What is the viewport attribute in HTML?
**Ans:** The viewport attribute is not a standard HTML attribute. It might be referring to the `<meta>` viewport tag used in HTML to control how a web page is displayed on mobile devices. Here's an example of its usage:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

This tag is used to configure the viewport's width to match the device's width and set the initial zoom level. It's crucial for making web pages responsive on various screen sizes.

## S.No 9: What is an attribute in HTML?
**Ans:** In HTML, an attribute is additional information provided within the opening tag of an element. Attributes are used to modify or provide extra information about an element. They are defined using a name-value pair, where the name represents the attribute's name, and the value specifies its value.

For example:
```html
<a href="https://www.example.com">Click here</a>
```

In this `<a>` (anchor) tag, `href` is an attribute, and `"https://www.example.com"` is its value. Attributes can be used to control an element's behavior, appearance, or link it to external resources.

## S.No 10: What is a block-level element and an inline element in HTML?
**Ans:** In HTML, elements are categorized into two main types: block-level and inline elements.

- **Block-Level Elements:** Block-level elements create a new block formatting context and typically start on a new line. They occupy the full available width of their parent container, pushing other content below them. Examples of block-level elements include `<div>`, `<p>`, and `<h1>`.

- **Inline Elements:** Inline elements do not create a new block formatting context and flow within the content of surrounding elements. They only occupy the necessary width to display their content, so they do not start on a new line. Examples of inline elements include `<span>`, `<a>`, and `<strong>`.

## S.No 11: What is the difference between HTML and HTML5?
**Ans:** I've already answered this question in point 4.

I hope these answers help clarify your HTML-related questions. If you have any more questions or need further information, feel free to ask.

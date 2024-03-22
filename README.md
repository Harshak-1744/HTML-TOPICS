# HTML Topics with Challenges

## Forms
Forms are used to gather information from the user and send that data to the server.

### Attributes:
- **`accept`**: Defines the types of files that the server accepts (only for `type="file"`).
- **`accept-charset`**: Specifies the character encodings accepted by the server for form submission.
- **`action`**: Specifies where to send the form data when the form is submitted.
- **`autocomplete`**: Specifies whether the form should have autocomplete on or off.
- **`enctype`**: Defines the content type of the form submission (used when method is "POST").
- **`method`**: Specifies the HTTP method to use when sending form data.
- **`name`**: Specifies the name of the form.
- **`novalidate`**: Indicates the form should not be validated when submitted.
- **`target`**: Specifies where to display the response received after submitting the form.

## Import
Import in the context of HTML and web development broadly refers to bringing external resources, such as CSS stylesheets, JavaScript files, fonts, and multimedia content, into an HTML document.

## Elements
In HTML, elements are the building blocks of web pages. An element can be a heading, a paragraph, a link, an image, etc. Elements are represented by tags, which can have attributes to provide additional information about the element's content or behavior.

## Attributes
Attributes provide additional information about HTML elements. They are always specified in the start tag (or opening tag) of an element and usually come in name/value pairs like `name="value"`.

## Semantics
Semantics in HTML refers to the meaning of the elements and attributes used to build web pages. Semantic HTML uses elements that accurately describe their purpose and content.

## Multimedia
Multimedia in HTML refers to the incorporation of media content such as images, audio, and video into web pages.

## Block Elements
Block elements are HTML elements that typically start on a new line and stretch out as wide as their parent element allows, creating a "block."

## Inline Elements
Inline elements are those that do not start on a new line and only take up as much width as necessary.

## Forms and Input
Forms and Input elements are used to create forms for user input.

## Tables
Tables are used to display data in a grid-like format of rows and columns.

## Lists
Lists in HTML are used to group a set of related items in a list format.

## CSS Integration
CSS Integration refers to the methods by which CSS is applied to HTML documents to control the presentation of web pages.

## Challenges

- **C1**: Create a Form which covers all the necessary attributes.

- **C2** (Import Challenge): Integrate External Resources: Create an HTML page that integrates external CSS for styling and an external JavaScript file for functionality. Use the `<link>` tag to include the CSS file and the `<script>` tag for the JavaScript file. Ensure the JavaScript manipulates the DOM to add dynamic content to the page.

- **C3** (Elements Challenge): Multimedia Content Page: Build a web page showcasing various HTML elements. Include headings, paragraphs, links, images, and a video. For a bonus challenge, make sure the page is semantically structured using elements like `<article>`, `<aside>`, `<footer>`, and `<header>`. Apply CSS for styling to differentiate between the types of content visually.

- **C4** (Attributes Challenge): Image Gallery with Advanced Attributes: Create an image gallery using the `<img>` element. Utilize the srcset attribute to offer different resolutions based on the user's device screen size. Also, use the alt attribute for accessibility. Style the gallery with CSS, making it responsive to screen size changes.

- **C5** (Semantics Challenge): Semantic Web Page Structure: Design a semantically structured web page for a blog post. The page should include a `<header>` with the site's navigation, an `<article>` for the blog post content, `<section>` elements for different parts of the content, `<aside>` for related links or information, and a `<footer>` for site-wide links or copyright information. Style the page with CSS to visually separate these sections.

- **C6** (Multimedia Challenge): Video and Audio Integration: Embed a video and an audio clip into a web page. Use the `<video>` and `<audio>` elements, ensuring controls are available for play, pause, and volume. For an extra challenge, customize the controls with JavaScript and CSS for a unique user interface.

- **C7** (Block Elements Challenge): Layout with Block Elements: Create a web page layout using block elements such as `<div>`, `<section>`, and `<article>`. Design a header, a main content area with a sidebar, and a footer. Use CSS Flexbox or Grid to arrange the layout. Ensure the layout is responsive and adjusts

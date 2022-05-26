# HTML & CSS Notes

HyperText Markup Language and Cascading Style Sheets - notes

## Semantic HTML

- Writing semantic HTML means giving meaning to the elements we use.
- Semantic HTML focuses on providing meaning and purpose for the elements you use.
- Some of the benefits of semantic HTML:
  - It makes your code machine-readable. Browsers and search engines will better understand your website.
  - It helps you make sense of the information on the page.
  - It helps you maintain the code as it makes it a lot more readable.

## Headings

- The h1 to h6 elements represent six levels of section headings. h1 is the highest section level, and h6 is the lowest.
- The h4, h5, and h6 elements are not very frequently used. You don't have to use all heading elements. It depends on the content that you're representing.
- Avoid skipping heading levels. If you have an h1, the following heading level under it should be h2.

## Heading: h1

- The heading 1 h1 element is used to represent the highest-level, most important topic of the current web page.
- h1 is the most important topic of the page
- When writing HTML code, it's important to focus on the semantics rather than the appearance. HTML is meant for the content, and the structure, whereas CSS is used to style that content (appearance).
- You should not use an HTML element based on its appearance but rather its meaning/purpose/role.
- If you're not sure which element should be labeled as the h1 on the page, ask yourself: What is the most important topic on this page?

## Accessibility

- In the context of HTML (and websites in general), accessibility refers to making your website usable for everyone.
- People have a range of abilities.
- As we get older, our functional abilities deteriorate.
- Here are some benefits of accessibility:
  - It's a technical skill that you add to your tool belt.
  - It helps you practice empathy.
  - It increases the conversion rate for your product as you allow more people to use it.
  - You get to decide whether you give people access or deny them access to your product. By making it accessible, you are allowing them to access it.
  - In some countries or organizations, accessibility is a legal requirement. That is the case in several countries.
- A screen reader is a software that has commands to jump between headings or specific landmark regions quickly.
- A survey of screen reader users concludes that they usually navigate an unfamiliar page by exploring the headings.

## Attributes

- Every HTML element can have one or more key="value" pairs that allow you to customize or configure the element. These key="value" pairs are called attributes.
- The lang attribute specifies the language of this element (and all of its children). By default, the language is unknown.
- The lang attribute does not default to English. It defaults to unknown, which is an accessibility issue.
- It's possible to have more than one attribute on the same element.

## HTML Structure

- The doctype specifies the version of HTML that you want the browser to use when rendering your page.
- The html element is the root element of the page. This is the highest element because all other elements on the page will be a descendant of this element. It is allowed to have two specific child elements, head and body.
- The head element contains information and data that is meant to be processed by machines (such as browsers, search engines, and crawlers used by social networks).
- The body element is the element that contains all the content of your HTML page.

## The head - metadata

- The head element contains information and data that is meant to be processed by machines (such as browsers, search engines, and crawlers used by social networks).
- The meta element is a generic element used to provide additional data and details about the current web page. For example, this could be the image used when this web page is shared on social media, and the behavior of the web page when opened on a mobile device.
- The meta element is the first element we learn that is an empty element. An empty element cannot have any child elements. Thus, it does not have a closing tag.
- Ensure the meta charset is specified as the first element inside the head element.
- The meta viewport asks the browser to represent the web page's width according to the current device (example: mobile phone)'s width. You should always use it.
- The title element shows the webpage's title in the browser's tab bar.

## Blank Space & New Lines

- If you have more than one blank space, it will be rendered as one blank space in the browser.
- Newline characters are converted into a single blank space character.
- If you need to render a new line character, you have to use the br tag.
- The Line Break br element produces a new line (also called carriage-return).
- The br element should not be used to separate paragraphs or two elements. It should only be used to create a new line within the same sentence or context.

## Comments

- A comment is a piece of text written by the developer with the purpose to describe what's happening in the code, providing clarification, a note to your future self, or other notes.
- A comment is not displayed by the browser. So it does not affect how your website looks or behaves.
- HTML elements that are commented out are not displayed by the browser. It's as if they never existed in the first place.
- Multi-line comments are possible. The comment starts with <!-- and ends with -->.

## The p element

- The p element is used to represent a paragraph of text on a web page.
- Screen readers announce the p element as a paragraph. This is important. It allows the user to hear a few words of the paragraph and then skip to another one.
- Breaking up content into paragraphs helps make a page more accessible.
- A paragraph does not necessarily need to have more than one sentence.
- You will notice that a paragraph always starts on a new line. Also, browsers will automatically add some space that acts as a separation before and after the paragraph.

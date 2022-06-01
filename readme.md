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
- Multiple paragraphs should be wrapped with multiple paragraph elements.
- The br element should not be used to separate paragraphs or two elements. Instead, it should only be used to create a new line within the same sentence or context.
- It's important to know that you cannot nest a paragraph inside another one.
- While you don't technically need to wrap text with a p element, we recommend that you do. This helps you write semantic and accessible code.

## Lists

- The ol (ordered list) element represents a list of items where the items have been intentionally ordered. Changing the order would change the meaning of the list (most likely breaking the original meaning).
- The ul element represents a list of items where the order of the items does not matter. Changing the order would not change the meaning of the document.
- The li (list item) element is used inside either an ol or a ul element. It does not have a meaning by itself, so it must be written inside an ol or ul.
- The ol and ul both represent a list of items. When the order matters, you should use an ol. When the order doesn't matter, you should use ul.
- An element is said to be nested inside another one when the opening and closing tags of the first element wrap the other element.
- ol>li + Tab will generate an ol element with a li element nested inside of it.

## HTML Validity

- Modern browsers never crash because of invalid HTML.
- Valid HTML will make your life easier when maintaining websites.
- The w3 offers an HTML validator hosted at validator.w3.org.
- Our recommendation in this course is to try often and validate your HTML code manually using this website. It will serve as a learning experience.
- Failing the validation with a few errors is better than failing with a dozen or a hundred.

## Landmark Elements

- Landmark elements aim to break the page into several recognizable areas.
- Accessibility benefit: A user can use accessibility software such as a screen reader to navigate and understand these landmarks.
- Semantics benefit: Machines such as search engines can better understand your page and how your website is linked when you have content inside landmarks.
- The main element is used to represent the dominant contents of the page. It contains the content related to the main topic of the page.
- The header element represents the content used to introduce the web page. This usually contains a heading element (such as h1), a logo, and some navigational elements (covered later).
- The footer element represents the footer of the page. The word footer here does not necessarily mean that the element is visually placed at the bottom of the page. Instead, it contains data usually represented towards the end of a document. Such as links to related documents, copyright data, additional information, etc.

## strong and b elements

- The strong element is used to represent content that has strong importance, seriousness, or urgency. This is usually seen in relation to its surrounding.
- The strong element is represented by most browsers as bold text. But, this should not be the reason why it's used.
- The b element (bring attention to) is used to draw attention to some content without giving it more importance, seriousness, or urgency.
- The differences between strong and b are subtle. It all comes down to whether you want to give importance to the content (strong) or not (b).
- As long as you're not overusing the strong and b tags, you can usually use strong if you're in doubt.

## em and i elements

- The em (emphasis) element represents a word or group of words that are stress emphasized. This often affects the meaning of the sentence.
- The em element is represented by most browsers as italic text (this is italic text). But, this should not be the reason why it's used.
- The i (idiomatic text) element represents a word or group of words usually said in an alternate voice or mood. It could also be used to denote technical terms, words from other languages, or idioms.
- It's a good practice to add the lang attribute when i is representing content in a different language.
- The strong element is used to represent content that has strong importance. In contrast, the em element is used to convey stress.

## Inline vs Block Elements

- The strong, em, b, and i elements behave differently than the p, ul, ol, li, and h1-h6 elements.
- p, ul, ol, li, div, and h1-h6 are block elements.
- Block elements stretch into the entire line.
- The strong, em, b, and i elements are examples of inline elements.
- Inline elements do not stretch into the entire line. They take up as much space as their content.

## The img element

- The img element is used to display an image on the page.
- The src attribute (short) for source is used on the img element to define the path (location) of the image to be loaded.
- The width and height attributes are used to define the image's aspect ratio. The browser uses this to reserve the appropriate number of pixels on the screen while the image is loading. Once the image is fully loaded, the empty pixels are swapped with the image without causing a layout shift.
- Make sure always to include the width and height attributes with the correct values, even if you'd like to make the image responsive. We'll discuss that later when we learn about CSS.
- Several scenarios prevent an image from being displayed.
- Providing an alternative text has many benefits. Mostly for accessibility and SEO.
- A decorative image is an image used for the sole purpose of aesthetics and design on a page. These require an empty alt text alt="".
- Informative images are images that add value to a web page. These require descriptive alt text.
- You should always provide an alt attribute (whether that's an empty string or an actual alternative text).

## CSS

- CSS stands for Cascading Style Sheets.
- CSS is used to style and design the content you wrote in HTML.
- So, CSS goes hand-in-hand with HTML. However, it's important to note that:
  - HTML is used for the content.
  - CSS is used for styling.
- The style tags are used in this course's lessons to display short HTML + CSS code combined.
- A CSS selector is used to find the elements in a webpage that will receive a set of styles.
- The CSS syntax is made up of 2 main elements:
  1.  A CSS selector (for example, h1)
  2.  A set of declarations that will be applied for this selector (the code between the curly braces).
- A declaration can be broken down into two parts:
  1.  CSS property (for example, color).
  2.  Value (for example, red).
- A CSS Comment /_ comment here _/ is ignored by the browser.

## Font Weight

- font-weight: bold makes a text represented in bold without affecting its semantic meaning.
- font-weight: normal makes a text represented in normal font weight (not bold).
- The strong element should not be used to make an element styled in bold. It should only be used to convey semantic meaning. A strong element can be rendered without bold font by adjusting its font-weight.

## The Cascade

The cascade is a set of rules defined by CSS that dictates which declaration is chosen when an element has the same property (but potentially with different values).

- The last encountered property will overwrite a previously specified property.
- Later, we'll learn about specificity, which affects how properties are overwritten.
- You can usually access DevTools by right-clicking anywhere on the page and selecting the Inspect or Inspect element option.

## User-Agent Stylesheet

- A user-agent stylesheet refers to a stylesheet provided by your browser.
- User-agent styles have the lowest priority in the cascade. Any CSS code you write will always overwrite the user-agent's styles.
- Every browser has a CSS file (user-agent stylesheet) that is always included first. Your CSS code comes after this. You never have to write the styles that are provided by the user-agent.
- User-agent styles are meant as a "default" stylesheet. Any CSS code you write will then overwrite it.

## CSS Inheritance

- Many CSS properties (but not all of them) are inherited. This means the CSS property will affect the child elements (as long as we do not overwrite it).
- When a CSS property value is passed from a parent to a child during inheritance, we call that value a computed value.

## font-size property

- The font-size CSS property is used to set the size of the font used on the current element.
- The font-size property is inherited.
- On the web, a pixel's size is not standardized. A pixel might be larger or smaller than on other displays. This is usually not an issue with the way we write responsive CSS.
- The page's default font-size is 16px.

## Block vs Inline Elements

- Block elements stretch and take up the entire line.
- Inline elements take up as much space as their content and do not stretch the entire line. This means they go within other content without "jumping" on a new line.
- By default, all HTML elements are set to display: inline. Then, the user-agent stylesheet will set specific elements to have a display: block.
- These elements have a display: block: p, ul, ol, li, h1-h6, div.

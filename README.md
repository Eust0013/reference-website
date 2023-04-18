# reference-website
1. Naming convention for all filenames, paths and folders
- The naming conventions for all filenames should be lowercase, no spaces, but dashes are fine. Folder naming conventions should be similar to filenames. For paths, the folders, assets and files should be inside the root folder so they can be easily linked inside any .html files. 
2. Best practices for commit messages
- Commit messages should be a minimum of 3 words, and 10 characters, with proper spelling and grammar. They must start with a capital letter and imperative verb, and not have a period at the end. You should pretend that every commit message starts with the phrase: "This commit will...".
3. What is HTML?
- HTML is Hypertext Markup Language. It's the coding language used to describe the content of websites.
4. Proper syntax for HTML tags
- The proper syntax for HTML tags is an open tag <>, the element content, and a close tag </> with the tag name in between the angle brackets.
5. Explain or demonstrate commonly used html tags/elements:
headings: h1-h6, p, lists: ul, ol, dl, a, img, q, blockquote, cite, em, strong, b, i, small.
- Heading tags are used to mark headings according to their importance. The most important heading on the page is marked H1, then as the importance of the headings lessens, the number next to the H in the tag gets higher. 
- P tags are used to define paragraphs of text. They will always start on a new line and they are a block-level element. Browsers will automatically add margins before and after each paragraph. 
- List tags are used to define lists and what type of lists they are. UL defines an unordered list, which is used when the order of the items isn’t relevant, and is marked by bullets by default. OL defines an ordered list and items are marked with numbers. DL defines a description list which encloses a list of groups of terms and descriptions using DT and DD elements respectively. 
- A tags are used to define links. To create a hyperlink you would use the A tag and HREF attribute, the value of which is the URL or location where the link is pointing to.
- IMG tags define images. They need the SRC attribute to specify the location of the image, and the ALT attribute to specify the alternative content for the image. 
- Q tags are used to define quotes embedded in other elements such as a paragraph.
- Blockquote tags are used to define large, stand alone quotes.
- Cite tags are used to mark the source of a quote. 
- EM is a phrasing element used for emphasis.
- Strong is a phrasing element used to give lots of emphasis on something of strong importance or urgency.
- b is a phrasing element used for keywords. 
- i is a phrasing element used for another language, technical term, or title.
- Small is a phrasing element used for side-comments and small print.
6. Explain block Elements and also explain the list of block elements and why they are used from below:
html, head, body, header, nav, main, section, article, div, aside, footer, span, small.
- Block elements begin a new line on a webpage, and extend to the full width of the horizontal space of its parent element. They create large blocks of content and are used within the HTML document’s body. They can contain inline elements and other block-level elements. 
- The HTML element defines the whole HTML document. It’s everything from the start tag to the end tag.
- The head element is placed between the HTML tag and the body tag. It contains metadata which is information about the document that isn’t displayed such as the title, character set, styles, and scripts.
- The body element contains all the content of the HTML document such as headings, paragraphs, images, hyperlinks, etc… There can only be one body element per HTML document. 
- The header elements contains introductory content or nav links. It typically contains one or more heading elements, a logo or icon, and/or authorship information. You can have several header elements per document but they cannot be placed within a footer, address, or other header element. 
- The nav element defines a set of navigational links. It’s intended for major blocks of navigational links only. 
- The main element contains the main content of the document. The content should be unique to the document and must not repeat in other documents.
- The section element defines a section of the document. 
- The article element contains independent, self-contained content. It should make sense on its own and it should be possible to distribute it independently from the rest of the site. This could be a forum post, blog post, news story, etc… 
- The div element defines a division or a section in an HTML document. It’s used as  a container for HTML elements, which is then styled with CSS or manipulated with Javascript. Any sort of content can be put inside the div tag, and browsers will automatically place a line break before and after this element. 
- The aside element defines a section of content that is aside from the content it’s placed in. The aside content should be indirectly related to the surrounding content. It’s often placed as a sidebar in a document. 
- The footer element defines a footer for a document or section and typically contains authorship information, copyright information, contact information, etc…
- The span element is an inline container used to mark up part of a text or document. It’s much like the div element but the div element is a block-level element, and the span element is an inline element. 
- The small element defines smaller text such as copyright and other side-comments. 
7. Explain why accessibility is important and also explain the accessibility properties like: landmark roles, aria labels, and image alternative texts. 
- Accessibility is important because it allows everyone, including users with disabilities, to have an ideal experience, and be able to access information equally. 
- Landmark roles are to help those using screen readers to jump directly to different sections within the site. 
- Aria labels provide users with a non-visual label for a link that will only be announced by screen readers. It contains a description of what the user will click through to go to a certain place. 
- Image alternative texts or the ALT attribute, provides users with a description of the image in case it doesn’t download or to describe the image to someone who cannot see the image such as someone using a screen reader. If the image is purely decorative you can leave this attribute blank and apply the presentation role.

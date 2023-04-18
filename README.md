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
8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)?
- CSS is a Cascading Style Sheet. It’s the language we use to control the appearance of our HTML page. We can implement CSS to our HTML file by creating a file in a code editor saved with the extension .css, for example, style.css. You would then place this file in the CSS folder, and link it to the HTML so the browser knows where to find it. You can attach it to the HTML by using the link element inside the head element. 
9. What is the difference between CSS property and value (write explanation and an example code)?
- CSS property is the type of design you want to add such as colour, width, border, etc.. CSS value is the accepted value for that property such as blue, 30px, etc… For example in the code (ignore .s)
HTML. {.
 colour: black;
} COLOUR would be the property and BLACK would be the value. 
10. Why do we use border-box property in CSS?
- By default, the width and the height of an element is calculated like width + padding + border = actual width of the element and height + padding + border = actual height of the element, therefore when you set the width and height of an element the element often appears bigger than you have set as it adds the padding and border to the total size. With the border box element, the padding and border are included inside the width and height of the box (not added) so the total width and height doesn’t change from the value set.
11. Explain different type of ways we can add spacing to an element.
- There are two ways to add spacing to an element; padding, and margin. Padding adds spacing inside the box, pushing the content away from its border. Margin adds spacing outside the box, pushing other boxes away from it. Margins can have positive or negative values.
12. What is the main difference between margin and padding?
- The main difference between margin and padding is that margin adds space outside of the box, and padding adds space inside of the box.
13. What are different types of display properties?
- There are four major display properties. Inline: allows the element on the same line (height and width properties have no effect). Block: forces the element to be on its own line regardless of its width. Inline-block: The element is formatted as an inline element but you can apply height and width values. None: The element is completely removed. 
14. Write a brief explanation of flexbox property.
- The flexbox property controls the flow and alignment of elements for more complex layouts. 
15. What are different types of flexbox properties and what is the major difference between them?
- The flexbox property controls the flow and alignment of elements for more complex layouts. The two types of flexbox properties are container properties (flex-direction, flex-wrap, justify-content, align-items, and align-content) and flex item properties (order, flex, flex-grow, flex-shrink, and align-self). Container properties affect the parent element, or container. The flex item properties affect the direct child elements, or flex items. 
16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
- You must first gave a parent element a display property by using display, then using a sub property of flex or inline-flex to create a container that allows a flex context for all of its direct children. The code for this, using the flex sub-property would be (ignoring .s):
.container {.
display: flex;.
} You can also use inline-flex as a sub property.
17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
.container {
    display: flex;
}
18. What is CSS grid property?
- CSS grid offers a grid-based way to layout your site with rows and columns, making it easier to design web pages without having to use floats and positioning.
19. Write the parent and two sub-properties used for CSS Grid Property.
- The parent property for CSS grid is display, and the sub-properties are grid and inline-grid.
20. What is the difference between display: flex and display: grid?
- The difference between display: flex; and display: grid; is that flex is for flexbox which is for layouts in one dimension (either a row or column), and grid is for CSS grid which is for layouts in two dimensions (rows and columns at the same time).
21. What sub-property we use to divide elements in CSS Grid properties?
- To divide elements in CSS grid properties you would use (without .s) <.div .class.="grid-container"> for the parent element, and  <.div class="grid-item">1</.div> with changing numbers for each element. 
So to divide items you would use the sub-property class=”grid-item”.
22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example).
- To fractionally divide the element width in CSS grid you would use the fr unit. Which would look like grid-template-columns: 1fr 1fr 1fr;. Other units you could use are ex, px, %, and em. 
23. What is the area property in CSS grid we use for the child elements?
- We use grid: row and grid: column for child elements.
24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
- To prevent displaying empty columns you would use the display property grid-auto-columns; and set the minmax to . The code would look like (without .s):
grid-auto-columns: minmax (0, 1fr) 
25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
- To add google fonts to your CSS file and attach it to your HTML file you would first go to google fonts and select the fonts you want to use. Then you would copy the link for the font and paste it in your HTML file in the head and above the title of the file. You can then use the property font family and set the element to the font you chose. 
- html and css practice(all)
- Breakdown(HTML)
  Day 1: Introduction to HTML

Understanding the purpose and role of HTML in web development.
Learning about the basic structure of an HTML document.
Study the DOCTYPE declaration and the <html>, <head>, and <body> elements.
Create a simple HTML document with headings, paragraphs, and basic formatting.

Day 2: HTML CONTENT CATAGORIES
Most HTML elements are a member of one or more content categories — these categories group elements that share common characteristics.
It doesn't actually create a relationship among elements of these categories.
but they help define and describe the categories' shared behavior and their associated rules

-Main content categories, which describe common rules shared by many elements.

-Form-related content categories, which describe rules common to form-related elements.

-Specific content categories, which describe rare categories shared only by a few elements, sometimes only in a specific context.

Venn diagram
![image info][def]

[def]: ./htmlandcss/venn.png

Main content categories

Metadata content

- Elements belonging to this category are <base>, <link>, <meta>, <noscript>, <script>, <style> and <title>.

Flow content
Encircle most elements that can go inside the <body> element, including heading elements, sectioning elements, phrasing elements, embedding elements, interactive elements, and form-related elements. It also includes text nodes (but not those that only consist of white space characters).

The flow elements are: -<a>: The Anchor element(with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address).

- Day 3

  - <abbr>: The Abbreviation element
    an abbreviation is used and you want to provide an expansion or definition outside the flow of the document's content, use <abbr> with an appropriate title.

  - <acronym>
    The <acronym> HTML element allows authors to clearly indicate a sequence of characters that compose an acronym or abbreviation for a word.

  - <address>: The Contact Address element
    The <address> HTML element indicates that the enclosed HTML provides contact information for a person or people, or for an organization.

        - Typically an <address> element can be placed inside the <footer> element of the current section, if any.

  - <area>: The Image Map Area element
    The <area> HTML element defines an area inside an image map that has predefined clickable areas. An image map allows geometric areas on an image to be associated with hypertext links. It is only used on <map> element.

  - <aside>: The Aside element
    The <aside> HTML element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

# Into-to-HTML-CSS
# Week 1
## Unit 1
### Introduction to HTML
HTML provides a structured framework for organizing and presenting information on the internet. Through a system of tags and elements, HTML allows developers to define the structure of a webpage, incorporating text, images, links and more. By understanding HTMl allows us to venture into web development, as it forms the basis for crafting visually appealing and functional websites. The websites can eiather be static or dynamic.
#### HTML Text Formatting
<p>HTML offers various tags for formatting text to enhance the appearance of and the structure of the content in the webpage. Following are some of the examples of formatting tags: 
  <ul>
  <li> "h1" to "h6" Are tags to define headings with different sizes</li>
  <li> "p"  Enclosing a paragraph of text within tags."</li>
  <li> "strong" or "b" To make text bold.</li>
  <li> Use "em" or "i" tags to initialise text to italics.</li>
  <li> For underlining we use "u" tags although it is not a standard HTML tags</li>
  <li> We use "s" or "del" tags to strike through text</li>
  </ul>
</p>

#### HTML Lists
<p>In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. Unordered and ordered lists are quite similar, except for the wrapping element they use. Unlike unordered or ordered lists with their list items, the <b>definition list</b> is used when we want to create a list that resembles a key-value pair in computer science. Instead of just items, we have terms and their corresponding descriptions.
</p> 

  #### Unordered lists    
    We use the "ul" tag to create an unordered list, where each item is represented by the "li" tag.
  #### Ordered lists 
    We use the "ol" tag to create an ordered list, where each item is represented by the "li" tag. The items in the ordered list are automatically numbered.  
  #### Definition lists
    To create a definition list, we use specific elements. The term or key is enclosed in a "dt" tag, which stands for definition term. The description or value is enclosed in a "dd" tag, which stands for definition description. We can have multiple descriptions for each term by using multiple  tags. The entire list is wrapped in a "dl" tag, representing the definition list. Interestingly, the "dd" tags and ""dt" tags are placed side by side without any additional wrapper around them. This is simply how a definition list is structured. 

#### HTML Quotes
<p>Introducing the quotes. We use the "blockquote" tag for longer quotationsand the "q" tag for the shorther quotation. To attribute the quote to the cited individuals, we can use the "cite" element. And to distinguish the quote from the surrounding text, we can wrap the whole thing in "blockquote" or "q"  element. These three elements, "cite", "blockquote" and "q", serve a semantic purpose. They inform other computers, "Hey, this is what this is." Additionally, they provide a convenient way to apply custom styling. With CSS, we can make these elements look however we want. We can make blockquotes stand out and give them a special appearance.
</p>

  #### An example of using blockquotes or q in context
  ![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/0d7b0d35-3fa8-45e0-906e-2f81650cf954)

In this example, inside the "q" element, we have two paragraphs and the "cite" element. But we can include any element we want within the blockquote. We can even put a list or a headline in there. The important thing is that elements should be nested within each other in a way that makes sense.

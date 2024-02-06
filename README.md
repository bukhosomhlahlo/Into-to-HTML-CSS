# Intro-to-HTML-CSS
# Week 1
## Unit 1
### Introduction to HTML
HTML provides a structured framework for organizing and presenting information on the internet. Through a system of tags and elements, HTML allows developers to define the structure of a webpage, incorporating text, images, links and more. By understanding HTMl allows us to venture into web development, as it forms the basis for crafting visually appealing and functional websites. The websites can eiather be static or dynamic.
## Unit 2
### HTML Text Formatting
<p>HTML offers various tags for formatting text to enhance the appearance of and the structure of the content in the webpage. Following are some of the examples of formatting tags: 
  <ul>
  <li> <code>&lt;h1&gt;</code> to <code>&lt;h6&gt;</code> Are tags to define headings with different sizes</li>
  <li> <code>&lt;p&gt;</code> Enclosing a paragraph of text within tags."</li>
  <li> <code>&lt;strong&gt;</code> or <code>&lt;b&gt;</code> To make text bold.</li>
  <li> Use <code>&lt;em&gt;</code> or <code>&lt;i&gt;</code> tags to initialise text to italics.</li>
  <li> For underlining we use <code>&lt;u&gt;</code> tags although it is not a standard HTML tags</li>
  <li> We use "<code>&lt;s&gt;</code> or <code>&lt;del&gt;</code> tags to strike through text</li>
  </ul>
</p>

#### HTML Lists
<p>In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. Unordered and ordered lists are quite similar, except for the wrapping element they use. Unlike unordered or ordered lists with their list items, the <b>definition list</b> is used when we want to create a list that resembles a key-value pair in computer science. Instead of just items, we have terms and their corresponding descriptions.
</p> 

#### Unordered lists    
We use the <code>&lt;ul&gt;</code> tag to create an unordered list, where each item is represented by the <code>&lt;li&gt;</code> tag.
#### Ordered lists 
We use the "<code>&lt;ol&gt;</code> tag to create an ordered list, where each item is represented by the <code>&lt;li&gt;</code> tag. The items in the ordered list are automatically numbered.  
#### Definition lists
To create a definition list, we use specific elements. The term or key is enclosed in a "dt" tag, which stands for definition term. The description or value is enclosed in a <code>&lt;dd&gt;</code> tag, which stands for definition description. We can have multiple descriptions for each term by using multiple  tags. The entire list is wrapped in a <code>&lt;dl&gt;</code> tag, representing the definition list. Interestingly, the <code>&lt;dd&gt;</code> tags and <code>&lt;dt&gt;</code> tags are placed side by side without any additional wrapper around them. This is simply how a definition list is structured. 

#### HTML Quotes
<p>Introducing the quotes. We use the <code>&lt;blockquote&gt;</code> tag for longer quotations and the <code>&lt;q&gt;</code> tag for the shorther quotation. To attribute the quote to the cited individuals, we can use the "cite" element. And to distinguish the quote from the surrounding text, we can wrap the whole thing in <code>&lt;blockquote&gt;</code> or <code>&lt;q&gt;</code>  element. These three elements, <code>&lt;cite&gt;</code>, "<code>&lt;blockquote&gt;</code> and <code>&lt;q&gt;</code>, serve a semantic purpose. They inform other computers, "Hey, this is what this is." Additionally, they provide a convenient way to apply custom styling. With CSS, we can make these elements look however we want. We can make blockquotes stand out and give them a special appearance.
</p>

  #### An example of using blockquotes in context
![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/34e87b29-3030-408f-9ffc-f4cd473dd348)


In this example, inside the "blockquote" element, we have two paragraphs and the "cite" element. But we can include any element we want within the blockquote. We can even put a list or a headline in there. The important thing is that elements should be nested within each other in a way that makes sense.

#### Inline Quotation
The "q" tag is used for shoter, inline qoutation. It automatically adds qoutation marks around the text. 

#### An example of using q  in context
![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/20261063-703d-4f9f-8945-be6fef25c6cf)


<b><em>In the example, the quote has been translated to different languages to show you how the quote marks differ. Comparing the block quote element to the "q" element is a good example of understanding HTML. Some HTML elements, like <code>&lt;strong&gt;</code>, "b", "I", and "em", are called "inline" because they are meant to wrap around phrases of text that are inline with other content. They serve a similar purpose as the "q" element. There are many more inline elements that you can use in HTML.

There are certain elements in HTML known as block-level elements, like block quotes, paragraphs, and unordered lists. These elements essentially create separate blocks on the page. Some of this relates to CSS, where you can switch the layout behavior of elements from block to inline or vice versa. However, before you dive into thinking about layout or CSS, it is important to understand the inherent nature of these HTML elements. 

Some elements serve as markers for something that is part of a larger entity, while others represent the larger entity itself. Let's take the example of block quotes and the "q" element. They may seem similar, but they serve different purposes. One is used for inline phrases, while the other creates a block context. These are the ways to markup quotes using the block quote, "q", and cite elements.</em><b>

#### Date Elements

      The datetime attribute allows us to specify the date or time in a format that computers can understand. 

#### Time Elements


      In HTML the "time" element represents the specific period of time or a preciese datetime. It can be used to mark up dates, times, durations, and machne- readable time values.
      The machine-readable version prefers numbers in the 24-hour clock format, and we can choose whether to include seconds and fractions of a second or not. 

#### Date(Time) Elements
    By using the time element with its datetime attribute, we can convey time in a way that computers can understand.

#### HTML Code, pre and br
<p> <ul> <li>In the <code>&lt;code&gt;</code> code element is used to define a piece of of the code. It is used  for displaying inline code snippets within a paragraph or block of text.</li> <li> In the <code>&lt;br&gt;</code> element is used to create a line break within content. It is a self-closing tab.</li> <li> In the <code>&lt;pre&gt;</code> element is used to define text. It preserves spacing, line breaks, and everything else.</li></ul> </p>


#### HTML Superscripts, Subscripts and Small Text

<p>In HTML, we use the flowing tags for superscipt, subscript, and small text:
<ul><li> Supercript: <code>&lt;sup&gt;</code> tag. For Example <code>&lt;sup&gt;&lt;superscript&gt;&lt;/sup&gt;</code>. </li>
<li> Subscript: <code>&lt;sub&gt; </code>tag. For Example <code>&lt;sub&gt;&lt;subrscript&gt;&lt;/sub&gt;</code>. </li>
<li> Smalltext: <code>&lt;small&gt; </code>tag. For Example <code>&lt;small&gt;&lt;smalltext&gt;&lt;/small&gt;</code>. </li></ul>

## Unit 3

### HTML Capabilities

#### HTML debugging code

<p>Debugging HTML usin browser Devtools involves inspecting the HTML elements, CSS style, and Javascript code to help identify and fix issues.<>
<ol><li> Opening DevTools: We  right click on the webpage and select "Inspect".</li><li> We then look for error messages in the console tab and fix any syntax errors or script issues first.</li><li>We use the "Elements" tab to inspect the HTML structure and look for missing tags, misplaed elements and invalid attributes</li></ol>

#### HTML attributes













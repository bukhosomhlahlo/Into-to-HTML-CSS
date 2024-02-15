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

<p>HTMl attributes provide additional information about HTML elements and can modify their behavior or appearance. The are the four most important Global Attributes: "class," "id," "lang," and "dir." </p>

<ul><li><strong>class:</strong> Specifies one or more class names for an element and are used to apply CSS styles or Javascriot functionality. For example: &lt;div class="codepushers"&gt;...&at;div&gt;.</li>
<li><strong>id:</strong> Specifies the unique identifier for an element within a document and provide a way to name HTML elements and reference them in other parts of the code stack. For example &lt;div id="myDiv"&gt;...&at;div&gt;.</li>
<li><strong>lang:</strong> In HTML, the "lang" attribute is used to specify the primary language of the content within an element. This attribute help browsers  and search engines understand the language of the text, which is important for accessibility and search engine optimization (SEO).For example: <code>&lt;p lang= "en"&gt This is English text. &lt;/p&gt</code></li>
<li><strong>dir:</strong> The "dir" attribute is used to specify the text directionality of the content within an elememnt. It can have two possible values: <ol><li><strong>ltr:</strong> Indicated left-to-right text direction which is the default direction for the most languages. For example <code>&lt;div dir= "ltr"&gt This is left-to-right. &lt;/div&gt</code></li>
<li><strong>rtl</strong> indicates right-to-left dirction, commonly used for languages such as Arabi,Hebrew and more. For axamlpe: <code>&lt;div dir= "rtl"&gt هذا من اليمين إلى اليسار &lt;/div&gt</code></li></ol>
</ul>

#### Formating HTML

HTML does not pay much attention to spaces, tabs, or line breaks? Even inbetween the spaces in sentences and also in paragraphs. The web browser ignores them. The comment written in the code by the programmer are disregarded by the browser. When writing the code the browser support is not affected either we use upper case or lower case. There are still ancient websites with all-caps HTML, and there are also newer sites that never use capital letters.

#### Unusual Characters

In HTML , there are certaincharacter the have special meanings and  need to be represented using character entities to display correctly. However, if we start writing something that resembles an HTML element, it magically disappears. The browser assumes that it is part of HTML code and does not display it.These are some of the characters:<ul><li>"<" - less than sign: <code>&lt ;</code></li><li>">" - greater than sign: <code>&gt ;</code></li><li>"&" - Ampersand: <code>&amp ;</code></li><li>""" - Double quotation mark: <code>&lquot ;</code></li><li>"'" - Single quotation mark: <code>&apos ; or &#39 ;</code></li></ul>

## Unit 4

### HTML Navigation and Linking

To create a link we use an '&lt;a href&gt;' anchor element and hypertext reference. An example of the basic syntax: &lt; a href="URL"&gt; Link Text &lt;/a&gt;. The "URL" is repplaced with the destination URL we want to link the point to, and the "Link Text" with the text we want to display for the link. For Example &lt; a href="//www.codepushers.com"&gt; Visit CodePushers website&lt;/a&gt;.<p>The standard HTTPS://codepushers.com is commonly used, but URLs can offer more flexibility. Absolute URLs, which include the entire URL when linking to another website or page, are versatile and precise. They must contain HTTP or HTTPS, defining communication rules on the web. HTTPS, denoting "Secure," is now recommended for improved security compared to HTTP. Modern browsers automatically add HTTPS:// to web addresses like codepushers.com.

#### HTML URL Pathways

In HTML we can use the <i>relative</i> and <i>absolute</i> pathways to specify the location of resources auch as images, videos, stylesheets(CSS), scripts, or links to the other pages.'<ul><li> The relative pathway are specified relative to the current location of the HTML document. For example &lt;img src="image.jpg"&gt;</li><li> The absolute pathway specify the full URL or path to the resource, starting from the root directory of the website. For example: &lt;img src="http://www.codepushers.com/images/image.jpg"&gt;.</li></ul><p>By using folders and index.html files, we can create clean and user-friendly URLs.</p>

#### Navigation Bars 

<p> Navigaton bars are commonly used in websites to provide users with easy accessto different sections or pages. They are implemented using HTML and CSS.

## Unit 5

### Working with graphics and images 
<p>When adding images we used the imgage element which is written as &lt;img src = "imgage.jpg" alt="Description of the image" width="300" height="200"&gt.
<ul>
  <li> &lt;img&gt;: is used to display images</li>
    <li> "src": attribute specifies the path of to the image file</li>
      <li> "alt": attribute provides a text description of the image.</li>
        <li> we also adjust the the size of the image using CSS or HTML attributes like 'width' and 'height'.</li>
</ul>

#### Image Formats

<p>There are several common image formats used on the web, Each with its own characteristics and best use cases. It is best to choose image formarts that provides a large amount of data to make the image look fantastic, but also want to minimize the data to ensure faster downloads and prevent excessive data usage for users. We aim for the highest possible quality with the smallest file size achievable.</p>

#### Responsive Images

<p>Responsive images are images that adapt to different screen sizes and resolutions to provide the best veiwing experience across various devices. Thee are several techniques for implementing responsive images in HTML.
<p>The source set '&lt;srcset&gt;' in the sizes attribute can be utilized to offer multiple image files to the browser, allowing it to decide which one to load and display.
On big screens, you want to show the whole field and the person's entire body, but on small screens, you only want to focus on her face. Just using the image element alone will not cut it, even if you add some attributes like source set or size. That is where the &lt;picture&gt; element comes into play.</p>
<p>Within the picture element, list alternative options using the source &lt;souce srcset&gt; element. In this instance, we provide two options by creating two source elements.</p>
#### Figcaption and Figures
<p> &lt;figure&gt; and &lt;figcaption&gt; are HTML elements used to markup content particularly for images, diagrams, illustrations, code snippets,etc. They provide structure to the content and improve accessibility. <ul><li>&lt;figure&gt; is used to contain the image</li><li>&lt;figcaption&gt; is used to provide a caption for the image</li></ul> </p>

## Unit 6

### HTML Working With Media

#### Working With Audio

<p> The audio element element has both an opening and a closing tag &lt;audio control src="Audios/audio.mp3"&gt; &lt;/audio&gt;.<p>
  
##### Working with the audio element<h6>
    
<p>![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/7570ee6d-6aa2-429a-82bd-1ee9bfa1c305)
<ul><li>We specify the audio file by using the &lt;source&gt; element within the %lt;audio&gt;.</li>
<li>We use &lt;audio control&gt; attribute to add basic controls such as play, pause, and volume to the audio player</li>
<li>&lt;audio control loop&gt; the 'loop' attribute i used to make the audio play repeatedly as soon as it reaches the end and will star over again</li>
<li>&lt;audio control autoplay&gt; attribute is used to make the audion to start playing automatically when the page loads</li></ul></p> 
<strong><em>When we create multiple files and list them in separate source elements, and the browser will use the first compatible file in the list.</em></strong>
  
#### Working With Video

<p>Video files can be encoded using a variety of codecs, just as image formats such as PNG, JPEG, GIF, or SVG. Video files include a great amount of data, which if not compressed, makes them too big to be efficiently transferred over the internet. Internet videos, as a result, utilize a technology to compress</p>

#### Working With Captions and Subtitles

<p>To work with subtitles and captions in HTML video element we use the &lt;track&gt; element. This allows us to provide timed text tracks that can include subtitles, captions, descriptions, chapters, metadata for video content.
  ![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/86dd1f62-e404-4942-ac54-d0d6f67bfae7)

<ul><li>&lt;track&gt; is used to specify a timed text track for the video.
</li>
<li>The 'src' attribute specifies the URL of the  subtitle file. This filr should be in WebVTT(.vtt)</li>
<li>The 'kind' attribute specifies the kind of text track. For subtitles and captions, we use 'kind="subtles"'</li>
<li>The 'srclang' attribute specifies the language of the subtitle track</li>
<li>The 'label' attribute provides a label for the subtitle track, which is displayed in the browser's settings menu.</li></ul></p>

#### Embedding Media via Iframes

<p>Using &lt;iframe&gt; elements allows us to embed external content, such as videos, maps, social media posts, and more into the HTML document.
<ul><li>For mbedding a Youtube video, we replace 'VIDEO_ID' in the 'src' attribute with the actual ID of the Youtube video we are embedding</li>
<li> For embbeding a Google Map, we replace 'the_map_coordinates' in the 'src' attribute with the approprate map coordinated or place ID.

## Unit 7

### HTML Content Identification

#### HTML Language Support 

<p>The lang attribute is used to specify the language of a webpage. This attribute is particularly useful for accessibility purposes, as it helps screen readers and other assistive technologies understand the language being used on the web page.
<li>The <html> element has a lang attribute set to "en", indicating that the primary language of the document is English.
Each &lt;p&gt; element has a &lt;html lang&gt; attribute specifying the language of the content within that paragraph. The first paragraph is in English ("en"), the second is in French ("fr"), and the third is in German ("de").
</li><li>By using the &gt;html lang&lt; attribute appropriately, helps the assistive technologies correctly pronounce and interpret the content of the web page, improving accessibility for users who rely on such tools. Additionally, search engines may use the lang attribute to understand the language of the content, which can be useful for indexing and providing relevant search results.</li></p>

##### The Meta Attribute

In HTML, the &lt;meta&gt; tag is used to provide metadata about the HTML document. Metadata is information about the data on a webpage and is not displayed on the page itself but is rather used by browsers and search engines to understand and process the page.
<p><ul><li>The &lt;meta&gt; tag with the charset attribute specifies the character encoding for the HTML document.<li>
  <li>The &lt;meta&gt; tag with the viewport attribute is commonly used for responsive web design. It controls the width and scaling of the viewport on mobile devices.</li></ul></p>
  <p>Nowadays, Unicode, particularly UTF-8, is widely used. It is like a massive specification that encodes content to support a vast range of characters, scripts, and even emojis.</p>

#### HTML Generic Elements, Div and Span

&lt;div&gt; is used for creating block-level containers to group and style larger sections of content, while &lt;span&gt; is used for applying styles to smaller, inline sections of content within larger blocks of text. Both elements are essential for structuring and styling content on web pages.

## Unit 8
### HTML Integration
#### HTML Page
<p>HTML and all the elements, attributes, roles, and tools used to mark up content on websites or web apps have been covered. HTML plays a major role in explaining what these things are, but it is not just limited to that.

<li>Main: the &lt;main&gt; element represent the main content of the document.</li>
<li>Header: the &lt;head&gt; element represents introductoryy content, typyically containing headings, logos and navigation menus </li>
<li>Footer: the &lt;footer&gt; element represents a footer section at the bottom of the page, containing, copyright notices, contact information and links to relative pages.</li>
<li>Article: this element represents a contained piece of content that can be distributable or resusable such aS BLOG POST or NEWSPAPER article.</li>
<li>Section: the &lt;section&gt; element defines a thematic grouping of content, typically with a heading</li></p>

#### The Link and Script element

<p>Both &lt;link&gt; and &lt;script&gt; elements are used to include external resources, but they server different purposes:
<ol><li>&lt;link&gt;: this elemtnt is used to link external resources such as stylesheets to an HTML document. It is is commonly uased to apply CSS sty;es to the HTML document.</li>
  <li>&lt;script&gt;: this element is used to include Javascrpt code or spripts within an HTML document. It can either contain the script directly with the element or reference an eternal script file using the 'src' attribute.</li></ol>
</p>

## Unit 9

### Working with Forms and Interactive Elements
#### Form Fundamentals

<p>Forms are used to collect user input. They are created using the &lt;form&gt; element and contain various input elements like'text-fields, checkboxes, radio buttons, dropdown menus and others not mentioned. The submit button is contained as it is used to send data to the server for processing. Below are the example of how forms are used for:</p> 
<a href= "https://github.com/bukhosomhlahlo/Into-to-HTML- CSS/assets/159022974/7f601540-b1d3-44f5-a3d2-9ce9f8e48b9a"></a>


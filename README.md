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

<p>Forms are used to collect user input. They are created using the &lt;form&gt; element and contain various input elements like'text-fields, checkboxes, radio buttons, dropdown menus and others not mentioned. The submit button is contained as it is used to send data to the server for processing. Below are the example of how forms are used for:
![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/7381d99b-3a78-466b-b5e8-995ece6417a2) 
We use the input element to provide places for users to input their name and email. The input element does not have a closing tag due to its older structure. It acts as a marker for the browser to bring in functionality and place it there. 

A button is needed for users to submit the form. We use the button element for this. The text on the button can be customized to whatever is required. Although the form looks good visually, it currently lacks functionality. To make it work, we need to connect it to a backend. We can add an action and method attribute to make a demo work, although using the "get" method is not secure and is not recommended for real websites.

Once set up, land on the response page, but the data that was entered does not appear. This is because the input fields need a "name" attribute to report the data. Add "name=name" to the first input element and "name=email" to the second. The name attribute can be customized as desired. After making these changes, the form works successfully, but only if you interact with it using a screen and a mouse. 

To make it accessible to everyone, we need to address the issue of the label and input elements not being connected. There are two options to achieve this. 

Adding a "for" attribute to the label that matches the "id" attribute of the input. 
Wraping the input with the label. 
Both methods work, and it is a matter of choosing the desired markup structure. You can test the connection by clicking on the label and ensuring that the focus jumps to the corresponding input. This is crucial for accessibility, as many people rely on this connection. Clicking on the label is a quick way to verify its functionality. 

For the above image, the code for version G goes like this:          <p>&lt;form action="sucess.html" method="get"&gt;</p>
                                                                     <p>&lt;label for="name"&gt;Name&lt;/label&gt;</p>
                                                                     <p>&lt;input name="name" id="name" type="text"&gt;</p>
                                                                     <p>&lt;label for="email"&gt;Email&lt;/label&gt;</p>
                                                                     <p>&lt;input name="email" id="email" type="email" placeholder="me@example.com" &gt;</p>
                                                                     <p>&lt;button>Sign Up&lt;/button&gt;</p>
                                                                     <p>&lt;/form&gt;</p>

![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/e37dfa02-2bed-40c2-92f1-4ef3f0f69f6f)
The <input> element is the most important form element.

The <input> element can be displayed in several ways, depending on the type attribute.

The different input types are as follows:

<p>&lt;input type="button"&gt;</p>
<p>&lt;input type="checkbox"&gt;</p>
<p>&lt;input type="color"&gt;</p>
<p>&lt;input type="date"&gt;</p>
<p>&lt;input type="datetime-local"&gt;</p>
<p>&lt;input type="email"&gt;</p>
<p>&lt;input type="file"&gt;</p>
<p>&lt;input type="hidden"&gt;</p>
<p>&lt;input type="image"&gt;</p>
<p>&lt;input type="month"&gt;</p>
<p>&lt;input type="number"&gt;</p>
<p>&lt;input type="password"&gt;</p>
<p>&lt;input type="radio"&gt;</p>
<p>&lt;input type="range"&gt;</p>
<p>&lt;input type="reset"&gt;</p>
<p>&lt;input type="search"&gt;</p>
<p>&lt;input type="submit"&gt;</p>
<p>&lt;input type="tel"&gt;</p>
<p>&lt;input type="text"&gt; (default value)</p>
<p>&lt;input type="time"&gt;</p>
<p>&lt;input type="url"&gt;</p>
<p>&lt;input type="week"&gt;</p>



We can add three more fields: password, search, and phone number:
<li>Password: <p>&lt;label for="password"&gt;Password&lt;/label&gt;</p>
              <p>&lt;input name="password" id="password" type="password"&gt;</p></li>
  <em>When we type into the password field, the browser will warn us not to use this textbox as the site is unsecured. That is because this page is set up to use HTTP and not HTTPS</em>
<li>Phone Number: <p>&lt;label for="phone"&gt;Phone Number&lt;/label&gt;</p>
                  <p>&lt;input name="phone" id="phone" type="tel"&gt;</p></li>
<li>Search: <p>&lt;label for="search"&gt;Search&lt;/label&gt;</p>
                  <p>&lt;input name="search" id="search" type="search"&gt;</p></li>

<qoute>The <input> tag specifies an input field where the user can enter data.

The <input> element is the most important form element.

The <input> element can be displayed in several ways, depending on the type attribute.

The different input types are as follows:

<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text"> (default value)
<input type="time">
<input type="url">
<input type="week">

## Unit 10
### Organizing Tabular Information in HTML
#### HTML Tables

<p>HTML tables are used for tabular data, for example in HTML email. HTML tables are used for structuring HTML emails due to their reliability and compatibility across email clients. Comparing prices of things that are for sale, population data by town, election results, product comparisons, schedules, bits of information collected that people want to quickly compare. This is what tables are for. The data might be numbers but not always. It could even be text, images or other things.</p>

#### Building HTML Tables

![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/a98a272e-36ad-40d4-989b-85f1c1b45868)
<em>The authoritative standard for HTML is found on the LIVING STANDARD</em>

# Intro-to-CSS
## Unit 1
### HTML and CSS
<p> CSS is divided into two parts: <ol><li>The Selector</li><li>the decleration block</li></ol></p>
<p>The selector specifies a pattern in the HTML and if the parttern matches, the styles within the decleration block are applied to the correspondin HTML elements</p>

#### Writing a class selector
<p>In HTML, we define a alass attribute within an element, and in CSS, we use period followed by by(.) the class name to style elements with that class. For example: &lt;div class="example"&gt; &lt!--adding a class attribute to the div element--&gt;. For CSS: .example{
  background-color: grey;
  padding: 20 px;
  }
<p>
  
## Unit 2
### Writing a Class Selector

<p> If we want the first paragraph to be green, we may add a class attribute to the paragraph element with a name such as "intro." This manner, it will stick out as the opening paragraph. CSS uses a dot (.) before the class name to distinguish it from HTML element selectors. Write ".intro" and change the color to green.<p>

#### Group Selectors

We use group selctor so that we do not write separate styles for each period p {blue;} and li {blue}. We can combine them using a p,li{blue}. The web browser will apply this style to all paragraphs and list items, assessing them independently. 

#### Descendent Selectors

<p>When working with CSS selectors that involve multiple terms, it is important to remember that they are read from right to left, even though we write them from left to right. In this case, we are saying "any list item descended f0rom an ordered list.</p>

## Unit 3
### Identify a Color Scheme

<p>When creating a website we can generate or create our own colors in CSS. The easiest way to fin colors for your wwebpage styling is to go to the color palette generator on Google and it will help you with the combination of colors. Which makes it easier for us not to memorize different colors.</p> If we come across an image that best suitable for the website and want to use its color scheme, simply upload it to Canva and we have just discovered a palette that suits the website.

![image](https://github.com/bukhosomhlahlo/Into-to-HTML-CSS/assets/159022974/ea9bc6b7-b797-49d2-9375-0b37adf41563)


We may also experiment with different color combinations, such as monochromatic (two identical hues) and analogous (varying shades of greens and blues, or triadic, which generates a pattern on the color wheel using an equilateral triangle). Tetradic creates a square's worth of colors. 

These combinations help you locate colors that match. We can change the saturation of the colors on the palette or try different variations.

### Formatting Color in CSS

<p>After selecting online the color pallete, we can now add id to our webpage as we have done before in in HTML but this time around we wont be using inline styling. The most common way to represent colors online is through hex codes, also known as hex values or hex format. Hex is short for hexadecimal.</p> <p>Hexadecimal values are generally six-digit long and comprise of numerals 0-9 and letters A-F. The first two digits signify red, the next two represent green, and the last two represent blue. These digits correspond to integers from 0 to 255.</p>

<em>The hex value "3337799" can be shortened to "379" if each two-digit pair is the same.</em>

#### Other Color Formats

<p>Another syntax that we can use in CSS is the RGB, which specifies the red, green, and blue channels by writing colors out in Base 10 integers. This format can alternatively be expressed as an eight-digit hexadecimal number, or RGBA. In both situations, the final number (e.g., "CC" in the hex value or "0.8" in the RGB value) represents Alpha, which refers to the color's opacity and transparency. It influences how easily we can see through the color. Other color standards, such as HSL or HSLA, may be used on occasion, especially on platforms like Squarespace.</p>

### Background and Text Color in CSS

<p>We use colors in text and background elements. We can choose a color for the text and another for the background, whether it is a specific element or the entire page.</p>

### Understanding Images in CSS

<p> <ol> <li>GIF:  Had limited colors but could include transparency and animation. </li>
    <li>PNG:  Had more colors and transparency but no animation. GIF and PNG were suitable for illustrations such as logos or cartoons. </li>
    <li>JPEG:  Stands for Joint Photographic Experts Group, was optimized for photographs and supported millions of colors but lacked transparency and animation.</li></ol></p>
<p>WebP is a modern image format that provides superior lossless and lossy compression for images on the web. Using WebP, webmasters and web developers can create smaller, richer images that make the web faster. WebP lossless images are smaller in size compared to PNGs.</p>


### Working with Background Images in CSS

<p>For additional flexibility, use the shorthand property background rather than background-image. By using "repeat-X," the picture will only repeat horizontally. You may use "repeat-Y" to repeat it vertically. To indicate where the background picture begins, use values such as "center," "right," or "left." In addition, you may use "bottom" to move the image to the bottom of the page.

<p>The background picture displays at the bottom of the text because the webpage's body height is determined by its content. To go around this, we may use a height number like "97vh" (97% of the viewport height) to put the picture where we want it. In this scenario, we want it near the bottom of the page, creating the appearance of dirt on the bottom. We may use the same background picture for other items on the page, such as a UL (unordered list), without specifying the height.</p>

## Unit 4
### Understanding Type in CSS
    
#### Common Font Types

<p> Two of the most recognizable fonts are:<ul><li><u>Serif</u> - fonts include tiny lines at the ends of each letter called serifs. Previously, serif typefaces were utilized for printed items with lengthy text blocks. When letters were manually placed on a printing press, they were never exactly aligned. The serifs connected the letters, making the text simpler to read.</li>
<li><u>Sans serif</u> -  fonts lack serifs and offer a more contemporary appearance. Sans serif fonts are commonly used on the web for lengthy content due to their clean appearance and ease of readability.</li></ul></p>

<p> When a font is not specifically stated, the web page will utilize a font from the user's device. This limits font options when working with CSS. To assure compatibility, it is usual to define many typefaces at the same time, a technique known as font stacking.</p>
 <table><tr><th>Absolute</th><th>Relative</th></tr><tr><td>Points</td><td>Percentage</td></tr><tr><td>Pixels</td><td>Rems</td></tr><tr><td>Don't change size with screens</td><td>Change with screen size and zoom</td></tr></table>




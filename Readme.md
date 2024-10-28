HTML ELEMENTS
- HTML is structured i.e. it has a beginning, body and end. - HTML is composed of tags or elements which are always enclosed in angle
brackets <>
In HTML there are two types of tags, container or open tags, and empty tags. 
Container tags occur in pairs. An example of a container tag is the <title></title>tag. Whatever is contained within this tag is assigned to the title. Notice that the closing tag has a slash in it.
Empty tags require no closing tag. An example of an empty tag is the break tag<br>. This forces the cursor to a new line. Tags should always be balanced hence containers should be nested within eachother.
** Structure of a HTML Document **
<HTML>
<HEAD>
<TITLE> title text goes here </TITLE>
</HEAD>
<BODY>
The text of the page goes here
</BODY>
</HTML>

**Introduction to the BODY Section**
The element <P> is used to instruct the web browser to place the text that follows it on a new paragraph.
*** Attributes of Paragraph tag ***
<P ALIGN= CENTER></P>
<P ALIGN= RIGHT></P>
<P ALIGN=LEFT></P>- is the default alignment i.e. if the align attribute is not included, the paragraph will be left aligned.

***Example***
<HTML>
<HEAD>
<TITLE>This is my first web page</TITLE>
</HEAD>
<BODY>
<P>Hello world!</P>
</BODY>
</HTML>

The element <BR> is used to move the text that follows it to a new line on your webpage. No blank line is inserted between the previous line and the new one.

<HTML>
<HEAD>
<!--Example of the line break element -->
</HEAD>
<BODY>
This text forms the first paragraph of my document. <BR>
This text starts on a new line. Notice that there is no space between this line and the previous one. <BR>
<BR>
This text is on a another new line. There are two line break elements above this text. <BR>
<BR>
<BR>
This line has three line break elements above it. </BODY>
</HTML>

***Inserting Section Heading***
Html has six levels of headings numbered H1 to H6 with H1 being the largest.
<HTML>
<HEAD>
<TITLE>Welcome to my page </TITLE>
</HEAD>
<BODY>
<H1> This is Heading 1 </H1>
<H2> This is heading 2 </H2>
<H3> This is heading 3 </H3>
<H4> This is heading 4 </H4>
<H5>This is heading 5 </H5>
<H6>This is heading 6 </H6>
The bulk of the page goes here
</BODY>
</HTML>

***Physical styles***

They offer consistency in that something you tag a certain way will always be displayed that way for readers of your document. Examples of physical styles
<B> Bold text
<I> Italic text
<TT> Typewriter text e.g. fixed-width font
<U> Underline text
<Strike> Strikethrough text
<blink> Causes text to blink
<Basefont> Used to specify the overall font for your page. It is added immediately after the <body> tag. It has a face, size and color attributes. It has noclosing tag. E.g. <body>
<basefont face =”arial, verdana, courier” size=”5” color =”red”>Hellothis is my page.<br>This is text<br></body>
<Font> It has face, size and color attributes. Font size: Used to set the size of the font from 1(smallest) to 7(largest)
with size 3 being the normal text. Format- <font size =”6”>font size 6</font>
The other method for using font tag is provided by relative size changefrom basefont size
i.e. <basefont size=”5”>size five<br>
<font size = “+1”> size six<br>
<font size = “-1”>size four</font><br>
Font face: Used to specify the desired font typeface. The faces selectedshould be standard. The browser uses the first font in the list availableonthe visitor’s computer. e.g. <body>
<font face =”verdana, Helvetica,courier”>Some text here</font>Attributes
<div align =”left”> This text is left aligned</div>
<div align=right”> This text is right aligned</div>

***Example***
<HTML>
<HEAD>
<TITLE> My Web Page </TITLE>
</HEAD>
<BODY>
<H1> Example HTML Source </H1>
<P>This is <I >my</I> first web page</P>
The next two words <B> are bold </B><BR>
<U> This text is underlined</U><BR>
Now back to unformatted text<BR>
<EM>emphasis <STRONG>emphasis and strong <STRIKE>emphasis, strong and strikeout
</STRIKE></STRONG></EM>
</BODY>
</HTML>

Prepare a two-paragraph text about your house. In this paragraph, mentionthat
your house has a garden, drawing room, two bedrooms, etc. Develop an
HTML document which displays these two paragraph in such a way that eachroom beomes apage of its own e.g. garden.html, drawing.html, kitchen.html.
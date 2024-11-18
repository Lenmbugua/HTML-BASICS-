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
HTML document which displays these two paragraph in such a way that eachroom beomes apage of its own e.g. garden.html, drawing.html, kitchen.html.-For this question we learn how to create links in html trhough the use of a href.

**The element center ie <center> is used to specify that text,graphics,and tables shown are centered on the browser window.

**Example**
<HTML>
<HEAD>
<TITLE>This is my web page</TITLE>
<!--Example of Centering -->
</HEAD>
<BODY>
This text is not centered
<CENTER>
This text is centered
</CENTER>
This text is not
</BODY>
</HTML>

**marquee**
This is a tag that creates a scrolling text. i.e. <marquee>……….</marquee>
-Marquee Align= top/middle/bottom
This align the marquee with the top, middle or bottom of neighboring text line. -Marquee behavior = scroll/ slide / alternate
This specifies the text behavior. -Marquee bgcolor = red
Sets the background color of marquee. -Marquee direction = left/right
This defines the direction in which the text scrolls
-Marquee loop= number/infinitive
This specifies the number of loops as a number value or infinite. -Marquee scrollamount = number
Sets the number of pixels to move the content for each scroll movement -Marquee scrolldelay = number
Specifies the delay in milliseconds between successive movement of the marqueecontent. -Marquee Hspace = number
Sets the amount of space to clear left or right of the marquee. -Marquee Vspace= number
Sets the amount of space to clear above or below the marquee.

**Example**
<HTML>
<HEAD>
<TITLE> My Web Page </TITLE>
</HEAD>
<BODY>
<marquee behavior= alternate bgcolor= "white" hspace= 2
vspace="4" >Some text here </marquee>
</BODY>
</HTML>

**Base Font Size**
The empty element <BASEFONT> allows you to change the size of the standardtext on the Web page displayed.
**Example;**
<HTML>
<HEAD>
<!—example of basefont size-->
</HEAD>
<BODY>
<BASEFONT SIZE=5>
The text here is size five
</BODY>
</HTML>
**Font Size**
The open element <FONT> allows the size of the text on the page to be altered
**Example;**
<BASEFONT SIZE=4>
This paragraph shows some of the font styles available <BR>
<FONT SIZE=1>size1 </FONT>
<FONT SIZE=3>size3 </FONT>
<FONT SIZE=5>size5 </FONT>
<FONT SIZE=7>size7 </FONT> <BR>
Back to base font size<BR>
<FONT SIZE=5 COLOR=red>red </FONT>
<FONT SIZE=6 COLOR=blue>blue </FONT>
<FONT SIZE=7 COLOR=green>green </FONT><BR>
Back to base font
</BODY>
</HTML>


Design a web page of your town and favorite friend using the elements discussed inthis chapter.-For this question we want to implement the use of marquee and base font size
which we previouly covered.

**Colours and Textures**
This section will exam changing the colours of the text and background of the webpages,and the use of textured wallpapers.

**Background Color**
BGCOLOR is used to change the color of the background window.
Example Format;
<HTML>
<HEAD>
<!--Example of changing background colour-->
</HEAD>
<BODY BGCOLOR=”#800080”>
This web page has a purple background!
</BODY>
</HTML>
**Background Wallpaper**
The <BODY> element has BACKGROUNDattribute which is used to define the background image to be used on the
page

Example
<HTML>
<HEAD>
<!--Example of Text colours-->
</HEAD>
<BODY BACKGROUND=”trainer/backlogo.gif”>
This web page has a wallpaper background. </BODY

**question**
Design a document describing you. Assign a suitable background
wallpaper, background colour and a text colour.


**Listing**
. A list is a sequence of
items, each displayed on a separate line and may be indented fromthe left
margin. Lists can either be numbered or bulleted.

**Unordered List**
The open elements<UL> is used to define a list of items which are on separatelines and marked with a bullet.
The empty element <LI> is used to define eachitem within the list ie
<UL>
<LI> first list item
<LI> second list item etc. </UL>

**Unordered List (Type)**
Unordered list can be of
TYPE = disc
TYPE = circle
TYPE = square

Example;
<HTML>
<HEAD>
<TITLE> My Web Page </TITLE>
</HEAD>
<BODY>
<UL TYPE="square">
<LI> first list item
<LI> second list item
</UL>
</BODY>
</HTML>
Example of nested unordered list
<HTML>
<HEAD>
<TITLE> example of nested UL </TITLE>
</HEAD>
<BODY>
<UL>
<LI> first item in the list
<LI> second item in the list
<UL TYPE="square">
<LI> first list item
<LI> second list item
</UL>
</UL>
</BODY>
</HTML>

**Ordered List**
The <OL> element is used to define a numbered list of items. It also uses
<LI>
**Ordered List (Type Start)**
<OL Type="type" START=number>
Type can be:
1 uses numbers (default)
a uses lower case letters in sequence
A uses upper case letters in sequence
i uses lower case Roman numbering i.e. i ii iii iv etc
I uses upper case Roman numbering i.e. I II III IV etc. Number defines the starting number or letter

Example
<HTML>
<HEAD>
<TITLE> My Web Page </TITLE>
</HEAD>
<BODY>
<OL TYPE=“a" START=3>
<LI> first list item
<LI> second list item etc. </OL>
</BODY>
</HTML>
Menu Lists
Menu lists are specified with the <MENU> element and are a form of unordered list. A menu list is a list of items which are supposed to have only one line per item. <HTML>
<HEAD>
<TITLE> example of nested UL </TITLE>
</HEAD>
<BODY>
<menu>
<LI> first item in the list
<LI> second item in the list
<menu TYPE="square">
<LI> first list item
<LI> second list item
</menu>
</menu>
</BODY>
</HTML>
**Directory Lists**
The <DIR> element is used to format a list of items up to 20 characters in length. This
is basically a unordered list. <HTML>
<HEAD>
<TITLE> example of nested DIR </TITLE>
</HEAD>
<BODY>
<DIR>
<LI> first item in the list
<LI> second item in the list
<DIR TYPE="square">
<LI> first list item
<LI> second list item
</DIR>
</DIR>
</BODY>
</HTML>
**Definition Lists**
A definition list is a list of terms and corresponding definitions. The element<DL>is
used to define a definition list. <DT> the term and <DD> the definition. <HTML>
<HEAD>
<TITLE> My Web Page </TITLE>
</HEAD>
<BODY>
<DL>
<DT> definition term
<DD> definition etc. </DL>
</BODY>
</HTML>

Exercises
Do the following exercise so that the outcome is as displayed. EAST AFRICA COUNTRIES AND
CITIES
1.KENYA
i. Nairobi
ii. Kisumu
iii. Mombasa
2. UGANDA
a. Entebe
b. Kampala
c. Tororo
3. TANZANIA
 Dar es salam
 Arusha
 Moshi

**Graphical Images**
This section will introduce the concept of graphical images and how to include themin web documents

**Horizontal Rule**
The closed <HR> element is used to define a horizontal rule. A horizontal rule is a
horizontal graphical line drawn across the screen. A <BR> element is assumed belowand above the line. The <HR> element has the following attributes;
SIZE- an indication of the line thickness
<HR SIZE-num>
WIDTH – An indication of the width of the line across the screen. It can be in pixels or as a percentage of the width of the web page. <HR WIDTH=num/percentage>
ALIGN – The alignment of the line. This specifies whether the line should be alignedto the left, right or centered. NOSHADE – The line should not be shaded. This instructs the browser to displaythelines as a solid black line.

**In-Line Images**
The <IMG> element is used to incorporate images into web pages. Images are storedas separate files from the textual HTML document and are loaded and inserted whereapplicable. Graphical images are usually stored in either GIF or JPEG format. The <IMG>element supports the following attributes;
SRC - The name and location of the image to be embedded. ALIGN – The alignment of the image to the document text. This allows you to
specify whether the image is aligned at the top, bottom or middle of any text on the
same line as the image. ALT – Alternative text to be displayed if the graphic is not. ISMAP – Defines the images as being a clickable map.

**Setting an Image Border**
It is possible to give a border of desired thickness to images. This is done using the
border attribute in the <IMG> tag. The thickness of the border may be from1 pixels
to 10 pixels. For example, when we write <IMG SRC=“elephant.gif” border=”5”>thepicture is shown with a 5 pixel thick border. This is illustrated in the following
example
<html>
<head>
<title> Elephant </title>
</head>
<body bgcolor= “aabbcc” text=”001100”><CENTER>,
<img src=”elephant.gif” align=center width=250 height=175
border=10></img>
<hr>
</body>
</html>

Design a web page of an international leader with an appropriate color
combination.. Design it with suitable headings and horizontal rules. 2. Design a web page of your favorite town with images of what it looks like


**HYPERTEXT LINKS**
This section of the course will examine some of the features of hypertext links andhow these can be combined with graphical images

**INTERNAL HYPERLINKS**
Assign location name to individual point in an HTML file
Location name can then be added to the page’s URL
Link to specific point on the page
Location marked by including a NAME attribute in an A (anchor) element
Ex. <A NAME = “features”></A> in list.html
URL of location
Format: page.html#name
Ex. list.html#features
A hot text is created with an anchor tag <A>text</A>. Format: <A HREF=”college.html”>St Xavier’s College</A>

**External Hyperlinks**
<A HREF> is used to connect to an external link.
An external Hyperlinks to an existing web page
It is possible to create hyperlinks to pages on other servers. This allows you to
share the resources and information already available on other internet sites. The element <A> is used with attribute HREF to form a link to an existing
web site page. Format: <A HREF=”location and name”>…</A>

**In-Line Images as Links**
The <A> text </A> hyperlink element is placed around text in order to forma
hypertext link. Clicking on the image will result in the hyperlink being activated. Format: <A HREF=”location and file name”><IMG SRC=”name and location”></A>

**Hyperlinks to Mail Dialogues**
The <A> element can link to mail tool instead of another web page. Format: <A HREF=mailto:name@location>….</A>

**Hyperlinks to Newsgroup Dialogues**
The <A> hyperlink element can link to a newsgroup dialogue, instead of another webpage. Format: <A HREF=news:news.group>…..</A>

**Hyperlinks to Files**
Hyperlinks can point to files on a server as well as web pages, mail and news grouptools. Format: <A HREF=”/directory/myprog.exe”>

**Embedding Files**
The <EMBED> element allows you to embed document of any type into the page.
Format: <EMBED SRC=”location and name”>
<EMBED SRC=”location and name” HEIGHT=num1 WIDTH=num2>

**Clickable Maps**
A clickable map is the name given to an in-line image which has been defined as a
clickable region. ISMAP is added to make the image clickable. Format: <IMG SRC=”name and location” ISMAP>
10.22 Creating and Using Image Maps
• Image maps – Designate certain sections of an image as hotspots – Use hotspots as anchors for linking
– All elements of image map inside <MAP>…</MAP> tags – <MAP> tag requires NAME attribute
• Ex. <MAP NAME = “picture”>
• Hotspots designated with AREA element – AREA attributes: • HREF sets the target for the link on that spot • SHAPE and COORDS set the characteristics of the AREAALT provides alternate textual description

Exercise
Write the names of several countries in a paragraph and store it as an HTMLdocument, “world.html”. Each continents name must be a hot text. When you clickEurope, it should open a file called “Europe.html”. So prepare “Europe.html”,” America.html”, “Africa.html”,” Asia.html” and “Australia.html”. Each of the HTMLdocuments must give a brief introduction of the continent and list a fewimportant
countries in it. Each country’s name must be a hot text. When you click India (for
example), it must open “India.html

**Forms**
**Introduction to Forms**
A form is a web page which uses HTML form elements. Form elements provide a
convenient method to collect user input through a web page.

**Basic Form elements**
The <FORM>…</FORM> element is used to define the start and end of a forminadocument. There can be several forms on a page; however forms should not be nested. The <FORM> element has two attributes:
1. ACTION ; This attribute defines the URL of the program that will receive andnprocess the data submitted on the form. All forms need to be linked to a
program in order that their data can be processed.
2. METHOD; This attribute defines the method in which the data will be
transmitted to the server. METHOD can take one of these values POST or
GET. With the default method being GET

Format: <FORM METHOD=POST|GET ACTION=”name and location”>
</FORM>
Example 1
Example of Form
<HTML>
<HEAD><!—Example of form element-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
This is a blank form!
</FORM>
</BODY>
</HTML>

**Basic Form Input**
HTML provides a number of different form fields who’s contents can be edited bytheuser. The <INPUT> element is used to specify the majority of these. <INPUT>elements have an attribute value which can be one of the following types:
i. CHECKBOX
ii. HIDDEN
iii. PASSWORD
iv. RADIO
v. RESET
vi. SUBMIT
vii. TEXT

Submit and Reset
All forms require a SUBMIT and RESET button. These produce a button on the
screen which the user can click on to transfer data on the form to the server program. While RESET clears the any data entered on the form. Example 2
<HTML>
<HEAD><!—Example of submit and reset-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
This is my form!
<input type=submit value=“send information” name=“submit”> <br>
<input type=reset value=“clear the form” name=“reset” </FORM>
</BODY>
</HTML>

**Checkbox Fields**
If the <INPUT> element has the attribute set to CHECKBOX then a checkbox fieldis
generated. A checkbox can take the following attribute:
i. NAME is the unique name of the checkbox field. ii. VALUE the data sent to the program is contained within the VALUEattribute. iii. CHECKED is used to set whether a checkbox is selected.

<HTML>
<HEAD><!—Example of checkbox-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>What doyou think about forms<p>
<input type=checkbox Name=Fun value=Y>
This course is fun <p>
<input type=checkbox Name=Tutor value=Y >
The tutor is great<BR>
<input type=checkbox Name=Home value=Y>
I want to go home<BR>
<input type=Submit value=“send information”> <BR>
<input type=Reset value=“clear form”>
</FORM>
</BODY>
</HTML>

**Radio Button Fields**
If the input element has the attribute set to RADIO a radio button field is generated. RADIO is used when you wish to accept a single value from a set of alternatives. It
takes the attributes, NAME, VALUE, CHECKED.

<HTML>
<HEAD> <!—Example of radio button-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
What is your favourite colour <p>
<INPUT TYPE=RADIO NAME=COLOUR value=RED> Red <BR>
<INPUT TYPE=RADIO NAME=COLOUR value=GREEN> Green <BR>
<INPUT TYPE=RADIO NAME=COLOUR value=BLUE> Blue <BR>
<INPUT TYPE=RADIO NAME=COLOUR value=YELLOW> Yellow<BR>
<INPUT TYPE=RADIO NAME=COLOUR value=WHITE> White<BR>
<INPUT TYPE=SUBMIT VALUE=“send information”> <BR>
<INPUT TYPE=RESET VALUE=“clear form”>
</FORM>
</BODY>
</HTML>

**Text Fields**
Text fields are used when you wish to accept a line of typed text, such as a person’s
name. A text field takes the attributes; NAME, VALUE, SIZE, MAXLENGTH.

<HTML>
<HEAD> <!—Example of a text field-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
Please enter your name
<p>
<INPUT TYPE=TEXT NAME=NAME SIZE=30>
<BR>
<INPUT TYPE=SUBMIT VALUE=“send information”> <BR>
<INPUT TYPE=RESET VALUE=“clear form”>
</FORM>
</BODY>
</HTML>

**Password Fields**
These are identical to text field, except the text is displayed as **** as it is entered. Example 6
<HTML>
<HEAD> <!—Example of a text field-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
Please enter your name
<p>
<INPUT TYPE=PASSWORD NAME=NAME SIZE=30>
<BR>
<INPUT TYPE=SUBMIT VALUE=“send information”> <BR>
<INPUT TYPE=RESET VALUE=“clear form”>
</FORM>
</BODY>
</HTML>

**Text Area Fields**
The <TEXTAREA>…</TEXTAREA> element is used to enable a user enter in morethan one line of text. It takes three attributes i.e, NAME, ROWS and COLS.

<HTML>
<HEAD> <!—Example of a textarea field-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
<TEXTAREA NAME=MESSAGE ROWS=5 COLS=50>
Please enter your message here!
</TEXTAREA>
<BR>
<INPUT TYPE=SUBMIT VALUE=“send information”>
<BR>
<INPUT TYPE=RESET VALUE=“clear form”>
</FORM>
</BODY>
</HTML>

**Menu Fields**
Pull down menus can be created through the open element <SELECT>…</SELECT>. Every option in this list is defined using a <OPTION> element. The <SELECT>element can take the attributes MULTIPLE, NAME, SIZE.

<HTML>
<HEAD> <!—Example of MENU field-->
</HEAD>
<BODY>
<FORM METHOD=POST ACTION=“location and file name”>
Please select your favourite colours:
<BR>
<SELECT NAME=MENU MULTIPLE SIZE=5>
<OPTION > Red
<OPTION > White
<OPTION SELECTED > Orange
<OPTION > Blue
<OPTION > Yellow
<OPTION > Green
</SELECT>
<BR>
<INPUT TYPE=SUBMIT VALUE=“send information”>
<BR>
<INPUT TYPE=RESET VALUE=“clear form”>
</FORM>
</BODY>
</HTML>


Exercise
Write an HTML code to design the following information;
i. Are you a vegetarian or a non-vegetarian?  Vegetarian
 Non-vegetarian
ii. What is your profession?  Teaching
 Research
 Medicine  Engineering
 Clerical  Business  Other
iii. Type your comments on our food items. ( use textarea field)



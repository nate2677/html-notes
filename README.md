# HTML and CSS Notes

## Chapter 1 TAGS
  Beginning of the script will consist of brackets &gt; and &lt;
    End of the Script will consist of brackets &lt;/&gt;

  HTML&gt; Tag will indicate that anything between &lt;&gt; and &lt;/&gt; will be HTML

  &lt;H1&gt; &lt;/H1&gt; Main Heading

  &lt;h2&gt; &lt;/&gt;h2&gt; form of sub Heading

  &lt;p&gt; &lt;/p&gt; text appears between these TAGS

  &lt;/Body&gt; tags indicates the end of what should appear in the main browser

### Attributes
  Provide additional info, Have two parts--Name and Value

EXAMPLE:

&lt;p lang="en-us"&gt; Paragraph in English &lt;/p&gt;

lang- attribute name shows what kind of extra info you are supplying about the
element's content.  Should be lowercase
Value- "en-us" value is the information or setting for the attribute.
It should be placed in ""  Most attribute values are either pre-defined
or follow a stipulated value.

&lt;Body&gt; Everything within this element is shown in the main browser

&lt;head&gt; Before Body, you will see HEAD element.
 This contains info about the page.  You usually find the TITLE element inside the HEAD.

 &lt;title&gt; contents are shown in the top of the browser, above where you usually type in the URL or on the tab for that page.

#### Creating a WEB PAGE on a MAC

Start up TextEdit in Applications
  You might also want to download text editor

##### Final Notes Chapter 1
  HTML pages are text docs

  HTML uses tags (characters that sit inside angled brackets) to give the info they surround special meaning.

  Tags are often referred to as elements and usually come in pairs.

  Opening Tags can carry attributes, which tell us more about the content of that element.

  Attributes require a name and a value.

  To Learn HTML- Need to know what tags are available for you to use, what they do, and where they can go.


###### Chapter 2
###### Headings
  HTML has 6 levels of headings; Browser displays the contents of the heading in different sizes. Contents of &lt;h1&gt; is the largest and &lt;h6&gt; is the smallest.

###### Paragraphs
To create a paragraph, surround the words that make up the paragraph with an opening &lt;p&gt;
tag and closing &lt;p&gt; tag.
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.

### Bold And Italic
 By enclosing words in Tags &lt;b&gt; and &lt;/b&gt; you can make characters BOLD.

 Same with Italics.  Place wrap the characters in &lt;i&gt; and &lt;/i&gt; to make them Italic.

#### Superscript and Subscript
### &lt;sup&gt;

The &lt;sup&gt; element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 2 squared.

### &lt;sub&gt;

The &lt;sub&gt; element is used to contain characters that should be subscript.  It is commonly used with foot notes or Chemical Formulas such as H2O.

### Line Breaks and Horizontal Rules

If you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag &lt;br/&gt;.  


To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the &lt;hr/&gt;tag.

### Empty elements

Elements that do not have any words between an opening and closing tag.  Usually only has one tag.  

### &lt;Strong&gt;
The use of the &lt;strong&gt;
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a &lt;strong&gt;
element in bold.

### &lt;Em&gt;

The &lt;Em&gt; element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an &lt;Em&gt;element
in italic.

### &lt;Blockquote&gt;

The &lt;Blockquote&gt; element is
used for longer quotes that take
up an entire paragraph. Note
how the &lt;p&gt; is still
used inside the &lt;Blockquote&gt;
element.

### &lt;q&gt;

The &lt;q&gt;element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the &lt;q&gt;element, however
Internet Explorer does not —
therefore many people avoid
using the &lt;q&gt; element.

### &lt;Abbr&gt;

If you use an abbreviation or
an acronym, then the &lt;Abbr&gt;
element can be used. A title
attribute on the opening tag is
used to specify the full term.

### &lt;DFN&gt;

The first time you explain some
new terminology (perhaps an
academic concept or some
jargon) in a document, it is
known as the defining instance
of it.
The &lt;DFN&gt; element is used to
indicate the defining instance of
a new term.

### &lt;ins&gt; and &lt;del&gt;

The &lt;ins&gt; element can be used
to show content that has been
inserted into a document, while
the &lt;del&gt; element can show text
that has been deleted from it.

&lt;s&gt;

The &lt;s&gt; element indicates
something that is no longer
accurate or relevant (but that
should not be deleted).
Visually the content of an &lt;s&gt;
element will usually be displayed
with a line through the center.


#### Chapter 3 LISTS

### Ordered LISTS

### &lt;ol&gt;

The ordered list is created with
the &lt;ol&gt; element.

### &lt;li&gt;

Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)

### example
&lt;ol&gt;
<li>Chop potatoes into quarters&lt;/li&gt;

&lt;li&gt;Simmer in salted water for 15-20
minutes until tender&lt;/li&gt;
&lt;li&gt;Heat milk, butter and nutmeg&lt;/li&gt;

&lt;li&gt;Drain potatoes and mash&lt;/li&gt;
&lt;li&gt;Mix in the milk mixture&lt;/li&gt;

&lt;ol&gt;


### Unordered Lists


###&lt;ul&gt;
  Unordered list element.  This uses &lt;li&gt; as well.

### Definition Lists

### &lt;dl&gt;
Element is created with this and usually consists of a series of terms and their definitions.

### ### &lt;dt&gt;

Used to contain the term

### &lt;dd&gt;

Used to contain the definition.


### Example

&lt;dl&gt;
&lt;dl&gt;Sashimi&lt;/dl&gt;

&lt;dd&gt;Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce&lt;/dd&gt;


#### Chapter 4  Links

### Writing Links

### Linking to Other Sites

Links are created using the &lt;a&gt; element. Users can click on anything between the opening &lt;a&gt; tag and the closing &lt;a&gt; tag. You specify which page you want to link to using the href attribute.

### Example

&lt;a href = "http://www.imdb.com" &gt;IMDB &lt;/a&gt;

### &lt;a&gt;

Links are created using the &lt;a&gt;
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.
Users can click on anything that
appears between the opening
&lt;a&gt; tag and the closing &lt;/a&gt;
tag and will be taken to the page
specified in the href attribute.
When you link to a different
website, the value of the href
attribute will be the full web
address for the site, which is
known as an absolute URL.

### Linking to Other Pages on the Same site

##  &lt;a&gt;
When you are linking to other
pages within the same site,
you do not need to specify the
domain name in the URL. You
can use a shorthand known as a
relative URL.

If all the pages of the site are in
the same folder, then the value
of the href attribute is just the
name of the file.

### Directory Structure

## Same Folder
To link to a file in the same folder, just use the file
name. (Nothing else is needed.)

## Child Folder

For a child folder, use the name of the child folder,
followed by a forward slash, then the file name.

## Grandchild Folder
Use the name of the child folder, followed by a
forward slash, then the name of the grandchild
folder, followed by another forward slash, then the
file name.

## Parent Folder
Use ../ to indicate the folder above the current one,
then follow it with the file name.

## GrandParent Folder
Repeat the ../ to indicate that you want to go up
two folders (rather than one), then follow it with the
file name.

### Email Links

### Mailto:

To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the &lt;a&gt;
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.

### Summary

Links are created using the &lt;a&gt; element.
The &lt;a&gt; element uses the href attribute to indicate the page you are linking to.

If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.

You can create links to open email programs with an
email address in the "to" field.

You can use the id attribute to target elements within
a page that can be linked to

### Chapter 5 Images

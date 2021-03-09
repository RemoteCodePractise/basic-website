# Basic HTML Concepts 

Elements, tags, and attributes are basic concepts in HTML.

## HTML element is a main structural unit of a web page. HTML tags are used to define HTML elements, and attributes provide additional information about these elements.

### About HTML Tags

HTML tags are used to structure website content (text, hyperlinks, images, media, etc). 
Tags are not displayed in the browsers, they only “instruct” browsers how to show the content of the web page.

*HTML tags are written in angle brackets (e.g <html>).*

- Most of HTML tags comes in pairs, like <p> </p> tags. 
- The first tag in a pair called the start (opening) tag, and the second tag is the end (closing) tag. 
- The information is written between opening and closing tags.

``` 
However, there are unpaired, or empty tags, which only have opening tag. (for ex. <img/>).
```


### HTML Attributes
HTML attributes are added to an HTML element to provide additional information about it. 
For example, if you define an image with <img/> tag, you can use src, height, width attributes to provide information about its source, height, width correspondingly.


### Structure of an HTML Document
The <!DOCTYPE html> declaration specifies the HTML version used in the document. 
Every HTML document should start with this declaration so that the browsers can render the page compliant with HTML standards.

*There exist several types of <!DOCTYPE> defined for each HTML version.*

All the content on the webpage is written between <html> </html> tags.
- The <html> element is used to give information to the browsers that it is an HTML document.

- The <head> element contains metadata (data about the HTML document), character set, document title, styles, etc. This data is not shown to viewers.

- The <title> displays the title of the website in the browser tab when the page is loaded. The title is written between <title> </title> tags.

- The <body> element contains the content of the webpage (text, images, videos, etc). The content is written between <body> </body>.

```
Heading elements contain different types of headings. 
There are six heading levels - <h1>-<h6>,  where <h1> is the most important and <h6> least important tags.
The <p> element contains paragraphs of the text. The content is written between <p> and </p> tags.
 ```
 
 
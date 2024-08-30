**<h1 style="text-align:center; font-weigth:bold;"> HTML </h1>**
**<h2>HTML: HyperText Markup Language</h2>**
-	HTML (HyperText Markup Language) is the most basic building block of the Web.
-	It defines the meaning and structure of web content. 
-	Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).
<h3>A Simple HTML Document</h3>

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

```

##### Explaination 
This is a simple HTML document structure:
- `<!DOCTYPE html>`: Declares the document type as HTML5.
- `<html>`: The root element that contains all the content of the webpage.
- `<head>`: Contains meta-information about the webpage, such as the title.
- `<title>`Page Title`</title>`: Sets the title of the webpage, which appears in the browser tab.
- `<body>`: Contains the content that will be displayed on the webpage.
- `<h1>`My First Heading`</h1>`: A heading element, representing the main title on the page.
- `<p>`My first paragraph.`</p>`: A paragraph element, containing some text.
This HTML document creates a simple webpage with a heading and a paragraph.

### HTML History

| Year 	| Version                                 	|
|------	|-----------------------------------------	|
| 1989 	| Tim Berners-Lee invented www            	|
| 1991 	| Tim Berners-Lee invented HTML           	|
| 1993 	| Dave Raggett drafted HTML+              	|
| 1995 	| HTML Working Group defined HTML 2.0     	|
| 1997 	| W3C Recommendation: HTML 3.2            	|
| 1999 	| W3C Recommendation: HTML 4.01           	|
| 2000 	| W3C Recommendation: XHTML 1.0           	|
| 2008 	| WHATWG HTML5 First Public Draft         	|
| 2012 	| WHATWG HTML5 Living Standard            	|
| 2014 	| W3C Recommendation: HTML5               	|
| 2016 	| W3C Candidate Recommendation: HTML 5.1  	|
| 2017 	| W3C Recommendation: HTML5.1 2nd Edition 	|
| 2017 	| W3C Recommendation: HTML5.2             	|

### HTML Page Structure
![page structure](../img/HTML%20Page%20Structure.png)

### Web Browsers
- The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

- A browser does not display the HTML tags, but uses them to determine how to display the document:
![browsers](../img/img_chrome.png)

### Tag
- A tag is a part of the HTML markup language that tells the browser how to structure the content on a web page.
- Tags are enclosed in angle brackets, e.g., `<tagname>`.
- Tags usually come in pairs: an opening tag and a closing tag.
- The closing tag is similar to the opening tag but with a slash (/) before the tag name.

**Example**

```<p>This is a paragraph.</p>```

### Element

- An element refers to the entire structure consisting of the opening tag, content, and the closing tag.
- The element is what actually forms the content on the page.

**Example**

```<p>This is a paragraph.</p>```

#### Types of Elements
1. ***Empty Elements (Self-Closing Tags):*** Some HTML elements don’t have any content and are called empty elements. They have only an opening tag and no closing tag.

**Example:**

 ```<img src="image.jpg" alt="Image"> or <br> (line break).```

2. ***Block-level Elements:*** These elements start on a new line and take up the full width available.

**Example:**

``` <div>, <h1>, <p>. ```

3. ***Inline Elements:*** These elements do not start on a new line and only take up as much width as necessary.

**Example:**

```<span>, <a>, <img>.```

### HTML Headings
- HTML headings are defined with the `<h1>` to `<h6>` tags.

- `<h1>` defines the most important heading. `<h6>` defines the least important heading: 

**Example**
```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>
```
### HTML Paragraphs
- HTML paragraphs are defined with the `<p>` tag:

**Example**
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

### HTML Links
- HTML links are defined with the `<a>` tag:

**Example**
```
<a href="https://www.example.com">This is a link</a>
```

- The link's destination is specified in the href attribute. 

- Attributes are used to provide additional information about HTML elements.

- You will learn more about attributes in a later chapter.


### HTML Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"

***Common Attributes:***
1. **id:** Assigns a unique identifier to the element.

```
<div id="header">This is a header</div>
```

2. **class:** Assigns one or more class names to the element, often used for CSS styling.
```
<p class="intro">This is an introduction paragraph.</p>
```

3. **src:** Specifies the source file for embedded content like images, scripts, or iframes.
```
<img src="image.jpg" alt="A beautiful scenery">
```

4. **href:** Specifies the URL for a link.
```
<a href="https://www.example.com">Visit Example</a>
```

5. **alt:** Provides alternative text for an image if it cannot be displayed.

```
<img src="image.jpg" alt="A beautiful scenery">
```

6. **style:** Applies inline CSS styles to an element.
```
<h1 style="color: blue; font-size: 20px;">This is a heading</h1>
```

7. **title:** Provides additional information about the element, typically shown as a tooltip when the user hovers over the element.

```
<abbr title="HyperText Markup Language">HTML</abbr>
```

### HTML Tag Reference
| Tag   	| Description                              	|
|-------	|------------------------------------------	|
| `<p>`   	| Defines a paragraph                      	|
| `<hr>`  	| Defines a thematic change in the content 	|
| `<br>` 	| Inserts a single line break              	|
| `<pre>` 	| Defines pre-formatted text               	|
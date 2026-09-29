##### 

##### **1.Understand <!DOCTYPE>, <html>, <head>, <body>. Create a simple HTML page.**

&#x09;

###### &#x09;**<!DOCTYPE>** - this defines Document type is html

###### &#x09;**<html>** - Html - hyper text markup language, it is used to create web layouts.

###### &#x09;	 html tag is root tag, this contains head, body and footer tags.

###### &#x09;**<head>** - head tag contain title tag and meta tags.

###### &#x09;	 title tag is used to define title name for webpage, it helps SEO(search engine optimization) 

###### &#x09;	   -for understand what our webpage is about.

###### &#x09;**<body>** - body tag contains header, main and footer tags and many more. it contains all the visible content of webpage.

###### 

###### **Create a simple HTML page:-**

###### &#x09;	

###### <!DOCTYPE html>

###### <html lang="en">

###### <head>

###### &#x20;   <meta charset="UTF-8">

###### &#x20;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

###### &#x20;   <title>Document</title>

###### </head>

###### <body>

###### &#x20;   <h1> Hello World! </h1>

###### &#x20;   <p> Welcome to my html page </p>

###### </body>

###### </html>

###### 

###### &#x20;

###### &#x09;

##### **2.Explore the root element <html>. Learn how it wraps the entire document.**



###### &#x09;HTML - all the tags are called elements, html is root element of html webpage, it wraps all the tags in entire html document

###### &#x09;html - root element

###### &#x09;head - information about webpage

###### &#x09;body - visible content

###### &#x09;

###### &#x09;<html>  - root element

###### &#x09;<head>	

###### &#x09;	<title> </title>

###### &#x09;</head>

###### &#x09;<body> 

###### &#x09;</body>

###### &#x09;</html>

###### 

##### **3.Understand the difference between block-level and inline elements. Practice examples with <div>, <p> (block) and <span>, <a> (inline).**

###### &#x09;

###### &#x09;Block-level element - block element will take whole width of webpage. (<div> <p>)

###### &#x09;inline element - this takes only needed space for their content (span, a)

###### 

###### &#x09; <!-- Block element -->

###### &#x20;   <div>

###### &#x20;       <h1>Hello World</h1>

###### &#x20;       <p>Lorem ipsum dolor sit amet consectetur adipisici</p>

###### &#x20;   </div>

###### &#x20;   <hr>

###### &#x20;   <div>

###### &#x20;       <!-- inline element -->

###### &#x20;       <a href="https://www.google.com/search?sca\_esv=05f3d1bca6a79ca3\&rlz=1C1ONGR\_enIN1019IN1019\&sxsrf=APpeQnsL-jgBYscJeSnVsLmx9QsxAT6Fhg:1790393372785\&udm=2\&fbs=ABfTbFVyMZGZf1hfvX9uKjN\_-G8cxpBkeIeqYwoCbfNVc4vKE7plZzta63Pe5DpJ3XFR9XzxI1gxDxLun-GtPKavu3kEzJNGNBebw1A\_XeIxzHPdHc5gGlqeYRrsKc2k\_QKKK6kt-AjhNNP6r-v8YZTEDEFOHvz2lLpCCJUsUbach\_pOXsAYdFRjnayctnF5WfiXo-KcdTL6sQuPlkZ9Qwpf2Q9WDTqyBw\&q=strawberry+ad+video+download\&sa=X\&ved=2ahUKEwjJwfiHp4uXAxXde2wGHWd1BVIQtKgLegQIFxAB\&biw=1536\&bih=730\&dpr=1.25"></a>

###### &#x20;       <p><span style="color: red;"> welcome </span>  to my page</p>

###### &#x20;   </div>



##### **4.Learn and practice basic tags: headings <h1>–<h6>, paragraph <p>, division <div>, and inline <span>. Create a sample page using them.**

###### &#x09;    <div> //division tag

###### &#x20;   <!-- heading tags -->

###### &#x20;    <h1>hello World</h1>

###### &#x20;    <h2>hello World</h2>

###### &#x20;    <h3>hello World</h3>

###### &#x20;    <h4>hello World</h4>

###### &#x20;    <h5>hello World</h5>

###### &#x20;    <h6>hello World</h6>

###### 

###### &#x20;    <hr>

###### &#x20;    <!-- paragraph tag -->

###### &#x20;    <p>Lorem ipsum dolor sit amet <span style="color: blue;"> consectetur <b>adipisicing</b> elit.</span> Praesentium illo eius, minus quidem 	id necessitatibus culpa quaerat non optio magnam.

###### &#x20;    </p>

###### &#x20;    </div>

##### **5.Learn what semantic tags are and why they are important for SEO \& accessibility. Compare semantic vs non-semantic tags.**

###### &#x09;

###### &#x09;Sematic tag will describe the meaning and purpose of the content, SEO can better understand the structure and purpose of the webpage.

###### &#x09;example: header, article, main, section, footer.

###### &#x09;Non-semantic tag doesn't have any meaning. example: div and span 







##### **6.Practice creating a webpage with a header and footer. Add title, logo, and footer info**



##### 

##### **7.Understand the difference between sectioning content (<section>) and standalone content (<article>). Create examples.**



###### &#x09;Section tag is used to sectioning the content in the web page. 



&#x09;	<main>

&#x09;	<section>

&#x09;	<h1> Frontend Courses </h1>

&#x09;	<ul>

&#x09;		<li> html </li>

&#x09;		<li> css </li>

&#x09;		<li> javascript </li>

&#x09;	</ul>

&#x09;	</section>



&#x09;	<section>

&#x09;	<h1> Backend Course </h1>

&#x09;		<li> Java </li>

&#x09;		<li> phython </li>

&#x09;		<li> C++ </li>

&#x09;	</ul>

&#x09;	</section>

&#x09;	</main>



###### &#x09;article tag is complete content by itself. also know as standalone content tag.





&#x09;	<main>

&#x09;	<article>

&#x09;		<h1> author 1: </h1>

&#x09;		<p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, facere! </p>

&#x09;	</article>



&#x09;	<article>

&#x09;		<h1> author 2: </h1>

&#x09;		<p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, facere! </p>

&#x09;	</article>

&#x09;	</main>






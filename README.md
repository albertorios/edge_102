#Welcome to EDGE 102: Intro to Web Design
1. [Lecture 1](#lecture-1)
  1. [Example 1.1](#example-11)
  2. [Example 1.2](#example-12)
  3. [Example 1.3](#example-13)
  4. [Example 1.4](#example-14)


##Lecture 1
###Basic HTML
```html
<!DOCTYPE html>
<html>
  <body>
  </body>
</html>
```
###Example 1.1
hello_world.html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello World!</title>
  </head>
  <body>
    <p>
      Hello,World!
    </p>
  </body>
</html>
```
###Example 1.2
HTML_Elements.html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HTML Elements</title>
  </head>
  <body>
    <h1>This is an h1 header</h1>
    <h2>This is an h2 header</h2>
    <h3>This is an h3 header</h3>
    <h4>This is an h4 header</h4>
    <h5>This is an h5 header</h5>
    <h6>This is an h6 header</h6>
    <p>
      Hello,World! This is a paragraph! This is <u>underlined</u>, this is
      <em>emphasized</em>, and this is <b>bold</b>.
      And here's a <a href="http://arios.me/edge_102/">link</a>
    </p>
    <ul>
      <li>So</li>
      <li>This</li>
      <li>Is</li>
      <li>An</li>
      <li>Unordered</li>
      <li>List</li>
    </ul>
    <ol>
      <li>And</li>
      <li>This</li>
      <li>Is</li>
      <li>An</li>
      <li>Ordered</li>
      <li>List</li>
    </ol>
    <p>
      Next up is an image!
    </p>
    <img src="https://pbs.twimg.com/media/BfXAH8RCAAAx5Tv.jpg" alt="Dun Boyir parti at mansooto" />
    <!--  This is a comment! -->
    <div>
      This is a div!
    </div>
  </body>
</html>
```
###Example 1.3
HTML_Attributes.html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HTML Attributes</title>
  </head>
  <body>
    <h1 id="header_1">This is an h1 header with the id attribute "header_1"</h1>
    <p>
      Hello,World! This is a <a href="http://arios.me/edge_102/">link</a> with
      the href attribute "http://arios.me/edge_102/".
    </p>
    <p>
      Next up is an image with the src attribute "https://pbs.twimg.com/media/BfXAH8RCAAAx5Tv.jpg"
      <b>and</b> the title attribute "I am a tool tip" <b>and</b> the alt attribute "Dun Boyir parti at mansooto"!
    </p>
    <img title="I am a tool tip" src="https://pbs.twimg.com/media/BfXAH8RCAAAx5Tv.jpg" alt="Dun Boyir parti at mansooto" />
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
    <p>
      Fun Fact: You can use an id attribute of an element in a <a href="#header_1">link</a> to create internal links. Just
      use the id as the href of a link prefixed by a "#".
    </p>
  </body>
</html>
```
###Example 1.4
HTML_head.html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HTML Head</title>
    <link rel="stylesheet" href="style.css">
    <style media="screen">
      p{
        color:blue;
      }
    </style>
  </head>
  <body>
    <h1>This is red header</h1>
    <p>
      This is a blue paragraph!
    </p>
  </body>
</html>
```
styles.css
```css
h1{
  color: red;
}
```


# The <script> Tag
<div>
  <p>In HTML, JavaScript code is inserted between <code><script></code> and <code></script></code> tags.</p>
  </div>
  
### ex.
``` js
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

## JavaScript Functions and Events

<div>
  <p>A JavaScript <code>function</code> is a block of JavaScript code, that can be executed when
    </br>"called" for.</p>
  <p>For example, a function can be called when an <b>event</b> occurs, like when the user
    </br>clicks a button</p>
</div>

## JavaScript in <head> or <body>

<div>
  <p>You can place any number of scripts in an HTML document.</p>
  <p>Scripts can be placed in the <code>< body></code>, or in the <code>< head></code> section of an HTML page,
    </br>or in both.</p>
</div>

## JavaScript in <head>

<div>
  <p>In this example, a JavaScript <code>function</code> is placed in the <code>< head></code> section of an
    </br>HTML page.</p>
  <p>The function is invoked (called) when a button is clicked:</p>
</div>

### ex.
``` html
<!DOCTYPE html>
<html>

  <head>
  <script>
    function myFunction() {
      document.getElementById("demo").innerHTML = "My First JavaScript";
  </script>
  </head>
  
  <body>
    <h1>A Web Page</h1>
    <p id="demo">A Paragraph</p>
    <button type="button" onclick="myFunction()">Try it</button>
  </body>
  
</html> 
```

## JavaScript in <body>

<div>
  <p>In this example, a JavaScript <code>function</code> is placed in the <code>< body></code> section of an
    </br>HTML page.</p>
  <p>The function is invoked (called) when a button is clicked:</p>
</div>

### ex.
``` html
<!DOCTYPE html>
<html>
  <body>
    <h1>A Web Page</h1>
    <p id="demo">A paragraph.</p>
    <button type="button" onclick="myFunction()">Try it</button>
    
    <script>
      function myFunction() {
         document.getElementById("demo").innerHTML = "Paragraph changed.";
      }
    </script>
  </body>
</html>
```

## External JavaScript

<div>
  <p>Scripts can also be placed in external files:</p>
</div>

## ex. myScript.js
``` js
function myFunction() {
   document.getElementById("demo").innerHTML = "Paragraph changed.";
 }
```

<div>
  <p>External scripts are practical when the same codes is used in many different web
    </br>pages.</p>
  <p>JavaScript files have the file extension <b>.js</b></p>
  <p>To use an external script, put the name of the script file in the <code>src</code>
</br>attribute of a <code>< script></code> tag:</p>
</div>

## ex.
``` js
<script src="myScript.js"></script>
```
<div>
  <p>You can place an external script reference in <code>< head></code> or <code>< body></code> as you like.</p>
    <p>The script will behave as if it was located exactly where the <code>< script></code> tag is
      </br>located.</p>
    </div>



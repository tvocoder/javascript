
# JavaScript Output
## JavaScript Display Possibilities
<div>
  <p>JavaScript can "display" data in different ways:</p>
  <ul>
    <li>Writing into an HTML element, using <code>innerHTML</code>.</li>
    <li>Writing into the HTML output using <code>document.write()</code>.</li>
    <li>Writing into an alert box, using <code>window.alert()</code>.</li>
    <li>Writing into the browser console, using <code>console.log()</code></li>
  </ul>
</div>

## Using innerHTML
<div>
  <p>To access an HTML element, JavaScript can use the
    </br><code>document.getElementById(id)</code> method.</p>
  <p>The <code>id</code> attribute defines the HTML element. The <code>innerHTML</code> property defines the
    </br>HTML content:</p>
</div>

### ex.
``` html
<!DOCTYPE html>
<html>
  <body>
    <h1>My first web page</h1>
    <p>My first paragraph</p>
    
    <p id="demo"></p>
    
    <script>
      document.getElementById("demo").innerHTML = 5 + 6;
    </script>
  </body>
</html>
```

<div>
  <p><mark>Changing the innerHTML property of an HTML element is a common way to
    </br>display data in HTML.</mark></p>
</div>


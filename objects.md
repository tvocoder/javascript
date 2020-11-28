
# 11.1
## Introduction

<ul>
  <li>The chapter presents a more formal
    </br>treatment of objects.</li>
  <li>We use HTML5's new web storage capabilities
    </br>to create a web application that stores a
    </br>user's favorite Twitter searches on the
    </br>computer for easy access at a later time.</li>
  <li>We also provide a brief introduction to JSON,
    </br>a means for creating JavaScript objects&#8212;
    </br>typically for transferring data over the
    </br>Internet between client-side and server-side
    </br>programs.</li>
</ul>

# 11.2
## Math Object

<ul>
  <li>Math object methods enable you to
    </br>conveniently perform many common
    </br>mathematical calculations.</li>
  <li>An object's methods are called by writing the
    </br>name of the object followed by a dot operator
    </br>(.) and the name of the method</li>
  <li>In parentheses following the method name is
    </br>are arguments to the method</li>
</ul>

# 11.1
## Software Engineering Observation

<div>
  <p>The difference between invoking a stand-alone function
    </br>and invoking a method of an object is that an object
    </br>name and a dot are not required to call a stand-alone
    </br>function.</p>
  </div>

# Fig. 11.1
## Math object methods.

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Description</th>
      <th>Examples</th>
    </tr>
  </thead>
  
  <tr rowspan="3">
  <td>abs( x )</td>
  <td>Absolute value of x.</td>
  <td>abs( 7.2 ) is 7.2
    </br>abs( 0 ) is 0
    </br>abs( -5.6 ) is 5.6</td>
  </tr>
  
  <tr rowspan="2">
  <td>ceil( x )</td>
  <td>Rounds x to the smallest
    </br>integer not less than x.</td>
  <td>ceil( 9.2 ) is 10
    </br>ceil( -9.8 ) is -9.0</td>
  </tr>
  
  <tr>
  <td>cos( x )</td>
  <td>Trigonometric cosine of x
    </br>(x in radians).</td>
  <td>cos( 0 ) is 1</td>
  </tr>
  
  <tr rowspan="2">
  <td>exp( x )</td>
  <td>Exponential method <i>e<sup>x</sup></i>.</td>
  <td>exp( 1 ) is 2.71828
    </br>exp( 2 ) is 7.38906</td>
  </tr>
  
  <tr rowspan="2">
  <td>floor( x )</td>
  <td>Rounds x to the largest
    </br>integer not greater than x</td>
  <td>floor( 9.2 ) is 9
    </br>floor( -9.8 ) is -10.0</td>
  </tr>
  
  <tr rowspan="2">
  <td>log( x )</td>
  <td>Natural logarithm of x
    </br>(base <i>e</i></td>
  <td>log( 2.718282 ) is 1
    </br>log( 7.389056 ) is 2</td>
  </tr>
  
  <tr rowspan="2">
  <td>max( x, y )</td>
  <td>Larger value of x and y.</td>
  <td>max( 2.3, 12.7 ) is 12.7
    </br>max( -2.3, -12.7 ) is -2.3</td>
  </tr>
</table>

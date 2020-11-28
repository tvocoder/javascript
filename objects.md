
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
    </br>(base <i>e</i>)</td>
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

## (Part 2 of 2.)

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Description</th>
      <th>Examples</th>
    </tr>
    
    <tr rowspan="2">
    <td>min( x, y )</td>
    <td>Smaller value of x and y.</td>
    <td>min( 2.3, 12.7 ) is 2.3
      </br>min( -2.3, -12.7 ) is -12.7</td>
    </tr>
    
    <tr rowspan="2">
    <td>pow( x, y )</td>
    <td>x raised to power y(x<sup>y</sup>).</td>
    <td>pow( 2, 7 ) is 128
      </br>pow( 9, .5 ) is 3.0</td>
    </tr>
    
    <tr rowspan="2">
    <td>round( x )</td>
    <td>Rounds x to the closest
      </br>integer.</td>
    <td>round( 9.75 ) is 10
      </br>round( 9.25 ) is 9</td>
    </tr>
    
    <tr>
    <td>sin( x )</td>
    <td>Trigonometric sine of x
      </br>(x in radians).</ts>
    <td>sin( 0 ) is 0</td>
    </tr>
    
    <tr rowspan="2">
    <td>sqrt( x )</td>
    <td>Square root of x.</td>
    <td>sqrt( 900 > is 30)
      </br>sqrt( 9 ) is 3</td>
    </tr>
    
    <tr>
    <td>tan( x )</td>
    <td>Trigonometric tangent of
      </br>x (x in radians).</td>
    <td>tan( 0 ) is 0</td>
    </tr>
</table>

# Fig 11.2
## Properties of the Math object.

<table>
  <thead>
    <tr>
      <th>Constant</th>
      <th>Description</th>
      <th>Value</th>
  </thead>
  
  <tr>
  <td>Math.E</td>
  <td>Base of a natural logarithm (<i>e</i>).</td>
  <td>Approximately 2.718</td>
  </tr>
  
  <tr>
  <td>Math.LN2</td>
  <td>Natural logarithm of 2.</td>
  <td>Approximately 0.693</td>
  </tr>
  
  <tr>
  <td>Math.LN10</td>
  <td>Natural logarithm of 10.</td>
  <td>Approximately 2.302</td>
  </tr>
  
  <tr>
  <td>Math.LOG2E</td>
  <td>Base 2 logarithm of <i>e</i></td>
  <td>Approximately 1.442</td>
  </tr>
  
  <tr>
  <td>Math.LOG10E</td>
  <td>Base 10 logarithm of <i>e</i>.</td>
  <td>Approximately 0.434</td>
  </tr>
  
  <tr>
  <td>Math.PI</td>
  <td>&pi;&#8212;the ratio of a circle's cir-
    </br>cumference to its diameter.</td>
  <td>Approximately
    </br>3.141592653589793</td>
  </tr>
  
  <tr>
  <td>Math.SQRT1_2</td>
  <td>Square root of 0.5.</td>
  <td>Approximately 0.707</td>
  </tr>
  
  <tr>
  <td>Math.SQRT2</td>
  <td>Square root of 2.0.</td>
  <td>Approximately 1.414</td>
  </tr>
</table>

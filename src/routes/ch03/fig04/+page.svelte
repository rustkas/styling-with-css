<svelte:head>
  <title>A Sample XHTML Document</title>
  <style>
    body {font-family: verdana, arial, sans-serif; font-size:100%;}
  </style>
</svelte:head>

<!--header--> 
<div id="logo"> <img src="/images/stylin_logo1.gif" width="150" height="80" alt="Stylin logo" /> 
  <h3>a New Riders book by Charles Wyke-Smith</h3> 
</div> 
<!--end header-->
<!--main content-->
<div id="contentarea"> 
  <h1>Moving to XHTML</h1> 
  <p>Creating XHTML compliant pages simply requires following a few simple rules.
    These rules may seem counter-intuitive or just a lot of extra work at first,
    but the benefits are significant and actually make coding sites much easier.
    Also, XHTML code can be easily validated online so you can be sure your code
    is correctly written.</p> 
  <p>Here are the key requirements for successful validation of your XHTML code.</p> 
  <ol> 
    <li>Declare a DOCTYPE</li> 	
    <li>Declare an XML namespace</li> 
    <li>Declare your content type</li> 
    <li>Close every tag, enclosing or non-enclosing</li> 
    <li>All tags must be nested correctly</li> 
    <li>Inline tags can't contain block level tags</li> 
    <li>Write tags in lowercase</li> 
    <li>Attributes must have values and must be quoted</li> 
    <li>Use encoded equivalents for left brace and ampersand</li> 
  </ol> 
  <a href="more.htm">more about these requirements</a> </div>
  <!--end main content--> 
<!--navigation--> 
<div id="navigation"> 
  <p>Here are some useful links from the web site of the <acronym title="Word Wide Web Consortium">W3C</acronym> (World
    Wide Web Consortium), the guiding body of the web's development.</p> 
  <ul> 
    <li><a href="http://validator.w3.org">W3C's XHTML validator</a></li> 
    <li><a href="http://jigsaw.w3.org/css-validator/">W3C's CSS validator</a></li> 
    <li><a href="http://www.w3.org/MarkUp/">XHTML Resources</a></li> 
    <li><a href="http://www.w3.org/Style/CSS/">CSS Resources</a></li> 
  </ul> 
</div>
<!--end navigation-->  
<!--footer--> 
<div id="homepagefooter"> 
  <p>&copy; 2004 Charlie Wyke-Smith and New Riders.</p> 
</div> 

<style>
  h1 {font-size:.1em}
  h3 {font-size:.8em}
  p {font-size:.8em}
  ol {font-size:.75em}
  ul {font-size:.75em}
  ul a {font-size:inherit}
  a {font-size:.7em}
</style>
<svelte:head>
	<title>Basic two column</title>
  <style>
    body {margin:0px; padding:0px;}
  </style>
</svelte:head>
<div id="nav">
	<ul>
		<li><a href="#">Link 1</a></li>
		<li><a href="#">Link 2</a></li>
		<li><a href="#">Link 3</a></li>
	</ul>
</div>
<div id="content">
	<h1>A Simple Two-Column Layout</h1>
	<p><strong>Step 3 - by adding a left margin to the content div that's equal to the width of the navigation, we have our two columns.</strong></p>
	<p> The next step is to do some stylin' and turn the page into a more professional looking layout.</p>
	<p>We need to pad the content away from the edge of the divs, change the typeface from boring old Times, and make the navigation look a 
	little more inviting.</p>
</div>

<style>
  div#nav {position:absolute; width:150px; left:0px; top:0px; border-right:2px solid red;}
	div#content {margin-left:150px;}
</style>
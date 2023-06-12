<svelte:head>
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
	<p><strong>Step 2 - the two divs are now aligned vertically.</strong> The navigation div (with its right border in red so you can see where it is) has been absolutely positioned 
	so it is removed from the flow of the document.</p>
	<p>As an absolutely positioned element, its default position is in the top left corner of its containing element, the body element.</p>
	<p>This allows the content div to take its place as the first element in the document flow.</p>
</div>

<style>
  div#nav {position:absolute;width:150px; top:0px; left:0px; border-right:2px solid red;}
</style>
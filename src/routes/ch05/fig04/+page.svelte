<svelte:head>
	<title>Basic two column</title>
  <style>
    body {margin:0px; padding:0px; font: 1em verdana, arial, sans-serif;}
  </style>
</svelte:head>
<div id="header"><h1>Three-column layout with header</h1></div>
<div id="nav">
  <ul>
    <li><a href="#">Rubovia</a></li>
    <li><a href="#">Middle Earth</a></li>
    <li><a href="#">Far, Far Away</a></li>
  </ul>
</div>
<div id="content">
  <h1>Adding a Header</h1>
  <p><strong>Step 2 - move the side columns down.</strong> Either modify the top property or 
  the margin-top property to push the columns down by an amount equal to the height of the header.</p>
	 
  <p>In this case, I adjusted the top property of the columns. Now let's style and center the type.</p>
  <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean vel sapien
    congue lacus fringilla viverra. Duis pellentesque sodales odio. Quisque pharetra
    aliquam ipsum.</p>
	<p>Nulla scelerisque. Sed tincidunt. Quisque eu nisl. Phasellus
    mi ante, aliquet vel, vestibulum sit amet, consectetuer non, ante. Suspendisse
    consequat condimentum enim. Morbi vestibulum lorem sit amet enim. Nulla venenatis
    fermentum purus.</p>
	<p>Nunc justo nisl, vulputate in, sagittis in, pretium sodales,
    magna. Nullam felis diam, bibendum ut, dictum in, tincidunt vitae, magna.
    Nunc mattis congue leo. Ut diam nibh, mollis at, luctus eget, rhoncus id,
    elit. Suspendisse potenti. Quisque eget justo rutrum erat placerat pellentesque.
    Pellentesque habitant morbi tristique senectus et netus et malesuada fames
    ac turpis egestas.</p>
</div>
<div id="rightcolumn">
	<p>Nunc justo nisl, vulputate in, sagittis in, pretium sodales,
    magna. Nullam felis diam, bibendum ut, dictum in, tincidunt vitae, magna.
    Nunc mattis congue leo.</p>
</div>

<style>
div#header {height:60px; background-color:#CCC;}
div#header h1  {margin-top:0;}
div#nav {position:absolute; left:0px; top:60px; width:150px;
				padding:.5em 0 0 0; margin:22px 0 0 15px; 
				border-top:2px solid #069; border-bottom:1px solid #069;}
div#nav ul {margin-top:0; margin-bottom:.8em;}
div#nav li {margin-bottom:.5em; font-weight:bold; font-size:.75em;}			
div#content {margin:20px 150px 0 165px; padding: 0 1em;}
div#content h1{font-size:1em;}
div#content p {font-size:.8em;}	
div#content li {font-size:.75em;}
div#rightcolumn {position:absolute; width:125px; top:60px; right:0px;  
		margin:20px 15px 0 0; padding:1em  .5em; border-top:2px solid #069; border-bottom:1px solid #069;}
div#rightcolumn p {font-size:.75em;}
</style>
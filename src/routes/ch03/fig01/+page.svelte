<svelte:head>
  <title>Font-family generic demo</title>
</svelte:head>
<p class="serif">Generic Fonts</p>
<h2 class="serif">A Serif headline</h2>
<p class="serif">Serif paragraph text.</p>
<h2 class="sansserif">A Sans-Serif headline</h2>
<p class="sansserif">Sans-Serif paragraph text.</p>
<h2 class="monospace">A Monospace headline</h2>
<p class="monospace">Monospace paragraph text.</p>
<h2 class="cursive">A Cursive headline</h2>
<p class="cursive">Cursive paragraph text.</p>
<h2 class="fantasy">A Fantasy headline</h2>
<p class="fantasy">Fantasy paragraph text.</p>

<style>
  /*
  font-size:120%;	
  , which is now available on , now , which*/
  .serif {font-family:serif;}
  .sansserif {font-family:sans-serif;}
  .monospace {font-family:monospace;}
  .cursive {font-family:cursive;}
  .fantasy {font-family:fantasy;}
  h2 {margin-bottom:0px;}
  p {margin-top:0px;}
</style>
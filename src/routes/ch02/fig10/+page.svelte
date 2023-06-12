<svelte:head>
  <title>Contextual Selectors example</title>
</svelte:head>

<h1 class="specialtext">This is a heading with the <span>same class</span> as the second paragraph</h1>
<p>This tag has no class.</p>
<p class="specialtext">When a tag is identified with a class, we can target it <span>regardless</span> of its position in the hierarchy.</p>

<style>
  p {font-family: Helvetica, sans-serif;}
  .specialtext {font-weight:bold;}
  p.specialtext {color:red;}
  p.specialtext span {font-style:italic;}	
</style>
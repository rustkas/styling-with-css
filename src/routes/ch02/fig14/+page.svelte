<svelte:head>
  <title>Contextual Selectors example</title>
</svelte:head>

<h1 class="specialtext">This is <em>a heading</em> with the <span>same class</span> as the second paragraph</h1>
<p>This tag has no class.</p>
<p class="specialtext">When a tag is identified with <em>a class</em>, we can target it <span>regardless</span> of its position in the hierarchy.</p>
<div class="specialtext">In this div, the span tag <span>may or may not</span> be styled.</div>

<style>
  p {font-family: Helvetica, sans-serif;}
  .specialtext {font-weight:bold;}
  p.specialtext {color:red;}
  p.specialtext span, h1.specialtext span {font-style:italic}	
  * {
    color: green;
  }
  p * em { font-weight: bold;}
</style>
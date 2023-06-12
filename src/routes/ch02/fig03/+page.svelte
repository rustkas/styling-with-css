<svelte:head>

</svelte:head>


<h1>Contextual selectors are <em>very</em> selective.</h1> 
<p>This example shows how to target a <em>specific</em> tag
  using the document hierarchy.</p>
<p>Tags only need to be descendants <span>in the <em>order stated</em> 
in the selector</span>; other tags can be in between and the selector still works.</p>

<style>
  h1 + p {font-variant:small-caps}
  h1 {
    font-size: 16pt;
    font-weight: bold;
  }
  p {
    color: blue;
  }
</style>
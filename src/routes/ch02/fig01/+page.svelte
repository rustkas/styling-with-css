<svelte:head>
  <title>Contextual Selectors example - no styling</title>
</svelte:head>

<p>This paragraph simply takes on the browser’s default paragraph style.</p>
<p style="font-size: 25pt; font-weight:bold; font-style:italic; color:red;">By adding inline CSS styling to this paragraph, we can override the default styles.</p>
<p>And now we are back to a regular default paragraph without any inline styles.</p>

<style>
 p {font-variant:small-caps}
   </style>
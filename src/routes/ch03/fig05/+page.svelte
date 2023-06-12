<svelte:head>
  <title>A Sample XHTML Document</title>
  <style type="text/css">
      /*
      font-size:120%;	
      */
      body {font-family:verdana, arial, sans-serif; font-size:1em; }
    </style>
</svelte:head>

<p>This is italicized text with <span>a piece of non-italic text</span> in the middle.</p>

<style>
  p {font-style:italic;}
  span {font-style:normal;}
</style>
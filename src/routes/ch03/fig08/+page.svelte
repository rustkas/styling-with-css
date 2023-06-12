<svelte:head>
  <style>
    body {font-family:verdana, arial, sans-serif; font-size:1em; }
  </style>
</svelte:head>

<p>Altering the letter-spacing changes the space between individual characters (numbers and symbols, as well as letters). This paragraph has normal spacing.
<p class="loose"> Positive letter-spacing values increase the space between every character. </p>
<p class="tight">Negative letter-spacing values bring the characters closer together.</p>
<h1>Here is a regular headline</h1>
<h1 class="tight">Here's a headline tightened</h1>
<!--end footer--> 

<style>
  .tight {letter-spacing:-.05em}
  .loose {letter-spacing:.5em}
  h1 {font-size:1.8em}
</style>
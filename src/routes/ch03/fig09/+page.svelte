<svelte:head>
  <title>Text box demo</title>
  <style>
    body {font-family:verdana, arial, sans-serif; font-size:100%; }
  </style>
</svelte:head>

<p class="lefttext">This is text that is left aligned and is the usual way that text is aligned. It's easy to read because every line starts against the left edge of the containing element  and that's why it's the default setting.</p>
<p class="centeredtext">This is text that is centered. Small blocks of text look good centered but it's hard large amounts of text to read as every line starts a different distance from the edge of the page.</p>
<p class="righttext">This is text that is right aligned and, like centered text, it can be somewhat hard to read because every line starts in a different place.</p>
<p class="justifiedtext">Justified text is both left and right aligned at the
  same time. This is achieved by mathematically increasing word space on a line
  by line basis, but this can result in gaps of white space throughout the text,
  specially if the containing element is narrow or if there are multiple numerous extended consecutive occurrences of exceptionally lengthy words like these, so that only a few fit
  on each line.</p>

<style>
  .lefttext {text-align:left;}
  .centeredtext {text-align:center;}
  .righttext {text-align:right;}
  .justifiedtext {text-align:justify;}
</style>
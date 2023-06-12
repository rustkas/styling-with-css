<svelte:head>
  <title>Boldness demo</title>
  <style>
    body {font-family:verdana, arial, sans-serif; font-size:1em; }
  </style>
</svelte:head>

<ul>
  <p class="nopad">Without padding, any border that you add to an element such as this paragraph is very close to the content; not always the desired result.</p>
  <p class="pluspad">Even a small amount of padding gives the content some visual breathing space. Note that the padding area around the content also takes on the background color; it makes perfect sense that the background color extends to the border and does not just color the area behind the content itself.</p>
  </ul>

<style>
  p.nopad {border: 2px solid #AAA; background-color:#EEE;}
  p.pluspad {border: 2px solid #AAA; padding:10px; background-color:#EEE}
</style>
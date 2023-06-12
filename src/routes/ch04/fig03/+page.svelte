<svelte:head>
  <style>
    body {font-family:verdana, arial, sans-serif; font-size:1em; }
  </style>
</svelte:head>

<h2 class="borderson">Margin demo with borders</h2>
<p class="borderson">This is the same heading and two paragraphs but now the borders are visible, and you can see how the default margins creates space between the elements.</p>
<p class="borderson">Margins push an element away from elements it would otherwise touch.</p>

<h2 class="nomargins">Margin demo with borders, without margins</h2>
<p class="nomargins">Here the margins are set to 0 (zero), so the elements' borders actually touch.</p>
<p class="nomargins">Be aware that many elements have margins by default, and you will often want to eliminate or adjust the default margin setting to get the effect you want.</p>


<style>
.borderson{border:1px solid #000;}
.nomargins{margin:0; border:1px solid #000;}
</style>
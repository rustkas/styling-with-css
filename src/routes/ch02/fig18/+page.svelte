<svelte:head>
  <title>Contextual Selectors example</title>
</svelte:head>

<h1>All about siblings selectors</h1>
<p>There must be at least two selectors, with a + sign before the last one.</p>
<p>The targeted selector will only be affected if it is a sibling to, and preceded by, the one before the + sign.</p>
<img src="/images/sunset.jpg" alt="Lahina Sunset" title="Lahina Sunset">

<div class="weather">
  It's <strong>very</strong> hot and <strong>incredibly</strong> humid.
</div>
<style>
  div.weather strong:first-child {
    color: red;
  }
</style>
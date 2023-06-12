<svelte:head>
  <title>Contextual Selectors example</title>
</svelte:head>

<h1>All about siblings selectors</h1>
<p>There must be at least two selectors, with a + sign before the last one.</p>
<p>The targeted selector will only be affected if it is a sibling to, and preceded by, the one before the + sign.</p>
<img src="/images/sunset.jpg" alt="Lahina Sunset" title="Lahina Sunset">
<img src="/images/stylin_logo1.gif" width="150" height="80" alt="Stylin logo" /> 

<hr>

<img src="/images/car1.gif" alt="car-toyota-prius">
<img src="/images/car2.gif" alt="car-honda-accord">
<img src="/images/car_montage.gif" alt="car">
<a href="https://ya.ru">link</a>
<style>
  img[title] {
    border: 2px solid blue;
  }
  img[alt="Stylin logo"] {border: 2px solid blue;}

  img[alt|="car"] {
    border:2px solid green;
  }
  a:link {color:black;}
  a:visited {color:gray;}
  a:hover {text-decoration: none;}
  a:active {color:navy;}
  
</style>
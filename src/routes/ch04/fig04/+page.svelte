<svelte:head>
  <style>
    body {font-family:verdana, arial, sans-serif; font-size:1em; margin:0px}
  </style>
</svelte:head>

<p>This element is 400 pixels wide. If we didn't set the width explicitly, the element would extend to the width of the page, as the body tag is its containing element. 
  On each side of the box, the paddding is 20 pixels and the border is 6 pixels.</p>


<style>
  p {width:400px; margin: 0; padding:0 20px;  border:#000 solid;  border-width: 0 6px  0 6px;  background-color:#CCC;}
</style>
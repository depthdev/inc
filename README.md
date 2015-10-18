# inc
Dynamic animated number incrementor.

<p>&#60; 1KB</p>
<p><a href="http://codepen.io/clearwavedesigns/pen/fFuKH" target="_blank">Demo</a></p>
<p>Example:</p>
<pre>
new Inc({
  elem: document.querySelector('#count'),
  speed: 50, // Optional: change in milliseconds
  decimal: 2, // Optional: decimal place
  currency: '$' // Optional: leading symbol
});
</pre>

<p>NOTE: If you have more than one element to increment, create multiple new Inc objects and assign them to a variable or array index.</p>

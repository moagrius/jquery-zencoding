<h1>jQuery - ZenCoding</h1>
<p>Simple jQuery plugin based on Sergey Chikuyonok's excellent Zen Coding implementation.</p>
<p>Adds a single method to jQuery instances, `zencode(abbreviation /* string */)`, which accepts a string abbreviation and expands it, then set the calling element's html to the expanded markup.</p>
<code>$('#some-element').zencode('div#page>div.logo+ul#navigation>li*5>a');</code>
<p>See demo.html for a simple example.</p>
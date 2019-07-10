### swig
---
.js
https://github.com/paularmstrong/swig

https://github.com/swig/swig

.py
http://www.swig.org/Doc1.3/Python.html

```sh
npm install swig


```

```js
var swig = require('swig');
var template = swig.compileFile();
var output = template({
  pagename: 'awesome people',
  authors: ['Paul', 'Jim', 'Jane']
});


```

```html
<h1></h1>
<ul>
{% for author in authors %}
  <li{% if loop.first %} class="first"{% endif %}>{{ author }}</li>
{% endfor %}
</ul>


<h1>Awesome People</h1>
<ul>
  <li class="first"></li>
  <li>Jim</li>
  <li>Jane</li>
</ul>
```


wordcut
=======

Thai word breaker for Node.js


Installation
------------

```
npm install wordcut
```


Usage
-----

```javascript
var wordcut = require("wordcut");

wordcut.init();
console.log(wordcut.cut("กากา"));
```

### Command line interface

```
npm install -g wordcut
worcut < input_file > output_file
```

#### Options
* --delim
* --dict

### Web API

    node server.js

#### Trying Web API

    curl -X POST --data-binary '{"line":"กากา"}' http://localhost:8882/segment
Development
-----------

* Explanation in Thai about version 0.0.3 http://veer66.wordpress.com/2014/02/19/wordcut2014/

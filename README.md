Neah
====
Generate Lorum Ipsum text from Arnold Schwarzenegger's exceptional film career.
Neah is compatible with web browsers and nodejs.

Installation
------------
### Bower

    bower install neah

or download/clone from here and put `neah.js` somewhere handy.

### Node

    npm install neah

Usage
-----
### Web

```
<script src="neah.js"></script>
<script>
    var neah = new Neah();
    console.log(neah.getRandom()); // Get random quote
    console.log(neah.paragraph()); // Generates 1 paragraph
    console.log(neah.paragraphs(5)); // Generates 5 paragraph
</script>
```

### Node
```
var Neah = require('neah');
    neah = new Neah();

console.log(neah.getRandom()); // Get random quote
console.log(neah.paragraph()); // Generates 1 paragraph
console.log(neah.paragraphs(5)); // Generates 5 paragraph
```

Thanks to this [awesome repository](https://github.com/maxdavid/arnold-quotes).
Neah
====
![Great](http://d3htz3r28tzhqz.cloudfront.net/KqtokYTuMo4Qq5GA5t_o2ekkloo=/original-e09d4d76-7d47-4097-89fd-c63743791877.GIF/oZz19.gif?c=desktop&l=search&f=.gif)
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
urldata
=======
Library to extract url data from css property
=======
[![Build Status](https://travis-ci.org/lexich/urldata.svg)](https://travis-ci.org/lexich/urldata)
### Instalation

```
npm install urldata --save
```

### Example

```javascript
var urldata = require("urldata");
var prop = "red url(cat.png) center bottom no-repeat, green url(\'dog.png\') center bottom no-repeat";
urldata(prop) // ["cat.png", "dog.png"]
```


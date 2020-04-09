# juiceLogger
Simple logger for JS.

Install

```
npm i juicelogger
```

Usage example

``` javascript
const express = require('express');
const {logSuccess, logInfo, logWarn, logError, log} = require('juicelogger');
const app = express();
const port = process.env.PORT || 3000;

app.listen( port, () => {
    logSuccess( port);
    logInfo( port);
    logWarn( port);
    log( port);
    logError( port);
});
```


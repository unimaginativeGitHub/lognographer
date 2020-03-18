# lognographer
Super simple logger that adds colorizing and beautifying of objects.
> Timestamps coming soon!

---

Works similarly to Winston and other loggers.

```javascript
const logger = require('lognographer');
...
logger.debug('Super critical message', objectOfLogging);
```

Supports two arguments (for now) and `warn`, `info`, `debug` and `error` log types (yellow, green, blue and red respectively).

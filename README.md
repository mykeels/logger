# Logger

A simple console log interface

## Usage

```bash
npm i mykeels/logger
```

```js
const logger = require('logger')('name-of-file.js')

logger.log('Hello World')
logger.warn('Hello World')
logger.info('Hello World')
logger.error('Hello World')
```
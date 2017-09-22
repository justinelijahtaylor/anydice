anydice.js
==========

## API

```javascript
const AnyDice = require("anydice").AnyDice;

const result = await AnyDice.run("output [highest 1 of 2d20]+10");
const rolls = result.roll(result.first(), 10);
console.log(rolls);
```

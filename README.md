 - Install latest [nodejs](https://nodejs.org/en) version. 
 - Setup with `npm install jest`
 - Run tests with `npm run test`

**Note:** Statement `import Game from './bowling'`present in the slides does not work with current structure. Instead, use provided `const { Game } = require('./bowling');` Initial content of `bowling.js`:

```
class Game {}

module.exports = {
    Game
}
```
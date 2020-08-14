4# Bots For Discord API
A simple library for interacting with the discordboats.zyx API.

## Getting Started
Simply install by navigating to your project directory then running `npm i https://github.com/botsfordiscord-xyz/bfd-xyz.js`.

## Example

```js
const Client = require('bfd-xyz.js');
const client = new Client('Bot ID', 'User Token');

client.getBot('d').then(bot => {
    console.log(bot)
}).catch((e) => {
    console.error(e)
})

client.getCurrent().then(bot => {
    console.log(bot)
}).catch((e) => {
    console.error(e)
})

client.getUser('423220263161692161').then(bot => {
    console.log(bot)
}).catch((e) => {
    console.error(e)
}) 

client.updateCount(1680).then(() => {
    console.log('Successfully updated server count.')
}).catch((e) => {
    console.error(e)
})
```

## License
[Apache 2.0 License](https://github.com/DetectiveHuman/discordboats-api/blob/master/LICENSE)
# bfd-xyz.js

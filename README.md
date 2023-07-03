# lib-r6 - Version 1.0.0

## Installation
```sh
npm i r6s-stats-api
```
```js
const rsix = require('r6s-stats-api')
```
| Installation required | Link | Version |
| ------ | ------ | ------ |
| rs6-stats-api | [link](https://github.com/hmes98318/r6s-stats-api) | v1.3.0 |
| discord.js | [link](https://discord.js.org/#/) | 16.9.0 |

---

## Use General Profile 
#### Function
```js
rsix_profile(plateform, profile) 
```

#### Example
```js
const R6 = require('./r6-lib')

if (message.content.startsWith('+mystats')) {
  var plateform = 'pc'
  var name_profile = 'Trois.Doigts'
  let result = R6.rsix_profile(plateforem, name_profile)

  message.channel.send({embeds: [result]})
};
```

---

## Use Casual Profile
#### Function
```js
casual(plateform, profile)
```

#### Example
```js
if (message.content.startsWith('+mystats')) {
  var plateform = 'pc'
  var name_profile = 'Trois.Doigts'
  let result = R6.casual(plateforem, name_profile)

  message.channel.send({embeds: [result]})
};
```

---

## Use Rank Profile
#### Function
```js
ranked(plateform, profile)
```

#### Example
```js
if (message.content.startsWith('+mystats')) {
  var plateform = 'pc'
  var name_profile = 'Trois.Doigts'
  let result = R6.ranked(plateforem, name_profile)

  message.channel.send({embeds: [result]})
};
```

---

## Use DeathMatch Profile
#### Function
```js
deathmatch(plateform, profile)
```

#### Example
```js
if (message.content.startsWith('+mystats')) {
  var plateform = 'pc'
  var name_profile = 'Trois.Doigts'
  let result = R6.deathmatch(plateforem, name_profile)

  message.channel.send({embeds: [result]})
};
```

---

## Feedback

<p>I'd be delighted to get your feedback on bugs and other issues.</p>
My Discord (FR) => [GX Développement](https://discord.com/invite/gxdev)

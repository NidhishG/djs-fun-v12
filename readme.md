# DJS-FUN-v12 Package By Nidhish#1295

A fun npm package for [Discord.js-v12](https://discord.js.org)

### Join [the support server](https://discord.gg/FF7brJcrEk) for any help.

*This package is [djs-fun](https://npmjs.org/djs-fun) but for normal discordjs-v12.

### Would You Rather

```js
const djs = require('djs-fun-v12')
djs.wyr(message, {
    firstButtonColor: "first button color here", //defualt: red
    secondButtonColor: "second button color here" //defualt: blurple
})
```

### Guess The Pokemon

```js
const djs = require('djs-fun-v12')
djs.gtp(message, {
    loadingMessage: "loading message here"// defualt: Loading ⚙️
})
```

### Rock Paper Scissors 

```js
const djs = require('djs-fun-v12') 
djs.rps(message, {
    startMessage: "message when command is triggered",
         //defualt: Rock Paper Scissors! \nHit a button below for your choice.
    rockButtonColor: "color for rock button here",
       //defualt: red
    paperButtonColor: "color for paper button here",
     //defualt: gray
    scissorsButtonColor: "color for scissors button here"
   //defualt: green
})
```
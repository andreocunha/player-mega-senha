# player-mega-senha
Pacote npm da classe player

## Installation & Usage
### install

```sh
npm i player-mega-senha
```

### usage

```js
const { Player, Status } = require('player-mega-senha');

const player = new Player("ID", "nickname");

if(player.status === Status.HINTING){
    console.log("Hinting");
}

player.setStatus(Status.GUESSING);
console.log(player.status);

```
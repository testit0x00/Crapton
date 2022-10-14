# Crapton
Crapton Framework

Crapton is a Framework that allows you to create a game using only a few lines of code.


![Crap](http://i.imgur.com/mJmDv6F.png)


Crapton is a simple, yet powerful framework that makes game development easy and fun.


## Features

- Ease of use
- Simplicity
- Power
- Fun


## Installation

Simply download the latest release from the [releases page](https://github.com/crapton/crapton/releases).


## Usage

Creating a game with Crapton is simple.

```javascript
var game = new Crapton.Game(800, 600, 'My Game');

game.state.add('MyState', {
  preload: function() {
    // preload assets here
  },
  create: function() {
    // create game objects here
  },
  update: function() {
    // update game logic here
  },
  render: function() {
    // render game objects here
  }
});

game.state.start('MyState');
```

## Documentation

Check out the [documentation site](http://crapton.io/docs) for detailed information on how to use Crapton.


## Examples

Check out the [examples page](http://crapton.io/examples) to see some examples of games made with Crapton.


## License

Crapton is released under the [MIT License](http://opensource.org/licenses/MIT).

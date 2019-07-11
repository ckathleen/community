Starter Snakes
=======

There are a host of [starter snakes](https://github.com/battlesnakeio?utf8=%E2%9C%93&q=starter-snake&type=&language=) to 
help you to get started building your first snake to compete in the Battlesnake tournament.

Each of the starter snakes have have enough scaffolding code to run a snake both locally and on heroku.
Every snake that takes part in Battlesnake is an http server that will accept requests from the battlesnake engine.

Snakes have three ways of interacting with the engine.

 - `start` - A call from the engine to tell the snake a game has begun.
 - `move` - A call from the engine to tell the snake the current board state and request the next move.
 - `end` - A call from the engine to tell the snake that the game has completed. 
 - `ping` - A call from the engine to keep your snake alive between games in case it gets hibernated by your cloud provider.
 
Each starter snake (should) also have three unit tests that you can run to ensure that these methods/functions are working.


## Design Philosophy
The target audience for the starter snakes is mainly junior programmers (but everyone is welcome to use them).

The Goals of them are to:
 - provide the boilerplate code.
 - [teach programming skills](mission-and-values.md#battlesnake-teaches-real-world-programming-skills).

To help provide boilerplate, we should provide:
 - http server
 - json serialization/deserialization in the a structured/accessible format.

To help teach programming skills, we should:
 - avoid guiding the design of the code/logic.
 - avoid providing helper functions (beyond json/http-server code)
 
 ## Official Starter Snakes
 
 Currently the supported official starter snakes are in the following languages:
 
 - [starter-snake-python](https://github.com/battlesnakeio/starter-snake-python) - written in [Python](https://www.python.org/downloads/release/python-2715/)
 - [starter-snake-go](https://github.com/battlesnakeio/starter-snake-go) - written in [GoLang](https://golang.org)  
 - [starter-snake-node](https://github.com/battlesnakeio/starter-snake-node) - written in [Node.js](https://nodejs.org)  
 - [starter-snake-java](https://github.com/battlesnakeio/starter-snake-java) - written in [Java](https://docs.oracle.com/javase/8/)
 
 ## Community Built Starter Snakes
 
 Thank you to the Battlesnake community for writing starter snakes in these languages:
 
 - [starter-snake-kotlin](https://github.com/athenian-programming/starter-snake-kotlin) - written in [Kotlin](https://kotlinlang.org/)
 - [starter-snake-rust](https://github.com/mcraealex/rustysnake) - written in [Rust](https://www.rust-lang.org)

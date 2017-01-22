The *Legacy Code Change Algorithm* starts with:

    1.) Identify change points.

Again, I'm using the [Reversi project](https://github.com/joedougherty/reversi/) code, so feel free to follow along.

Here's the view from 30,000 ft:

  * `server.py` (primarily) accepts network connection and routes user input
  * `Game.py` handles: receiving/executing moves, broadcasts messages to players
  * `Board.py` encodes the rules and logic of the game itself


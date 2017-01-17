## Motivation: ##

Learn some techniques from _Working Effectively with Legacy Code_ by Michael Feathers.

## Objective: ##
Add a feature to my reversi telnet server that lets users play against an AI opponent. In order to do so, I'll be applying the *Legacy Code Change Algorithm* outlined in Chapter Two.

## Tools I'll be using: ##

  * [Reversi project](https://github.com/joedougherty/reversi/)
  * [py.test](http://doc.pytest.org/en/latest/)
  * [coverage](https://coverage.readthedocs.io/en/latest/index.html)

Here are the results of the initial run of `coverage report` on my reversi repo at the outset.

    Name            Stmts   Miss  Cover
    -----------------------------------
    Board.py           80     63    21% 
    Game.py            77     67    13% 
    directions.py      16      8    50% 
    server.py         171    129    25% 
    -----------------------------------
    TOTAL             344    267    22% 


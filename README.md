# Typing Game - intermediate

This is an intermediate step before I can make the game multi-player.  You will see a random 
word on screen and need to type it. 

There are two hippos, and if you type the correct letter, one of them (randomly chosen) will react to your input and move one step forward. If not, it will remember the number of incorrect letters. Press equal number of backspaces to erase errors, and then move forward.

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `cd assets && npm install`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:80`](http://localhost:80) from your browser.

If you need port 4000, make sure you change the config file (config/dev.exs).

### Note:

Please note that the code in the live folder is not refactored on purpose. You will see that almost the same function repeats for two players - 'x' and 'y'. The multi-player version will not need that redundancy, because the process will automatically figure out which player to move.



# 2248

A chain-merge puzzle in a single HTML file. Drag through equal or doubling tiles to merge them into powers of two.

Play it at https://white-hat-lab.github.io/2248/

- 5 x 8 board, starts at 16 with a first goal of 16K; reaching 16K clears the 16s, 32K clears the 32s, and so on
- A chain starts with two equal tiles; after that each tile may be equal or double the last
- The result is the chain sum rounded down to a power of two; points equal the chain sum
- Tiles above 8192 show as 16K, 1M, 1B, 1T, 1AA and so on
- Boosters: Smash removes a tile, Swap exchanges two neighbours, Shuffle rearranges the board. Two of each to start, one more of each per goal
- Synthesized sound, mute button, one-step undo, and the game and best score are saved in the browser so you can resume
- No build step and no dependencies: open `index.html` in any browser

# 2248

A chain-merge puzzle in a single HTML file. Drag through equal or doubling tiles to merge them into powers of two.

Play it at https://white-hat-lab.github.io/2248/

- 5 x 8 board, starts at 16 with a goal of 256; reaching a goal clears every tile of the lowest value and doubles the goal
- Merged sum rounds up to the next power of two; doubling is allowed once two equal tiles start the chain
- Long chains pay x2 (5+) and x3 (8+)
- Synthesized sound, mute button, one-step undo, best score saved in the browser
- No build step and no dependencies: open `index.html` in any browser

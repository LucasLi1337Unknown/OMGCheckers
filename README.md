# OMG Checkers

A human-vs-AI American checkers game powered by Lucas's OMG programming language. You play Red.

## GitHub Pages

Upload `index.html`, `game.omg`, and this README to the root of a GitHub repository. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

The playable page has forced captures, chained jumps, kings, win detection, restart, and undo. The embedded OMG interpreter reads the rules and AI scoring values from the OMG program when the page loads. Browsers cannot execute `.omg` files natively, so `index.html` contains the interpreter that runs the OMG program.

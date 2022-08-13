# k-in-a-row-web-experiment

Code for the web experiment used in the paper "Adaptive search space pruning in complex
strategic problems".

To use the code, you can run the file tictactoe.html (in the "tictactoe" folder). 
For the code to run, you need to use a server (either locally or on an external server. If using an IDE such as pycharm you can simply run it from the IDE).

You will need to specify which of the experimental board to use but passing a "board" parameter in the url.
There are 5 boards, each having a "full" and "truncated" version (see paper for details). 
To run a specific configuration, use the board number, and either "f" or "t" for the full or truncated versions, respectively.
For example, to use board 1 full version, you will need to specify "board=1f". 
For instance, the url might look like this:
http://localhost:63342/k-in-a-row-web-experiment/tictactoe/tictactoe.html?board=1f
(with the server specification depending on where you deployed your code)

By default, you will have to answer the quiz questions to proceed. You can avoid this by adding "debug=1" to the url, e.g.:
http://localhost:63342/k-in-a-row-web-experiment/tictactoe/tictactoe.html?board=1f&debug=1

For questions, you can email Ofra Amir <oamir@technion.ac.il>

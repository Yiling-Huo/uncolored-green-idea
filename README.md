# Uncolored Green Idea Game
A game where you get to build grammatical nonsense sentences like Chomsky did.

[Download for Windows](https://github.com/Yiling-Huo/worldle-forever/releases/download/v1.0.0/worldle-forever.exe)

[Download for Mac](https://github.com/Yiling-Huo/uncolored-green-idea/releases/download/v0.1.3/uncolored-green-idea-game-v0.1.3-mac.app.zip)

### version 0.1.3

2024-03-11:
- Added a high score board.
- Added some words.
- Deleted some ambiguous words.
- Fixed the bug where the game sometimes generates more than 10 sentences per game. 

### version 0.1.2

2024-03-11:
- Improved player experience: 
    - Less chance for the game to accidently say something is ungrammatical when it's not: Changed the logic to determine ungrammaticality from the block-list to a white-list. 
    - Sense-making now depends on all previous content words instead of just one, so the points you gain are more fair. 
- Added some more words.

### version 0.1.1

2024-03-10:
- Changed the title to Uncolored Green Idea Game.
- Added a debriefing at the end of each game.

### version 0.1.0

2024-03-10: Initially created the game.

## Source code issues

Known issues: 
- Some of the words in the corpus are POS-ambiguous. Game might say ungrammatical when the selected option can work with the sentence as another POS than the game thinks. 

*For forkers: assets is missing images and sounds because of copyright issues, as well as the gensim pre-trained word2vec model because of size and copyright issues. Get a model from gensim in the .txt format [here](https://github.com/piskvorky/gensim-data) and put it in assets.*

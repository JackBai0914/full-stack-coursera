# Project: Online Gomoku Platform

## Introduction

Gomoku is a strategy board game popular among the world, especially in Asia. This game is beginner-friendly, convenient to play, and suitable for people of all ages. 

Despite there are some online platforms supporting Gomoku, none of them allows users to play freely (many needs register and buy "energy"), and only a few of them provide chess bots. This project aims to build a light-weighted online Gomoku platform, which supports multiple kinds of games and allows users to play against each other with a few clicks. Moreover, this platform can also provide analysis to the game played, so that the players can review their games and improve their skills.

<img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Renju.jpg" alt="Renju.jpg" style="zoom:25%;" />

## Expected List of Features

### Basic Structure

- A 19 * 19 chess Gomoku board that allows users to put tokens on.
- A few links to the rule and introduction of Gomoku.

### Games

- Users can choose to play with different levels of bots, ranging from beginner level to world-champion level. 

  I have always written a Gomuku AI based on the alpha-beta pruning algorithm, which can easily beat humans.

- Users can choose to play against another user, using only one computer.

  In this mode, the website only serves as a board.

- Users can choose to play against other users online.

- The website will automatically judge whether the game ends and which player wins.

### Analysis

- After each game ends, the website will allow users to analyse the game. The platform will provide scores for each step played, and suggest the best move at each stage.

  This feature is also based on the Gomoku bot I implemented.


## Market Survey

None of the platform I found supports game analysis function.

- https://alternativeto.net/software/gomoku--online-game-hall/

This is a large game platform that supports Gomoku. It's very inconvenient to use.

- https://skillgamesboard.com/play-gomoku-online.aspx?option=start_game#

This webpage needs registration and can only invite your component. This lack of functionality sacrifices the convenience of the game.

- https://gomokuonline.com/

This website is neat and has a chess bot. However, it cannot support players to play against each other, and the bot is too easy to beat. Also, the token in this game is red and blue, which looks very unreal.

- https://www.playok.com/en/gomoku/

This is a neat Gomoku online platform, but you can't play with bots, nor can you analyze or record your games.

- [Go-Moku - Classic 5 in a Row Game](https://www.etsy.com/market/gomoku?utm_source=google&utm_medium=cpc&utm_campaign=Search_UK_DSA_GGL_Main_General_New&utm_ag=UK-EN_DSA-General&utm_custom1=_k_CjwKCAiAudD_BRBXEiwAudakX0gJozpWX6nufskGNkyfGDoeteAVeMn4Ir3YCkYZCU0afwLmKSFOyBoCUOIQAvD_BwE_k_&utm_content=go_11120727342_112118310227_474876607394_dsa-19959388920_c_&utm_custom2=11120727342&gclid=CjwKCAiAudD_BRBXEiwAudakX0gJozpWX6nufskGNkyfGDoeteAVeMn4Ir3YCkYZCU0afwLmKSFOyBoCUOIQAvD_BwE)

This game app is not free.

## References

https://alternativeto.net/software/gomoku--online-game-hall/

https://skillgamesboard.com/play-gomoku-online.aspx?option=start_game#

https://gomokuonline.com/

https://www.playok.com/en/gomoku/

[Go-Moku - Classic 5 in a Row Game](https://www.etsy.com/market/gomoku?utm_source=google&utm_medium=cpc&utm_campaign=Search_UK_DSA_GGL_Main_General_New&utm_ag=UK-EN_DSA-General&utm_custom1=_k_CjwKCAiAudD_BRBXEiwAudakX0gJozpWX6nufskGNkyfGDoeteAVeMn4Ir3YCkYZCU0afwLmKSFOyBoCUOIQAvD_BwE_k_&utm_content=go_11120727342_112118310227_474876607394_dsa-19959388920_c_&utm_custom2=11120727342&gclid=CjwKCAiAudD_BRBXEiwAudakX0gJozpWX6nufskGNkyfGDoeteAVeMn4Ir3YCkYZCU0afwLmKSFOyBoCUOIQAvD_BwE)

https://en.wikipedia.org/wiki/Gomoku

https://www.wikihow.com/Play-Gomoku
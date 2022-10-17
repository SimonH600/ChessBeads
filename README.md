# ChessBeads

## The Research Question
This is the project proposal for the STA-310 project of Jiayi, Pinkie, Max, and Simon. Our research question is to identify whether or not we believe Hans Niemann cheated. After Magnus Carlsen accused Hans Niemann of cheating, a number of high profile chess detectives and statisticans made claims about whether or not he cheated. Chess.com notably released a report looking at 2 factors: his irregular growth in skill, and his irregular play pattern that aligned closely with engines. We seek to further explore these results, as they tended to disagree with other experts.
read the report here: https://www.chess.com/blog/CHESScom/hans-niemann-report

## The Data
Hans Niemann was accused of cheating both online and in person. Luckily, we have a wealth of data about how Hans Niemann plays and the trends in his play because Chess.com stores all games played on it's platform. Using the chessR package, we can extract these games. The bigchess package, in combination with stockfish, can then analyze these games.

## The Variables in Question
The various reports on Hans Niemann studied his accuaracy, as it aligned with stockfish, his rating and strength growth, as compared to other players of similar skill, and the center and spread of time usage. All of these are used to identify suspicious behaviour, and are at the root of what chess.com used to close the account of Hans Niemann.


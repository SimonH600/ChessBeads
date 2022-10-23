# ChessBeads

## The Research Question
This is the project proposal for the STA-310 project of Jiayi, Pinkie, Max, and Simon. Our research question is to identify whether or not we believe Hans Niemann cheated. After Magnus Carlsen accused Hans Niemann of cheating, a number of high profile chess detectives and statisticans made claims about whether or not he cheated. Chess.com notably released a report looking at 2 factors: his irregular growth in skill, and his irregular play pattern that aligned closely with engines. We seek to further explore these results, as they tended to disagree with other experts.
read the report here: https://www.chess.com/blog/CHESScom/hans-niemann-report

## The Data
Hans Niemann was accused of cheating both online and in person. Luckily, we have a wealth of data about how Hans Niemann plays and the trends in his play because Chess.com stores all games played on it's platform. Using the chessR package, we can extract these games. The bigchess package, in combination with stockfish, can then analyze these games.

## The Variables in Question
The various reports on Hans Niemann studied his accuaracy, as it aligned with stockfish, his rating and strength growth, as compared to other players of similar skill, and the center and spread of time usage. All of these are used to identify suspicious behaviour, and are at the root of what chess.com used to close the account of Hans Niemann.

## Summary Statistics

<p align="center">
  <img src=https://github.com/SimonH600/ChessBeads/blob/910b9b3701d56edafcdc30a0767a11c5ab679b5e/Summary%20Stats%20Chess%20Project.png />
</p>


## What We Will Study
This study will aim to answer the following questions:
    1. Was Hans Niemann's Improvement Irregular?
    2. Did Hans Niemann Play Irregularly?
    3. Can we provide statistical evidence that Hans Niemann cheated?
    
## How we will complete our study

### Did Hans Niemann Improve Irregularly?
Testing whether Hans Niemann's ratings improved irregularly is quite easy. Chess.com compiled graphics and numerical benchmarks comparing Hans Niemann to the greatest chess players of all time. These included everyone from Vishi Anand to Bobby Fischer to Alireza Firouzja. By looking at rating plotted against time, we can see a clear pattern. We see that fitting a logarithmic graph to ratings works for nearly all high level players who started while they were 

### Did Hans Niemann Play Irregularly?
There are 2 key factors to irregular play: Accuaracy and Time Management. Engines take time to process positions, a time that tends to be constant. Thus, low variance combined with high accuaracy is a strong indicator in play patterns. 

The other important factor is whether Hans Niemann matained a consistent level of play. We don't expect for Chess Players to swing between 70% accuaracy and 90% accuaracy from session to session. These wild variations in ratings are key indicators of irregular play.

### Can we provide statistical evidence that Hans Niemann cheated?
To demonstrate Hans Niemann cheated, we must demonstrate that he played at a much higher level than he is actually capable of. The previous two questions have laid the groundwork for this. If we can show that Hans Niemann has grown at an impossible rate, and that his play patterns align closely with an engine, then we have some evidence that Hans Niemann cheated.

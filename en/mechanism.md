# Payment Mechanism for Players

The play fees paid by players for arcade games are distributed to the game's leaderboard.

Example）Dragotchi Parkour Race Leaderboard
<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/exampleLeaderBoard.png" alt="Leaderboard Example" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

For instance, if Alice's distribution rate is 33.74%, when someone plays, approximately 0.3374 USD of the 1 USD play fee is transferred to Alice's wallet.

The algorithm for determining the distribution rate in Dragotchi races is set so that the distribution rate for the player who ran the farthest among those who did not reach the GOAL is half the rate of the slowest player among those who did. The distribution rate is determined in proportion to the score (among players who reached the GOAL, it's based on time speed; among players who did not, it's based on the distance run).

Rankings are not reset as a rule. If a reset is to be done, it will be announced on Discord at least 14 days in advance. Each game has a different algorithm for determining the distribution rate, but we aim to devise and adopt as fair an algorithm as possible. Details of the game's distribution rate algorithm will be organized and published in the algorithm section.

<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/paymentworld.webp" alt="paymentworld" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

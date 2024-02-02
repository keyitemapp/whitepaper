# 玩家支付费用的机制

玩家支付的街机游戏费用将分配到游戏的排行榜中。

示例）Dragotchi Parkour Race 排行榜
<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/exampleLeaderBoard.png" alt="排行榜示例" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

例如，如果Alice的分配率是33.74%，当有人玩时，1美元的游戏费用中的大约0.3374美元会转入Alice的钱包。

在Dragotchi赛跑中决定分配率的算法设定为，未达到终点的玩家中跑得最远的玩家的分配率是达到终点的玩家中最慢的人的分配率的一半。分配率按照得分比例确定（对于达到终点的玩家，基于时间速度；对于未达到终点的玩家，基于跑过的距离）。

排名原则上不会重置。如果要进行重置，将至少提前14天在Discord上通知。每个游戏决定分配率的算法各不相同，但我们旨在设计和采用尽可能公平的算法。游

<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/paymentworld.webp" alt="paymentworld" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<title>皇室战争 - 游戏介绍与攻略</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:"Microsoft YaHei";
}

body{
background:linear-gradient(135deg,#1e3c72,#2a5298);
color:#333;
line-height:1.8;
}

/* 导航栏 */

nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,0.7);
padding:15px;
z-index:999;
}

nav ul{
display:flex;
justify-content:center;
list-style:none;
}

nav li{
margin:0 20px;
}

nav a{
color:white;
text-decoration:none;
font-size:18px;
transition:0.3s;
}

nav a:hover{
color:#ffd700;
}

/* 标题 */

header{
height:350px;
display:flex;
justify-content:center;
align-items:center;
color:white;
text-align:center;
}

header h1{
font-size:48px;
letter-spacing:3px;
animation:fadeDown 1.5s;
}

@keyframes fadeDown{
from{
opacity:0;
transform:translateY(-50px);
}
to{
opacity:1;
transform:translateY(0);
}
}

/* 内容容器 */

.container{
width:80%;
margin:auto;
margin-top:60px;
}

/* 卡片 */

.card{
background:white;
padding:30px;
margin:30px 0;
border-radius:12px;
box-shadow:0 10px 20px rgba(0,0,0,0.2);
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 20px 30px rgba(0,0,0,0.3);
}

.card h2{
color:#2a5298;
margin-bottom:15px;
}

/* 视频区域 */

.video{
height:250px;
background:#000;
margin-top:15px;
border-radius:8px;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:20px;
}

/* 列表 */

ul{
margin-left:20px;
}

/* 评论区 */

.comment{
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 10px 20px rgba(0,0,0,0.2);
}

textarea{
width:100%;
height:120px;
padding:10px;
border-radius:6px;
border:1px solid #ccc;
margin-top:10px;
}

button{
margin-top:10px;
padding:10px 20px;
border:none;
background:#2a5298;
color:white;
border-radius:6px;
cursor:pointer;
transition:0.3s;
}

button:hover{
background:#1e3c72;
}

footer{
text-align:center;
color:white;
padding:30px;
margin-top:40px;
}

</style>
</head>

<body>

<nav>
<ul>
<li><a href="#play">核心玩法与机制</a></li>
<li><a href="#feature">游戏特色与现状</a></li>
<li><a href="#deck">热门强势卡组推荐</a></li>
<li><a href="#rule">卡组搭配通用原则</a></li>
</ul>
</nav>

<header>
<h1>皇室战争</h1>
</header>

<div class="container">

<div class="card">
<p>
《部落冲突：皇室战争》（Clash Royale）是一款由芬兰游戏公司Supercell开发的融合了
即时策略、卡牌与塔防元素的手机游戏，于2016年上线。玩家通过收集卡牌组建牌组，
在实时对战中以摧毁对方城堡为目标。
</p>
</div>

<div class="card" id="play">

<h2>核心玩法与机制</h2>

<ol>

<li>
获胜条件：每场对战的目标是摧毁对方的“国王塔”和“公主塔”。常规对战时间为3分钟，
若未决出胜负则进入加时赛（“突然死亡”模式），最终通过比较摧毁塔的数量或塔剩余血量决定胜负。
</li>

<li>
卡牌系统：卡牌是游戏核心，分为军队卡、建筑卡和法术卡三大类型。
卡牌有普通、稀有、史诗、传奇等不同稀有度。玩家需要从收集的卡牌中挑选8张组建自己的战斗牌组。
</li>

<li>
资源管理：使用卡牌需要消耗“圣水”，圣水会随时间自动增长（上限10点），合理分配圣水是取胜关键。
比赛后期会进入“双倍圣水”甚至“三倍圣水”阶段，加快节奏。
</li>

<li>
主要模式：游戏支持1v1实时对战、2v2合作对战、部落战以及各种挑战活动。
</li>

</ol>

<div class="video">【玩法视频】</div>

</div>

<div class="card" id="feature">

<h2>游戏特色与现状</h2>

<ol>

<li>实时与策略：游戏主打快节奏实时对战（每局3-5分钟），并具有“易上手，难精通”的深度策略性。</li>

<li>收集与成长：玩家通过赢得对战、开启宝箱来收集和升级卡牌，提升实力。</li>

<li>社交元素：玩家可以组建或加入部落，分享卡牌、进行私人对战或参与部落战。</li>

<li>持续更新：游戏持续推出新卡牌、新竞技场、主题赛季和活动。</li>

</ol>

<div class="video">【特色视频】</div>

</div>

<div class="card" id="deck">

<h2>热门强势卡组推荐</h2>

<ol>

<li>毒矿刺客消耗流：以野蛮人攻城槌、掘地矿工、毒药法术和幻影刺客为核心。</li>

<li>三枪矿工流：核心是三个火枪手与矿工，搭配公主、骷髅守卫等卡牌。</li>

<li>精英哥布林体系：核心搭配“精英哥布林+觉醒哥布林钻机”。</li>

<li>2V2双矿工消耗流：适合双人模式，组合三个火枪手、矿工、哥布林飞桶、公主和熔炉。</li>

<li>低费野猪电塔组合：圣水消耗仅约2.9，性价比高。</li>

<li>地震皇猪迫炮流：双核速攻体系。</li>

</ol>

<div class="video">【卡牌解说视频】</div>

</div>

<div class="card" id="rule">

<h2>卡组搭配通用原则</h2>

<ol>

<li>费用平衡：平均圣水消耗建议在3.7到4.5之间。</li>

<li>
功能齐全：卡组应包含不同类型卡牌以应对各种局面：

<ul>
<li>单体伤害卡牌（如火枪手、迷你皮卡）</li>
<li>溅射伤害卡牌（如女巫、火球）</li>
<li>肉盾卡牌（如巨人、皮卡超人）</li>
<li>对空卡牌（如飞龙宝宝、亡灵）</li>
<li>防御建筑卡牌（如特斯拉电磁塔、加农炮）</li>
</ul>

</li>

</ol>

</div>

<div class="comment">

<h2>评论区</h2>

<textarea placeholder="写下你的评论..."></textarea>
<br>
<button>发布评论</button>

</div>

</div>

<footer>

皇室战争攻略网页示例

</footer>

</body>
</html>

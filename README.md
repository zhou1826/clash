<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>皇室战争 - 官方风格攻略站</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:"Microsoft YaHei",sans-serif;
}

body{
background:#0f172a;
color:#e5e7eb;
line-height:1.7;
}

/* 导航栏 */

nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,0.85);
backdrop-filter:blur(6px);
padding:15px 0;
z-index:1000;
}

nav ul{
display:flex;
justify-content:center;
list-style:none;
}

nav li{
margin:0 25px;
}

nav a{
color:#fff;
text-decoration:none;
font-size:17px;
letter-spacing:1px;
transition:0.3s;
}

nav a:hover{
color:#facc15;
}

/* 英雄头图 */

.hero{
height:520px;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
overflow:hidden;
margin-bottom:40px;
}

/* 背景图片层 */
.hero::before{
content:"";
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
background:url("https://i.pinimg.com/1200x/81/24/1c/81241c6d8e7e052cb4a982a8061881a1.jpg") center/cover no-repeat;
filter:blur(8px);
transform:scale(1.1);
z-index:0;
}

/* 黑色遮罩层 */
.hero::after{
content:"";
position:absolute;
width:100%;
height:100%;
background:rgba(0,0,0,0.55);
z-index:1;
}

.hero-content{
position:relative;
z-index:2;
}

.hero h1{
font-size:64px;
letter-spacing:4px;
margin-bottom:20px;
animation:fadeDown 1.5s ease;
}

.hero p{
font-size:20px;
opacity:0.9;
}

@keyframes fadeDown{
from{opacity:0;transform:translateY(-40px)}
to{opacity:1;transform:translateY(0)}
}

.container{
width:85%;
max-width:1200px;
margin:auto;
}

.section{
margin:60px 0;
}

.section-title{
font-size:34px;
margin-bottom:25px;
color:#facc15;
}

/* 信息卡片 */

.card{
background:#1e293b;
padding:30px;
border-radius:14px;
box-shadow:0 10px 25px rgba(0,0,0,0.4);
margin-bottom:30px;
transition:0.35s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 20px 35px rgba(0,0,0,0.6);
}

.card h3{
color:#facc15;
margin-bottom:12px;
}

/* 卡组网格 */

.deck-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}

.deck-card{
background:#1e293b;
padding:20px;
border-radius:12px;
transition:0.3s;
}

.deck-card:hover{
transform:scale(1.05);
background:#334155;
}

.deck-card h4{
margin-bottom:10px;
color:#facc15;
}

/* 视频 */

.video{
margin-top:20px;
position:relative;
padding-bottom:56.25%;
height:0;
overflow:hidden;
border-radius:10px;
}

.video iframe{
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
}

/* 列表 */

ul{
margin-left:20px;
margin-top:10px;
}

/* 页脚 */

footer{
text-align:center;
margin-top:80px;
padding:40px 0;
background:#020617;
color:#94a3b8;
}

</style>
</head>

<body>

<nav>
<ul>
<li><a href="#play">核心玩法</a></li>
<li><a href="#feature">游戏特色</a></li>
<li><a href="#deck">强势卡组</a></li>
<li><a href="#rule">搭配原则</a></li>
</ul>
</nav>

<div class="hero">
<div class="hero-content">
<h1>皇室战争</h1>
<p>策略 · 卡牌 · 实时竞技</p>
</div>
</div>

<div class="container">

<section class="section">
<div class="card">
<p>
《部落冲突：皇室战争》是一款由 Supercell 开发的实时策略卡牌游戏。玩家通过收集卡牌、
构建卡组并与全球玩家实时对战，以摧毁对方防御塔为目标。
</p>
</div>
</section>

<section class="section" id="play">
<h2 class="section-title">核心玩法</h2>

<div class="card">
<h3>战斗目标</h3>
<p>摧毁敌方公主塔和国王塔，3分钟内获得更多塔即获胜。</p>
</div>

<div class="card">
<h3>卡牌系统</h3>
<p>卡牌分为军队、建筑与法术三类。玩家需要从卡池中选择8张组成自己的战斗卡组。</p>
</div>

<div class="card">
<h3>圣水机制</h3>
<p>出牌需要消耗圣水。圣水随时间恢复，合理的圣水管理是胜负关键。</p>
</div>

<div class="video">
<iframe src="https://www.youtube.com/embed/1RC1kfevGmE" frameborder="0" allowfullscreen></iframe>
</div>

</section>

<section class="section" id="feature">
<h2 class="section-title">游戏特色</h2>

<div class="card">
<ul>
<li>实时对战，平均3分钟一局</li>
<li>全球竞技天梯排名系统</li>
<li>数百张卡牌自由组合</li>
<li>部落战与团队协作玩法</li>
<li>赛季更新与新卡持续推出</li>
</ul>
</div>

</section>

<section class="section" id="deck">
<h2 class="section-title">热门卡组</h2>

<div class="deck-grid">

<div class="deck-card">
<h4>毒矿消耗流</h4>
<p>矿工 + 毒药持续消耗敌方防御塔。</p>
</div>

<div class="deck-card">
<h4>三枪矿工流</h4>
<p>三个火枪手作为核心输出。</p>
</div>

<div class="deck-card">
<h4>精英哥布林速攻</h4>
<p>依靠高速突袭快速破塔。</p>
</div>

<div class="deck-card">
<h4>野猪2.9循环</h4>
<p>低费高频进攻的经典卡组。</p>
</div>

<div class="deck-card">
<h4>皇猪地震</h4>
<p>皇室野猪配合地震压制建筑。</p>
</div>

<div class="deck-card">
<h4>迫击炮控制</h4>
<p>通过防守反击慢慢压制。</p>
</div>

</div>

</section>

<section class="section" id="rule">
<h2 class="section-title">卡组搭配原则</h2>

<div class="card">
<ul>
<li>平均圣水消耗建议 3.0 - 4.0</li>
<li>必须拥有空中防御单位</li>
<li>至少一张法术卡</li>
<li>具备防守反击能力</li>
<li>确保卡组循环速度合理</li>
</ul>
</div>

</section>

</div>

<footer>
<p>皇室战争策略指南网站 · Clash Royale Fan Guide</p>
</footer>

</body>
</html>

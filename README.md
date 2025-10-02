# resume.html
<html lang="zh-Hant">


.contact-bar{display:flex;gap:12px;flex-wrap:wrap;margin-top:10px}


@media (max-width:880px){
.container{grid-template-columns:1fr;}
.card{order:2}
.content{order:1}
}


@media print{
body{padding:0}
.container{max-width:100%;grid-template-columns:1fr}
.card .profile-photo{display:none}
.content, .card{box-shadow:none;border-radius:0}
}
</style>
</head>
<body>
<div class="container">
<aside class="card">
<img class="profile-photo" src="images/profile.jpg" alt="個人照片">
<div class="name">吳秉澤</div>


<div class="contact">
<div class="muted">聯絡方式</div>
<div class="contact-bar">
<div>✉️ <a href="mailto:hallow3096@gmail.com">hallow3096@gmail.com</a></div>
<div>📱 0962077962</div>
</div>
</div>


<div style="margin-top:14px">
<div class="muted">技能</div>
<div class="skills">
<div class="skill">打掃</div>
<div class="skill">煮飯</div>
</div>
</div>
</aside>


<main class="content">
<section>
<h2>個人簡介</h2>
<p class="muted">我來自新北中和，有一點點社交恐懼，但是不用認識多久就會很活潑，面對考試的心態是臨時抱佛腳。</p>
</section>


<section>
<h2>工作經歷</h2>
<article class="job">
<h3>補習班工讀生</h3>
</article>
</section>


<section>
<h2>興趣</h2>
<div class="skills">
<div class="skill">打遊戲</div>
<div class="skill">看漫畫</div>
<div class="skill">聽音樂</div>
</div>
</section>
</main>
</div>


</body>
</html>

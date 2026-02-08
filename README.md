<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>東都みらいが丘小学校 公式サイト</title>
<style>
body{font-family:"ヒラギノ明朝 Pro","Hiragino Mincho Pro","MS PMincho",serif;margin:0;background:#f5f7fb;color:#222}
header{background:#9ed7b8;color:#fff;padding:16px}
nav a{color:#fff;margin-right:12px;text-decoration:none;font-weight:600;cursor:pointer}
main{max-width:1100px;margin:0 auto;padding:20px}
section{background:#fff;border-radius:12px;padding:20px;margin-bottom:18px;box-shadow:0 8px 24px rgba(0,0,0,.06);display:none}
section.active{display:block}
h2{margin-top:0}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
table{width:100%;border-collapse:collapse;margin-bottom:20px}
th,td{border:1px solid #e5e7eb;padding:10px;text-align:center}
th{background:#f0f4ff}
.month{margin-bottom:14px}
.secret{cursor:pointer;color:inherit;text-decoration:none;transition: transform 0.1s;}
.secret:active{transform: translateY(2px);}
.end{display:none;padding:16px;border-radius:10px;background:#eef6ff;margin-top:12px}
footer{padding:24px;text-align:center;color:#666}
.home-buttons{display:flex;flex-wrap:wrap;gap:16px;margin-top:20px}
.home-buttons button{background:#9ed7b8;color:#fff;padding:16px 24px;font-size:18px;border:none;border-radius:8px;cursor:pointer;flex:1 1 200px}
td[data-secret]{cursor:pointer;}
@media(max-width:800px){.grid{grid-template-columns:1fr}}
</style>
</head>
<body>
<header>
<h1>東都みらいが丘小学校</h1>
<nav>
<a onclick="go('home')">ホーム</a>
<a onclick="go('greeting')">校長あいさつ</a>
<a onclick="go('classroom')">教室紹介</a>
<a onclick="go('events')">学校行事</a>
<a onclick="go('timetable')">時間割</a>
<a onclick="go('news')">最近のお知らせ</a>
<a onclick="go('access')">アクセス</a>
</nav>
</header>
<main>

<section id="home" class="active">
<h2>ホーム</h2>
<div class="home-buttons">
<button onclick="go('greeting')">校長あいさつ</button>
<button onclick="go('classroom')">教室紹介</button>
<button onclick="go('events')">学校行事</button>
<button onclick="go('timetable')">時間割</button>
<button onclick="go('news')">最近のお知らせ</button>
<button onclick="go('access')">アクセス</button>
</div>
</section>

<section id="greeting">
<h2>校長あいさつ</h2>
<p>本校では基礎学力と協働的な学びを重視し、子どもたち一人ひとりが安心して学べる環境づくりを行っています。毎日の積み重ねで自然に <span class="secret" data-k="home1">成長</span> していく姿を大切にしています。</p>

<h3>1年生学年代表</h3>
<p>新しい学校生活に不安もありますが、毎日少しずつ <span class="secret" data-k="teacher1">挑戦</span> し、友達と助け合いながら学んでほしいと思います。</p>

<h3>2年生学年代表</h3>
<p>勉強も運動も少しずつ自分の力を伸ばしていくことが大切です。皆さんの <span class="secret" data-k="teacher2">努力</span> をしっかり見守ります。</p>

<h3>3年生学年代表</h3>
<p>友達との協力や発表を通して、自分の考えを伝える力を伸ばしていきましょう。毎日の <span class="secret" data-k="teacher3">学習</span> の積み重ねが大きな成果につながります。</p>

<h3>4年生学年代表</h3>
<p>理科や社会など、学ぶ内容が増えてきますが、好奇心を持って <span class="secret" data-k="teacher4">探求</span> することを楽しんでほしいです。</p>

<h3>5年生学年代表</h3>
<p>林間学校や学習発表会など、体験を通した学びも大切です。自立心を育てながら <span class="secret" data-k="teacher5">観察</span> する力を身につけましょう。</p>

<h3>6年生学年代表</h3>
<p>卒業に向けてまとめの学習や発表も増えます。最後まであきらめずに <span class="secret" data-k="teacher6">挑戦</span> して、自信をもって次のステップに進んでほしいです。</p>
</section>

<section id="classroom">
<h2>教室紹介</h2>
<div class="grid">
<div>
<h3>普通教室</h3>
<p>明るく風通しの良い教室で、ICT機器も整備されています。話し合いや発表がしやすい配置を工夫しています。黒板・電子黒板を活用し、視覚的に理解しやすい授業を行います。児童の作品や <span class="secret" data-k="class1">机</span> の配置も工夫されています。</p>
</div>
<div>
<h3>理科室</h3>
<p>安全に実験できる設備が整っています。実験では <span class="secret" data-k="class2">顕微鏡</span> や化学器具を使用します。児童が安全に学べるようにルールを徹底しています。</p>
</div>
<div>
<h3>図工室</h3>
<p>作品制作のための設備が充実しており、完成した <span class="secret" data-k="class3">作品</span> は展示して互いに鑑賞します。創造力を育む時間を大切にしています。</p>
</div>
<div>
<h3>音楽室</h3>
<p>授業では <span class="secret" data-k="class4">楽器</span> を活用し、表現力や協調性を養います。学年ごとの合奏練習や発表会も行われます。</p>
</div>
<div>
<h3>図書室</h3>
<p>多数の <span class="secret" data-k="class5">本</span> が揃っており、読書活動や調べ学習に活用できます。静かで集中できる環境です。</p>
</div>
<div>
<h3>コンピュータ室</h3>
<p>プログラミング学習やICT活用授業が行えるパソコンが揃っています。児童が主体的に学べる環境です。</p>
</div>
<div>
<h3>多目的室</h3>
<p>委員会活動や学年集会に使用されます。柔軟に利用できる広さと設備が整っています。</p>
</div>
<div>
<h3>特別支援教室</h3>
<p>個別学習サポート用の部屋で、児童一人ひとりに合わせた学習支援を行います。</p>
</div>
</div>
</section>

<section id="events">
<h2>学校行事</h2>
<!-- 行事は文章中に押せる単語を自然に配置 -->
<div class="month"><h3>4月</h3><p>入学式・<span class="secret" data-k="event1">始業式</span>。新しい学年が始まり、学校生活の目標を確認します。</p></div>
<div class="month"><h3>5月</h3><p><span class="secret" data-k="event2">運動会</span>。赤組・白組に分かれ、練習を通して協力する力を育てます。</p></div>
<div class="month"><h3>6月</h3><p><span class="secret" data-k="event3">体力テスト</span>。自分の体の成長を確認し、次の目標を立てます。</p></div>
<div class="month"><h3>7月</h3><p><span class="secret" data-k="event4">七夕会</span>。児童が短冊を書き、願いごとを発表します。</p></div>
<div class="month"><h3>8月</h3><p><span class="secret" data-k="event5">夏休み課題発表</span>。自由研究や制作物を展示します。</p></div>
<div class="month"><h3>9月</h3><p><span class="secret" data-k="event6">修学旅行</span>（6年生）。歴史や文化を体験します。</p></div>
<div class="month"><h3>10月</h3><p><span class="secret" data-k="event7">学芸会</span>。劇や発表を通して表現力や協調性を高めます。</p></div>
<div class="month"><h3>11月</h3><p><span class="secret" data-k="event8">校内音楽会</span>。各学年が合奏や合唱を披露します。</p></div>
<div class="month"><h3>12月</h3><p><span class="secret" data-k="event9">持久走大会</span>。最後まであきらめない心を育てます。</p></div>
<div class="month"><h3>1月</h3><p><span class="secret" data-k="event10">書初め大会</span>。新年の抱負を筆で表現します。</p></div>
<div class="month"><h3>2月</h3><p><span class="secret" data-k="event11">学習発表会</span>。劇や展示で学んだことを発表します。</p></div>
<div class="month"><h3>3月</h3><p><span class="secret" data-k="event12">卒業式</span>。6年生が新しい道へ進みます。</p></div>
</section>

<section id="timetable">
<h2>時間割</h2>
<h3>1～3年生</h3>
<table>
<tr><th>時限</th><th>月</th><th>火</th><th>水</th><th>木</th><th>金</th></tr>
<tr><td>1</td><td>国語</td><td>算数</td><td>国語</td><td>算数</td><td data-secret="normalTrigger">国語</td></tr>
<tr><td>2</td><td>算数</td><td>国語</td><td>算数</td><td>国語</td><td>算数</td></tr>
<tr><td>3</td><td>生活</td><td>生活</td><td>生活</td><td>生活</td><td>生活</td></tr>
<tr><td>4</td><td>音楽</td><td>図工</td><td>音楽</td><td>体育</td><td>図工</td></tr>
<tr><td>5</td><td>体育</td><td>体育</td><td>図工</td><td>音楽</td><td>体育</td></tr>
<tr><th>下校時刻</th><td>14:30</td><td>14:30</td><td>14:30</td><td>14:30</td><td>13:30</td></tr>
</table>

<h3>4～6年生</h3>
<table>
<tr><th>時限</th><th>月</th><th>火</th><th>水</th><th>木</th><th>金</th></tr>
<tr><td>1</td><td>国語</td><td>算数</td><td>理科</td><td>社会</td><td>国語</td></tr>
<tr><td>2</td><td>算数</td><td>国語</td><td>社会</td><td>理科</td><td>算数</td></tr>
<tr><td>3</td><td>理科</td><td>社会</td><td>理科</td><td>社会</td><td>社会</td></tr>
<tr><td>4</td><td>社会</td><td>理科</td><td>図工</td><td>音楽</td><td>理科</td></tr>
<tr><td>5</td><td>英語</td><td>英語</td><td>英語</td><td>英語</td><td>英語</td></tr>
<tr><td>6</td><td>体育</td><td>体育</td><td>体育</td><td>体育</td><td>―</td></tr>
<tr><th>下校時刻</th><td>15:30</td><td>15:30</td><td>15:30</td><td>15:30</td><td>14:00</td></tr>
</table>
</section>

<section id="news">
<h2>最近のお知らせ</h2>
<ul>
<li>3月1日：卒業式を行いました。</li>
<li>2月20日：学習発表会が行われました。</li>
<li>1月15日：持久走大会が行われました。</li>
<li>12月10日：校内音楽会が開催されました。</li>
<li>11月5日：図工作品展を開催しました。</li>
<li>10月18日：運動会結果発表。</li>
<li>9月20日：修学旅行（6年生）実施。</li>
<li>8月25日：夏休み課題発表展示。</li>
<li>7月7日：七夕会を行いました。</li>
<li>6月15日：体力テストを実施しました。</li>
</ul>
</section>

<section id="access">
<h2>アクセス</h2>
<p>〒XXX-XXXX 東都県あさひ市みらいが丘</p>
<p>TEL: 00XX-XX-XXXX</p>
</section>

<section id="normalEnd">
<h2>普通エンド</h2>
<p class="end"><strong>みんな卒業おめでとう！</strong><br>中学校でも頑張ってね！</p>
<p>今まで学校で学んだ日々や経験を通して、<span class="secret" data-k="normal1">探求</span>する心や、<span class="secret" data-k="normal2">努力</span>を惜しまない姿勢が大切です。これらを見つけていくと真の挑戦が始まります。</p>
</section>

<section id="trueEnd">
<p class="end"><strong>真エンド達成！</strong><br>最後まで観察しました。制作後記もぜひ読んでください。</p>
<p class="secret" data-k="true1">観察</p>
<p class="secret" data-k="true2">挑戦</p>
</section>

<section id="after">
<h2>制作後記</h2>
<p>このページはみんなの卒業をお祝いするために作成しました。この学校、東都みらいが丘小学校には、みらいが丘のように膨らんでいってほしいという思いを込めています。このサイトはチャットGPTに作ってもらいました。このサイトは本物の学校のサイトをイメージして作ってもらったので、まるで本物に感じたと思います。そう思ってもらったならうれしいです。これからも勉強や部活をがんばってください！</p>
</section>

</main>
<footer>© 東都みらいが丘小学校</footer>

<script>
function go(id){
 document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));
 document.getElementById(id).classList.add('active');
}

// 普通エンド
let normalCell = document.querySelector('#timetable td[data-secret="normalTrigger"]');
if(normalCell){
 normalCell.addEventListener('click', ()=>{
  document.getElementById('normalEnd').querySelector('.end').style.display='block';
  go('normalEnd'); // 普通エンドページへ移動
});
}

// 真エンド
let trueOrder=[];
document.querySelectorAll('#normalEnd .secret').forEach(el=>{
 el.addEventListener('click',()=>{
  if(!trueOrder.includes(el.dataset.k)) trueOrder.push(el.dataset.k);
  if(trueOrder.length===2){
   document.getElementById('trueEnd').querySelector('.end').style.display='block';
   go('after'); // 真エンド達成で制作後記へ
  }
 });
});
</script>
</body>

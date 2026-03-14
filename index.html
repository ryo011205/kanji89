<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ラーニング89</title>
<style>
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Helvetica Neue',Arial,'Hiragino Kaku Gothic ProN','Hiragino Sans',Meiryo,sans-serif;background:#f5f5f0;min-height:100vh;display:flex;justify-content:center;align-items:flex-start;padding:1rem;}
#wrap{max-width:560px;width:100%;margin:0 auto;padding:1rem 0.75rem 2.5rem;}
.screen{display:none;}.screen.active{display:block;}
.title-area{text-align:center;padding:1.5rem 0 1rem;}
.title-area h1{font-size:22px;font-weight:500;color:#1a1a1a;margin-bottom:4px;}
.title-area p{font-size:13px;color:#666;}
.section-label{font-size:12px;font-weight:500;color:#666;margin-bottom:6px;padding-left:2px;}
.cat-section{margin-bottom:10px;}
.cat-section-header{display:flex;align-items:center;gap:8px;margin-bottom:6px;}
.cat-section-tag{font-size:10px;font-weight:500;padding:2px 8px;border-radius:3px;}
.tag-kanji{background:#EEEDFE;color:#3C3489;}
.tag-eng{background:#E1F5EE;color:#085041;}
.tag-abc{background:#FAEEDA;color:#633806;}
.cat-section-line{flex:1;height:0.5px;background:#e0e0e0;}
.cat-row{display:grid;gap:8px;}
.cat-row-2{grid-template-columns:1fr 1fr;}
.cat-row-3{grid-template-columns:1fr 1fr 1fr;}
.cat-btn{background:#fff;border:0.5px solid #ccc;border-radius:10px;padding:10px 8px;cursor:pointer;transition:border 0.15s,background 0.15s;text-align:center;display:flex;flex-direction:column;align-items:center;gap:2px;}
.cat-btn:hover{background:#f5f5f5;}
.cat-btn.selected-kanji{border:2px solid #534AB7;background:#EEEDFE;}
.cat-btn.selected-eng{border:2px solid #1D9E75;background:#E1F5EE;}
.cat-btn.selected-abc{border:2px solid #BA7517;background:#FAEEDA;}
.cat-name{font-size:13px;font-weight:500;color:#1a1a1a;line-height:1.3;}
.cat-desc{font-size:10px;color:#666;line-height:1.3;}
.cat-btn.selected-kanji .cat-name{color:#3C3489;}
.cat-btn.selected-eng .cat-name{color:#085041;}
.cat-btn.selected-abc .cat-name{color:#633806;}
.mode-row{display:flex;gap:8px;justify-content:center;margin-bottom:0.8rem;}
.mode-btn{flex:1;border:0.5px solid #ccc;border-radius:8px;padding:10px 6px;background:#f5f5f0;color:#1a1a1a;cursor:pointer;font-size:13px;font-weight:500;transition:background 0.15s,border 0.15s;text-align:center;}
.mode-btn .mode-label{font-size:15px;font-weight:500;}
.mode-btn .mode-desc{font-size:10px;color:#666;margin-top:2px;}
.mode-btn.active-soft{background:#E1F5EE;border-color:#5DCAA5;color:#085041;}
.mode-btn.active-normal{background:#E6F1FB;border-color:#85B7EB;color:#0C447C;}
.mode-btn.active-hard{background:#FCEBEB;border-color:#F09595;color:#791F1F;}
.mode-btn.active-soft .mode-desc{color:#0F6E56;}
.mode-btn.active-normal .mode-desc{color:#185FA5;}
.mode-btn.active-hard .mode-desc{color:#A32D2D;}
.grade-row{display:flex;gap:6px;justify-content:center;flex-wrap:wrap;margin-bottom:0.6rem;}
.grade-btn{border:0.5px solid #ccc;border-radius:8px;padding:6px 12px;background:#f5f5f0;color:#1a1a1a;cursor:pointer;font-size:13px;transition:background 0.15s,border 0.15s;}
.grade-btn.active{background:#bfdbfe;border-color:#60a5fa;color:#1e40af;}
.start-btn{display:block;width:100%;background:#378ADD;border:none;border-radius:8px;color:#042C53;font-size:16px;font-weight:500;padding:13px;cursor:pointer;transition:background 0.15s,transform 0.1s;margin-top:0.8rem;}
.start-btn:hover{background:#85B7EB;}.start-btn:active{transform:scale(0.98);}
.start-btn:disabled{background:#e0e0e0;color:#999;cursor:not-allowed;}
#time-preview{text-align:center;font-size:12px;color:#666;margin-bottom:0.5rem;min-height:18px;}

/* game screen */
.scoreboard{background:#fff;border:0.5px solid #e0e0e0;border-radius:12px;padding:12px 14px;margin-bottom:0.8rem;}
.sb-row{display:flex;justify-content:space-between;align-items:center;gap:8px;}
.sb-item{text-align:center;flex:1;}
.sb-label{font-size:10px;color:#666;margin-bottom:2px;}
.sb-val{font-size:18px;font-weight:500;color:#1a1a1a;}
.sb-sep{width:0.5px;height:32px;background:#e0e0e0;}
.count-area{display:flex;gap:6px;margin-top:10px;padding-top:10px;border-top:0.5px solid #e0e0e0;align-items:center;}
.count-label{font-size:10px;color:#666;min-width:32px;}
.count-dots{display:flex;gap:4px;}
.cdot{width:14px;height:14px;border-radius:50%;border:0.5px solid #ccc;background:#f0f0f0;transition:background 0.2s;}
.cdot.hit{background:#4ade80;border-color:#22c55e;}
.cdot.out{background:#f87171;border-color:#ef4444;}
.bar-wrap{height:8px;background:#e0e0e0;border-radius:99px;overflow:hidden;border:0.5px solid #d0d0d0;margin-bottom:0.8rem;}
#timer-bar{height:100%;width:100%;background:#378ADD;border-radius:99px;transition:width 0.05s linear,background 0.3s;}
.q-card{background:#fff;border:0.5px solid #e0e0e0;border-radius:12px;padding:1.2rem 1.2rem 1rem;text-align:center;margin-bottom:0.8rem;}
.q-badge{font-size:11px;color:#666;margin-bottom:6px;}
.q-main{font-size:36px;font-weight:500;color:#1a1a1a;line-height:1.3;}
.q-time{font-size:12px;color:#666;margin-top:4px;}

/* grid */
.seq-label{font-size:11px;color:#666;margin-bottom:4px;text-align:center;}
.answer-sequence{display:flex;gap:6px;justify-content:center;align-items:center;min-height:36px;margin-bottom:8px;flex-wrap:wrap;}
.ans-slot{width:32px;height:32px;border-radius:8px;background:#f0f0f0;border:0.5px solid #ccc;display:flex;align-items:center;justify-content:center;font-size:16px;font-weight:500;color:#1a1a1a;}
.ans-slot.filled{background:#E6F1FB;border-color:#85B7EB;color:#0C447C;}
.ans-slot.correct-final{background:#dcfce7;border-color:#4ade80;color:#166534;}
.ans-slot.wrong-final{background:#fee2e2;border-color:#f87171;color:#991b1b;}
.grid-9{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-bottom:0.8rem;}
.grid-cell{background:#fff;border:0.5px solid #ccc;border-radius:8px;aspect-ratio:1;display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:500;color:#1a1a1a;cursor:pointer;transition:background 0.12s,border 0.12s,transform 0.08s;user-select:none;}
.grid-cell:hover{background:#f5f5f5;}
.grid-cell:active{transform:scale(0.95);}
.grid-cell.selected{background:#bfdbfe;border-color:#60a5fa;color:#1e40af;}
.grid-cell.correct{background:#dcfce7;border-color:#4ade80;color:#166534;}
.grid-cell.wrong{background:#fee2e2;border-color:#f87171;color:#991b1b;}
.grid-cell.used{background:#f0f0f0;color:#aaa;opacity:0.5;cursor:default;}
.grid-cell.disabled{pointer-events:none;}

/* input */
.input-wrap{margin-bottom:0.8rem;}
.input-wrap input{width:100%;font-size:22px;font-weight:500;text-align:center;padding:14px;border-radius:8px;border:0.5px solid #ccc;background:#fff;color:#1a1a1a;outline:none;}
.input-wrap input:focus{border:2px solid #378ADD;}
.submit-btn{display:block;width:100%;background:#378ADD;border:none;border-radius:8px;color:#042C53;font-size:15px;font-weight:500;padding:12px;cursor:pointer;margin-top:8px;transition:background 0.15s,transform 0.1s;}
.submit-btn:hover{background:#85B7EB;}.submit-btn:active{transform:scale(0.98);}

/* result */
.result-popup{background:#fff;border:0.5px solid #e0e0e0;border-radius:12px;padding:1.2rem;text-align:center;margin-bottom:0.8rem;min-height:72px;display:flex;flex-direction:column;align-items:center;justify-content:center;}
.result-big{font-size:28px;font-weight:500;margin-bottom:4px;}
.result-sub{font-size:13px;color:#666;}
.col-hit{color:#15803d;}.col-foul{color:#b45309;}.col-out-fly{color:#9a3412;}.col-out-goro{color:#7c3aed;}.col-strike{color:#dc2626;}.col-gameover{color:#dc2626;}.col-clear{color:#15803d;}

/* end */
.end-card{background:#fff;border:0.5px solid #e0e0e0;border-radius:12px;padding:2.5rem 1.5rem 2rem;text-align:center;}
.end-card h2{font-size:22px;font-weight:500;color:#1a1a1a;margin-bottom:0.3rem;}
.end-big{font-size:48px;font-weight:500;margin:0.5rem 0;}
.end-card p{font-size:14px;color:#666;margin-bottom:1.5rem;line-height:1.6;}
.end-stats{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:1.5rem;}
.e-stat{background:#f5f5f0;border-radius:8px;padding:8px 4px;text-align:center;}
.e-stat-l{font-size:10px;color:#666;margin-bottom:2px;}
.e-stat-v{font-size:16px;font-weight:500;color:#1a1a1a;}

@media(max-width:400px){
  .cat-row-3{grid-template-columns:1fr 1fr;}
  .end-stats{grid-template-columns:1fr 1fr;}
}
</style>
</head>
<body>
<div id="wrap">

<!-- ===== START SCREEN ===== -->
<div id="start-screen" class="screen active">
  <div class="title-area">
    <h1>タイムアタックゲーム</h1>
    <p>早く解いて得点チャレンジ！</p>
  </div>

  <div class="section-label">カテゴリを選ぶ</div>

  <div class="cat-section">
    <div class="cat-section-header">
      <span class="cat-section-tag tag-kanji">漢字</span>
      <div class="cat-section-line"></div>
    </div>
    <div class="cat-row cat-row-2">
      <div class="cat-btn" data-cat="kanji-read" data-group="kanji" onclick="selectCat(this)">
        <div class="cat-name">読み方</div>
        <div class="cat-desc">漢字 → 読みをひらがなで入力</div>
      </div>
      <div class="cat-btn" data-cat="kanji-write" data-group="kanji" onclick="selectCat(this)">
        <div class="cat-name">入力</div>
        <div class="cat-desc">読み → 9マスから漢字を選択</div>
      </div>
    </div>
  </div>

  <div class="cat-section">
    <div class="cat-section-header">
      <span class="cat-section-tag tag-eng">英語</span>
      <div class="cat-section-line"></div>
    </div>
    <div class="cat-row cat-row-3">
      <div class="cat-btn" data-cat="eng-read" data-group="eng" onclick="selectCat(this)">
        <div class="cat-name">読み</div>
        <div class="cat-desc">英語 → 日本語を入力</div>
      </div>
      <div class="cat-btn" data-cat="eng-mean" data-group="eng" onclick="selectCat(this)">
        <div class="cat-name">意味</div>
        <div class="cat-desc">日本語 → 9マスから文字を順に選択</div>
      </div>
      <div class="cat-btn" data-cat="eng-write" data-group="eng" onclick="selectCat(this)">
        <div class="cat-name">入力</div>
        <div class="cat-desc">日本語 → 9マスからABCを順に選択</div>
      </div>
    </div>
  </div>

  <div class="cat-section">
    <div class="cat-section-header">
      <span class="cat-section-tag tag-abc">アルファベット</span>
      <div class="cat-section-line"></div>
    </div>
    <div class="cat-row cat-row-2">
      <div class="cat-btn" data-cat="abc-upper" data-group="abc" onclick="selectCat(this)">
        <div class="cat-name">大文字</div>
        <div class="cat-desc">読み → 9マスの小文字から大文字を選択</div>
      </div>
      <div class="cat-btn" data-cat="abc-lower" data-group="abc" onclick="selectCat(this)">
        <div class="cat-name">小文字</div>
        <div class="cat-desc">大文字 → 小文字を入力</div>
      </div>
    </div>
  </div>

  <div class="section-label" style="margin-top:1rem;">モードを選ぶ</div>
  <div class="mode-row">
    <button class="mode-btn" data-mode="soft" onclick="setMode('soft',this)">
      <div class="mode-label">SOFT</div><div class="mode-desc">1文字 5秒</div>
    </button>
    <button class="mode-btn active-normal" data-mode="normal" onclick="setMode('normal',this)">
      <div class="mode-label">NORMAL</div><div class="mode-desc">1文字 3秒</div>
    </button>
    <button class="mode-btn" data-mode="hard" onclick="setMode('hard',this)">
      <div class="mode-label">HARD</div><div class="mode-desc">1文字 1秒</div>
    </button>
  </div>

  <div class="section-label">学年を選ぶ（漢字カテゴリに反映）</div>
  <div class="grade-row">
    <button class="grade-btn active" onclick="setGrade(1,this)">小1</button>
    <button class="grade-btn" onclick="setGrade(2,this)">小2</button>
    <button class="grade-btn" onclick="setGrade(3,this)">小3</button>
    <button class="grade-btn" onclick="setGrade(4,this)">小4</button>
    <button class="grade-btn" onclick="setGrade(5,this)">小5</button>
    <button class="grade-btn" onclick="setGrade(6,this)">小6</button>
  </div>
  <div id="time-preview"></div>
  <button class="start-btn" id="start-btn" onclick="startGame()" disabled>カテゴリを選んでください</button>
</div>

<!-- ===== GAME SCREEN ===== -->
<div id="game-screen" class="screen">
  <div class="scoreboard">
    <div class="sb-row">
      <div class="sb-item"><div class="sb-label">問題</div><div class="sb-val" id="g-qnum">1/10</div></div>
      <div class="sb-sep"></div>
      <div class="sb-item"><div class="sb-label">タイム</div><div class="sb-val" id="g-time">—</div></div>
      <div class="sb-sep"></div>
      <div class="sb-item"><div class="sb-label">連続ファール</div><div class="sb-val" id="g-foul">0</div></div>
      <div class="sb-sep"></div>
      <div class="sb-item"><div class="sb-label">アウト</div><div class="sb-val" id="g-out">0</div></div>
    </div>
    <div class="count-area">
      <div class="count-label">HIT</div>
      <div class="count-dots" id="hit-dots"></div>
      <div style="flex:1;"></div>
      <div class="count-label" style="text-align:right;">OUT</div>
      <div class="count-dots" id="out-dots"></div>
    </div>
  </div>
  <div class="bar-wrap"><div id="timer-bar"></div></div>
  <div class="q-card">
    <div class="q-badge" id="q-badge"></div>
    <div class="q-main" id="q-main"></div>
    <div class="q-time" id="q-time-hint"></div>
  </div>
  <div id="answer-area">
    <div class="seq-label" id="seq-label"></div>
    <div class="answer-sequence" id="answer-sequence"></div>
    <div class="grid-9" id="grid-9"></div>
    <div class="input-wrap" id="input-wrap" style="display:none;">
      <input type="text" id="ans-input" placeholder="ここに入力..." autocomplete="off" autocorrect="off" autocapitalize="off" spellcheck="false"/>
      <button class="submit-btn" onclick="submitText()">こたえる (Enter)</button>
    </div>
  </div>
  <div class="result-popup" id="result-popup" style="display:none;">
    <div class="result-big" id="rp-big"></div>
    <div class="result-sub" id="rp-sub"></div>
  </div>
</div>

<!-- ===== END SCREEN ===== -->
<div id="end-screen" class="screen">
  <div class="end-card">
    <h2 id="end-title">ゲーム終了</h2>
    <div class="end-big" id="end-icon"></div>
    <p id="end-comment"></p>
    <div class="end-stats">
      <div class="e-stat"><div class="e-stat-l">Hit</div><div class="e-stat-v" id="es-hit">0</div></div>
      <div class="e-stat"><div class="e-stat-l">ファール</div><div class="e-stat-v" id="es-foul">0</div></div>
      <div class="e-stat"><div class="e-stat-l">アウト</div><div class="e-stat-v" id="es-out">0</div></div>
      <div class="e-stat"><div class="e-stat-l">問題数</div><div class="e-stat-v" id="es-total">0</div></div>
    </div>
    <button class="start-btn" onclick="goStart()">もう一度あそぶ</button>
  </div>
</div>

</div><!-- #wrap -->

<script>
const MODE_SEC={soft:5,normal:3,hard:1};
const KANJI_BY_GRADE={
  1:["一","二","三","四","五","六","七","八","九","十","百","千","日","月","火","水","木","金","土","山","川","林","森","竹","花","草","石","貝","虫","犬","田","年","空","天","気","雨","夕","白","青","赤","大","中","小","上","下","左","右","口","目","手","足","耳","音","見","立","円","力","休","出","入","女","男","子","人","名","字","文","本","学","校","先","生","早","正","王","玉","糸","車","村","町"],
  2:["引","羽","雲","園","遠","何","科","夏","家","歌","画","回","会","海","絵","外","角","楽","活","間","丸","岩","顔","汽","記","帰","弓","牛","魚","京","強","教","近","兄","形","計","元","言","原","戸","古","午","後","語","工","公","広","交","光","考","行","高","黄","合","谷","国","黒","今","才","細","作","算","止","市","矢","姉","思","紙","寺","自","時","室","社","弱","首","秋","週","春","書","少","場","色","食","心","新","親","図","数","西","声","星","晴","切","雪","船","線","前","組","走","多","太","体","台","地","池","知","茶","昼","長","鳥","朝","直","通","弟","店","点","電","刀","冬","当","東","答","頭","同","道","読","内","南","肉","馬","売","買","麦","半","番","父","風","分","聞","米","歩","母","方","北","毎","妹","万","明","鳴","毛","門","夜","野","友","用","曜","来","里","理","話"],
  3:["悪","安","暗","医","委","意","育","員","院","飲","運","泳","駅","央","横","屋","温","化","荷","界","開","階","寒","感","漢","館","岸","起","期","客","究","急","級","宮","球","去","橋","業","曲","局","銀","区","苦","具","君","係","軽","血","決","研","県","庫","湖","向","幸","港","号","根","祭","皿","仕","死","使","始","指","歯","詩","次","事","持","式","実","写","者","主","守","取","酒","受","州","拾","終","習","集","住","重","宿","所","暑","助","消","商","章","勝","乗","植","身","神","真","深","進","世","整","全","相","送","息","速","族","打","対","待","代","第","題","短","談","着","注","調","定","庭","鉄","転","都","度","投","動","農","波","配","倍","発","反","坂","悲","美","筆","氷","表","病","品","部","服","物","平","勉","味","命","面","問","役","薬","油","遊","葉","落","流","旅","両","緑","礼","列","練","和"],
  4:["愛","案","以","衣","位","囲","胃","印","英","栄","塩","億","加","果","貨","課","芽","改","械","害","街","各","覚","完","官","管","関","観","願","希","季","紀","喜","旗","器","機","議","求","泣","救","給","挙","漁","共","協","鏡","競","極","訓","軍","型","景","芸","欠","結","建","健","験","固","功","好","候","航","康","告","差","菜","最","材","昨","察","参","産","散","残","氏","史","司","試","児","治","辞","失","借","種","周","祝","順","初","笑","唱","焼","照","賞","信","成","省","清","静","席","積","折","節","説","戦","選","然","争","倉","巣","束","側","続","卒","孫","帯","隊","達","単","置","仲","貯","伝","努","灯","堂","働","特","得","毒","熱","念","敗","博","飯","飛","費","必","票","標","不","夫","付","府","副","粉","兵","別","辺","変","便","包","法","望","牧","末","満","未","民","無","約","勇","要","養","浴","利","陸","良","料","量","輪","類","令","冷","例","歴","連","老","労","録"],
  5:["圧","移","因","永","営","衛","易","益","液","演","応","往","桜","恩","可","仮","価","河","過","賀","快","解","格","確","額","刊","幹","慣","眼","基","寄","規","技","義","逆","久","旧","居","許","境","均","禁","句","群","経","潔","件","券","険","検","限","現","減","故","個","護","効","厚","耕","鉱","構","興","講","混","査","再","災","妻","採","際","在","財","罪","雑","酸","賛","支","志","枝","師","資","飼","示","似","識","質","舎","謝","授","修","述","術","準","序","招","承","証","条","状","常","情","織","職","制","性","政","勢","精","製","税","責","績","接","設","舌","絶","銭","祖","素","総","造","像","増","則","測","属","率","損","退","貸","態","団","断","築","張","提","程","適","敵","統","銅","導","徳","独","任","燃","能","破","犯","判","版","比","肥","非","備","評","貧","布","婦","富","武","復","複","仏","編","弁","保","墓","報","豊","防","貿","暴","務","夢","迷","綿","輸","余","預","容","略","留","領"],
  6:["異","遺","域","宇","映","延","沿","我","灰","拡","革","閣","割","株","干","巻","看","簡","危","机","揮","貴","疑","吸","供","胸","郷","勤","筋","系","敬","警","劇","激","穴","絹","権","憲","源","厳","己","呼","誤","后","孝","皇","紅","降","鋼","刻","穀","骨","困","砂","座","済","裁","策","冊","蚕","至","私","姿","視","詞","誌","磁","射","捨","尺","若","樹","収","宗","就","衆","従","縦","縮","熟","純","処","署","諸","除","将","傷","障","城","蒸","針","仁","垂","推","寸","盛","聖","誠","宣","専","泉","洗","染","善","奏","窓","創","装","層","操","蔵","臓","存","尊","宅","担","探","誕","段","暖","値","宙","忠","著","庁","頂","潮","賃","痛","展","討","党","糖","届","難","乳","認","納","脳","派","拝","背","肺","俳","班","晩","否","批","秘","腹","奮","並","陛","閉","片","補","暮","宝","訪","亡","忘","棒","枚","幕","密","盟","模","訳","郵","優","幼","欲","翌","乱","卵","覧","裏","律","臨","朗","論"]
};
const KANJI_READINGS={"一":"いち","二":"に","三":"さん","四":"し","よん","五":"ご","六":"ろく","七":"なな","しち","八":"はち","九":"く","十":"じゅう","百":"ひゃく","千":"せん","日":"にち","月":"つき","火":"ひ","水":"みず","木":"き","金":"かね","土":"つち","山":"やま","川":"かわ","林":"はやし","森":"もり","竹":"たけ","花":"はな","草":"くさ","石":"いし","貝":"かい","虫":"むし","犬":"いぬ","田":"た","年":"とし","空":"そら","天":"てん","気":"き","雨":"あめ","夕":"ゆう","白":"しろ","青":"あお","赤":"あか","大":"だい","中":"なか","小":"しょう","上":"うえ","下":"した","左":"ひだり","右":"みぎ","口":"くち","目":"め","手":"て","足":"あし","耳":"みみ","音":"おと","見":"けん","立":"りつ","円":"えん","力":"ちから","休":"きゅう","出":"しゅつ","入":"にゅう","女":"おんな","男":"おとこ","子":"こ","人":"ひと","名":"なまえ","字":"じ","文":"もん","本":"ほん","学":"がく","校":"こう","先":"せん","生":"せい","早":"はやい","正":"ただしい","王":"おう","玉":"たま","糸":"いと","車":"くるま","村":"むら","町":"まち","引":"ひく","羽":"はね","雲":"くも","園":"えん","遠":"とおい","何":"なに","夏":"なつ","家":"いえ","歌":"うた","回":"かい","会":"かい","海":"うみ","絵":"え","外":"そと","角":"かど","楽":"たのしい","間":"あいだ","丸":"まる","岩":"いわ","顔":"かお","牛":"うし","魚":"さかな","強":"つよい","教":"おしえる","近":"ちかい","兄":"あに","形":"かたち","元":"もと","言":"いう","原":"はら","戸":"と","古":"ふるい","後":"あと","高":"たかい","黄":"きいろ","国":"くに","黒":"くろ","今":"いま","細":"ほそい","作":"つくる","止":"とまる","市":"し","矢":"や","姉":"あね","思":"おもう","紙":"かみ","寺":"てら","時":"とき","社":"しゃ","弱":"よわい","首":"くび","秋":"あき","春":"はる","書":"かく","少":"すくない","色":"いろ","食":"たべる","心":"こころ","新":"あたらしい","親":"おや","数":"かず","西":"にし","声":"こえ","星":"ほし","雪":"ゆき","船":"ふね","前":"まえ","走":"はしる","多":"おおい","太":"ふとい","体":"からだ","地":"ち","池":"いけ","茶":"ちゃ","昼":"ひる","長":"ながい","鳥":"とり","朝":"あさ","通":"とおる","弟":"おとうと","店":"みせ","電":"でん","刀":"かたな","冬":"ふゆ","東":"ひがし","頭":"あたま","道":"みち","読":"よむ","南":"みなみ","肉":"にく","馬":"うま","麦":"むぎ","父":"ちち","風":"かぜ","聞":"きく","米":"こめ","歩":"あるく","母":"はは","北":"きた","妹":"いもうと","万":"まん","明":"あかるい","毛":"け","夜":"よる","野":"の","友":"ともだち","来":"くる","里":"さと","話":"はなす","悪":"わるい","安":"やすい","暗":"くらい","育":"そだてる","飲":"のむ","運":"はこぶ","泳":"およぐ","駅":"えき","横":"よこ","温":"あたたかい","開":"あける","寒":"さむい","感":"かんじる","起":"おきる","急":"いそぐ","球":"たま","橋":"はし","区":"く","苦":"くるしい","軽":"かるい","血":"ち","研":"とぐ","県":"けん","湖":"みずうみ","向":"むく","幸":"しあわせ","港":"みなと","根":"ね","死":"しぬ","使":"つかう","始":"はじめる","指":"ゆび","歯":"は","次":"つぎ","事":"こと","持":"もつ","実":"み","写":"うつす","守":"まもる","取":"とる","酒":"さけ","終":"おわる","習":"ならう","集":"あつめる","住":"すむ","重":"おもい","所":"ところ","暑":"あつい","助":"たすける","消":"きえる","勝":"かつ","乗":"のる","植":"うえる","身":"み","神":"かみ","深":"ふかい","進":"すすむ","全":"すべて","相":"あい","送":"おくる","息":"いき","速":"はやい","打":"うつ","待":"まつ","短":"みじかい","着":"きる","注":"そそぐ","調":"しらべる","定":"さだめる","庭":"にわ","鉄":"てつ","転":"ころがる","動":"うごく","波":"なみ","発":"はつ","悲":"かなしい","美":"うつくしい","筆":"ふで","氷":"こおり","病":"やまい","物":"もの","勉":"べん","味":"あじ","命":"いのち","問":"とう","役":"やく","薬":"くすり","油":"あぶら","遊":"あそぶ","葉":"は","落":"おちる","流":"ながれる","旅":"たび","緑":"みどり","礼":"れい","練":"ねる","和":"わ","愛":"あい","英":"えい","覚":"おぼえる","完":"かん","願":"ねがう","希":"のぞむ","喜":"よろこぶ","機":"き","求":"もとめる","泣":"なく","救":"すくう","競":"きそう","建":"たてる","健":"けん","固":"かたい","好":"すき","差":"さ","最":"もっとも","察":"さっする","産":"うむ","残":"のこる","試":"こころみる","治":"なおす","失":"うしなう","借":"かりる","種":"たね","笑":"わらう","照":"てらす","信":"まこと","成":"なる","清":"きよい","静":"しずか","積":"つむ","折":"おる","戦":"たたかう","選":"えらぶ","争":"あらそう","続":"つづく","帯":"おびる","置":"おく","伝":"つたえる","努":"つとめる","働":"はたらく","得":"える","熱":"あつい","敗":"まける","飛":"とぶ","必":"かならず","変":"かわる","包":"つつむ","望":"のぞむ","満":"みちる","民":"たみ","勇":"いさむ","養":"やしなう","良":"よい","量":"はかる","令":"れい","冷":"つめたい","連":"つらなる","老":"おいる","異":"こと","危":"あぶない","机":"つくえ","貴":"とうとい","疑":"うたがう","吸":"すう","胸":"むね","勤":"つとめる","敬":"うやまう","劇":"げき","激":"はげしい","絹":"きぬ","困":"こまる","座":"すわる","若":"わかい","収":"おさめる","従":"したがう","縮":"ちぢむ","除":"のぞく","傷":"きず","城":"しろ","推":"おす","誠":"まこと","洗":"あらう","染":"そめる","善":"よい","創":"つくる","操":"あやつる","存":"ある","尊":"たっとい","担":"になう","探":"さがす","暖":"あたたかい","忠":"まごころ","痛":"いたい","届":"とどける","難":"むずかしい","認":"みとめる","拝":"おがむ","背":"せ","晩":"ばん","秘":"ひめる","腹":"はら","閉":"とじる","補":"おぎなう","暮":"くれる","宝":"たから","亡":"なくなる","忘":"わすれる","乱":"みだれる","卵":"たまご","裏":"うら"};
function getReading(k){return KANJI_READINGS[k]||null;}

const ENG_DATA=[
  {q:"dog",mean:"いぬ"},{q:"cat",mean:"ねこ"},{q:"apple",mean:"りんご"},{q:"blue",mean:"あお"},
  {q:"run",mean:"はしる"},{q:"happy",mean:"うれしい"},{q:"big",mean:"おおきい"},{q:"water",mean:"みず"},
  {q:"school",mean:"がっこう"},{q:"book",mean:"ほん"},{q:"mountain",mean:"やま"},
  {q:"friend",mean:"ともだち"},{q:"dream",mean:"ゆめ"},{q:"strong",mean:"つよい"},{q:"quickly",mean:"はやく"},
];
const ENG_DATA_SHORT=ENG_DATA.filter(d=>d.q.length<=7&&d.mean.length<=7);
const ABC_ALL="ABCDEFGHIJKLMNOPQRSTUVWXYZ".split("");
const ABC_KANA={"A":"え","B":"びー","C":"しー","D":"でぃー","E":"え","F":"えふ","G":"じー","H":"えいち","I":"あい","J":"じぇい","K":"けい","L":"える","M":"えむ","N":"えぬ","O":"おー","P":"ぴー","Q":"きゅー","R":"あーる","S":"えす","T":"てぃー","U":"ゆー","V":"ぶい","W":"だぶりゅー","X":"えっくす","Y":"わい","Z":"ぜっと"};

let selCat=null,selMode='normal',selGrade=1;
let questions=[],qIdx=0,hits=0,outs=0,consecutiveFouls=0,totalHits=0,totalFouls=0,totalOuts=0;
let timerInterval=null,timeLeft=0,maxTime=0,answered=false;
let gridCells=[],selectedSeq=[],answerChars=[];
let isGridMode=false;

function selectCat(el){
  document.querySelectorAll('.cat-btn').forEach(b=>b.classList.remove('selected-kanji','selected-eng','selected-abc'));
  el.classList.add('selected-'+el.dataset.group);
  selCat=el.dataset.cat;updateBtn();updatePreview();
}
function setMode(m,el){
  selMode=m;
  document.querySelectorAll('.mode-btn').forEach(b=>b.className='mode-btn');
  el.className='mode-btn active-'+m;
  updatePreview();
}
function setGrade(g,el){
  selGrade=g;
  document.querySelectorAll('.grade-btn').forEach(b=>b.classList.remove('active'));
  el.classList.add('active');
}
function updateBtn(){
  const b=document.getElementById('start-btn');
  if(selCat){b.disabled=false;b.textContent='プレイボール！';}
  else{b.disabled=true;b.textContent='カテゴリを選んでください';}
}
function updatePreview(){
  const el=document.getElementById('time-preview');
  if(!selCat){el.textContent='';return;}
  const s=MODE_SEC[selMode||'normal'];
  el.textContent='1文字 '+s+'秒 × 答えの文字数 = 制限時間';
}
function shuffle(a){const b=[...a];for(let i=b.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[b[i],b[j]]=[b[j],b[i]];}return b;}

function buildGridCells9(answerArr,poolFn){
  const pool=poolFn();
  const extras=shuffle(pool.filter(c=>!answerArr.includes(c))).slice(0,9-answerArr.length);
  const all=[...answerArr,...extras].slice(0,9);
  return shuffle(all.map(c=>c));
}

function buildQuestions(){
  const sec=MODE_SEC[selMode];
  if(selCat==='kanji-read'){
    return shuffle([...KANJI_BY_GRADE[selGrade]]).slice(0,10).map(k=>{
      const r=getReading(k)||'?';
      return{type:'text',display:k,badge:'小'+selGrade+' 漢字の読みをひらがなで入力',answer:r,time:Math.max(r.length*sec,2)};
    });
  }
  if(selCat==='kanji-write'){
    return shuffle([...KANJI_BY_GRADE[selGrade]]).slice(0,10).map(k=>{
      const r=getReading(k)||'?';
      return{type:'grid',display:r,badge:'小'+selGrade+' 読みに合う漢字を順に選択',answer:k,answerChars:[...k],gridPool:()=>KANJI_BY_GRADE[selGrade],time:Math.max(k.length*sec,2)};
    });
  }
  if(selCat==='eng-read'){
    return shuffle(ENG_DATA).slice(0,10).map(d=>({
      type:'text',display:d.q,badge:'英単語の意味を日本語で入力',answer:d.mean,time:Math.max(d.mean.length*sec,2)
    }));
  }
  if(selCat==='eng-mean'){
    return shuffle(ENG_DATA_SHORT).slice(0,10).map(d=>{
      const chars=[...d.q];
      return{type:'grid',display:d.mean,badge:'日本語に合う英単語の文字を順に選択',answer:d.q,answerChars:chars,
        gridPool:()=>"abcdefghijklmnopqrstuvwxyz".split("").filter(c=>!chars.includes(c)),
        time:Math.max(chars.length*sec,2)};
    });
  }
  if(selCat==='eng-write'){
    return shuffle(ENG_DATA_SHORT).slice(0,10).map(d=>{
      const chars=[...d.q];
      return{type:'grid',display:d.mean,badge:'日本語から英単語の文字を順に選択',answer:d.q,answerChars:chars,
        gridPool:()=>"abcdefghijklmnopqrstuvwxyz".split("").filter(c=>!chars.includes(c)),
        time:Math.max(chars.length*sec,2)};
    });
  }
  if(selCat==='abc-upper'){
    return shuffle(ABC_ALL).slice(0,10).map(upper=>{
      const lower=upper.toLowerCase();
      return{type:'grid',display:ABC_KANA[upper]||upper,badge:'読みに合う大文字を小文字マスから選択',
        answer:upper,answerChars:[lower],isUpperMode:true,
        gridPool:()=>"abcdefghijklmnopqrstuvwxyz".split("").filter(c=>c!==lower),
        time:Math.max(1*sec,2)};
    });
  }
  if(selCat==='abc-lower'){
    return shuffle(ABC_ALL).slice(0,10).map(upper=>({
      type:'text',display:upper,badge:'大文字に対応する小文字を入力',answer:upper.toLowerCase(),time:Math.max(1*sec,2)
    }));
  }
  return[];
}

function startGame(){
  if(!selCat)return;
  questions=buildQuestions();qIdx=0;hits=0;outs=0;consecutiveFouls=0;totalHits=0;totalFouls=0;totalOuts=0;
  showScreen('game-screen');updateScoreboard();showQ();
}
function showScreen(id){document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));document.getElementById(id).classList.add('active');}
function renderCountDots(){
  let hh='';for(let i=0;i<10;i++)hh+=`<div class="cdot${i<hits?' hit':''}"></div>`;
  document.getElementById('hit-dots').innerHTML=hh;
  let oh='';for(let i=0;i<3;i++)oh+=`<div class="cdot${i<outs?' out':''}"></div>`;
  document.getElementById('out-dots').innerHTML=oh;
}
function updateScoreboard(){
  document.getElementById('g-qnum').textContent=(qIdx+1)+'/10';
  document.getElementById('g-foul').textContent=consecutiveFouls;
  document.getElementById('g-out').textContent=outs+'/3';
  renderCountDots();
}
function showQ(){
  answered=false;selectedSeq=[];gridCells=[];
  document.getElementById('result-popup').style.display='none';
  document.getElementById('answer-area').style.display='block';
  const q=questions[qIdx];
  document.getElementById('q-badge').textContent=q.badge;
  document.getElementById('q-main').textContent=q.display;
  document.getElementById('q-time-hint').textContent='制限時間 '+q.time+'秒（'+q.answer.length+'文字 × '+MODE_SEC[selMode]+'秒）';
  document.getElementById('g-qnum').textContent=(qIdx+1)+'/10';
  isGridMode=q.type==='grid';
  const iw=document.getElementById('input-wrap');
  const g9=document.getElementById('grid-9');
  const as=document.getElementById('answer-sequence');
  const sl=document.getElementById('seq-label');
  if(isGridMode){
    iw.style.display='none';g9.style.display='grid';as.style.display='flex';
    sl.textContent=q.isUpperMode?'大文字：':'選択順：';
    answerChars=q.answerChars;
    renderAnswerSlots(q);
    const cells=buildGridCells9(q.answerChars,q.gridPool);
    renderGrid9(cells,q);
  } else {
    g9.style.display='none';as.style.display='none';sl.textContent='';
    iw.style.display='block';
    const inp=document.getElementById('ans-input');
    inp.value='';inp.style.borderColor='';inp.disabled=false;
    setTimeout(()=>inp.focus(),50);
  }
  maxTime=q.time;startTimer();updateScoreboard();
}
function renderAnswerSlots(q){
  const as=document.getElementById('answer-sequence');
  const n=q.isUpperMode?1:q.answerChars.length;
  as.innerHTML=Array.from({length:n},(_,i)=>`<div class="ans-slot" id="slot-${i}"></div>`).join('');
}
function renderGrid9(cells,q){
  const g=document.getElementById('grid-9');g.innerHTML='';gridCells=[];
  cells.forEach((char,idx)=>{
    const div=document.createElement('div');
    div.className='grid-cell';div.textContent=char;div.dataset.char=char;div.dataset.idx=idx;
    div.addEventListener('click',()=>onCellClick(div,char,q));
    g.appendChild(div);gridCells.push(div);
  });
}
function onCellClick(div,char,q){
  if(answered||div.classList.contains('used')||div.classList.contains('disabled'))return;
  const pos=selectedSeq.length;
  const expected=q.isUpperMode?q.answer.toLowerCase():q.answerChars[pos];
  if(char===expected){
    selectedSeq.push(div);div.classList.add('used');
    const slotIdx=q.isUpperMode?0:pos;
    const slot=document.getElementById('slot-'+slotIdx);
    if(slot){slot.textContent=q.isUpperMode?q.answer:char;slot.classList.add('filled');}
    if(selectedSeq.length===q.answerChars.length){
      clearInterval(timerInterval);answered=true;
      setTimeout(()=>{
        selectedSeq.forEach(d=>{d.classList.remove('used');d.classList.add('correct');});
        document.querySelectorAll('[id^="slot-"]').forEach(s=>s.classList.add('correct-final'));
        gridCells.forEach(c=>c.classList.add('disabled'));
        setTimeout(()=>processResult(timeLeft>0,true,q),300);
      },50);
    }
  } else {
    div.classList.add('wrong');
    clearInterval(timerInterval);answered=true;
    gridCells.forEach(c=>{
      c.classList.add('disabled');
      if(q.answerChars.includes(c.dataset.char)&&!c.classList.contains('used')&&!c.classList.contains('wrong'))
        c.classList.add('correct');
    });
    document.querySelectorAll('[id^="slot-"]').forEach(s=>s.classList.add('wrong-final'));
    setTimeout(()=>processResult(timeLeft>0,false,q),300);
  }
}
function processResult(inTime,correct,q){
  let rpBig,rpSub,rpClass;
  if(correct&&inTime){hits++;totalHits++;consecutiveFouls=0;rpBig='Hit!!';rpSub='せいかい！時間内にきめた！';rpClass='col-hit';}
  else if(correct&&!inTime){consecutiveFouls++;totalFouls++;rpBig='ファール';rpSub='せいかいだが時間オーバー... ('+consecutiveFouls+'/3)';rpClass='col-foul';}
  else if(!correct&&inTime){outs++;totalOuts++;consecutiveFouls=0;rpBig='フライアウト';rpSub='時間内だが誤選択... こたえ:「'+q.answer+'」';rpClass='col-out-fly';}
  else{outs++;totalOuts++;consecutiveFouls=0;rpBig='ゴロアウト';rpSub='時間オーバー＆誤選択... こたえ:「'+q.answer+'」';rpClass='col-out-goro';}
  updateScoreboard();
  document.getElementById('answer-area').style.display='none';
  showResultPopup(rpBig,rpSub,rpClass);
  if(consecutiveFouls>=3){setTimeout(()=>handleStrikeOut(),1000);return;}
  if(outs>=3){setTimeout(()=>endGame(false),1400);return;}
  if(hits>=4){setTimeout(()=>endGame(true),1400);return;}
  setTimeout(()=>advanceQ(),1400);
}
function submitText(){
  if(answered)return;
  const val=document.getElementById('ans-input').value.trim();
  if(!val)return;
  clearInterval(timerInterval);answered=true;
  const q=questions[qIdx];
  const inTime=timeLeft>0,correct=val===q.answer;
  document.getElementById('ans-input').disabled=true;
  document.getElementById('ans-input').style.borderColor=correct?(inTime?'#4ade80':'#fbbf24'):'#f87171';
  processResult(inTime,correct,q);
}
function onTimeout(){
  if(answered)return;answered=true;
  const q=questions[qIdx];
  if(isGridMode){
    gridCells.forEach(c=>{
      c.classList.add('disabled');
      if(q.answerChars.includes(c.dataset.char)&&!c.classList.contains('used'))c.classList.add('correct');
    });
    document.querySelectorAll('[id^="slot-"]').forEach(s=>s.classList.add('wrong-final'));
    setTimeout(()=>processResult(false,false,q),300);
  } else {
    const val=document.getElementById('ans-input').value.trim();
    document.getElementById('ans-input').disabled=true;
    const correct=val===q.answer;
    document.getElementById('ans-input').style.borderColor=correct?'#fbbf24':'#f87171';
    processResult(false,correct,q);
  }
}
function startTimer(){
  clearInterval(timerInterval);timeLeft=maxTime;updateBar();
  timerInterval=setInterval(()=>{timeLeft-=0.05;if(timeLeft<=0){timeLeft=0;clearInterval(timerInterval);if(!answered)onTimeout();}updateBar();},50);
}
function updateBar(){
  const bar=document.getElementById('timer-bar');
  const pct=Math.max(0,timeLeft/maxTime)*100;
  bar.style.width=pct+'%';
  document.getElementById('g-time').textContent=timeLeft.toFixed(1)+'秒';
  bar.style.background=pct>50?'#378ADD':pct>20?'#fbbf24':'#f87171';
}
function handleStrikeOut(){
  consecutiveFouls=0;outs++;totalOuts++;updateScoreboard();
  showResultPopup('STRIKE OUT!','3回連続ファール → アウト！('+outs+'/3)','col-strike');
  if(outs>=3){setTimeout(()=>endGame(false),1500);return;}
  if(hits>=4){setTimeout(()=>endGame(true),1500);return;}
  setTimeout(()=>advanceQ(),1500);
}
function showResultPopup(big,sub,cls){
  document.getElementById('rp-big').textContent=big;
  document.getElementById('rp-big').className='result-big '+cls;
  document.getElementById('rp-sub').textContent=sub;
  document.getElementById('result-popup').style.display='flex';
}
function advanceQ(){qIdx++;if(qIdx>=questions.length){endGame(hits>=4);return;}showQ();}
function endGame(cleared){
  showScreen('end-screen');
  if(cleared){
    document.getElementById('end-title').textContent='クリア！';
    document.getElementById('end-icon').textContent='🏆';
    document.getElementById('end-icon').className='end-big col-clear';
    document.getElementById('end-comment').textContent='見事クリア！'+hits+'本ヒットを記録！素晴らしいバッティング！';
  } else {
    document.getElementById('end-title').textContent='GAME OVER';
    document.getElementById('end-icon').textContent='⚾';
    document.getElementById('end-icon').className='end-big col-gameover';
    document.getElementById('end-comment').textContent='3アウト。'+hits+'Hit '+totalOuts+'アウト。またチャレンジ！';
  }
  document.getElementById('es-hit').textContent=totalHits;
  document.getElementById('es-foul').textContent=totalFouls;
  document.getElementById('es-out').textContent=totalOuts;
  document.getElementById('es-total').textContent=Math.min(qIdx+1,10);
}
function goStart(){
  showScreen('start-screen');
  document.querySelectorAll('.cat-btn').forEach(b=>b.classList.remove('selected-kanji','selected-eng','selected-abc'));
  selCat=null;updateBtn();updatePreview();
}
document.addEventListener('keydown',function(e){
  if(e.key==='Enter'&&!answered&&!isGridMode&&document.getElementById('input-wrap').style.display!=='none')submitText();
});
</script>
</body>
</html>

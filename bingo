<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>夏まつりビンゴ</title>

<style>
body {
  margin: 0;
  font-family: "游ゴシック", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
  background-image: url("https://drive.google.com/uc?export=view&id=1yCmioNHSj1dT_tvaF8lx4n9BoojUj-UW");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  min-height: 100vh;
  padding: 24px 8px;
  box-sizing: border-box;
}

.container {
  background: rgba(255, 255, 255, 0.9);
  border-radius: 16px;
  padding: 16px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
  max-width: 420px;
  width: 100%;
  position: relative;
  overflow: hidden;
}

h1 {
  font-size: 20px;
  text-align: center;
  margin: 4px 0 12px;
}

.bingo-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 4px;
}

.cell {
  position: relative;
  background: #ffffff;
  border-radius: 8px;
  border: 2px solid #1e4f8f;
  padding: 8px 6px;
  min-height: 80px;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-size: 12px;
  box-sizing: border-box;
  transition: transform 0.08s ease, box-shadow 0.08s ease;
}

.cell:active {
  transform: scale(0.96);
}

.cell-text {
  line-height: 1.3;
}

ruby {
  ruby-position: over;
  font-size: 12px;
}

rt {
  font-size: 9px;
}

.stamp {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  pointer-events: none;
  opacity: 0;
  transform: scale(0.3);
  transition: opacity 0.12s ease, transform 0.12s ease;
}

.stamp.visible {
  opacity: 1;
  transform: scale(1);
}

.stamp-circle {
  width: 52px;
  height: 52px;
  border-radius: 50%;
  border: 3px solid #3b2a1a;
  display: flex;
  align-items: center;
  justify-content: center;
}

.stamp-face {
  font-size: 26px;
  color: #3b2a1a;
}

.note {
  font-size: 11px;
  margin-top: 8px;
  text-align: center;
  color: #555;
}
</style>
</head>

<body>

<div class="container">
  <h1>夏まつりビンゴ</h1>

  <div class="bingo-grid" id="bingoGrid">

    <!-- ここから9マス（千明の元コードそのまま） -->
    <div class="cell" data-index="0">
      <div class="cell-text">
        <ruby>盆踊<rt>ぼんおど</rt></ruby>りを
        <ruby>一曲<rt>いっきょく</rt></ruby><ruby>以上<rt>いじょう</rt></ruby>
        <ruby>踊<rt>おど</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="1">
      <div class="cell-text">
        <ruby>加藤<rt>かとう</rt></ruby>ふみあきさんを
        <ruby>発見<rt>はっけん</rt></ruby>した
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="2">
      <div class="cell-text">
        <ruby>盆踊<rt>ぼんおど</rt></ruby>りを
        <ruby>一曲<rt>いっきょく</rt></ruby><ruby>以上<rt>いじょう</rt></ruby>
        <ruby>踊<rt>おど</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="3">
      <div class="cell-text">
        オタゲーを<ruby>見<rt>み</rt></ruby>た
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="4">
      <div class="cell-text">
        とうもの<ruby>会<rt>かい</rt></ruby>のゲームに
        <ruby>参加<rt>さんか</rt></ruby>した
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="5">
      <div class="cell-text">
        <ruby>屋台<rt>やたい</rt></ruby>で
        <ruby>何<rt>なに</rt></ruby>かを
        <ruby>買<rt>か</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="6">
      <div class="cell-text">
        <ruby>盆踊<rt>ぼんおど</rt></ruby>りを
        <ruby>一曲<rt>いっきょく</rt></ruby><ruby>以上<rt>いじょう</rt></ruby>
        <ruby>踊<rt>おど</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="7">
      <div class="cell-text">
        <ruby>学校<rt>がっこう</rt></ruby>の
        <ruby>先生<rt>せんせい</rt></ruby>に
        <ruby>会<rt>あ</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

    <div class="cell" data-index="8">
      <div class="cell-text">
        <ruby>盆踊<rt>ぼんおど</rt></ruby>りを
        <ruby>一曲<rt>いっきょく</rt></ruby><ruby>以上<rt>いじょう</rt></ruby>
        <ruby>踊<rt>おど</rt></ruby>った
      </div>
      <div class="stamp"><div class="stamp-circle"><div class="stamp-face">☺</div></div></div>
    </div>

  </div>

  <div class="note">
    マスをタップすると☺スタンプがつきます。<br>
    たて・よこ・ななめのどれかがそろうと花火と「CLEAR」が出ます。
  </div>
</div>

<!-- クリック動画（マスの中） -->
<video id="clickEffect"
  src="https://drive.google.com/uc?export=download&id=1HB9MjU4dn5mVsAO_5xVlKvAUsw2t9-JG"
  style="position:absolute; display:none; pointer-events:none; z-index:9999;">
</video>

<!-- 花火動画（全画面） -->
<video id="fireworksVideo"
  src="https://drive.google.com/uc?export=download&id=1JMdyIOHDOO7ENTXqn00E5xoYuRHHjSD3"
  style="position:fixed; top:0; left:0; width:100vw; height:100vh;
         display:none; pointer-events:none; z-index:99999;">
</video>

<script>
const cells = Array.from(document.querySelectorAll(".cell"));
let marked = Array(9).fill(false);

// クリック動画（マスの中）
function playClickEffect(cell) {
  const rect = cell.getBoundingClientRect();
  const video = document.getElementById("clickEffect");

  video.style.width = rect.width + "px";
  video.style.height = rect.height + "px";
  video.style.left = rect.left + "px";
  video.style.top = rect.top + "px";

  video.style.display = "block";
  video.currentTime = 0;
  video.play();

  video.onended = () => {
    video.style.display = "none";
  };
}

// 花火動画（全画面）
function playFireworks() {
  const video = document.getElementById("fireworksVideo");
  video.style.display = "block";
  video.currentTime = 0;
  video.play();

  video.onended = () => {
    video.style.display = "none";
  };
}

// ビンゴ判定
function checkBingo() {
  const lines = [
    [0,1,2],[3,4,5],[6,7,8],
    [0,3,6],[1,4,7],[2,5,8],
    [0,4,8],[2,4,6]
  ];
  return lines.some(line => line.every(i => marked[i]));
}

// クリック処理
cells.forEach((cell, index) => {
  cell.addEventListener("click", () => {
    if (marked[index]) return;
    marked[index] = true;

    // スタンプ
    const stamp = cell.querySelector(".stamp");
    stamp.classList.add("visible");

    // クリック動画
    playClickEffect(cell);

    // ビンゴ成立
    if (checkBingo()) {
      playFireworks();
    }
  });
});
</script>

</body>
</html>

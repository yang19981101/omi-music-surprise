<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8" />
<title>給今天的妳專屬小驚喜</title>
<style>
    body { 
        font-family: "微軟正黑體", sans-serif; 
        background-color: #fff3f3; 
        text-align: center; 
        padding: 80px 20px; 
        color: #c2185b; 
    }
    h1 { font-size: 36px; margin-bottom: 20px; }
    p { font-size: 28px; margin-bottom: 40px; }
    .heart { font-size: 48px; animation: bounce 1.2s infinite; }
    @keyframes bounce {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-15px); }
    }
</style>
</head>
<body>
<h1>🎁 今天的妳，辛苦了</h1>
<p id="message">正在載入溫柔話語…</p>
<div class="heart">❤️</div>

<audio id="bgm" autoplay loop>
    <source id="audioSrc" src="" type="audio/mpeg" />
    你的瀏覽器不支援音樂播放。
</audio>

<script>
(() => {
    const MAX_HISTORY = 7;
    const user = "你的GitHub帳號";     // <-- 這裡改成你的GitHub使用者名稱
    const repo = "omi-music-surprise"; // <-- 改成你的repo名稱
    const branch = "main";

    const messages = [
        "今天的妳，是休假天嗎？如果是的話，好好睡一覺；如果不是，那就...加油，我知道妳可以。",
        "不管今天多忙，都記得偷偷對自己說一句：『妳已經做得很好了』。",
        "我不知道妳今天過得怎樣，但我想說：無論什麼情緒，妳都有資格擁有。",
        "夜班真的很累吧？如果我可以，我想把妳肩上的壓力分一點走。",
        "今天的天空是不是一樣灰？沒關係，心裡還是可以亮一點。",
        "如果有誰讓妳難過，希望妳知道…至少有個傻理工男，在默默為妳集氣。",
        "有些累，不說出口也沒關係，反正我懂。",
        "好像每次想起妳，腦袋都會自己彈出一句：『她還好嗎？』",
        "這世界太吵的時候，我願意做那個不出聲的背景。",
        "不需要解釋，不需要回應，只希望妳…過得舒服一點。",
        "如果今天是小夜，那就…多喝水、多休息。",
        "其實啊，不需要特別什麼理由，只是單純…想給妳一點點力量。",
        "當妳覺得喘不過氣的時候，偷偷想想：有個人，正在替妳加油。",
        "如果今天是休假，那就…好好放縱一下自己。",
        "天知道我有多想把一句『辛苦了』，塞進妳的行李袋。",
        "感覺最近的妳…很忙吧？如果有機會，也想請妳好好吃一頓。",
        "我不會問妳的近況，因為我知道…有時候，安靜，比關心更溫柔。",
        "不知道妳現在在哪裡，但希望，妳正在對自己好一點。",
        "夜晚總是讓人特別脆弱，如果妳剛好看到這行字，就當我陪妳說晚安。",
        "這裡沒有什麼驚天動地，只有一點…不被察覺的溫柔。"
    ];

    const musics = [
        "day1.mp3",
        "day2.mp3",
        "day3.mp3",
        "day4.mp3",
        "day5.mp3",
        "day6.mp3",
        "day7.mp3"
    ];

    // 取得歷史（localStorage）
    let msgHistory = JSON.parse(localStorage.getItem("last7messages")) || [];
    let musicHistory = JSON.parse(localStorage.getItem("last7musics")) || [];

    // 篩選未出現過的候選
    const filterIndices = (arrayLength, history) => {
        const indices = [];
        for(let i=0; i<arrayLength; i++) {
            if(!history.includes(i)) indices.push(i);
        }
        return indices;
    };

    let msgCandidates = filterIndices(messages.length, msgHistory);
    let musicCandidates = filterIndices(musics.length, musicHistory);

    // 如果沒候選了，清空歷史重新來
    if(msgCandidates.length === 0) msgHistory = msgCandidates = [...Array(messages.length).keys()];
    if(musicCandidates.length === 0) musicHistory = musicCandidates = [...Array(musics.length).keys()];

    // 隨機選擇一個
    const randomPick = arr => arr[Math.floor(Math.random() * arr.length)];
    const msgIdx = randomPick(msgCandidates);
    const musicIdx = randomPick(musicCandidates);

    // 更新歷史並保持長度不超過MAX_HISTORY
    msgHistory.push(msgIdx);
    musicHistory.push(musicIdx);
    if(msgHistory.length > MAX_HISTORY) msgHistory.shift();
    if(musicHistory.length > MAX_HISTORY) musicHistory.shift();

    // 儲存回 localStorage
    localStorage.setItem("last7messages", JSON.stringify(msgHistory));
    localStorage.setItem("last7musics", JSON.stringify(musicHistory));

    // 顯示語錄
    document.getElementById("message").innerText = messages[msgIdx];

    // 設定音樂來源並播放
    const audioSrc = document.getElementById("audioSrc");
    audioSrc.src = `https://raw.githubusercontent.com/${user}/${repo}/${branch}/${musics[musicIdx]}`;

    const audio = document.getElementById("bgm");
    audio.load();
})();
</script>

</body>
</html>

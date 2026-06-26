<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Podcast</title>

<style>
body {
    font-family: Arial, sans-serif;
    background: #f2f2f2;
    padding: 40px;
}

.player {
    background: #fff;
    padding: 20px;
    border-radius: 12px;
    max-width: 600px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

button {
    background: #333;
    color: white;
    border: none;
    border-radius: 50%;
    width: 60px;
    height: 60px;
    font-size: 20px;
    cursor: pointer;
}

.progress {
    width: 100%;
    margin: 15px 0;
}

.time {
    font-size: 14px;
    color: #666;
}
</style>
</head>

<body>

<div class="player">
    <h2>Podcast anhören</h2>

    <button id="play">▶</button>

    <input type="range" id="progress" class="progress" value="0">

    <div class="time">
        <span id="current">0:00</span> /
        <span id="duration">0:00</span>
    </div>

    <audio id="audio" src="Sprinter.mp3"></audio>
</div>

<script>
const audio = document.getElementById("audio");
const playBtn = document.getElementById("play");
const progress = document.getElementById("progress");
const current = document.getElementById("current");
const duration = document.getElementById("duration");

// Play / Pause
playBtn.onclick = () => {
    if (audio.paused) {
        audio.play();
        playBtn.innerText = "⏸";
    } else {
        audio.pause();
        playBtn.innerText = "▶";
    }
};

// Fortschritt aktualisieren
audio.ontimeupdate = () => {
    progress.value = (audio.currentTime / audio.duration) * 100;

    current.innerText = formatTime(audio.currentTime);
};

// Gesamtlänge setzen
audio.onloadedmetadata = () => {
    duration.innerText = formatTime(audio.duration);
};

// klicken auf Fortschrittsbalken
progress.oninput = () => {
    audio.currentTime = (progress.value / 100) * audio.duration;
};

// Zeit formatieren
function formatTime(time) {
    const minutes = Math.floor(time / 60);
    const seconds = Math.floor(time % 60);
    return minutes + ":" + (seconds < 10 ? "0" : "") + seconds;
}
</script>

</body>
</html>

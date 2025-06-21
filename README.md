<h1>🎶 Emotion-Based Tamil Music Player using Face Detection</h1>

<p>
  A Python-based project that detects your facial emotion using your webcam and plays a matching Tamil song from YouTube automatically. It uses DeepFace for emotion analysis, OpenCV for capturing images, and yt-dlp for downloading and playing songs dynamically.
</p>

<h2>✨ Features</h2>
<ul>
  <li>Detects real-time facial expressions (happy, sad, angry, neutral, etc.)</li>
  <li>Plays matching Tamil songs based on emotion</li>
  <li>Downloads music on-the-fly from YouTube</li>
  <li>Simple and interactive console-based interface</li>
</ul>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>Python 3.10+</strong></li>
  <li>OpenCV</li>
  <li>DeepFace</li>
  <li>yt-dlp</li>
  <li>Pygame</li>
  <li>FFmpeg (for audio extraction)</li>
</ul>

<h2>📸 Screenshot</h2>
<p>
  <img src="https://your-image-url.png" alt="Emotion Detection Screenshot" width="500"/>
</p>

<h2>🚀 How It Works</h2>
<ol>
  <li>User starts the app</li>
  <li>Webcam opens — press <strong>SPACE</strong> to capture your face</li>
  <li>Emotion is detected using DeepFace</li>
  <li>The system searches YouTube for matching Tamil songs (e.g., <em>happy tamil songs</em>)</li>
  <li>First result is downloaded and played</li>
</ol>

<h2>📥 Installation</h2>
<pre>
git clone https://github.com/your-username/emotion-music-player.git
cd emotion-music-player
pip install -r requirements.txt
</pre>

<h3>Install FFmpeg:</h3>
<p>
Download from <a href="https://www.gyan.dev/ffmpeg/builds/">FFmpeg Builds</a> and update the <code>FFMPEG_PATH</code> in the script with the <code>/bin</code> path.
</p>

<h2>▶️ Run</h2>
<pre>
python main.py
</pre>

<h2>📦 Output Example</h2>
<pre>
📸 Press SPACE to capture your face...
🔍 Detecting emotion...
😶 Detected Emotion: sad
🔎 Searching YouTube for: sad tamil songs
🎵 Now Playing: Enna Solla Pogirai - Kandukondain Kandukondain
</pre>

<h2>🙌 Credits</h2>
<ul>
  <li>DeepFace – for emotion detection</li>
  <li>yt-dlp – for downloading YouTube audio</li>
  <li>Pygame – for music playback</li>
  <li>OpenCV – for webcam capture</li>
</ul>


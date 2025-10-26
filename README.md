<!-- First Section: Past Electronic Music Productions -->
<p>This is the page for my productions showcase, for my research output demos: (<a href="https://shinxinyangdemo.github.io/shinxinyangdemo.github.io-rs/" target="_blank">shinxinyangdemo.github.io/shinxinyangdemo.github.io-rs//</a>)</p>
<h1>Electronic Music Productions Previews</h1>

<!-- Description -->
<p>
    Previews of tracks I made years ago submit to (<a href="https://soundcloud.com/ussoanah/tracks" target="_blank">soundcloud.com/ussoanah/tracks</a>). And some made recently unreleased.
</p>

<style>
  .audio-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 20px;
    align-items: start;
  }
  .audio-item { text-align: center; }
  audio { width: 100%; }
</style>

<div class="audio-grid">
  <div class="audio-item">
    <h3>Binds</h3>
    <audio controls preload="none">
      <source src="binds_preview.mp3" type="audio/mpeg">
      <source src="binds_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="audio-item">
    <h3>Summer Was Fun</h3>
    <audio controls preload="none">
      <source src="summer was fun_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="audio-item">
    <h3>Deep Like the Ocean</h3>
    <audio controls preload="none">
      <source src="deep like the ocean_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="audio-item">
    <h3>Blast</h3>
    <audio controls preload="none">
      <source src="blast_preview.mp3" type="audio/mpeg">
      <source src="blast_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="audio-item">
    <h3>Away</h3>
    <audio controls preload="none">
      <source src="all_the_way_preview.mp3" type="audio/mpeg">
      <source src="all_the_way_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="audio-item">
    <h3>Dream</h3>
    <audio controls preload="none">
      <source src="dream_preview.mp3" type="audio/mpeg">
      <source src="dream_preview.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>




<!-- Image -->
<img src="live.jpg" alt="Live DJing" style="width: 100%; height: auto;">
<p>Live DJing <span>📍Hialeah, FL</span></p>

<!-- Third Section: Soundtracks for Interactive Theatre -->
<h1>Soundtracks for Interactive Theatre</h1>
<p>The indoor interactive theatre showcased original stories, where I took on the role of sound designer, horror-themed plays mostly.</p>


<h3>Soundtrack 1</h3>
<p>Start of one scene and following ambience</p>
<audio controls>
    <source src="soundtrack 2.wav" type="audio/wav">
    Your browser does not support the audio element.
</audio>

<h3>Soundtrack 2</h3>
<p>Almost the end of one ending triggered</p>
<audio controls>
    <source src="soundtrack 3.wav" type="audio/wav">
    Your browser does not support the audio element.
</audio>

<h3>Soundtrack 3</h3>
<p>Tension buildup</p>
<audio controls>
    <source src="soundtrack 1.wav" type="audio/wav">
    Your browser does not support the audio element.
</audio>

<h3>Soundtrack 4</h3>
<p>Quarrel</p>
<audio controls>
    <source src="soundtrack 4.wav" type="audio/wav">
    Your browser does not support the audio element.
</audio>

<h3>Soundtrack 5</h3>
<p>Accident happened</p>
<audio controls>
    <source src="soundtrack 5.wav" type="audio/wav">
    Your browser does not support the audio element.
</audio>

<!-- Images for the Theatre Soundtracks -->
<div style="width: 100%; margin-top: 20px;">


    <!-- Second Row: Smaller Third Image -->
    <div style="width: 100%; display: flex; justify-content: center; margin-top: 20px;">
        <img src="theatre3.jpg" alt="Theatre Scene 3" style="max-width: 100%; height: auto;">
    </div>

</div>


<p>"Back when Work-in-progress, one of the theatre scenes, depicting replicas of small towns from the 1990s."</p>

<script>
  const audios = Array.from(document.querySelectorAll('audio'));
  audios.forEach(a => {
    a.addEventListener('play', () => {
      audios.forEach(b => {
        if (b !== a && !b.paused) b.pause();
      });
    });
  });
</script>

<h1>End</h1>

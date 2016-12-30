# simpleBeeps
A very simple beat tracker based on Web Audio API. This is meant to be the basis for a larger project as manually adding beats as boolean values in an array is somehting tedious. 

To create a new tracker, use var myTracker = new tracker();

Track objects have the following attributes: <br>
<blockquote>
   beats: array of boolean values<br>
   config: {
   <blockquote>
        attack: 30,
        decay: 1500,
        frequency: 100,
        type: "sawtooth"
    </blockquote>
    }
</blockquote>

Special thanks to Brian Rinaldi for his exellent introduction to <a href="https://modernweb.com/audio-synthesis-in-javascript/">javascript Audio Synthesis</a>. 

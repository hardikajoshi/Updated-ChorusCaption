# download-musiccaps-dataset

Download the MusicCaps dataset for music captioning.
<h3>About this Dataset</h3>
The MusicCaps dataset contains 5,521 music examples, each of which is labeled with an English aspect list and a free text caption written by musicians.
<br>
-An aspect list is for example "pop, tinny wide hi hats, mellow piano melody, high pitched female vocal melody, sustained pulsating synth lead".
<br>
<br>
-The caption consists of multiple sentences about the music, e.g., "A low sounding male voice is rapping over a fast paced drums playing a reggaeton beat along with 
 a bass. Something like a guitar is playing the melody along. This recording is of poor audio-quality. In the background a laughter can be noticed. This song may be 
 playing in a bar."
<br>
<br>
 The text is solely focused on describing how the music sounds, not the metadata like the artist name.
<br>
<br>
The labeled examples are 10s music clips from the AudioSet dataset (2,858 from the eval and 2,663 from the train split).
<br>
<h3> Output:</h3>

![Screenshot 2023-09-23 162412](https://github.com/hardikajoshi/Updated-ChorusCaption/assets/90562304/e187f058-add8-4d6e-b7c0-03a8405cb851)




![Screenshot 2023-09-23 162457](https://github.com/hardikajoshi/Updated-ChorusCaption/assets/90562304/48def064-6fd9-4b16-97e7-f1ad7b420574)


Requires `datasets[audio]`, `ffmpeg`, `yt-dlp`, `torchaudio`.

![App Logo](data/icons/hicolor/scalable/apps/app.svg)

# Utile Music
An elegant music player for Linux based on Gapless designed for Utile OS.

As always, Utile OS's philosophy is minimal friction: giving you the most beautiful and rich experience with the least amount of clutter and effort possible. This is why we chose to base our music player on G4Music/Gapless by Nanling Zheng over GNOME Music.

Both apps were incredibly well designed; however, Gapless provided a few specifically important set of features that, fully combined, made for a really good base experience:
- Fast loading and file change monitoring.
- Group and sorts by album/artist/title, shuffle list, full-text searching.
- Coloured background Gaussian blur with the colour of your song's cover art, to offer a more personal experience where the entire app transforms to match the song artist's vibe.
- Simple, roomy UI that's easy on the eyes; with an epic visualiser and reasonably sized buttons.
- Supports gapless playback (hence, the name).
- Supports volume normalisation with ReplayGain.
- Allows you to choose a specific audio output plugin for the more technical users out there.

Now, of course, this isn't all; the app provided a good enough *starting point* for Utile OS to build on top of (we plan to add many more features) without the highly integrated project structure and development process of GNOME Music with the broader GNOME project.

Plans, in order of importance:

<ol>
	<li>Allow adding cover images to audio files</li>
	<li>Allow adding cover images to albums in case the audio file formats are incompatible</li>
	<li>Allow collapsing the side section to only show the song cover and controls</li>
	<li>Allow adding song lyrics</li>
	<li>Rewrite in Python; Vala is too niche</li>
</ol>
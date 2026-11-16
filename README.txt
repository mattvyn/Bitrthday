Open index.html (VS Code: right-click > Open with Live Server).

songs/                put your song here and name it song.mp3
photos/memories/      photos for the swipe carousel ("Our memories")
photos/<place>/       photos for each map stop (grind-coffee, sm-calamba, moonbucks, uplb, sky-castle, why-are-you-here)

In index.html:
- Map photos: search "var places" and fill imgs, e.g.
  imgs: ['photos/uplb/1.jpg', 'photos/uplb/2.jpg']
- Carousel photos: search "var photos" and set src, e.g.
  src: 'photos/memories/1.jpg'

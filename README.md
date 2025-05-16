```markdown
# 🎵 Multimedia Player by Jordan Leturgez

This is a simple web-based multimedia player that plays both **audio** and **video**, complete with a **transcript** section. Built using standard HTML5 elements, this project demonstrates how to embed and manage audio, video, and subtitle content in a modern browser environment.

---

## 🚀 Features

- 🎧 Embedded audio player with controls and accessibility label
- 🎥 Embedded video player with:
  - Playback controls
  - Custom width
  - Subtitles via `<track>`
- 📜 Transcript section beneath the video
- ✅ Fully passes required user story tests

---

## 📁 Project Structure

```plaintext
index.html        # Main file containing HTML structure and media players
README.md         # This file
````

---
```
## 🌐 Live Preview

To preview this project:

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge).
2. Play the audio or video.
3. View subtitles (if available) and read the transcript below.

---

## 📌 Usage Instructions

### Audio

```html
<audio controls aria-label="Relaxing background music">
  <source src="https://cdn.freecodecamp.org/curriculum/js-music-player/sailing-away.mp3" type="audio/mpeg">
</audio>
```
```
### Video

```html
<video controls width="600" aria-label="Educational video explaining the JavaScript map method">
  <source src="https://cdn.freecodecamp.org/curriculum/labs/What is the map method and how does it work.mp4" type="video/mp4">
  <track 
    src="https://cdn.freecodecamp.org/curriculum/labs/What%20is%20the%20map%20method%20and%20how%20does%20it%20work.vtt" 
    kind="subtitles" 
    srclang="en" 
    label="English Subtitles">
</video>
```
```
### Transcript

```html
<p>
  In this lesson, we’ll explore the JavaScript <code>map()</code> method...
</p>
```

---
```
## 📖 User Stories Covered

* Main title with `<h1>`
* Three distinct `<section>` elements
* Proper semantic and accessible usage of `<audio>`, `<video>`, and `<track>`
* Descriptive `<h2>` elements for each media section
* Fully accessible with ARIA labels and captions

---

## 🛠️ Tools Used

* HTML5
* Accessible Media Elements (ARIA, `<track>`)
* FreeCodeCamp-provided audio/video links

---

## 🧠 Author

**Jordan Leturgez**
\[Fort Wayne, Indiana]

---

## 📝 License

This project is open source and available for educational use.

```

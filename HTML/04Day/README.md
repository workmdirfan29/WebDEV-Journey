# HTML Anchor Tags, Media Links, and Elements

This document explains various HTML elements like anchor tags (`<a>`), media links (`<img>`, `<iframe>`), and how to use them in a web page.

---

## 1. **Anchor Tag**: Creating Clickable Hyperlinks

Anchor tags are used to create hyperlinks, which allow users to navigate between different web pages or resources.

```html
<!-- Anchor Tag: Creates clickable hyperlinks to navigate to different pages or resources -->
<a href="https://www.google.com/">Google</a>
```

## Understanding  `target="_blank"` and  `target="_main"`
- `target="_main"` : Opens the link in a new window or tab.
- `target="_blank"` : Opens the link in the same window/tab, replacing the current page.

### Example with `target="_main"` :

```html
<a href="https://github.com/workmdirfan29" target="_main">Github</a>
```
- The above link opens the GitHub profile in a new window/tab.

### Example with `target="_blank"` :

```html
<a href="https://www.linkedin.com/in/mdirfan2470/" target="_blank">Linkedin</a>
```
- The above link opens the LinkedIn profile in the same window/tab.

# 2. Relative and Absolute URLs
- **Relative URL** : Links to pages within the same website using only the path.

- **Absolute URL** : Links to external websites with the full URL.

### Example of `Relative URL` :
```html
<a href="/HTML/04Day/page2.html">Page2</a>
```
- The above link refers to a page within the same website (using a **Relative** path).
### Example of `Absolute URL` :
```html
<a href="https://freecomponentslib.vercel.app/">freecomponentslib</a>
```
- The above link refers to an external website using an **Absolute** URL.

# 3. Media Tags: Image and Video
- `<img>` Tag - Displaying Images

- The `<img>` tag is used to display images on a webpage.

### Example:
```html
<img src="https://cdn.inflearn.com/public/files/courses/330001/418e517b-6978-4c9e-9ac4-8b54f8d3b54e/%EB%8C%80%EC%A7%80%201.png" alt="logo"/>
```
- This image is displayed from an external source. The `alt` attribute provides alternative text for users who cannot view the image.
## 4. `<iframe> Tag` - Embedding Videos
- The `<iframe>` tag allows embedding external content, such as videos, directly into the webpage.
### Example:
```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/BsDoLVMnmZs?si=knI1HTTH3M5-wg_0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe>
```
- This embeds a YouTube video directly in the webpage.

## 5. Audio Tag (`<audio>`)
The `<audio>` tag is used to embed audio files into a webpage with playback controls.
```html
<audio src="/HTML/04Day/music.mp3" controls></audio>
```
- This embeds an audio file (`music.mp3`) from the specified relative path and provides the user with controls to play, pause, and adjust the volume.





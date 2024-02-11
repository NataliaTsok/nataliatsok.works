```html
<style>
  .aspect-ratio-wrapper {
    position: relative;
    width: 100%; /* Full width of the parent */
    padding-top: 56.25%; 
  }
  
  .aspect-ratio-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>

<div class="aspect-ratio-wrapper">
  <iframe src="[YOUTUBE_VIDEO_URL]?controls=0&rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
```

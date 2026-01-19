---
title: Recent & Upcoming Events

# Listing view
view: compact

# Optional header image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: ''
---

<style>
/* Flip image and text for compact event view */
.media.stream-item.view-compact {
  display: flex;
  flex-direction: row-reverse; /* moves image to left */
  align-items: center; /* vertically center */
}

.media.stream-item.view-compact .media-body {
  text-align: left; /* ensure text stays left-aligned */
  flex: 1; /* take remaining space */
}

.media.stream-item.view-compact .ml-3 {
  margin-left: 0; /* remove old left margin */
  margin-right: 2rem; /* add space between image and text */
}
</style>
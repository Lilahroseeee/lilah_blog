---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
pagination: 
  enabled: true
---

<!-- Home page tweaks: show small thumbnails for posts and clamp long excerpts -->
<style>
  /* Thumbnail inside post cards on home */
  #post-list .post-preview img {
    width: 140px;
    height: 88px;
    object-fit: cover;
    float: left;
    margin-right: 1rem;
    border-radius: 6px;
  }

  /* Limit card excerpt height to keep the list compact */
  #post-list .card-text.content {
    max-height: 5.5rem;
    overflow: hidden;
  }

  /* Ensure the card body clears the floated image */
  #post-list .card-body:after { content: ''; display: table; clear: both; }
</style>

<!-- You can edit this file to add a short intro under the site title if you like -->

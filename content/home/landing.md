---
widget: blank
headless: true

# ... Put Your Section Options Here (title etc.) ...
title:
subtitle:
weight: 10  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.s
  columns: '1'
---
<!-- <link rel="stylesheet" href="custom.css"> -->
<style>
.home-section {
  padding: 30px 0 30px 0;
}

  .custom-header {
    position: relative;
    width: 100%;
    padding-top: 30.25%; /* 16:9 Aspect Ratio */
  }

  .custom-header .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5); /* Optional: overlay effect */
  }

  .custom-header video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

</style>

<header class="custom-header">
  <div class="overlay"></div>
  <video playsinline="playsinline" autoplay="autoplay" muted="muted" loop="loop">
    <source src="media/hudf_fly.mp4#t=40,70" type="video/mp4">
  </video>
</header>
<p><span style="color: #999999;"><small>Hubble Ultra Deep Field | NASA, ESA, and F. Summers</small></span></p>
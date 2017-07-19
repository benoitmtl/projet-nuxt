<template>
<div>
    <nav class="navbar" id="navbar">
     <div class="navbar-start">
       <div class="navbar-brand">
    <a class="navbar-item" href="http://bulma.io">
      <img src="http://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
    </a>

    <a class="navbar-item is-hidden-desktop" href="https://github.com/jgthms/bulma" target="_blank">
      <span class="icon" style="color: #333;">
        <i class="fa fa-github"></i>
      </span>
    </a>

    <a class="navbar-item is-hidden-desktop" href="https://twitter.com/jgthms" target="_blank">
      <span class="icon" style="color: #55acee;">
        <i class="fa fa-twitter"></i>
      </span>
    </a>

    <div class="navbar-burger burger" data-target="navMenuExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Docs
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            {{Overview}}
          </a>
          <a class="navbar-item">
            {{Elements}}
          </a>
          <a class="navbar-item">
            {{Components}}
          </a>
          <hr class="navbar-divider">
          <div class="navbar-item">
            Version 0.4.3
          </div>
        </div>
      </div>

      </div>
      <div class="navbar-end">
        <div class="navbar-burger">
        <span></span>
        <span></span>
        <span></span>
      </div>

      <div class="navbar-item">
  <div class="field is-grouped">
    <p class="control">
      <a class="button">
        <span class="icon">
          <i class="fa fa-twitter"></i>
        </span>
        <span>Tweet</span>
      </a>
    </p>
    <p class="control">
      <a class="button is-primary">
        <span class="icon">
          <i class="fa fa-download"></i>
        </span>
        <span>Download</span>
      </a>
    </p>
  </div>
  </div>
  </div>
  </nav>
</div>

</template>
<script>
let data = {
  Overview: 'Overview 1',
  Elements: 'Elements 2',
  Components: 'Components 3'
}

export default {
  el: '#navbar',
  data: function () {
    return data
  }
}
</script>

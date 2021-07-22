---
layout: default
title: About
permalink: /about
nav_order: 5
---
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>


## About the project

KiwiChat is &copy; 2019-{{ "now" | date: "%Y" }} by [Oscar BaiatRau](http://showchat.tk).

### License

KiwiChat is distributed by an [GPLv3 or later](http://www.gnu.org/licenses/gpl-3.0.html).

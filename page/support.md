---
layout: default
title: Support
permalink: /support
nav_order: 3
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

## Support >> Plugin kiwiChat NextClient

Do you have something to say? Do you need help?
See the support forum [Support Forum](https://wordpress.org/support/plugin/kiwichat/).

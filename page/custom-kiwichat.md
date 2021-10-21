---
layout: default
title: Custom KiwiChat Generator
permalink: /custom-kiwichat
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


## WORDPRESS PLUGIN KIWICHAT GENERATOR

### Create your amazing KiwiChat based plugin

Custom KiwiChat WordPress Plugin Generator, generate a custom zip file based on the KiwiChat is an online chat client, your IRC client based on kiwiirc supports direct websocket connections to IRC servers [BUILD](https://custom.kiwichat.ml/).

---
layout: default
title: Pull Requests
permalink: /pull
nav_order: 2
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

## Welcome to Pull Requests!

Pull requests help you collaborate on code with other people. 
As pull requests are created, they’ll appear here in a searchable and filterable list. 
To get started, you should [create a pull request](https://github.com/KiwiChat/wp-kiwichat/pulls).

---
layout: default
title: Contributing
permalink: /contributing
nav_order: 4
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

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/KiwiChat/wp-kiwichat.

### Submitting code changes:

- Open a [Pull Request](https://github.com/KiwiChat/wp-kiwichat/pulls)

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

## Thank you to the contributors of 

[![alt text][1]][2]

[1]: https://avatars.githubusercontent.com/u/52504536?s=60&v=4
"KiwiChat GitHub"
[2]: https://github.com/KiwiChat


[![alt text][3]][4]

[3]: https://avatars.githubusercontent.com/u/34014529?s=60&v=4
"Show-Chat GitHub"
[4]: https://github.com/Show-Chat

This project follows the [all-contributors](https://github.com/KiwiChat/wp-kiwichat/graphs/contributors) specification. Contributions of any kind welcome!

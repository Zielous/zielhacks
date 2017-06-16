# ZielHacks

---

#### About

> https://github.com/zielous/zielhacks
> v1.0 | 20170616
> License: none (public domain)

A set of files to quickly setup your projects which includes useful common resources.

Copy or clone this repo, and make sure to change this README file.



## Included directories and misc files

1. **Directories:** Contains the following structure:
  - /resources/css
  - /resources/images

2. **.gitignore:** The only line added is to ignore a folder called 'gitignore' (a personal preference to stuff local files in this directory won't get committed eg project brief and redline spec)



## Included HTML files

1. **index.html:** Contains the following:
  - Basic structure
  - Links to all CSS files below
  - Viewport to ensure media query simulation works



## Included CSS files

1. **reset.css:** meyerweb.com's simple yet powerful reset teplate. Swap it with your own preferred reset file. Loaded first in HTML.

1. **z-visiborder.css:** Easy visual indicators while building your HTML, complimenting the use of DevTools. Loaded second in HTML.

2. **z-scaffold.css:** Provide foundational common css selectors to act as a skeleton. This file shouldn't be edited. Loaded third in HTML.

3. **z-style.css:** This css is the editable partner to z-scaffold. Loaded fourth in HTML, followed by your own css files (or this can be your primary css file).

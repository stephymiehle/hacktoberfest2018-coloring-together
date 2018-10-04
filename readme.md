## Coloring Together

**Coloring Together** is a cute, simple project to display color schemes and contributions as a part of [Hacktoberfest 2018](https://hacktoberfest.digitalocean.com/).

## What is Hacktoberfest?

Hacktoberfest is a celebration of the open-source community; you can contribute by making a **pull request** (PR) to any public repo on GitHub. You can learn more (and find out how to get a free shirt!) at https://hacktoberfest.digitalocean.com/

## How can I contribute to this project?

Add your color scheme and attribution to the `index.html` file.

Copy this snippet and add it right before the `</body>` tag:

```html
<div
  class="swatch-card"
  style="
    --color1: #222;
    --color2: #444;
    --color3: #666;
    --color4: #888;
    --color5: #AAA;
    --background: #DDD;
    --text: #000;
  ">
  <div class="ampersand"></div>
  <span class="author">
    by <a href="https://github.com/YOUR-USERNAME-HERE" class="author">YOUR-USERNAME-HERE</a>
  </span>
</div>
```

Replace the color codes for `color1`, `color2`, `color3`, `color4`, `background`, and `text`. Your colors should be in hexadecimal, rgb, rgba, hsl, or hsla format.

Replace `YOUR-USERNAME-HERE` with... well, your username. **Do not** edit the rest of the markup in any other way!

After your PR is accepted, your colored ampersand will appear on the project website.
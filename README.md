# &lt;gravatar-image&gt;

[![license](https://img.shields.io/github/license/cluttered-components/gravatar-image.svg)](https://raw.githubusercontent.com/cluttered-components/gravatar-image/master/LICENSE)
[![Build Status](https://travis-ci.org/cluttered-components/gravatar-image.svg?branch=master)](https://travis-ci.org/cluttered-components/gravatar-image)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/cluttered-components/gravatar-image)

`gravatar-image` Display gravatar icon

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="gravatar-image.html">
    <style>
      .center-white-on-black {
        background-color: #000;
        color: #fff;
        text-align: center
      }
    </style>
    <div class="center-white-on-black">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<gravatar-image email="cluttered.code@gmail.com"></gravatar-image>
```

## Options

|   Attribute   | Options  |              Default               |                      Description                                              |
| ------------- | -------- | ---------------------------------- | ----------------------------------------------------------------------------- |
| `email`       | *string* | <EMPTY>                            | Your gravatar email                                                           |
| `rating`      | *string* | `g`                                | image rating (g, pg, r, x)                                                    |
| `size`        | *int*    | `80`                               | The img size                                                                  |
| `fallback`    | *string* | `404`                              | fallback on failure (404, mm, identicon, monsterid, wavatar, retro, blank, y) |
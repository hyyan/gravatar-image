# &lt;gravatar-image&gt;

Display a gravatar image

[![license](https://img.shields.io/github/license/cluttered-components/gravatar-image.svg)](https://raw.githubusercontent.com/cluttered-components/gravatar-image/master/LICENSE)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/cluttered-components/gravatar-image)

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="gravatar-image.html">
    <style>
      .center {
        text-align: center
      }
    </style>
    <div class="center">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<gravatar-image email="cluttered.code@gmail.com"></gravatar-image>
<gravatar-image email="cluttered.code@gmail.com" size="128"></gravatar-image>
<gravatar-image email="invalid_email" fallback="mm"></gravatar-image>
```

## Options

|   Attribute   | Options  |              Default               |                      Description                                              |
| ------------- | -------- | ---------------------------------- | ----------------------------------------------------------------------------- |
| `email`       | *string* | <EMPTY>                            | Your gravatar email                                                           |
| `rating`      | *string* | `g`                                | image rating (g, pg, r, x)                                                    |
| `size`        | *int*    | `80`                               | The img size                                                                  |
| `fallback`    | *string* | `404`                              | fallback on failure (404, mm, identicon, monsterid, wavatar, retro, blank) |
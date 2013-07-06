# connect-fonts-railway

Railway fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-railway");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/railway/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* railway

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/railway/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin

5. Set your CSS up to use the new font by using the "Railway" font-family.
```
    body {
      font-family: 'Railway', 'sans-serif', 'serif';
    }
```

## Font Info
Railway

* Copyright: Copyright (c) Justin Howes. An Unpublished work from Justin Howes., 1994. All rights reserved.

Revised July 2012 (c) Greg Fleming.
* Trademark: Railway is a trademark of Justin Howes. An Unpublished work from Justin Howes.

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-railway
* Repo: https://github.com/shane-tomlinson/connect-fonts-railway

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL


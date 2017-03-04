# image
> Image utility suite

Placeholder for some more generic browser image utilities (`image-clip` or maybe `image-data`), but for now it's just good for namespacing `load`:

```javascript
const Image = require('image')

Image.load(paths, callback)
```

It shouldn't clash with `window.Image` if you use a module bundler, but if that ends up being bothersome you could just import it as `Utils` or `ImageUtils` or something. That looks gross though so don't do it

## Install
```sh
npm install semibran/image
```

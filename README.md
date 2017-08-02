# Esri Leaflet RequireJS Example

Example of using [Leaflet](http://leafletjs.com) and [Esri Leaflet](http://esri.github.io/esri-leaflet/) with [RequireJS](http://requirejs.org/)!

1. [Fork and clone this repo](https://help.github.com/articles/fork-a-repo)
2. `cd` into `esri-leaflet-browserify-example`
3. Install dependencies with `npm install`
4. Open `index.html` in your browser.

## Using r.js

This example includes a configuration file `build-config.js` that also bundles Leaflet and Esri Leaflet with the [RequireJS Optimizer](http://requirejs.org/docs/optimization.html). You can run the optimizer with:

```bash
npm run build
```

afterwards, you'll need to update `index.html` in order to fetch the dependencies in a single bundle instead of plucking them individually from the `/node_modules` directory.

```html
<script src="node_modules/requirejs/require.js" data-main="app-built.js"></script>
```

### Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/Esri/esri-leaflet-requirejs-example/blob/master/CONTRIBUTING.md).

### Licensing
Copyright 2017 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [LICENSE](./LICENSE) file.

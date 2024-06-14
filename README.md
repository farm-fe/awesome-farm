<div align="center">
  <p align="center">
    <a href="https://farm-fe.github.io/" target="blank"><img src="https://raw.githubusercontent.com/farm-fe/farm/main/assets/logo.png" width="600" alt="Farm Logo" /></a>
  </p>
<h1>Awesome Farm</h1>
<p>A curated list of awesome things related to <a href="https://github.com/farm-fe/farm">Farm</a></p>

  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</div>

## Resources

### Official Resources

- [Documentation](https://farm-fe.github.io/)
- [GitHub Repo](https://github.com/farm-fe)
- [Release Notes](https://github.com/farm-fe/farm/blob/main/packages/core/CHANGELOG.md)

## Get Started

- [create-farm](https://github.com/vitejs/vite/tree/main/packages/create-vite) - Scaffolding Your First Farm Project.

## Plugins

### RustPlugins

#### Official Plugins

- **[`@farmfe/plugin-react`](https://github.com/farm-fe/farm/tree/main/rust-plugins/react)**：Support React `jsx` and `react-refresh`.
- **[`@farmfe/plugin-sass`](https://github.com/farm-fe/farm/tree/main/rust-plugins/sass)**：Support compiling `sass/scss` files.

#### Community Plugins

- **[`farm-plugin-remove-console`](https://github.com/jstors/farm-plugin-remove-console)**: ✂️ farm's plugin of remove console
- **[`farm-plugin-html-template`](https://github.com/jstors/farm-plugin-html-template)**: used to dynamically replace variables injected into HTML.
- **[`farm-plugin-replace-dirname`](https://github.com/jstors/farm-plugin-replace-dirname)**: replacement `__dirname`, `__filename` in node.
- **[`farm-plugin-compression`](https://github.com/Weeken/farm-plugin-compression)**: compress resources from dist and generate `.gz` file.

### JsPlugins

#### Official Plugins

- **[`@farmfe/js-plugin-postcss`](https://github.com/farm-fe/farm/tree/main/js-plugins/postcss)**：Support `postcss` in your project.
- **[`@farmfe/js-plugin-less`](https://github.com/farm-fe/farm/tree/main/js-plugins/less)**：Support compiling `less` files.
- **[`@farmfe/js-plugin-svgr`](https://github.com/farm-fe/farm/tree/main/js-plugins/svgr)**：Support compiling `svg` files.
- **[`@farmfe/js-plugin-dts`](https://github.com/farm-fe/farm/tree/main/js-plugins/dts)**：Support compiling `*.d.ts` files.
- **[`@farmfe/js-plugin-sass`](https://github.com/farm-fe/farm/tree/main/js-plugins/sass)**：Support compiling `sass/scss` files.

#### Community Plugins

- **[`@vitejs/plugin-vue`](https://github.com/vitejs/vite-plugin-vue/blob/main/packages/plugin-vue/README.md)**
- **[`@vitejs/plugin-vue-jsx`](https://github.com/vitejs/vite-plugin-vue/tree/main/packages/plugin-vue-jsx)**
- **[`vite-plugin-solid`](https://www.npmjs.com/package/vite-plugin-solid)**
- **[`vite-plugin-mock`](https://www.npmjs.com/package/vite-plugin-solid)**
- **[`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import)**
- **[`unplugin-vue2-script-setup`](https://github.com/antfu/unplugin-vue2-script-setup)**
- **[`unplugin-icons`](https://github.com/antfu/unplugin-icons)**
- **[`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components)**
- **[`farm-js-plugin-pwa`](https://github.com/Weeken/farm-js-plugin-pwa)**：PWA integrations for farm.

## Examples

Farm support compiling React, Vue, SolidJS, Sass, Less, and Css Modules officially out of the box. See our examples:

### React

#### Official Examples

- [`React-Basic`](https://github.com/farm-fe/farm/tree/main/examples/react)
- [`React-Ant-Design`](https://github.com/farm-fe/farm/tree/main/examples/react-antd)
- [`React-Sass-CssModules`](https://github.com/farm-fe/farm/tree/main/examples/css-modules)
- [`React-Multi-Page-Application`](https://github.com/farm-fe/farm/tree/main/examples/multi-page-app)
- [`React-SSR`](https://github.com/farm-fe/farm/tree/main/examples/react-ssr)
- [`React-TailwindCSS`](https://github.com/farm-fe/farm/tree/main/examples/tailwind)

#### Community Examples

- [`Farm-react-admin`](https://github.com/jstors/farm-react-admin): 🧚Out-of-the-box Farm react template projects,Integrated router, global state library, and arco component library.

### Vue

#### Official Examples

- [`Vue-Basic`](https://github.com/farm-fe/farm/tree/main/examples/vue)
- [`Vue-Jsx`](https://github.com/farm-fe/farm/tree/main/examples/vue-jsx)
- [`Vue-Antdv`](https://github.com/farm-fe/farm/tree/main/examples/vue-antdv)
- [`Plugin-Vue`](https://github.com/farm-fe/farm/tree/main/examples/vite-adapter-vue)
- [`Plugin-Solid`](https://github.com/farm-fe/farm/tree/main/examples/solid)

#### Community Examples

- [`farm-soybean-admin`](https://github.com/farm-fe/farm-soybean-admin): Migrate project from Vite to Farm

## Ecosystem

> Farm is already compatible with part of the vite ecosystem, and we are also improving the compatibility of the entire vite plugin.

- [Farm Ecosystem](https://farm-fe.github.io/docs/plugins/community-plugins)
- [Awesome Vite](https://github.com/vitejs/awesome-vite/blob/master/README.md)
- [Unplugin Ecosystem](https://unplugin.unjs.io/showcase/)
- [Swc Plugins](https://swc.rs/docs/plugin/selecting-swc-core)

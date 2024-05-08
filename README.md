<div align="center">
  <p align="center">
    <a href="https://farm-fe.github.io/" target="blank"><img src="https://raw.githubusercontent.com/farm-fe/farm/main/assets/logo.png" width="600" alt="Farm Logo" /></a>
  </p>
<h1>Awesome Farm</h1>
<p>A curated list of awesome things related to Farm</p>

<a href="#resources">Resources</a>
&nbsp;&nbsp;&nbsp;
<a href="CONTRIBUTING.md">Contribution guide</a>
&nbsp;&nbsp;&nbsp;
<a href="https://farm-fe.github.io/">Official documentation</a>

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


## Ecosystem

> Farm is already compatible with part of the vite ecosystem, and we are also improving the compatibility of the entire vite plugin.

- [Farm Ecosystem](https://farm-fe.github.io/docs/plugins/community-plugins)
- [Awesome Vite](https://github.com/vitejs/awesome-vite/blob/master/README.md)

## Plugins

### JsPlugins

- [vite plugins](https://github.com/vitejs/awesome-vite?tab=readme-ov-file#plugins)

* **[`@farmfe/js-plugin-postcss`](https://github.com/farm-fe/farm/tree/main/js-plugins/postcss)**：Support `postcss` in your project.
* **[`@farmfe/js-plugin-less`](https://github.com/farm-fe/farm/tree/main/js-plugins/less)**：Support compiling `less` files.
* **[`@farmfe/js-plugin-svgr`](https://github.com/farm-fe/farm/tree/main/js-plugins/svgr)**：Support compiling `svg` files.
* **[`@farmfe/js-plugin-dts`](https://github.com/farm-fe/farm/tree/main/js-plugins/dts)**：Support compiling `*.d.ts` files.
* **[`@farmfe/js-plugin-sass`](https://github.com/farm-fe/farm/tree/main/js-plugins/sass)**：Support compiling `sass/scss` files.

### RustPlugins

> Other ecology supported
- [swc plugins](https://swc.rs/docs/plugin/selecting-swc-core)

> Farm ecology

* **[`@farmfe/plugin-react`](https://github.com/farm-fe/farm/tree/main/rust-plugins/react)**：Support React `jsx` and `react-refresh`.
* **[`@farmfe/plugin-sass`](https://github.com/farm-fe/farm/tree/main/rust-plugins/sass)**：Support compiling `sass/scss` files.

> Farm Plugins

* **[`farm-plugin-remove-console`](https://github.com/jstors/farm-plugin-remove-console)**: ✂️ farm's plugin of remove console
* **[`farm-plugin-html-template`](https://github.com/jstors/farm-plugin-html-template)**: used to dynamically replace variables injected into HTML.
* **[`farm-plugin-replace-dirname`](https://github.com/jstors/farm-plugin-replace-dirname)**: replacement `__dirname`, `__filename` in node.


### Examples

Farm support compiling React, Vue, SolidJS, Sass, Less, and Css Modules officially out of the box. See our examples:

<table>
  <thead>
    <th>React Examples</th>
    <th>Vue Examples</th>
    <th>Vite Plugin Examples</th>
  </thead>
  <tbody>
    <td>
      <ul>
        <ul>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/react">React-Basic</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/react-antd">React-Ant-Design</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/css-modules">React-Sass-CssModules</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/multi-page-app">React-Multi-Page-Application</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/react-ssr">React-SSR</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/tailwind">React-TailwindCSS</a></li>
      </ul>
    </td>
    <td>
      <ul>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/vue">Vue-Basic</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/vue-jsx">Vue-Jsx</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/vue-antdv">Vue-Antdv</a></li>
</ul>
    </td>
    <td>
    <ul>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/vite-adapter-vue">Plugin-Vue</a></li>
<li><a href="https://github.com/farm-fe/farm/tree/main/examples/solid">Plugin-Solid</a></li>
<li><a href="https://github.com/farm-fe/farm-soybean-admin">farm-soybean-admin</a>：A real admin project migrated from Vite to Farm</li>
</ul>
    </td>
  </tbody>
</table>

### Farm Plugins

See [Using Plugins](https://farm-fe.github.io/docs/using-plugins) for how to use plugins in Farm.

### Rust Plugins

- **[`@farmfe/plugin-react`](https://farm-fe.github.io/docs/plugins/official-plugins/react)**
- **[`@farmfe/plugin-sass`](https://farm-fe.github.io/docs/plugins/official-plugins/sass)**

### Js Plugins

- **[`@farmfe/js-plugin-postcss`](https://farm-fe.github.io/docs/plugins/official-plugins/js-postcss)**
- **[`@farmfe/js-plugin-less`](https://farm-fe.github.io/docs/plugins/official-plugins/js-less)**
- **[`@farmfe/js-plugin-svgr`](https://farm-fe.github.io/docs/plugins/official-plugins/js-svgr)**
- **[`@farmfe/js-plugin-dts`](https://farm-fe.github.io/docs/plugins/official-plugins/js-dts)**
- **[`@farmfe/js-plugin-sass`](https://farm-fe.github.io/docs/plugins/official-plugins/js-sass)**

### Community Plugins

Plugins of Vite/Rollup/Unplugin can be directly used in Farm.

- **[`@vitejs/plugin-vue`](https://github.com/vitejs/vite-plugin-vue/blob/main/packages/plugin-vue/README.md)**
- **[`@vitejs/plugin-vue-jsx`](https://github.com/vitejs/vite-plugin-vue/tree/main/packages/plugin-vue-jsx)**
- **[`vite-plugin-solid`](https://www.npmjs.com/package/vite-plugin-solid)**
- **[`vite-plugin-mock`](https://www.npmjs.com/package/vite-plugin-solid)**
- **[unplugin-auto-import](https://github.com/antfu/unplugin-auto-import)**
- **[unplugin-vue2-script-setup](https://github.com/antfu/unplugin-vue2-script-setup)**
- **[unplugin-icons](https://github.com/antfu/unplugin-icons)**
- **[unplugin-vue-components](https://github.com/antfu/unplugin-vue-components)**
- ...

See [Community Plugins](https://farm-fe.github.io/docs/plugins/community-plugins) for more available plugins.

## Then start the project:

```bash
cd farm-project && npm start
```

See our 1 minute quick start video:

https://github.com/farm-fe/farm/assets/8372439/51e8834b-584a-4d9f-ae6f-516da70d3173

Refer to the [Documentation](https://farm-fe.github.io) to learn more about Farm.

- **[Farm Guide](https://farm-fe.github.io/docs/quick-start)**
- **[Farm Config](https://farm-fe.github.io/docs/config/farm-config)**
- **[Farm Plugins](https://farm-fe.github.io/docs/plugins/overview)**


### All Benchmark

![performance](./assets/2023-12-5.benchmark.jpg)

> Test Repository: https://github.com/farm-fe/performance-compare
>
> Test Machine (Linux Mint 21.1 Cinnamon, 11th Gen Intel© Core™ i5-11400 @ 2.60GHz × 6, 15.5 GiB)

<br />

### Hot (Startup and Build) Benchmark

> [!NOTE]
> Since Farm v0.14, Farm has implemented persistent cache. The following compares Farm's use of persistent cache in hot starts and production builds with other tools.

![performance](<./assets/2023-12-5.benchmark(hot).jpg>)

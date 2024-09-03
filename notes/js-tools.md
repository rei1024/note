# JavaScript Tooling

```mermaid
flowchart BT
  v8 --> node[Node.js]
  v8 --> chromium[Chromium]
  v8 --> deno[Deno]
  dprint --> deno
  swc[SWC] --> dprint
  swc --> deno
  swc --> rspack[Rspack]
  swc --> rollup[Rollup]
  swc --> turbopack[Turbopack]
  swc --> parcel[Parcel]
  lightningcss --> parcel
  rollup --> vite
  biome[Biome]
  esbuild
  jsc[JavaScriptCore] --> bun[Bun]
  oxc[Oxc] --> rolldown[Rolldown]
  acorn[Acorn] --> webpack
```

- [SWC](https://swc.rs/)
  - JavaScript parser
- [Rollup](https://rollupjs.org/)
  - JavaScript bundler
- [Rolldown](https://rolldown.rs/)
  - JavaScript bundler
- [Oxc](https://oxc.rs/)
  - JavaScript parser
- [dprint](https://dprint.dev/)
  - JavaScript formatter
- [Deno](https://deno.com/)
  - JavaScript runtime
- [Biome](https://biomejs.dev/)
  - JavaScript formatter
- [V8](https://v8.dev/)
  - JavaScript engine
- [Chromium](https://www.chromium.org/Home/)
  - Browser
- [esbuild](https://esbuild.github.io/)
  - JavaScript bundler
- [JavaScriptCore](https://docs.webkit.org/Deep%20Dive/JSC/JavaScriptCore.html)
  - JavaScript engine
- [Bun](https://bun.sh/)
  - JavaScript runtime
- [Rspack](https://rspack.dev/)
  - JavaScript bundler
- [Parcel](https://parceljs.org/)
  - JavaScript bundler
- [Lightning CSS](https://lightningcss.dev/)
  - CSS parser
- [Turbopack](https://turbo.build/pack/docs)
  - JavaScript bundler
- [SpiderMonkey](https://spidermonkey.dev/)
  - JavaScript engine
- [webpack](https://webpack.js.org/)
  - JavaScript bundler
- [acorn](https://github.com/acornjs/acorn)
  - JavaScript parser
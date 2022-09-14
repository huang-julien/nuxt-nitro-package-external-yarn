# nitro nuxt issue build -- npm

this repo HELPS TO reproduce an issue on nitro.

Several versions of estree-walker is present in this repo due to :`

````
=> Found "estree-walker@2.0.2"
info Has been hoisted to "estree-walker"
info Reasons this module exists
   - Hoisted from "nuxt#nitropack#@vercel#nft#estree-walker"
   - Hoisted from "nuxt#nitropack#@rollup#plugin-commonjs#estree-walker"
   - Hoisted from "nuxt#nitropack#@rollup#plugin-inject#estree-walker"
   - Hoisted from "nuxt#nitropack#@rollup#pluginutils#estree-walker"
   - Hoisted from "nuxt#unimport#@rollup#pluginutils#estree-walker"
   - Hoisted from "nuxt#vue#@vue#compiler-sfc#estree-walker"
   - Hoisted from "nuxt#vue#@vue#compiler-dom#@vue#compiler-core#estree-walker"
   - Hoisted from "nuxt#vue#@vue#compiler-sfc#@vue#reactivity-transform#estree-walker"
info Disk size without dependencies: "88KB"
info Disk size with unique dependencies: "88KB"
info Disk size with transitive dependencies: "88KB"
info Number of shared dependencies: 0
=> Found "@rollup/pluginutils#estree-walker@1.0.1"
info This module exists because "@rollup#pluginutils" depends on it.
info Disk size without dependencies: "32KB"
info Disk size with unique dependencies: "32KB"
info Disk size with transitive dependencies: "32KB"
info Number of shared dependencies: 0
=> Found "@nuxt/vite-builder#estree-walker@3.0.1"
info This module exists because "nuxt#@nuxt#vite-builder" depends on it.
info Disk size without dependencies: "44KB"
info Disk size with unique dependencies: "44KB"
info Disk size with transitive dependencies: "44KB"
info Number of shared dependencies: 0
=> Found "unctx#estree-walker@3.0.1"
info This module exists because "nuxt#unctx" depends on it.
info Disk size without dependencies: "44KB"
info Disk size with unique dependencies: "44KB"
info Disk size with transitive dependencies: "44KB"
info Number of shared dependencies: 0
=> Found "rollup-pluginutils#estree-walker@0.6.1"
info This module exists because "nuxt#nitropack#@vercel#nft#rollup-pluginutils" depends on it.
info Disk size without dependencies: "28KB"
info Disk size with unique dependencies: "28KB"
info Disk size with transitive dependencies: "28KB"
info Number of shared dependencies: 0
````


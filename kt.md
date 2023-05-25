# UI libraries

We have mithil.js even faster than every framwork
POC: https://developit.github.io/preact-perf/

# Angular has analog framework like nextjs for SSR, SSG approaches

https://analogjs.org/

Vue has NuxtJs

React has NextJs

Angular has Analog

Solid has SolidStart

# Nx is faster than Turborepo in case of monorepo builds

# We have next generation build tools

SWC (used by nextjs), Esbuild (Fast but for react only now, vendor split is an easy solution), snowpack, vite (widely used)

# React is heavy. React-dom is heavy. We have below alternates

Solid js, Preact, Mithil js,

# Some old build tools

1. Webpack (is very advance and solve many real time problems)
2. rollup (getting advance day by day)
3. parcel (zero config bundler. Only used in playgrounds)

# UI performance benchmarks. All ui frameworks

https://krausest.github.io/js-framework-benchmark/current.html

# Static site generators

1. Hugo
2. gatsby
3. nextjs
4. Remix

# Real time page update, we have below options

1. https://driftdb.com/ (React)
2. Webrtc

# Game engine inspired by react

https://replay.js.org/tutorial/5

# Comparison of react, vue and angular

https://krausest.github.io/js-framework-benchmark/current.html

https://www.browserstack.com/guide/angular-vs-react-vs-vue#:~:text=A%20simple%20difference%20between%20these,Vue%20with%2018.97%25%20of%20developers.

# Edge Cdn The future where server keeps on CDN and secure. We dont need extra aws kind of servers.

https://edge.network/en/content-delivery/documentation/#managing-your-deployment

https://www.netlify.com/with/nextjs/

# we have many "code-mods" which helps to transform the code to correct syntax, fix the issues

fix code: https://github.com/facebook/jscodeshift

syntax tree: https://astexplorer.net/  

https://www.carlrippon.com/codemods-for-react-typescript/

# A guideance on WASM
https://github.com/mbasso/awesome-wasm

# React nice blogs
https://www.benmvp.com/blog/

https://overreacted.io/

https://syntax.fm/

https://surma.dev/things/react-redux-comlink/

# More type (Typescript) safe using
https://github.com/total-typescript/ts-reset

# Code splitting React Js

Vendor split webpack

Lazy and dynamic imports for React

Lodable library for server side: https://www.npmjs.com/package/react-loadable

Route based splitting

Prefect, preload based splitting

# A plugins which helps on mdx and also many other tools supported
https://github.com/unifiedjs/unified

https://react-docgen.dev/docs/getting-started/nodejs

# Code Splitting (lazy, dynamic import) is on client side. To achieve it on server side 
If you're doing SSR you'll want to consider using Loadable (https://github.com/gregberge/loadable-components) instead of React.lazy, as suggested by the official React.lazy

# Webpack prefetch, preload explained
https://github.com/evanw/esbuild/issues/1240#issue-874351016

# Nextgen testing framework
1. Unit testing: https://vitest.dev/guide/mocking.html
2. E2E testing: https://playwright.dev/

# NextJs examples
https://reactjsexample.com/an-e-commerce-project-developed-by-nextjs-and-typescript/

# Alternate to redux in react (state management tool)
1. React-query : https://tanstack.com/query/latest/docs/react/overview
2. Redux-webworker: https://surma.dev/things/react-redux-comlink/

# Webworker for parallel proccessing and multithreading concept
use https://github.com/GoogleChromeLabs/comlink
https://www.youtube.com/watch?v=7Rrv9qFMWNM

# WebGpu is faster than webGL
https://www.youtube.com/watch?v=nUYe3a1mp6c

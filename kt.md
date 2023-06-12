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

# Redux-toolkit and Zustand
1. Both are redux tools but zustand has less boilerplate code
2. Redux-toolkit and Zustand perform same in case of array and objects (non premitive types). 
3. It re-renders in case of object and array comparisons
4. We need to use shallowEqual in both cases for non-primitive types

# What a build tool has
1. Code splitting
2. Vendors split and further split in vendors
3. Lazy load
4. Prefetch and preload mechanism
5. Webworker support
6. Lang support
7. source map generator
8. Vendor cash
9. Incremental builds support- (Nx.dev supports it)
10. Multiple entry points/ outputs support
11. Plugins support, Good doc, Active community, Fast compilation
13. Split dynamic imports

# Load, Performance testing UI
https://github.com/hatoo/oha

used in: https://www.youtube.com/watch?v=3Q2q2gs0nAI

# Core web vital reporting
https://lookerstudio.google.com/u/0/reporting/55bc8fad-44c2-4280-aa0b-5f3f0cd3d2be/page/M6ZPC

Google tool to verify web vitals: https://github.com/GoogleChrome/lighthouse-ci

Lighthouse information: https://www.npmjs.com/package/lighthouse

# Interaction to next paint
https://web.dev/inp/

https://web.dev/top-cwv-2023/

# Web book
https://almanac.httparchive.org

# Library to ease animations
https://greensock.com/gsap/

# A tool to create nextJs with latest stack
https://create.t3.gg/en/usage/next-js

# dummy API endpoints
https://rapidapi.com/apininjas/api/cars-by-api-ninjas

https://jsonplaceholder.typicode.com/guide/

# Accessibility plugin and verification
https://larsmagnus.co/blog/how-to-test-for-accessibility-with-axe-core-in-next-js-and-react

https://web.dev/accessibility-auditing-react/

https://github.com/dequelabs/axe-core-npm/tree/develop/packages/react

# Debuggin tool for FE dev
https://jam.dev/  => Details https://www.youtube.com/watch?v=JKbDbF5z8qU


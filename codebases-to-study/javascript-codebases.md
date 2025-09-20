# JavaScript Codebases to Study

Learn from industry-leading JavaScript projects. These codebases represent best practices in modern JavaScript development.

## ⚛️ Frontend Frameworks & Libraries

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**facebook/react**](https://github.com/facebook/react) | 217k+ | UI library | Virtual DOM, hooks, reconciliation, fiber architecture | `packages/react`, `packages/react-dom`, `packages/scheduler` |
| [**vuejs/vue**](https://github.com/vuejs/vue) | 206k+ | Progressive framework | Reactivity, compiler, composition API, virtual DOM | `src/core`, `src/compiler`, `src/platforms` |
| [**angular/angular**](https://github.com/angular/angular) | 93k+ | Full framework | Dependency injection, RxJS, change detection, Ivy compiler | `packages/core`, `packages/compiler`, `packages/router` |
| [**sveltejs/svelte**](https://github.com/sveltejs/svelte) | 73k+ | Compiler framework | Compiler design, runtime optimization, reactive declarations | `src/compiler`, `src/runtime`, `src/internal` |

## 🚀 Backend & Runtimes

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**nodejs/node**](https://github.com/nodejs/node) | 101k+ | Runtime environment | Event loop, C++ bindings, libuv, module system | `lib/`, `src/`, `deps/` |
| [**expressjs/express**](https://github.com/expressjs/express) | 63k+ | Web framework | Middleware, routing, request/response handling, error handling | `lib/application.js`, `lib/router/`, `lib/express.js` |
| [**nestjs/nest**](https://github.com/nestjs/nest) | 61k+ | Node.js framework | Architecture, decorators, modules, dependency injection | `packages/core`, `packages/common`, `packages/microservices` |
| [**socketio/socket.io**](https://github.com/socketio/socket.io) | 59k+ | Real-time engine | WebSockets, fallback protocols, rooms, namespaces | `lib/`, `client/`, `examples/` |

## 🛠️ Build Tools & Utilities

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**webpack/webpack**](https://github.com/webpack/webpack) | 64k+ | Module bundler | Plugin system, dependency graph, loaders, chunk optimization | `lib/`, `schemas/`, `bin/` |
| [**babel/babel**](https://github.com/babel/babel) | 43k+ | JavaScript compiler | AST manipulation, plugins, presets, code generation | `packages/babel-parser`, `packages/babel-core`, `packages/babel-generator` |
| [**rollup/rollup**](https://github.com/rollup/rollup) | 24k+ | Module bundler | Tree shaking, ES modules, plugin API, code splitting | `src/`, `cli/`, `utils/` |
| [**parcel-bundler/parcel**](https://github.com/parcel-bundler/parcel) | 42k+ | Zero-config bundler | Asset processing, caching, multicore compilation, HMR | `packages/`, `src/`, `website/` |

## 🎨 UI Components & Libraries

| Repository | Stars | Focus | What to Learn | Key Files to Study |
| :--- | :--- | :--- | :--- | :--- |
| [**mui/material-ui**](https://github.com/mui/material-ui) | 90k+ | React UI library | Component design, theming, accessibility, customization | `packages/mui-material/src/`, `packages/mui-system/` |
| [**chartjs/Chart.js**](https://github.com/chartjs/Chart.js) | 62k+ | Charting library | Canvas rendering, animation, plugins, responsive design | `src/`, `types/`, `test/` |
| [**moment/moment**](https://github.com/moment/moment) | 47k+ | Date library | Date manipulation, localization, formatting, parsing | `src/`, `locale/`, `lib/` |
| [**lodash/lodash**](https://github.com/lodash/lodash) | 58k+ | Utility library | Functional programming, performance optimization, modular design | `lodash.js`, `*.js` in root |

## 📚 Learning Strategy

1.  **Start with the documentation** - Understand the project's purpose and architecture
2.  **Look at the examples/** directory - See practical usage patterns
3.  **Study the test files** - Tests show expected behavior and edge cases
4.  **Examine the package.json** - Understand dependencies and build scripts
5.  **Read the contributing guidelines** - Learn about code style and PR process
6.  **Check the release notes** - Understand how the project evolves

## 🔧 Practical Exercises

1.  **Create a simple plugin** for webpack or babel
2.  **Build a custom middleware** for express
3.  **Create a React component** using the same patterns as material-ui
4.  **Modify a small feature** in a utility library like lodash
5.  **Read and understand** the event loop implementation in Node.js

## 🌐 Additional Resources

- [**How to Read JavaScript Source Code**](https://www.freecodecamp.org/news/how-to-read-javascript-source-code/)
- [**JavaScript Engine Fundamentals**](https://mathiasbynens.be/notes/shapes-ics)
- [**V8 JavaScript Engine**](https://v8.dev/)

---

**Tip:** Start with smaller, well-documented projects like `express` or `lodash` before tackling larger frameworks like `react` or `angular`.

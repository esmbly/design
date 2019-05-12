# User stories

## Prototype stories [Current phase]
- [x] **US-Proto 1**: As a Flow user, I want to transform a [simple JavaScript program](examples/us-proto-1) with Flow annotations to TypeScript using the Flow transformer.
- [x] **US-Proto 2**: As a package maintainer, I want to take a [simple JavaScript program](examples/us-proto-2) with JSDoc comments and transform it to TypeScript using the JSDoc transformer.
- [x] **US-Proto 3**: As a developer interested in migrating to TypeScript, I want to take a [simple JavaScript program](examples/us-proto-3) that is covered by a test suite, and transform it to TypeScript using the V8 transformer.

## MVP stories
- [ ] **US-MVP 1**: As a maintainer of a small library, I want to automatically generate a TypeScript definition file based on type information collected during test runs using the V8 transformer. (Example TBD)
- [x] **US-MVP 2**: As a company interested in migrating parts of a project to TypeScript, we want to generate TypeScript source code, based on type information collected during test runs using the V8 transformer. [Radians example](https://github.com/esmbly/esmbly/tree/master/examples/radians), [Repeat example](https://github.com/esmbly/esmbly/tree/master/examples/repeat)
- [x] **US-MVP 3**: As a maintainer of a small package, I want to migrate my entire code base from using Flow typed JavaScript to TypeScript. [Yarn/lockfile example](https://github.com/esmbly/esmbly/tree/master/examples/lockfile)
- [ ] **US-MVP 4**: As a Flow user, I want to automatically generate TypeScript definition files instead of manually maintaining multiple type definition files. (Example TBD)
- [x] **US-MVP 5**: As a maintainer of a web application written with Flow annotations, I want to compile a performance heavy part of my application to a WebAssembly binary and provide asm.js as a fallback. [Pad example](https://github.com/esmbly/esmbly/tree/master/examples/pad)
- [x] **US-MVP 6**: As a JavaScript developer wanting to experiment with WebAssembly, I want to try different ways of turning simple JavaScript programs into WebAssembly binaries.
- [x] **US-MVP 7**: As a JavaScript developer wanting to experiment with WebAssembly, I want to be able to output WebAssembly text format for learning more about how WebAssembly works.
- [x] **US-MVP 8**: As maintainer of a small legacy package, I want to migrate my code base to TypeScript based on JSDoc comments using the JSDoc transformer. [ms example](https://github.com/esmbly/esmbly/tree/master/examples/ms), [Lodash example](https://github.com/esmbly/esmbly/tree/master/examples/lodash)
- [ ] **US-MVP 9**: As a maintainer of a small legacy package, I want to automatically generate a TypeScript definition file based on JSDoc comments. (Example TBD)
- [x] **US-MVP 10**: As a developer with needs that are not covered by any current transformer, I want to write my own custom transformer by following a guide. [Custom transformer example](https://github.com/esmbly/esmbly/tree/master/examples/custom-transformer)

## Post MVP stories
- TBD

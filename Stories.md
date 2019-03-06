# User stories

## Prototype stories [Current phase]
- **US-Proto 1**: As a Flow user, I want to transform a [simple JavaScript program](examples/us-proto-1) with Flow annotations to TypeScript using the Flow transformer.
- **US-Proto 2**: As a package maintainer, I want to take a [simple JavaScript program](examples/us-proto-2) with JSDoc comments and transform it to TypeScript using the JSDoc transformer.
- **US-Proto 3**: As a developer interested in migrating to TypeScript, I want to take a [simple JavaScript program](examples/us-proto-3) that is covered by a test suite, and transform it to TypeScript using the V8 transformer.

## MVP stories
- **US-MVP 1**: As a library maintainer, I want to automatically generate a TypeScript definition file for my library based on type information collected during test runs using the V8 transformer.
- **US-MVP 2**: As a company interested in migrating a project to TypeScript, we want to generate TypeScript source code, based on type information collected during test runs using the V8 transformer.
- **US-MVP 3**: As a package maintainer, I want to migrate my entire code base from using flow typed JavaScript to TypeScript.
- **US-MVP 4**: As a Flow user, I want to automatically generate TypeScript definition files instead of manually maintaining multiple type definition files.
- **US-MVP 5**: As a maintainer of a web application written with Flow annotations, I want to compile a performance heavy part of my application to a WebAssembly binary and provide asm.js as a fallback.
- **US-MVP 6**: As a JavaScript developer wanting to experiment with WebAssembly, I want to try different ways of turning simple JavaScript programs into WebAssembly binaries.
- **US-MVP 7**: As a JavaScript developer wanting to experiment with WebAssembly, I want to be able to output WebAssembly text format for learning more about how WebAssembly works.
- **US-MVP 8**: As a package maintainer, I want to migrate my code base to TypeScript based on JSDoc comments using the JSDoc transformer.
- **US-MVP 9**: As a library maintainer, I want to automatically generate a TypeScript definition file based on JSDoc comments
- **US-MVP 10**: As the creator of a new type system, I want to write my own custom transformer.
- TDB

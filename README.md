# NodeJS, Express && TypeScript starter

**Developers are lazy.**

A quick google shows guides for installing TypeScript with NodeJS. Something so simple, yet no starter pack is available. I've done that for you.

Included in this barebones starter

- express
- dotenv
- nodemon
- typescript
- @types/node && @types/express

Typescript options

- outDir: ./dist
- target: es2016
- module: commonjs
- strict: true
- esModuleInterop: true
- skipLibCheck: true
- forceConsistentCasingInFileNames: true

Get Started
`npm install`
Run server
`npm run dev` to trigger concurrently command (see below).

The command `"dev":  "concurrently \"npx tsc --watch\" \"nodemon -q dist/index.js\""` watches for changes while compiling it into javascript

Quick, easy and to the point - the true express experience.

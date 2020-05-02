# node-typescript-cheatsheet

Cheatsheets for experienced Node.js developers getting started with TypeScript

## Helpful tools

- https://ts-engine.dev/

## Tip 1

`tsconfig.json`:

```json
{
  "compilerOptions": {
    "target": "es2015",
    "module: "commonjs"
  }
}
```

## Tip 2

shipping typescript sourcemaps from a node server: http://npm.im/source-map-support

## Tip 3

Instead of

```bash
nodemon --exec ts-node src/index.ts
```

do:

```bash
tsc --watch
nodemon dist/src/index.js
```

https://twitter.com/benawad/status/1211700652549779456

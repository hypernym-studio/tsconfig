<h1 align="center">@hypernym/tsconfig</h1>

<p align="center">Hypernym's config for TypeScript.</p>

<p align="center">
  <a href="https://github.com/hypernym-studio/tsconfig">Repository</a>
  <span>✦</span>
  <a href="https://www.npmjs.com/package/@hypernym/tsconfig">Package</a>
  <span>✦</span>
  <a href="https://github.com/hypernym-studio/tsconfig/releases">Releases</a>
  <span>✦</span>
  <a href="https://github.com/hypernym-studio/tsconfig/discussions">Discussions</a>
</p>

<br>

<pre align="center">pnpm add -D @hypernym/tsconfig</pre>

<br>

## Usage

```js
// tsconfig.json

{
  "extends": "@hypernym/tsconfig"
}
```

## Custom Setup

```ts
// tsconfig.json

{
  "extends": "@hypernym/tsconfig",
  "compilerOptions": {
    "baseUrl": "./",
    "paths": {
      "@": ["./src"],
      "@/*": ["./src/*"]
    }
  }
}
```

## Community

Feel free to ask questions or share new ideas.

Use the official [discussions](https://github.com/hypernym-studio/tsconfig/discussions) to get involved.

## License

Developed in 🇭🇷 Croatia, © Hypernym Studio.

Released under the [MIT](LICENSE.txt) license.

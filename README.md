# JingtumMask Browser Extension

本项目为井通公链SWTC的钱包插件，参考了以太坊的metamask（[https://github.com/MetaMask/metamask-extension]()）

## Building locally

- Install [Node.js](https://nodejs.org) version 8 and the latest available npm@6
    - If you are using [nvm](https://github.com/creationix/nvm#installation) (recommended) running `nvm use` will automatically choose the right node version for you.
    - If you install Node.js manually, ensure you're using npm@6
        - Install npm@6 using `npm install -g npm@6`
- Install dependencies: `npm install`
    - If you have issues with node-sass compilation, try `npm rebuild node-sass`
- Install gulp globally with `npm install -g gulp-cli`.
- Build the project to the `./dist/` folder with `gulp build`.
- Optionally, to rebuild on file changes, run `gulp dev`.
- To package .zip files for distribution, run `gulp zip`, or run the full build & zip with `gulp dist`.

 Uncompressed builds can be found in `/dist`, compressed builds can be found in `/builds` once they're built.


## Build for Publishing

```bash
npm run dist
```


# Obsidian Sample Plugin

![Obsidian plugin downloads badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fscambier.xyz%2Fobsidian-endpoints%2Fsample.json)

This is a sample plugin for Obsidian (https://obsidian.md).

## Usage

1. Open the `Command palette` (https://help.obsidian.md/Plugins/Command+palette).
2. Search for the `Sample` command.
3. Press <kbd>Enter</kbd>.

## Contributing

### Setup

1. Go to [settings/actions](../../settings/actions).
2. Enable `Read and write permissions` under `Workflow permissions`.
3. Click `Save`.

### Installation

1. Install `Node.js` by following the instructions from
   https://docs.npmjs.com/downloading-and-installing-node-js-and-npm.
2. Install the `Node.js` dependencies by running
   ```sh
   npm install
   ```

### Usage

```sh
npm run dev
```

### Releasing

1. Run `npm version <major/minor/patch>`.
2. Optionally add release notes to the created GitHub draft release.
3. Publish the GitHub draft release.

## License

[MIT](LICENSE)

# Moralis Mutants NFT Collection | Generative Art Engine

The survivors of Rekt City welcome you.

## About

Aim: Saving time and resources for artists and developers, allowing them to generate and host NFT art, across-chains (ETH/BSC/MATIC/…) in one place (utilising Moralis).

This initial tutorial video is a great introduction: [Link to Moralis YouTube Video](https://youtu.be/TBC).

## Quick Launch 🚀

Via terminal, navigate to root directory:

```sh
npm install

```

Go to [Moralis.io](https://moralis.io/) to create your server instance. Then in root `index.js` file, point to your Moralis server:

```sh
const appId = "xxx";
const serverUrl = "https://xxx.usemoralis.com:2053/server";
const masterKey = "xxx";

```

Create your layered artwork and split into folders in `./input` and configure your collection to match your layer structure and preferences accordingly by editing `./input/config.js`:

Finally, via terminal in the project directory run:

```sh
node index.js

```

This injects the mutagen that will bring your Moralis mutants ALIVE!

## Dependencies 🏗

`moralis`: [ℹ️ Docs](https://docs.moralis.io/)

`canvas`: [ℹ️ Docs](https://www.npmjs.com/package/canvas)

`react-final-form`: [ℹ️ Docs](https://final-form.org/docs/final-form/getting-started)

## Todos ✅

- [ ] NFT contract allowing tokens to be minted and tranferred for Opensea.
- [ ] Users can mint NFT collection via custom dapp frontend.
- [ ] Compatibility across-chains (SOL/MATIC).
- [ ] Much more TBA.

## Community BUIDLing 👨‍🔧👩‍🔧

- [Moralis Forum](https://forum.moralis.io/)
- [Moralis Discord](https://discord.com/channels/819584798443569182)
- [Moralis GitHub](https://github.com/MoralisWeb3)
- [Moralis YouTube](https://www.youtube.com/channel/UCgWS9Q3P5AxCWyQLT2kQhBw)

# Aleo Web Wallet Snap

Access Aleo network from your browser using MetaMask

![Project logo](logo.png)

## How it works

![Snap diagram](snap-diagram.png)

## Demo

[Aleo Web Wallet Snap](https://aleo-snap-ethdenver-2022.netlify.app/)

### Demo Instructions

In order to run this demo, we need to install a modified snap version:
*   Pull down this [branch](https://github.com/MetaMask/metamask-extension/tree/eth-denver-2022)
*   Build the extension locally: `yarn setup && yarn dist --build-type flask`
*   Load the unpacked extension (see "custom build" instructions) from [here](https://github.com/MetaMask/metamask-extension/tree/eth-denver-2022#other-docs)

### Local Installation Instructions (WIP)

First, navigate to `aleo/wasm` and run the following command to package the wasm library: 

`wasm-pack build --scope aleohq`

If you do not have `wasm-pack` installed, you can install it with npm. 
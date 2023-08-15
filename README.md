# Enigmatic Mango Dex <a href="https://enigmatic-dex-19xr.vercel.app/" target="_blank">Dive In</a>

Exchange with only one asset pair (Enigma / ETH)
Decentralized Exchange will take a fee of 1% on swaps
When user adds liquidity, they are given Enigma LP tokens (Liquidity Provider tokens)
LP tokens are given proportional to the Ether user is willing to add to the liquidity

## Tech Stack

~In this project I used Hardhat for an Ethereum development environment and framework. I go on to use React which is a javascript framework used to make websites and Next.js which is a React framework that also allows writing backend APIs code along with the frontend, so you don't need two separate frontend and backend services.

The smart contract itself was written in Solidity language utilizing ethers.js, which aims to be a complete and compact library for interacting with the Ethereum Blockchain and its ecosystem.

~Web3Modal library - Web3Modal is an easy to use library to help developers easily allow their users to connect to your dApps with all sorts of different wallets. By default, Web3Modal Library supports injected providers like (Metamask, Dapper, Gnosis Safe, Frame, Web3 Browsers, etc) and WalletConnect

### Overview/Notes
The project came together flawlessly as a Decentalized Exchange that allows users the abililty to add & rmove liquidity, allowing for swaps between token from a previous ICO project to ETH.

The amount of Ether tokens that are sent back to the user is based the following ratio - (Eth sent back to the user) / (current Eth reserve) = (amount of LP tokens that user wants to withdraw) / (total supply of LP tokens).

The amount of Enigma tokens that are sent back to the user is based on the following ratio - (Enigma sent back to the user) / (current Enigma token reserve) = (amount of LP tokens that user wants to withdraw) / (total supply of LP tokens).

<a href='https://enigmatic-dex-19xr.vercel.app/' target='_blank'><img src='https://i.postimg.cc/vmW9nFp7/enigma.png' border='0' alt='memory-Game'/></a>



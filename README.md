Cambrian's Uniswap V4 Demo
Description

This repo is Cambrian's Network Uniswap V4 Volatility Hook demo, where we build a dynamic fee AMM that uses volatility data from ETH/USDC V3 pool on Ethereum, which is provided by Cambrian Network, to adjust fee on-chain.

This repo contains:
* Smart Contract Repo: Contains related smart contract for the demo as well as a demonstration for on-chain query with Cambrian Network
* Front-end: Contains a web-app for dynamic AMM as well as a demonstration for off-chain query with Cambrian Network
* Cache System: Contains a cache system to store volatility/fee data for front-end through contstantly querying from Cambrian API Endpoint
* Volatility/Fee Jupiter Notebook Analysis: Contains a Jupiter Notebook on the relationship between volatility and corresponding fee and the calculation behind it

I built a Fat Contract in Rust that interacts with the National Weather Service and gets the current temperature for me. This could be used in the future to create a special decentralized oracle for something like a weather prediction market or futures exchange. The trustless nature of such an oracle comes from the contract itself being able to get real-world data from a trusted third-party source (the US government), without a human running a server that's sending numbers on-chain. 

I think this is a really neat application of the unique ability of Fat Contracts to interact with the real world/web services, and not just have smart contracts be pure functions on a single immutable store. 

Contract on testnet: https://polkadot.js.org/apps/#/explorer/query/0x1af26a74724ab83f183c0e7ba9124f5db22fd65f67343157fd92d67ce424bf8b

To run: go to frontend/, `yarn`, `yarn dev`, 
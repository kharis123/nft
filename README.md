// get NFTs for current user on Mainnet
Moralis.Web3.getNFTs();

// get testnet NFTs for user
Moralis.Web3.getNFTs({ chain: 'ropsten' });

// get polygon NFTs for address
const options = { chain: 'matic', address: '0x...' };
Moralis.Web3.getNFTs(options);

# Wrapped NFTs

The Wrapped NFT pattern involves wrapping an NFT (Non-Fungible Token) into another NFT or token. It's used for a variety of purposes including enabling new functionalities, improving interoperability, and enhancing privacy. Here are some uses.  

From OpenZeppelin's `ERC721Wrapper.sol` contract description: "Users can deposit and withdraw an "underlying token" and receive a "wrapped token" with a matching tokenId. This is useful in conjunction with other modules. For example, combining this wrapping mechanism with {ERC721Votes} will allow the wrapping of an existing "basic" ERC721 into a governance token."  

## Use Cases  

1. Fractional Ownership
Wrapped NFTs can represent a fraction of the ownership of the original NFT, making it easier to trade and own portions of expensive NFTs.

```solidity
# Wrapping an NFT into fractionalized tokens
fractionalTokens = fractionalize(originalNFT, totalShares)
```

Example:  
- [Tessera (Shut Down)](https://twitter.com/tessera)  

2. Collateralization  
Wrapped NFTs can be used as collateral for loans or in decentralized finance (DeFi) applications.  

```solidity
# Using wrapped NFT as collateral
loan = getLoan(wrappedNFT, loanAmount)
```

Example:  
- [NFTFi](https://nftfi.com/)  
- [BendDAO](https://www.benddao.xyz/en/)  

3. Privacy  
By wrapping an NFT, the ownership and transaction history can be obfuscated, providing privacy to the owners.  

```solidity
# Wrapping an NFT to obfuscate ownership
privateNFT = wrapForPrivacy(originalNFT)
```

4. Enhanced Functionality  
Wrapping can add extra functionalities to NFTs such as governance rights, staking, or additional metadata.  

```solidity
# Wrapping an NFT to add extra functionality
enhancedNFT = wrapWithFeatures(originalNFT, extraFeatures)
```

5. Interoperability  
- Wrapping can make an NFT compatible with different blockchain ecosystems or platforms.

```solidity
# Wrapping an Ethereum-based NFT to be used on a different blockchain
wrappedNFT = wrap(originalNFT, targetBlockchain)
```

### Additional Resources  
- [OpenZeppelin ERC721Wrapper](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/extensions/ERC721Wrapper.sol)  
- [Wrapped Pudgy Penguins Story](https://www.coindesk.com/business/2022/01/07/pudgy-penguins-nft-project-ousts-founders-as-mood-turns-icy/)  
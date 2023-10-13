# Wrapped NFTs

The Wrapped NFT pattern involves wrapping an NFT (Non-Fungible Token) into another NFT or token. It's used for a variety of purposes including enabling new functionalities, improving interoperability, and enhancing privacy. Here are some uses.  

_Wrapping a token is exchanging one set of standards for token interaction with another set of standards._  

From OpenZeppelin's `ERC721Wrapper.sol` contract description: "Users can deposit and withdraw an "underlying token" and receive a "wrapped token" with a matching tokenId. This is useful in conjunction with other modules. For example, combining this wrapping mechanism with {ERC721Votes} will allow the wrapping of an existing "basic" ERC721 into a governance token."  

## Use Cases  

1. **Fractional Ownership**: Wrapped NFTs can represent a fraction of the ownership of the original NFT, making it easier to trade and own portions of expensive NFTs.  

Example:  
- [Tessera (Shut Down)](https://twitter.com/tessera)  

2. **Collateralization**: Wrapped NFTs can be used as collateral for loans or in decentralized finance (DeFi) applications.  

Example:  
- [NFTFi](https://nftfi.com/)  
- [BendDAO](https://www.benddao.xyz/en/)  

3. **Privacy**: By wrapping an NFT, the ownership and transaction history can be obfuscated, providing privacy to the owners.  

4. **Enhanced Functionality**: Wrapping can add extra functionalities to NFTs such as governance rights, staking, or additional metadata.  

5. **Interoperability**: Wrapping can make an NFT compatible with different blockchain ecosystems or platforms.

### Additional Resources  
- [OpenZeppelin ERC721Wrapper](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/extensions/ERC721Wrapper.sol)  
- [Wrapped Pudgy Penguins Story](https://www.coindesk.com/business/2022/01/07/pudgy-penguins-nft-project-ousts-founders-as-mood-turns-icy/)  
- 👋 Hi, I’m @Moriarty2021m
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Moriarty2021m/Moriarty2021m is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/extensions/ERC721Enumerable.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract MyNFT is ERC721Enumerable, Ownable {
    using SafeMath for uint256;

    // Base URI for metadata
    string private _baseTokenURI;

    // Current token ID
    uint256 private _tokenIdCounter;

    // Mapping to store whether a particular NFT has been minted
    mapping(uint256 => bool) private _mintedTokens;











































    

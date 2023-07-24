![CryptoBaby](/cryptobaby.png)

## CryptoBaby: Collectible Characters on the Ethereum Blockchain

CryptoBaby are 404 unique collectible characters with proof of ownership stored on the Ethereum blockchain. No two are exactly alike, and each one of them can be officially owned by a single person as managed and verified by a contract running on the Ethereum blockchain. You can see which babys are still available along with some more general information over at https://cryptobaby.com

This repo contains the Ethereum contract used to manage the Babys, a verifiable image of all the babys.

### How to Use the CryptoBaby Contract

The easiest way is to use [MyEtherWallet](https://www.myetherwallet.com/#contracts) which has added CryptoBaby to their contract dropdown. If you prefer to use an Ethereum wallet on your computer, the main CryptoBaby contract can be found at address **0x992caafc971d17f2949ee89eea52cb321ba6a771**. Watch this contract in your Ethereum wallet using that address and [this ABI file](/cryptobaby/abi.json).

### Verifying the Babys are 100% Authentic and Legit CryptoBaby™


This is the official and genuine image of all of the CryptoBaby that have been created. To allow verification that the babys being managed by the CryptoBaby Ethereum contract are the same as what you see in the image, we have embedded a SHA256 hash of the each image file into the metadata contract can see in https://ipfs-eth.cryptobaby.app/metadata. full hash can see in https://ipfs-eth.cryptobaby.app/Hash.sol. Example: You can generate this hash for the babys image file via a command line similar to ```openssl sha -sha256 cryptobaby/nft/1.png``` and compare that to the embedded hash in the contract: ```96c9b2e8cf43a40ab948e48d153c2981ce66116bb33834901a3e9df872da9d0a```.
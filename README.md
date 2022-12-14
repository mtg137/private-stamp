# PrivateStamp (Alpha version)

### A private proof-of-existence DApp.

### Prove that you've had a file (of any type & size) at a certain time without compromising your privacy.

`Currently deployed on Rinkeby network`

## Technologies used:

_Solidity_, _Truffle_, _IPFS_, _Javascript_, _Web Crypto API_, _Vue_, _Vuetify_

## You need MetaMask extension installed to interact with the app

## Features:

### Secure:

- Your original file is never transmitted over the network, both encryption & decryption happen locally.

- Every encryption process generate a different file/hash even if the same file is encrypted with the same password, that's because a random salt is generated everytime.

### Decentralized:

- Relies on Ethereum blockchain to store/retrieve data

### Cheap:

`Currently, the app is deployed on test network, so using it is FREE anyway.`

- All expensive operations, such as encryption/decryption/hashing are done locally, only the string that represent the hash that is stored on ethereum.

## Development:

Requirements:

- NodeJS v10 (with node-gyp installed globally)
- `npm` or `yarn`
- `truffle`

Smart contract interaction:

- `truffle migrate`

Frontend app interaction:

- `cd app`
- `npm install` or `yarn`
- `npm run serve` or `yarn serve`

# Introduction

![4thTech logo](https://github.com/4thtech/static-assets/blob/d30afd40f39a20b21de01d569aba288f56e64cb4/image/4thtech-ecosystem.svg)

4thTech is a Block Labs project built as a Web3 infrastructure technology occupying the protocol, encryption, SDK and client White-label layers. The project aims to:
- empower permissionless communication that can enable 1000s of communication dApps to evolve on Web3, via SDKs & White-labels, while it's core Web3 primitive; 1 email/message/data-exch = 1 L1/L2 transaction utilises blockchain security to enable immutable and non-custodial E2EE W2W on-chain communication,
- pioneer the future of encrypted, non-custodial and decentralized on-chain communication, and
- contribute to the next Web3 adoption wave.

## Core Primitives

While various use cases are possible, let's use dMail and dChat as examples. The dChat W2W message exchange happens on-chain as one short message represents one L1 or L2 blockchain transaction. As dMail is data heavier, lite encrypted JSON objects are created to hold dMail metadata. The link to this metadata and checksum is recorded on the chain as a blockchain transaction. The same goes for W2W data file transfers where; 1 data file package transfer = 1 L1/L2-TX. So again, the core primitive described by the formula below applies; 

💡1 email/message/data-exch = 1 L1/L2-TX

Every wallet becomes an on-chain identity, and the message or data vault can be accessible (i.e. decrypted) only with users' private keys! There are three encryption options available within the protocol; (1) custom encryption; (2) AES-randomly generated secret key (i.e. Advanced Encryption Standard), and; (3) AES secret key produced by ECDH (i.e. Elliptic-Curve Diffie-Hellman); 

💡not your keys = not your email/message/data

## Infrastructure by Layers

Zooming out, the architecture is quite straightforward. As shown in the Infrastructural layer stack schematic, there are [UI White-label](https://github.com/4thtech/white-label-client) clients built on top of the [SDK v.1](https://github.com/4thtech/4thtech-sdk-js), powered by [Protocol v.1](https://github.com/4thtech/smart-contracts), encryption, storage and blockchain networks. To be able to establish Web3's first communication standard, the protocol will need to be available for many L1s and L2s, which is a matter of the Level 1 integrator. To support enterprise and mobile on-chain communication at scale, the deployment of communication-specific blockchain would be needed in the future.

![Infrastructure by Layers](https://github.com/4thtech/static-assets/blob/d166e3a2054f20d70213ef391adfd427dd9c8226/image/infrastructural-layer-schematic-4thtech.svg)

## Encryption

Encryption is one of the key parts of the infrastructure. There are three options available: 

- custom encryption,
- AES-randomly generated secret key,
- AES-SK produced by ECDH [[Encryptor Extension](https://github.com/4thtech/encryptor-extension)] 

![Encryption](https://github.com/4thtech/static-assets/blob/6406e4801581652614e4e9ea8924ddea4d5faca2/image/4thTech-encryption.svg)

## Integrator economics

Level 1 integrators can set the desired protocol **BASE-FEEs**, while Level 2 integrators can set their protocol **DAPP OWNER-FEEs**.

💡Protocol v.1 build-in monetisation layers enables independent out-of-the-box integrator economics, permitting developers to focus on application UI/UX features.

![Protocol FEE schematic](https://github.com/4thtech/static-assets/blob/42cac1093f758807aefc0ded7ee37aae114b10c5/image/4thTech-protocol-fees-schematic.svg)

## Start Building

A permissionless Level 2 integrator licence is available via Level 1 integrator [Immu3](https://wiki.immu3.io/) and is perfect for teams wanting to build their own on-chain communication dApps. Enterprise Level 1 integrator licence is available via Block Labs and is meant for traditional businesses or offices, L1s, wallets, and existing applications.

💡**4thTech SDK** provides abstractions to assist you with interacting with the v1 Protocol smart contracts in a Typescript/Javascript environment. With the SDK, you can manipulate data that has been queried from the EVM using libraries that assist with needs such as data modelling, protection from rounding errors, and compiling time-enforced typing.

💡**4thTech dMail & dChat white-label framework** enables fast and easy builds. White-label-based modern minimalistic design style emphasizes simplicity with simple intuitive but effective navigation and setup system. A simple user interface has been developed to offer a step-by-step setup enabling the best possible user experience.

 ****            | **Repo** | **Wiki** |
:---------------:|:--------:|:--------:|
 **SDK v.1**     |     [Go](https://github.com/4thtech/4thtech-sdk-js)     |     [Go](https://wiki.4thtech.io/docs/sdk)     |     
 **White-label** |      [Go](https://github.com/4thtech/white-label-client)    |     [Go](https://wiki.4thtech.io/docs/white-label)     |

## Interested in reading more?

In-depth articles and documentation can be found on
our [wiki page](https://wiki.4thtech.io).

## Contact

If you have any questions or want to be part of our community, please DM us on [Twitter](https://twitter.com/4thtechProject).

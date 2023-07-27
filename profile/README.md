# Introduction to 4thTech

![4thTech logo](https://github.com/4thtech/static-assets/blob/91e1e2f69b50cda946fdbff4f28154fadb38defa/image/4thtech-ecosystem.svg)

4thTech is a Block Labs project built as a Web3 infrastructure technology occupying the protocol, encryption, SDK and storage layers. The project aims to:
- enable permissionless communication that enables 1000s of communication dApps to evolve on Web3, via TypeScript SDKs & White-labels, while it's core Web3 primitive; 1 email/message/data-exch = 1 L1/L2 transaction utilises blockchain security to enable immutable and non-custodial E2EE W2W on-chain communication,
- contribute to the next Web3 adoption wave, and
- pioneer the future of encrypted, non-custodial and decentralized on-chain communication.

## Core Primitives

While various use cases are possible, let's use dMail and dChat as examples. The dChat W2W message exchange happens on-chain as one short message represents one L1 or L2 blockchain transaction. As dMail is data heavier, lite encrypted JSON objects are created to hold dMail metadata. The link to this metadata and checksum is recorded on the chain as a blockchain transaction. The same goes for W2W data file transfers where; 1 data file package transfer = 1 L1/L2-TX. So again, the core primitive described by the formula below applies. 

💡1 email/message/data-exch = 1 L1/L2-TX

Every wallet becomes an on-chain identity, and the message or data vault can be accessible (i.e. decrypted) only with users' private keys! There are three encryption options available within the protocol; (1) custom encryption; (2) AES-randomly generated secret key (i.e. Advanced Encryption Standard), and; (3) AES secret key produced by ECDH (i.e. Elliptic-Curve Diffie-Hellman). 

💡not your keys = not your email/message/data

## Infrastructure by Layers

Zooming out, the architecture is quite straightforward. As shown in the Infrastructural layer stack schematic, there are UI clients built on top of the SDK, powered by protocols, encryption, storage and blockchain networks. To be able to establish Web3's first communication standard, the protocol will need to be available for many L1s and L2s, which is a matter of the level 1 integrator. To support enterprise and mobile on-chain communication, the deployment of application-specific L1 would be needed in the future. 

![Infrastructure by Layers](https://github.com/4thtech/static-assets/blob/717eddd5a6ef66fd2fa757f13f7f35a00b15afc3/image/infrastructural-layer-schematic-4thtech.svg)

## Interested in reading more?

In-depth articles and documentation can be found on
our [Medium page](https://medium.com/4thtech)
or [wiki page](https://wiki.4thtech.io).

## Contact

If you have any questions or want to be part of our community, please DM us on [Twitter](https://twitter.com/4thtechProject).

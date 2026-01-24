The most critical design principles in Ergo L2s are as follows:

* anyone may create a reserve box on Ergo. A reserve may be in form of ERG or custom tokens. Reserve is associated with a public key. Anyone may withdraw from a reserve by presenting a signed message associated with a public key, which contains amount and also protection against double-spending (unique spending id or token like done in ChainCash)

* then there could be variety of offchain protocols a signed message may come from. It could be p2p protocol, like Lightning, or multiple users with a payment server they choose (like Torrent server), federated protocols (where a federation, or double layered federation, like Rosen, is tracking offchain state), or even sidechain.

Common approaches:

* Lightning Network
* Hydra

Ergo specific solutions:


# base-package-p2p

The p2p substrate, ours: store, discovery, connections, replication, channels, repositories on Hypercore, the name service, the node and its managers.

## The package

- holds: `pear-full-square/p2p-store`, `pear-full-square/p2p-dht`, `pear-full-square/p2p-connect`, `pear-full-square/p2p-replicate`, `pear-full-square/p2p-channel`, `pear-full-square/p2p-mrepo`, `pear-full-square/p2p-rns`, `pear-full-square/p2p-node`, `pear-full-square/p2p-node-manager`, `pear-full-square/p2p-swarm-manager`
- requires: [haiccing/base-package-mycelium](https://github.com/haiccing/base-package-mycelium), [haiccing/base-package-haicc](https://github.com/haiccing/base-package-haicc)
- hash: `3814cc72da611fdc6ada81e4149461d262a60e7299ec692a1b63f8299a3951f1`

In a work folder (see [haiccing/base-package-haicc](https://github.com/haiccing/base-package-haicc)), installed by HAICC as a project needs it, or by `./haicc install p2p`, into `.haicc/packages` with what it requires; tested there, within the package: `./haicc test p2p`.

Written by the package manager from the development repository ([splectrum/dev-env-2-p2p-cluster](https://github.com/splectrum/dev-env-2-p2p-cluster)): not edited here.

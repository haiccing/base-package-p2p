# base-package-p2p

The p2p substrate, ours: store, discovery, connections, replication, channels, repositories on Hypercore, the name service, the node and its managers.

A package: self-contained, its code ready to run, laid out as it is installed. Written by the package manager (`pear-full-square/pkgm-base-manager`) from the development repository; do not edit here.

- requires: `haiccing/base-package-mycelium`, `haiccing/base-package-haicc`
- hash: `3814cc72da611fdc6ada81e4149461d262a60e7299ec692a1b63f8299a3951f1`

## Holds

- `pear-full-square/p2p-store`
- `pear-full-square/p2p-dht`
- `pear-full-square/p2p-connect`
- `pear-full-square/p2p-replicate`
- `pear-full-square/p2p-channel`
- `pear-full-square/p2p-mrepo`
- `pear-full-square/p2p-rns`
- `pear-full-square/p2p-node`
- `pear-full-square/p2p-node-manager`
- `pear-full-square/p2p-swarm-manager`

## Installed

By the package manager, into the host's install folder (`~/.haicc/packages`), with the packages it requires; its tests run there:

```sh
node <install folder>/pear-full-square/pkgm-base-manager/cli.js install p2p --from <folder of haiccing repositories>
node <install folder>/pear-full-square/pkgm-base-manager/cli.js test p2p
```

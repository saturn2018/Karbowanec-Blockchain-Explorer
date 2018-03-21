# Tantal Blockchain Explorer
Block explorer for Tantal CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon saturnd. It should be accessible from the Internet. Run saturnd with open port as follows:
```bash
./tantald --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=37832
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

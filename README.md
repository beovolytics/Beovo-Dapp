# Beovo-Dapp
Depdencey :
-----------------------------------------------
curl https://raw.githubusercontent.com/creationix/nvm/v0.30.2/install.sh | bash
nvm use 8.9.4
npm


truffle - smart contract framework 

npm install -g truffle@4.1.7 --unsafe-perm=true

ganache - local inmemory blockchain for dev
npm install -g ganache-cli

ganache-cli -p 5545

truffle :
truffle compile
truffle migrate
truffle test



/opt/ethererum/dapp_token-master
truffle console


geth installation 
sudo yum install golang
$  sudo yum install gmp-devel
$  git clone https://github.com/ethereum/go-ethereum
$  cd go-ethereum/
$  make geth
$  ls -al  build/bin/geth
cp /opt/ethererum/go-ethereum/build/bin/geth /usr/local/bin/.


Starting geth : 
geth --rinkeby --rpc  --rpcport 9945 --wsport 9946 --rpcapi="db,eth,net,web3,personal" 

geth attach ipc:/root/.ethereum/rinkeby/geth.ipc

eth.syncing

geth --rinkeby account new 




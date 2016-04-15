# token
A basic standard token dApp (semantic/jquery/web3)

### Installation

0. Install <a href="https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum">geth</a>, create an account:

		geth --testnet account new

1. Copy the new account address, paste it in the ZeroGox faucet, click "Gimme Wei":

		https://zerogox.com/ethereum/wei_faucet

1. Run an Ethereum testnet geth node:

		geth --testnet --unlock "0" --shh --rpc --rpcapi="db,eth,net,web3,shh" --rpcaddr="0.0.0.0" --rpccorsdomain="*"

2. Open the dApp.html in Chrome


### Run Simple Python Server
```
cd token
python -m SimpleHTTPServer 8000
```

Then in Chrome open `http://localhost:8000` to view the dApp

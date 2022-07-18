# ape-sandbox

## Setup

```console
python3 -m venv venv
source venv/bin/activate
pip install -U pip
pip install wheel
pip install eth-ape
ape install infura etherscan
export WEB3_INFURA_PROJECT_ID=<YOUR_INFURA_PROJECT_ID>
ape console --network ethereum:mainnet:infura
```

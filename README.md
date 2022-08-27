# ape-sandbox

## Setup

```console
python3 -m venv venv
source venv/bin/activate
pip install -U pip
pip install wheel
pip install eth-ape
ape plugins install infura etherscan ledger polygon
export WEB3_INFURA_PROJECT_ID=<YOUR_INFURA_PROJECT_ID>
ape console --network ethereum:mainnet:infura
```

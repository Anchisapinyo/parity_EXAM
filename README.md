"# parity_EXAM" 

Parity Blokchain Network node with Proof of Authority (Aura) plugable consensus  


Step 1. Clone the project

git clone https://github.com/Anchisapinyo/parity_EXAM

Step 2. Download and install parity

https://github.com/openethereum/parity-ethereum/releases

parity.exe should be placed in the parity_EXAM floder

Step 3. Create floder for node's database
For example: paritybase

Step 4. Create new account
$ D:\parity>parity account new --chain validator.json --keys-path \paritybase\keys

Enter password 

Step 5. take the new account put in 
node.toml file 
unlock = []
engine_signer = ""

validator.json file
"list": [""]

Step 6. Run node
$ D:\parity>parity --config node.toml

 


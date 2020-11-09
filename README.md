# final_demo_thesis

geth --nousb --datadir=$pwd --syncmode 'full' --port 30310 --miner.gasprice 0 --miner.gastarget 470000000000 --shh --http --http.addr 'localhost' --http.port 8545 --http.api admin,eth,miner,net,txpool,personal,web3, shh --mine --allow-insecure-unlock --unlock "0x91F94AE0d9308953b4530B4611a33Ff05BEF50D4" --password password.txt 


geth --nousb --datadir=$pwd --syncmode 'full' --port 30311 --miner.gasprice 0 --miner.gastarget 470000000000 --shh --http --http.addr 'localhost' --http.port 8545 --http.api admin,eth,miner,net,txpool,personal,web3, shh --mine --allow-insecure-unlock --unlock "0x4305a01E91C11279fe4a5FCcB0DC4f26cE463704" --password password.txt

geth --nousb --datadir=$pwd --syncmode 'full' --port 30312 --miner.gasprice 0 --miner.gastarget 470000000000 --shh --http --http.addr 'localhost' --http.port 8545 --http.api admin,eth,miner,net,txpool,personal,web3, shh --mine --allow-insecure-unlock --unlock "0x42De6794FbcB9627B551dB4e51EEeA023d81B838" --password password.txt


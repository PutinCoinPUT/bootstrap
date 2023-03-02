# bootstrap
Up-to-Date Bootstrap for synching the node wallet

Assure yourself, that your node wallet has been totally closed ("exit") and is not running in the background. 

Go to your PUTinCoin wallet data folder (e.g. C:\\Users\"YourWindowsUserName"\AppData\Roaming\PutinCoin), and delete the folders "database", "txleveldb" and the file "blk001.dat". Copy the bootstrap.zip file you've downloaded from this repository and unpack it in the PUTinCoin wallet data folder. Delete the bootstrap.zip (you don't need it anymore) and restart the wallet. Wait until the wallet has read the blockchaindata (this could take a while) and let it sync until the little checkmark is shown in the right bottom corner of the wallet window. Unlock your wallet for "staking" and have phun! :-)

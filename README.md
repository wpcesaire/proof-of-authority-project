  ##Starting the power network:
launch node1 by using this code ./geth --datadir node1 --unlock "13fe7b5bfd83324b7d001a923542e5d6a755543e" --mine --rpc --allow-insecure-unlock
In a new terminal launch node2 by using this code ./geth --datadir node2 --unlock "<node 2 address>" --mine --port 30304 --bootnodes <enode address from node1>
the code ran for node 2 has the enodes which hold the key from node1 which is considered the bootnode. 
In both node 1 and node 2 the accounts had to be unlocked so that history of transactions will be noted in proper files

  #how to configure the network connecting to MyCrypto:
To use Mycryprto involved connecting a crypto wallet to the network. to configure the network I used mycrypto to create a custom node by naming the custom node, match the chain id  provided by network and put in the url from the local machine and the default rpc port.
This procedure allowed me to connect to the ethereum network with my custom node. to do an  transaction on the network you need to bring in private key of address of wallet i created


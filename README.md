  ## How to start  the  network:
  
* launch node1 by using this code ./geth --datadir
  node1--unlock"13fe7b5bfd83324b7d001a923542e5d6a755543e" --mine --rpc --allow-insecure-unlock

* In a new terminal launch node2 by using this code ./geth --datadir node2 --unlock "<node 2   
  address>" --mine --port 30304 --bootnodes <enode address from node1>.
 
* The code  I ran for node2 has the enodes which hold the key from node1 which is considered the
   bootnode. 
 
* In both node1 and node2 the accounts had to be unlocked ( as noted above by the code used) so that a
 history of transactions will be noted in  proper files
  

## How to configure the network connecting to MyCrypto:
  
  * To use Mycryprto involved connecting a crypto wallet to the network. To configure the network I used
    MyCrypto to create a custom node by naming the custom node, matching  the chain id  provided by
    the  network , and putingt in the url from the local machine and the default rpc port.
    
    
 * This procedure allowed me to connect to the ethereum network with my custom node. To do a  transaction
   on the network I needed to bring in the private key of the address of the wallet i created

 ![connecting to MYCrypto](https://github.com/wpcesaire/Proof-of-Authority-Development-Chain/blob/master/Screen%20Shot%202020-07-25%20at%2010.33.26%20AM.png)
![tx](https://github.com/wpcesaire/Proof-of-Authority-Development-Chain/blob/master/screenshots/Screen%20Shot%202020-07-31%20at%201.44.09%20PM.png)
   

![tx](https://github.com/wpcesaire/Proof-of-Authority-Development-Chain/blob/master/Screen%20Shot%202020-08-01%20at%208.50.41%20AM.png)



Bitcoin was designed to be a virtual currency in which transactions can be made between two or more parties, secured by cryptography. 
To send a payment, users digitally sign transactions between themselves and the recipient, then publish the transaction publically. 
The transaction is then validated then placed onto a public ledger that can be read by anyone. 
To prevent the ledger from being tampered with eg someone deleting a transaction after it is sent, a number of different security protocals can be used. 
For bitcoin, the algorithm used is proof of work and the process of computing this algorithm is referred to as mining.

The proof of work algorithm works by taking a group of transactions, a reference to the previous ledger entry and a random number then calculating a 
cryptographic hash of this data. If the resulting hash value is less than a specific value (the difficulty) a valid ledger entry has been found. If it is
not lower than the difficulty value, a miner picks a new random number and trys again. This continues until a miner finds a valid ledger entry and publishes it.
Once this happens, the process starts again to find the next valid entry with a new group of transactions.

The proof of work part comes from a special property of cryptographic hash functions: while it is very easy to calculate the hash for a given piece of data it is
very difficult to calculate a piece of data which will give a specific hash value. This means that the only way to find a valid ledger entry is to try lots of 
random numbers by trial and error until a valid one is found - proving that you have done a specific amount of work to find the ledger entry. Miners who find a
valid ledger entry are rewarded with a payout of bitcoin and from transaction fees on the transactions included in the ledger entry.

To remain secure, a crypto currency using proof of work for security honest participants in the network must control a majority of the computational power involved
in mining. Bitcoin and many other proof of work crypto currencies also include a scaling mechanism - the difficulty, this difficulty value is recalculated from time
to time to react to more or less computing power being available to the network to ensure that valid ledger entries are found at a consistent rate. These two 
properties taken together mean that Bitcoin will continue to use more and more computational power as the network expands. 

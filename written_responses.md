## Written Responses

1. Describe the general process of how blocks are added to a blockchain.

 Adding a new block chain is a classic example of something being easy in theory but hard in practice.
 The theory is that you basically guess a number called a proof that when hashed equals the hash of the the entire last block. If guessed correctly, a new block is mined and given an index, sometimes a timestamp, all the pending transactions, the proof used to mine the new block and the hash of the previous block and lastly the finder is awarded a coin. It then is shared to the nodes in the network which check to make sure its valid and then the process repeats. The inclusion of the hash of the previous block preserves the integrity of the chain as a whole because if someone changes a block in the middle of the chain in their favor it would change that blocks hash. So it won't match with the next block in the chain and can be easily detected. If they were to chop off the chain after their change the network would reject it because it goes by the longest chain. The reason its harder in practice to find a proof is because of the odds stacked against you, such as the amount of other people searching for the next proof and the fact that others can have dedicated computers designed specifically for the purpose of mining coins.

2. How can blockchain users mine coins?
    Blockchain users can mine for coins by connecting to the server and using a proof of work type algorithm to constantly make guesses for the next proof in the blockchain. If the user is successful, they are awarded a coin for their work in continuing the growth of the chain.

3. Explain how simulations like Conway's Game of Life can be used in real-world applications.
    Conway's Game of Life and other cellular automata can be used for real world applications such as growth of crystals, tracking the path and amount of people affected by a virus in a given region and can be used in evolution predictions. Traffic flows can also be predicted.
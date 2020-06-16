## Introduction & Definitions
- This was a horse^&#$ class and a complete waste of time.

- Overview:

- Definitions:
    1. Blockchain: Consensus-based secure decentralized public database which stores information immutabaly over a peer-to-peer network.
        - Public or private.
        - Data recorded via consensus-based algorithms.
        - Uses cryptography. 
        - Exists over a peer-to-peer network.
    2. Bitcoin: Decentralized virtual cryptocurrency built on top of Blockchain.
        - Removes the dependency on trusted third-party to exesute the transaction.
        - Executed transactions via peers based upon consensus-based algorithms and recorded in the Blocks by miners.
        - Allows you to execute a transaction without tructing the receiving party in franction(s) of seconds.
    3. Mining: The process of recording the transactions as a block into the Blockchain of that currency.
        - You can earn virtual currency through mining by inversting computational power into it.
        - Answer is that they are asked to solve a very complex computation problem to identify the next block in the Blockchain.
        - Miners use CPU power to identify a nonce (number used only once) through which they can create the digest/signature of the next block in the Blockchanin which is less than the recently added block.
    4. Consensus Algorithm: Computation methodology of resolving conflicts in Blockchain.
    5. Decentralized: Centralized, decentralized (clustered), and distributed.
    6. P2P: And server-based versus peer-to-peer (clients interact with each other.)


## Blockchain Basics
- What is Blockchain and how does it work?:
    1. Blockchain is a decentralized ledger which tracks digital assets on P2P networks. e.g.: a large book.
        - Blocks in a chain refer to previous blocks, like page numbers in a book.
        - e.g.: Book Analogy: Book = Blockchain. Page = Block. Page entry = Blockchain transaction.
        1. Easy to detect if a page/block has been removed or deleted.
        2. Easy to arrange the pages/blocks and identify suspicious activity.
        3. Impossible to temper a previous entry in the ledger without someone noticing it.
    2. Each block is built on top of the recent block and use its content/signature and nonce.
    3. Building a block and adding it in the blockchain is the task of the miner nodes (optional.)
    4. In public blockchain it is computationally difficult to add a block to prevent attacks.
    5. Miners try to guess a nonce in such a way that if it gets crunched with the most recent block's fingerprint then it will create a new fingerprint which will be less that the last/most recent block in the blokchain.
- *Our* definition: "Blockchain is a consensus-based secure decentralized public/private database which stores information immutably over peer-to-peer network."

- Private versus public Blockchain:
    1. Public blockchain:
        - Anyone can read/write without explicit authorization.
        - More complex rules for better security.
        - Complex consensus algorithm.
        - Computationally expensive to mine and add a block.
        - No one owns it.
        - Computational power is distributed globally.
    2. Private blockchain:
        - Only authorized nodes can read/write without explicit authorization.
        - Security cn be implemented easily.
        - Only the authorized node can be the arbitrator for any dispute.
        - Easy or computationally less expensive to add a block.
        - One of more private entities own the Blockchain.
        - Many things can be replaced by legal contract giving more control to one party.

- How transactions get executed and distributed:
    - e.g.: 
    1. Alice in US wants to send Bob in Australia $10.00.
    2. She will execute the transaction via net banking.
    3. Bank will take 3-4 days for cross-border transaction and charges a percentage of $0.50.
    4. Alice's bank is acting as a trusted third party.
    - Cost/delay make this a very unattractive option. 
    - What if the money os to be used for a medical emergency?
    - Blockchain e.g.:
    1. Alice -> $10.00 -> Bob. Within a few seconds.

- Consensus: How the conflicts are being resolved.
    1. An example of a conflict:
    - All nodes have synchronized the Blockchain and are at block 100.
    - Three miers have mined the new block 101 at nearly the same time.
    - All of their block has a different signature and, hence, are not exactly the same.
    - Let's say the new blocks are 101a, 101b, and 101c.
    - Which is the final new block? How can we reolve this conflict?
    - (In Bitcoin the problem is worth 25BTC or $18,735 as of today. Costly problem, yes?)
    2. Longest chain rule:
    - In public blockchains conflicts are being resolved by longest chain rule.
    - So, the block with the longest chain, the amount of blocks built off of that block version, will win.
    3. How about private?
    - Make a miner as an arbitrator or trusted.

- When to use a Blockchain:
    1. When you want to store something immutably.
    2. When you keep adding but older one does not change.
    - e.g.: Court judgements. Health records.
    3. Decentralization. When you want to deentralize the control.
    - e.g.: User identity management system.
    4. Proof of ownership. When you want to prove that you are the ownder of the digital document.

- Why Blockchain is more secure:
    1. Nodes follow longest chain rule. Mr. X alters block number 23. Nodes follow longest chain rule.
    - So, the smaller chain of 0 - 23 is unchosen because 0 - 100 exists.
    2. Computationally expensive. And time-consuming to create a block. It's called "mining."
    3. Decentralized nature: There are many honest nodes in the network.
    - Faking a transaction will be expensive and ultimately rejected by honest upcoming blocks.

- How Blockchain can be hacked:
    1. 51% attack. Often considered a very large flaw.
    - If a single entity contrinuted the majority of the network's mining hashrate, it would have the power to manipulate the public ledger.
    - In theory, this could happen. Blockchain is publically open. COnfidence in the currency would be lost.
    - Potential damage:
        1. Decline in pricing. Prevention of transaction confirmation.
        2. Reverse transaction resulting in double spent. And prevent miners to find blocks.
    2. Eclipse attack. Cripple a node in such a way that it cannot talk to other nodes in the network.
    - If there are three nodes with 30%, 30%, and 40% network hash power and node 2 is crippled in such a way that it cannot talk to node 1 then node 3 can control Blockchain's public ledger. 

- Private Blockchain. Can I set up my very own?:
    1. Yes. Yes you can.
        - It is fully owned by you. You are responsible for its security.
        - e.g.: Ethereum. Custom Genesis file. Custom data directory. Custom NetworkId. And disable node discovery.
        - e.g.: Multichain is the easiest. Open source. Great features like permissions, data streams, etc...
        - e.g.: Hyperledger Fabric. No concept of mining or cryptocurrency. IBM is a major contributor.
        - e.g.: Openchain. Open-source distributed ledger technology. 
            1. Suited to manage digital assets in a robust, secure, and scalable manner.
            2. Every transaction is digitally signed.
        - e.g.: Bitcoin core.

## Summary
- What's next? Yawn.
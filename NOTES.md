## Introduction & Definitions
- Overview:

- Definitions:
    1. Blockchain: COnsensus-based secure decentralized public database which stores information immutabaly over a peer-to-peer network.
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

## Summary


# How Blockchain Works

To understand how blockchain works, let's walk through the process of a typical transaction. Imagine Alice wants to send 1 Bitcoin to Jared. Here's what happens:

First, Alice creates a transaction using her digital wallet. This transaction includes Jared's public address (like an email address), the amount she wants to send, and a digital signature that proves she owns the Bitcoin she's trying to spend. The digital signature is created using Alice's private key, a secret number that only she knows.

> Just like an email address is public, so are wallet addresses. It's only anonoymous so long as the link between real human and address is private. Hence it's often refered to as pseudonymity.  

Once Alice submits the transaction, it's broadcast to the entire Bitcoin network. Thousands of computers around the world receive this transaction and begin the verification process. They check several things: Does Alice actually own the Bitcoin she's trying to spend? Has she already spent this Bitcoin elsewhere? Is the transaction properly formatted? Just like Rummikub, they look through the chain of all of Alice's transcations to check that it all tallies up, such that Alice has **unspent transaction outputs (UTXOs)**, aka money on her ledger.

If the transaction passes all these checks, it gets added to a pool of pending transactions waiting to be included in the next block. Her transcations from her game of Rummikub waits in the queue, usually at most 10 minutes, for others to finish their rounds and submit transaction/round scores. This is where mining comes in; miners compete to solve a complex mathematical puzzle, with the winner getting to create the next block of transactions and taking the prize (paid via the transcation fee).

When a miner successfully creates a new block, it includes Alice's transaction along with many others. The block is then cryptographically linked to the previous block in the chain, and the entire network updates their copies of the blockchain to include this new block. At this point, Alice's transaction is confirmed and becomes part of the permanent record. 

The beauty of this system is that it eliminates the need for trust in a central authority. Instead of relying on a bank to verify and record the transaction, the entire network works together to ensure accuracy and security. This distributed approach makes the system incredibly robust as there's no single point of failure, and no single entity can control or manipulate the network.

> Fun Fact: When we were little, my sibling and I would often collude against my father by trading Rummikub tiles under the table. Consensus and collusion are 2 sides of the same tile. ;)

## Optional "Well, Actually..." Section: UTXO vs Account Model

The "Well, actually..." asshole in the group may point out that **unspent transaction outputs (UTXOs)** is specifically how Bitcoin (and it's offshoots) handles the ledger. This is like physical bills, you have a $10, a $5, and a $1 bill. You have cents that go down to a penny, but that's it. Bitcoin's smallest unit is the SAT or Satoshi. It's the cents to the dollar. Simply put, BTC deals in integers. 

You may be thinking, right that's how money works. 

Recall, the skimming half-penny scheme from real life and the movie "Office Space". This requires half-pennies...which doesn't exist in our phsyical world. It's a function of digital calculation, floating decimal points. Etherum uses an **Account-based model** for its ledger. Simply: It allows decimal point mathematics. 

This is purely an implementation detail, and you do not need to know it to function happily in the cryptocurrency world. You can live happily without ever storing UTXOs in your brainspace. I won't mention it again. 

UXTOs: Bitcoin, Bitcoin Lightening, DOGECoin, Zcash, ...

Account Model: Etherum, Solana, Tron, ...

# Bitcoin Basics

https://bitcoin.org/bitcoin.pdf

# Introduction

Today, most of the online transactions we make rely on financial institutions to process them. These institutions act as trusted third parties, meaning that they are responsible for making sure that the transactions are legitimate and that the money is transferred correctly.

However, this system has some weaknesses. For example, it can be slow and expensive, and it can be difficult to reverse transactions if there is a problem.

The authors of the paragraph you gave me are proposing a new way to make online payments that doesn't rely on trusted third parties. They call this system "electronic cash".

Electronic cash would work by using cryptography to create a secure way to track transactions. This would make it possible to make payments that are much more difficult to reverse, and it would also make the system more efficient and cheaper.

The authors propose to use a peer-to-peer network to create electronic cash. This means that everyone who uses the system would be connected to each other, and there would be no central authority.

The network would be secure as long as there are more honest users than dishonest users. This is because the dishonest users would not be able to control the network and prevent legitimate transactions from happening.

# Double Spending Problem

A double-spending problem is a problem that occurs in digital currency systems where a user can spend the same digital coin twice. This is possible because digital currencies are not physical, and therefore there is no way to prevent someone from copying and spending the same coin multiple times.

The double-spending problem is a major challenge for any digital currency system. If it is not addressed, it could undermine the trust in the system and make it worthless.

There are a number of ways to prevent double spending, including:

- **Proof-of-work:** This is the most common way to prevent double spending in cryptocurrencies. It involves miners competing to solve a mathematical puzzle, and the first miner to solve the puzzle gets to add a new block of transactions to the blockchain. The block is then broadcast to the rest of the network, and all nodes in the network verify the block before adding it to their own copy of the blockchain. This makes it very difficult for someone to double-spend, because if they try to spend the same coin twice, their transaction will be rejected by the network.
- **Proof-of-stake:** This is a newer consensus mechanism that is gaining popularity. It involves nodes staking their coins to participate in the consensus process. The nodes with the most coins staked have the most voting power, and they are responsible for validating transactions and adding new blocks to the blockchain. This makes it very difficult for someone to double-spend, because if they try to spend the same coin twice, their transaction will be rejected by the network.
- **Centralized authorities:** Some digital currency systems use centralized authorities to prevent double spending. This means that there is a trusted third party that verifies transactions and prevents double spending. This approach is not as secure as proof-of-work or proof-of-stake, but it is easier to implement and manage.

The double-spending problem is a complex issue, and there is no single solution that is perfect. The best solution for a particular digital currency system will depend on a number of factors, including the security requirements, the scalability requirements, and the cost of implementation.

Imagine you have a notebook and you want to keep track of all the money you have. You could write down every time you get money and every time you spend money. But this would be a lot of work, and it would be easy to make a mistake.

A better way to keep track of your money is to use a blockchain. A blockchain is like a giant notebook that is shared by everyone in the world. Every time someone makes a transaction, it is written down in the blockchain. This makes it very difficult to cheat, because everyone can see all the transactions that have been made.

The blockchain is also very secure. To add a new transaction to the blockchain, you need to solve a very difficult math problem. This problem is so difficult that it would take a very powerful computer a long time to solve. This makes it very difficult for someone to cheat the system.

The blockchain is a very important technology. It is used to power cryptocurrencies like Bitcoin and Ethereum. It is also used by banks and other financial institutions to keep track of transactions.

In the paragraph you gave me, the authors are proposing a way to use the blockchain to create a peer-to-peer electronic cash system. This would allow people to send money to each other without going through a financial institution. This would make it cheaper and faster to send money.

The authors propose to use a proof-of-work system to prevent double spending. Double spending is when someone tries to spend the same money twice. In a proof-of-work system, miners compete to solve a math problem. The first miner to solve the problem gets to add a new block of transactions to the blockchain. The block is then broadcast to the rest of the network, and all nodes in the network verify the block before adding it to their own copy of the blockchain. This makes it very difficult for someone to double-spend, because if they try to spend the same money twice, their transaction will be rejected by the network.

# Transactions

To prevent double-spending, a digital currency system needs a way to keep track of all the transactions that have been made. One way to do this is to have a trusted central authority, like a bank, keep track of all the transactions. This way, the bank can see if someone tries to double-spend a coin. However, this solution has a problem. It relies on the bank being honest. If the bank is corrupt, they could steal your coin or allow someone else to double-spend it.

Another way to prevent double-spending is to use a blockchain. A blockchain is a distributed ledger that records all the transactions that have ever been made in a digital currency system. This way, everyone can see all the transactions that have been made, and it is very difficult to cheat the system.

In the paragraph, the authors are talking about how to use a blockchain to prevent double-spending. They say that the payee (the person who is receiving the coin) needs proof that at the time of each transaction, the majority of nodes agreed it was the first received. This means that if someone tries to double-spend a coin, the majority of people in the network would know about the first transaction and would reject the second one.

---

Here are some additional details about the paragraph:

- The authors define an electronic coin as a chain of digital signatures. This means that each coin is linked to the previous coin in the chain, and each signature is verified by the next owner of the coin. This makes it very difficult to counterfeit a coin or spend it twice.
- The authors say that the problem of double-spending can be solved by using a trusted central authority. However, this solution is not ideal because it relies on the central authority being honest.
- The authors propose a solution to the double-spending problem using a blockchain. In a blockchain, all transactions are recorded in a public ledger that is distributed to all the nodes in the network. This makes it very difficult to cheat the system because everyone can see all the transactions that have been made.
- The authors say that the payee needs proof that at the time of each transaction, the majority of nodes agreed it was the first received. This means that if someone tries to double-spend a coin, the majority of people in the network would know about the first transaction and would reject the second one.

# Timestamp Server

A timestamp server is a system that takes a hash of a block of data and publishes it publicly. A hash is a mathematical function that converts data into a unique string of characters. The hash of a block of data is used to prove that the data existed at the time the hash was created.

The Bitcoin blockchain is a chain of blocks, each of which contains a hash of the previous block, as well as a timestamp and other information about the transaction. The timestamp server is used to create the first block in the blockchain.

The blockchain is a distributed ledger, which means that it is stored on multiple computers all over the world. This makes it very difficult to tamper with the blockchain, because if someone tried to change a block, they would also have to change all the blocks that came after it.

The blockchain is used to record Bitcoin transactions. When someone sends Bitcoin to someone else, the transaction is recorded in a block on the blockchain. The blockchain is then updated and distributed to all the nodes in the network.

The timestamp server and the blockchain work together to create a secure and tamper-proof way to record transactions.

# Proof-of-Work

To create a distributed timestamp server, the authors propose using a proof-of-work system. A proof-of-work system is a way of making sure that someone has done some work before they are allowed to do something else. In this case, the work that the person has to do is to find a number that, when hashed, produces a certain number of zero bits. The more zero bits that are required, the more work that has to be done.

The authors argue that using a proof-of-work system has several advantages. First, it makes it very difficult to tamper with the timestamp server. If someone tries to change a block of data, they would also have to redo the proof-of-work for that block and all the blocks that come after it. This would be very difficult to do, because the proof-of-work gets more and more difficult as more blocks are added to the blockchain.

Second, the proof-of-work system also solves the problem of determining who has the authority to make decisions about the timestamp server. In a traditional system, this would be done by one person or organization. But with a proof-of-work system, anyone can participate in the decision-making process. This makes the system more democratic and less likely to be corrupted.

Finally, the proof-of-work system also helps to keep the timestamp server running smoothly. If there are too many blocks being generated, the difficulty of the proof-of-work increases. This makes it more difficult for people to tamper with the system, and it also helps to ensure that the blocks are generated at a steady rate.

# Network

1. New transactions are broadcast to all nodes. This means that they are sent to everyone in the network.
2. Each node collects new transactions into a block. A block is a group of transactions that have been verified and added to the blockchain.
3. Each node works on finding a difficult proof-of-work for its block. The proof-of-work is a mathematical problem that is very difficult to solve, but easy to verify. The node that solves the proof-of-work first gets to add the block to the blockchain.
4. When a node finds a proof-of-work, it broadcasts the block to all nodes. This tells everyone in the network that the block has been added to the blockchain.
5. Nodes accept the block only if all transactions in it are valid and not already spent. This means that the transactions must follow the rules of Bitcoin and that the coins being used in the transactions have not already been spent.
6. Nodes express their acceptance of the block by working on creating the next block in the chain. The next block is created using the hash of the previous block as the previous hash.

The network always considers the longest chain to be the correct one. This means that if two nodes broadcast different versions of the next block at the same time, the nodes will accept the version of the block that has the most blocks after it.

If a node does not receive a block, it will request it from another node. This ensures that all nodes in the network have the same copy of the blockchain.

# Incentive

- **Block reward:** Each block in the Bitcoin blockchain contains a special transaction called the coinbase transaction. This transaction is always created by the node that mines the block, and it rewards the miner with a certain number of newly minted bitcoins. The block reward is halved every 210,000 blocks, and it will eventually reach zero.
- **Transaction fees:** When a user sends bitcoins to another user, they can also include a transaction fee. This fee is paid to the miner who mines the block that contains the transaction. The transaction fee is optional, but it is usually included to incentivize miners to process the transaction quickly.

The incentive system is designed to ensure that nodes have a financial incentive to participate in the Bitcoin network. This helps to keep the network secure and reliable.

The paragraph also mentions that the incentive system can help to prevent attacks on the Bitcoin network. If an attacker tried to take control of the network, they would need to have more computing power than all the honest nodes combined. However, if the attacker did this, they would be better off using their computing power to mine blocks and earn bitcoins legitimately.

# Reclaiming Disk Space

The Bitcoin blockchain is a growing list of blocks, each of which contains a number of transactions. As the blockchain grows, it becomes more and more difficult to store all of the blocks.

To address this problem, the Bitcoin blockchain uses a technique called Merkle trees. A Merkle tree is a data structure that allows you to efficiently store a large number of items. In the case of the Bitcoin blockchain, the Merkle tree is used to store the hashes of all of the transactions in a block.

The hash of a block is calculated by taking the hash of the Merkle tree for that block. This means that if you only need to store the hash of a block, you can also reconstruct the Merkle tree and all of the transactions in the block.

This makes it possible to store the Bitcoin blockchain efficiently, even as it grows larger and larger.

The paragraph also mentions that the size of a block header is about 80 bytes. This means that the Bitcoin blockchain would only require about 4.2 MB of storage per year if blocks were generated every 10 minutes.

This is a relatively small amount of storage, and it is likely to continue to decrease as computer storage prices continue to fall.

# Simplified Payment Verification

A full node is a computer that stores the entire Bitcoin blockchain. This includes all of the blocks and all of the transactions in those blocks. Running a full node requires a lot of storage space and computing power.

A simplified node is a computer that does not store the entire Bitcoin blockchain. Instead, it only stores the block headers of the longest proof-of-work chain. The block headers are a small amount of data that summarizes each block.

To verify a Bitcoin transaction, a simplified node can query network nodes for the Merkle branch linking the transaction to the block it is timestamped in. The Merkle branch is a data structure that allows you to efficiently verify that a transaction is included in a block.

The simplified node cannot check the transaction for itself, but by linking it to a place in the chain, it can see that a network node has accepted it, and blocks added after it further confirm the network has accepted it.

As such, the verification is reliable as long as honest nodes control the network. However, if the network is overpowered by an attacker, the simplified node can be fooled by the attacker's fabricated transactions.

One strategy to protect against this is to accept alerts from network nodes when they detect an invalid block. This would prompt the simplified node's software to download the full block and alerted transactions to confirm the inconsistency.

Businesses that receive frequent payments will probably still want to run their own nodes for more independent security and quicker verification.

# Combining and Splitting Value

Bitcoin transactions can have multiple inputs and outputs. An input is a reference to a previous transaction that the current transaction is spending. An output is a transfer of value to a new address.

Normally, a transaction will have either a single input from a larger previous transaction or multiple inputs combining smaller amounts. The transaction will also have at most two outputs: one for the payment and one returning the change, if any, back to the sender.

It is important to note that fan-out, where a transaction depends on several transactions, and those transactions depend on many more, is not a problem in Bitcoin. This is because there is never the need to extract a complete standalone copy of a transaction's history.

To understand this better, let's take an example. Suppose Alice wants to send Bob 1 Bitcoin. She could create a transaction with one input from a previous transaction where she received 1 Bitcoin and one output to Bob's address.

Alternatively, she could create a transaction with multiple inputs from previous transactions where she received smaller amounts of Bitcoin. The transaction would then have one output to Bob's address for the total amount of 1 Bitcoin.

In either case, the transaction would be valid and would be added to the blockchain.

# Privacy

Bitcoin transactions are public, meaning that anyone can see the sender, recipient, and amount of each transaction. However, the Bitcoin protocol does not require the sender or recipient to be identified by their real names or addresses.

Instead, Bitcoin uses public and private keys to identify users. The public key is like a username, and the private key is like a password. The public key is used to receive bitcoins, and the private key is used to spend them.

When you create a Bitcoin wallet, you are given a pair of public and private keys. The public key is made public, and the private key is kept secret.

When you send bitcoins to someone, you use their public key. The recipient can then use their private key to spend the bitcoins.

This system of public and private keys allows for a high degree of privacy. The sender and recipient of a Bitcoin transaction can remain anonymous if they choose to do so.

However, there are some limitations to Bitcoin's privacy. For example, if you use the same public key to receive bitcoins from multiple people, it is possible to link those transactions together. This is because the blockchain is a public ledger, and all transactions are recorded on it.

To improve your privacy, you should use a new public key for each transaction. This will make it more difficult to link your transactions together.

You can also use a mixing service to further obscure your Bitcoin transactions. Mixing services mix your bitcoins with the bitcoins of other users, making it even more difficult to track your transactions.

Overall, Bitcoin offers a good level of privacy. However, it is important to be aware of the limitations of the system and take steps to protect your privacy if necessary.

# Calculations

# Conclusion

- **Peer-to-peer network:** Bitcoin is a peer-to-peer network, which means that there is no central authority that controls it. Instead, the network is made up of nodes that communicate with each other directly.
- **Proof-of-work:** Bitcoin uses a system of proof-of-work to secure the network and prevent double-spending. Proof-of-work is a mathematical problem that is very difficult to solve, but easy to verify. To add a block to the blockchain, a miner must solve a proof-of-work problem. The miner who solves the problem first gets to add the block to the blockchain and is rewarded with bitcoins.
- **Unstructured simplicity:** The Bitcoin network is designed to be simple and robust. Nodes do not need to be identified, and they can join and leave the network at will. The network is also designed to be resistant to censorship and attack.
- **Consensus mechanism:** The Bitcoin network uses a consensus mechanism to ensure that all nodes agree on the state of the blockchain. This consensus mechanism is based on the proof-of-work system.

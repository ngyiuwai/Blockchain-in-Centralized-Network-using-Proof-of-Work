## Project Blockchain: Mining in Centralized Network using PoW

This is a simple project to demonstration the Proof of Work Algorithm of Bitcoin, which is the most well-known blockchain, using a centralized network. **Please read the pdf for details. Algorithm is explained in the report.**

Bitcoin, the most well-known blockchain network, is described as 

*“A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution. Digital signatures provide part of the solution, but the main benefits are lost if a trusted third party is still required to prevent double-spending. We propose a solution to the double-spending problem using a peer-to-peer network. **The network timestamps transactions by hashing them into an ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without redoing the proof-of-work. The longest chain not only serves as proof of the sequence of events witnessed, but proof that it came from the largest pool of CPU power.** As long as a majority of CPU power is controlled by nodes that are not cooperating to attack the network, they'll generate the longest chain and outpace attackers. The network itself requires minimal structure. Messages are broadcast on a best effort basis, and nodes can leave and rejoin the network at will, accepting the longest proof-of-work chain as proof of what happened while they were gone.”* [1]

In this project, I am going to build a proof-of-work blockchain network which only retains below two characteristics of Bitcoin:
(i) Blockchain is a chain of blocks connected by hash-based proof-of-work.
(ii) Miner who has highest CPU power could add new blocks to the blockchain.

[1]"Bitcoin: A Peer-to-Peer Electronic Cash System", Satoshi Nakamoto, https://bitcoin.org/bitcoin.pdf

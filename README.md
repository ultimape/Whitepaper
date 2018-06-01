# Whitepaper

##Abstract

The Digital Trust Protocol defines a way to handle trust in the digital world. The idea is to use the trust network of your social network and ignore anything else. The goal of the DTP system is that it can be used for literally anything trust related, like security, rating and identity. 

The system works by a person named Alice trust another person named Bob that trust his Car mechanic. Alice can now check the trust of the Car mechanic without asking Bob for his advice first, this work by querying Alice own trust network on a graph server. The final trust result will depend on a calculation of the trust from Alice to Bob to the Car mechanic. Trust is subjective and therefore it should be resolved in a subjective way, this will eliminate the influence from others that are not within Alice trusted network. 

The protocol is build with decentralization in mind, however the data is not stored on a blockchain, but it leverage of the time stamp feature from a blockchain as crucial part of the system. There is no need for a blockchain because the trust issued to a person cannot be spend by that person, therefore there is no need for consensus against double spending. 

A trust is a small piece of data with a claim attached to it. It is signed by the creator using a Public/Private key algorithm. When the trust is send to a DTP Server, it will be time stamped by using a blockchain. The trust is stored on a DTP server in a graph data structure, this makes it possible to query for trust in a subjective way. The signing and timestamping will enable the DTP Server to share the trust with other 3rd party DTP Servers without the risk of the trust has been tampered with.

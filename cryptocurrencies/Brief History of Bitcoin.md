# Origins of Money (Notes)
Dawkins suggests, "money is a formal token of delayed reciprocal altruism"

The appraisal or value measurement problem is very broad. For humans it comes into play in any system of exchange – reciprocation of favors, barter, money, credit, employment, or purchase in a market. It is important in extortion, taxation, tribute, and the setting of judicial penalties
coincidence of interests(wants)

Characteristics of money: uniform value
wealth vs value
Laffer Curve
only governments could enforce anti-counterfeiting measures
low velocity money

("Fiat" means not backed by any reserve commodity, as the gold- and silver-based currencies of previous centuries were

Lydian kings Midas

Settling disputes through punishments or payments sanction by the clans of the disputing parties substituted for cycles of revenge or vendetta wars
Livestock was used in herding cultures

https://nakamotoinstitute.org/shelling-out/


# Building Blocks of Bitcoin:

## Hash Functions
fixed length output
One Way Property: computatinally infeasible to find x for given h, such that H(x) = h
collision resistance:  computatinally infeasible to find y for any x, such that if y != x, H(y) = H(x)
   computatinally infeasible to find any pair (x,y) such that H(x) = H(y)									

## Public key cryptography (Assymetric key cryptography)
Key Pair (Private,Public)
Private key is kept secret, whereas public key is shared.
sender encrypt/sign message with receipient's public key and send it to receipient.
receipient with help of secret key can decrypt/verify message on receipt. 

## Merkel Tree
Hash based tree,
used for,
  consistency verification
  data verification

## Distributed P2P Network
decentralised (No body controls network)
fault tolerant (It can work if nodes fails in network )
every node can verify authenticity of blocks and transaction
	
## POW based on Hash Cash ( Sybil Resistance )
Makes it permissionless (Any can join and leave at will)
resistance to sybill attacks (Makes hard to attack network with creation of multiple identities)
Mathemetical puzzle with no bias.
	
## Novel Consensus protcol with cryptoeconomics incentives
Every node follows rules set out in protocol,
  Assign transaction in blocks, every new block is linked with hash pointer to previous block to make it a chain of blocks with hash pointers
  A new transaction is always linked to its originating transaction (Except coinbase transaction) 	
  Fixed supply of 21 million
  Fixed schedule of new Bitcoin generation, every 10 minutes a block is generated, 
   if over a period of 2 weeks it deviates from 10 minutes, 
  protocol responds by increasing or decreasing difficulty in finding a new block.

Protocol has cryptoeconomics incentives to follow rules.
Attacks are costly and visible (Other )


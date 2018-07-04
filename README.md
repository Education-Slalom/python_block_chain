# Sample Block Chain application

this is a sample block chain application written in python

## TODO:
split out code into common segments: flask code, server start up, etc
make classes and call where relevant
step 1: start up server, will look for chain, if no chain create a new one
step 2: create new blocks as it receives transactions, block size by transactions?
block size = number of transactions in transactions pool to make block payload
transactions pool are transactions that node knows about that can be put into a block
node registration (uid?)

#### Wallet:
a signer private and public key
private key is transaction signer key
public key is the wallet CC public address
a local copy of the latest block chain
when sending a payment to receiver may not receive the funds immediately
therefore the payment will be in pending until a miner verifies the block
containing the transaction

#### Make Generic:
Strip away the crypto currency specifics so only left with block chain
of encrypted & signed data on a distributed data store platform

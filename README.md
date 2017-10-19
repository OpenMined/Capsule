# capsule
> Service for Storing And Interacting with Secrets (particularly Keys or MPC Shares) Off Blockchain

The goal of this library is to allow developers of OpenMined to simulate participating in a network where others have access to secret information that developers do not. In the trivial case, Capsule can generate a private Encryption key and never reveal it to the developer. See the [notebooks](./notebooks) folder for tutorials on how to use the library. 

## Run with Docker
Pre-requisites: python3, jupyter, docker

```sh 
docker-compose up
```
```sh 
jupyter notebook notebooks
```


## Step 1: Open Terminal and Run:

```sh 
sh build_and_run.sh
```

## Step 2: Open Terminal and Run:

```sh 
jupyter notebook
```

## Step 3: Select Notebook

In the [notebooks](./notebooks) folder, you'll find that there are several example notebooks showing how to use the Capsule. You'll find that the general setup is a server (which you started in Step 1) which holds onto secret information. From the Jupyter notebook you can interact with the server as if you were interacting with individuals on a live global network.

## Current Research

### NuCypherKMS: decentralized key management system
- https://arxiv.org/pdf/1707.06140.pdf

### ZoE: Zcash over Ethereum cross chain zk-snarks
- https://z.cash/blog/zcash-eth.html
- https://github.com/zcash/babyzoe
- https://github.com/zcash/babyzoe/blob/master/talks/2016-07-27-IC3---SNARKs-for-Ethereum.pdf
- https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/
- https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b

### Hawk: blockchain model of cryptography and privacy-preserving smart contracts
- https://eprint.iacr.org/2015/675.pdf

### Fast and Secure Linear Regression and Biometric Authentication with Security Update
- https://eprint.iacr.org/2015/692.pdf

### A Comparison of the Homomorphic Encryption Schemes: 
- https://eprint.iacr.org/2014/062.pdf

### Multi-bit homomorphic encryption based on learning with errors over rings
- https://eprint.iacr.org/2013/138.pdf

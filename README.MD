
# Indy network registry

This repository contains a registry created and governed by the Hyperledger Indy community. It aims to improve interoperability of indy networks by establishing a registry for existing Indy-based networks and providing genesis files for the corresponding ledgers. It is based on the work of the did:indy spec available [on github](https://github.com/hyperledger/indy-did-method) or in a [rendered version](https://hyperledger.github.io/indy-did-method/).


# About

### Repository structure 

To register a network, please create a pull request and adhere to the following folder structure for the genesis files:

#### did:indy:network_primary_name
```
networks/
   └──network_primary_name/
         └──pool_transactions_genesis.json
```

#### did:indy:network_name:network_secondary_name
```
networks/
   └──network_primary_name/
         └──network_secondary_name/
             └──pool_transactions_genesis.json
```

### License

This repository is licensed under an Apache 2 License. It is protected by a Developer Certificate of Origin on every commit. This means that any contributions you make must be licensed in an Apache-2-compatible way, and must be free from patent encumbrances or additional terms and conditions. By raising a PR, you certify that this is the case for your contribution.

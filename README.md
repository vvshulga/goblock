# goblock
Go package educational package, implementing blockchain functions.

## Installation
```
go get github.com/vvshulga/goblock
```

## Usage

Create Blockchain:
```
miningDificulty int8 = 2
blockchain := CreateBlockchain(miningDificulty)
```

Add block to blockchain:
```
from := "Alice"
to   := "Bob"
amount := 5
blockchain.addBlock(from, to, amount)
```

Check if blockchain is valid:
```
blockchain.isValid()
```

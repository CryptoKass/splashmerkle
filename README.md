# splashmerkle - SplashLedger:
[![GODOC](https://godoc.org/github.com/CryptoKass/splashmerkle?status.svg)](https://godoc.org/github.com/CryptoKass/splashmerkle)
*This project is part of the \*offical suite for the Splash Distributed Ledger. This repo is maintained by the Splash Foundation [http://SplashLedger.com](SplashLedger.com)*


# Getting stated:
```shell
go get github.com/CryptoKass/splashmerkle
```
If you do not have the go command on your system, you need to [Install Go](http://golang.org/doc/install) first

<br></br>
*quick start:*
```
//make a tree
tree := splashmerkle.Tree{}
tree.ConstructTree{ inputs }

//get the merkle root
merkleroot := tree.Root.leaf.Bytes()
```

<br></br>
# Documentaion:
Visit [GoDoc](https://godoc.org/github.com/CryptoKass/splashmerkle) 



# Contribution: 
**If I got something wrong (which I almost certainly have) please let me know:**
- Pull requests welcomed!
- Feedback: cryptokass@gmail.com


---

*Readme last updated: 2018.12.27*
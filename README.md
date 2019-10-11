# Code generator
This repository contains the key generator for BTC & ETH


## Building and installing
1. cd to `~/go/src/github.com/aimldevelopers/Code`
2. install required packages with `go get`
3. build the executable with `go build`
4. include the executable in `$PATH`: `sudo cp Code /usr/local/bin`

## Usage
For generating keys, run:

```bash
Code btc <page number>
Code eth <page number>
```

For searching by private key, run:
```bash
Code btc-search <btc private key>
Code eth-search <eth private key>
```

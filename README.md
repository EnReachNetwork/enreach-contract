
## Getting Started

### Compile Contracts

```sh
$ yarn
$ hh compile
```

### Deploy Contracts

#### Prepare `.env` 

With same keys to `.env-example`

```sh
$ hh run scripts/1-deploy.ts --network <mainnet/sepolia/holesky>

# Etherscan verify
$ hh clean
$ yarn verify <mainnet/sepolia/holesky>
```

### Run Test Cases

```sh
$ hh test
# To run test cases of a test file:
$ hh test ./test/xxx.ts
```

## License

Distributed under the Apache License. See [LICENSE](./LICENSE) for more information.
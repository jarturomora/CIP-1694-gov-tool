# CIP-1694-gov-tool
A MVP implementation of a CIP 1694 governance tool for managing an organisation in the CC.

### Deploy/purge local testnet
In a shell (`nix develop`) use
```bash
deploy-local-testnet
```
to launch a local testnet. The `node.sockets` are in located in `/local-testnet/example/node-spoX`, for example in
```bash
export CARDANO_NODE_SOCKET_PATH=local-testnet/example/node-spo1/node.sock
```
To purge an existing local testnet and its logs you can use
```bash
purge-local-testnet
```
which will just delete the `local-testnet/example` and `local-tesnet/logs` folder generated by the above deploy command.
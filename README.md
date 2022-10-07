# USDF Provenance Network Testnets
Testnet configurations for [USDF Provenance.io](https://usdf.provenance.io) network

validate genesis file by running:
```bash
provenanced  validate-genesis <PATH_TO_GENESIS_FILE>/genesis.json
```
start provenance with 
```bash
provenanced -t start --custom-denom=vspn --minimum-gas-prices=0vspn --msgfee-floor-price=0

```
## Active Test Networks

| Name           | Genesis Version | Software Version       | wasmd Verison | Genesis Finalized    | Network Start        |
|----------------|-----------------|------------------------|---------------|----------------------|----------------------|
| pio-usdf-testnet-1 | 1.0.0           | v1.13 (to be released) | v0.26.0       | 09-30-2022 16:20:00Z | 09-30-2022 16:20:00Z |

### pio-usdf-testnet-1

The first public testnet using the 0.46 SDK base Provenance Blockchain is focused on streamlining the process for building the public test network configuration and early beta testing of three of the 4 main Provenance modules (name, attribute, and marker).

- **Explorer** - TBD
- **Persistant Peer** - TBD
- **Seed Node** - TBD

#### `pio-usdf-testnet-1` Software Upgrades

The full upgrades list can be found at https://explorer.test.provenance.io/network/upgrades

| Upgrage Name  | Software Version | Wasm Version. | Block Height         |
|---------------|------------------|---------------|----------------------|
| Genesis       | v1.13.0-rc1      | v0.28.0       | 0                    |

## Development Networks

Development networks can be started by cloning the github.com/provenance-io/provenance repository and running the `make localnet-start` target.

<h2 align=center>Ora Protocol Node Guide</h2>

## Project Info

ORA is a verifiable oracle protocol that integrates AI and complex computations into blockchain environments. By offering richer data sources and computational capabilities, ORA expands the potential of smart contracts, enabling developers to innovate more freely

![image](https://github.com/user-attachments/assets/0c21b43f-f7b7-40d6-bc70-98afd857818c)


## System Requirements

| Component        | Minimum Requirement        | Recommended Requirement  |
|------------------|----------------------------|--------------------------|
| **Operating System** | Any OS with Docker installed | Any OS with Docker installed |
| **CPU**           | 1-core CPU                 | 1-core CPU               |
| **RAM**           | 8 GB RAM                   | 12 GB RAM                |

- If you want, you can buy from [PQ Hosting](https://pq.hosting/?from=622403&lang=en) using crypto currency

## Prerequisites

- Create a new EVM address
- Request sepolia faucet to this address
- Visit [alechemy site](https://dashboard.alchemy.com/apps) and copy the following endpoints 
1. Ethereum mainnet https endpoint 
2. Ethereum mainnet wss endpoint
3. Sepolia Ethereum https endpoint
4. Sepolia Ethereum wss endpoint

## Installation
- Use this one click command on ur terminal to run this node
```bash
[ -f "ora.sh" ] && rm ora.sh; wget -q https://raw.githubusercontent.com/dxzenith/Ora-Protocol-Node/main/ora.sh && chmod +x ora.sh && ./ora.sh
```
## Node Status

- You can check logs using this command
```bash
docker logs ora-tora -f -n 100
```
- If you see something like this, it means, it is working fine

![image](https://github.com/user-attachments/assets/d0f46d5f-159d-40a4-8cf7-21111f899a6f)

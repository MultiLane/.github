## Multilane 🖖

Multilane makes assets interoperable without tradtional bridging. 

## Problem Statement

Right now tokens on 1 chain can’t be used on another directly. If someone want’s to use their tokens on the other chain they have to bridge the tokens first and only then they can use it. Although this solution works there are couple of problem in doing this

Problems:

1. Bridging assets takes time
2. Fees are charged by the bridges every time you bridge
3. Your funds are fragmented across different chains

## Solution
User deposits their funds on 1 chain and after depositing this funds he can use this funds on any chain without bridging becuase we would be sponsoring users transaction (both ERC20 and native token).

## How to run the project?
Installation of individual components are mentioned in their respective README. Here is an overview of of the installation flow

1. Deploy Smart contracts, this will give you multilane contract address on different chains
2. Intall Dashboard abis from backend repo
3. Run landing page: This will return landing page URL. It requires dashboard app url which you will get in next step
4. Run Dashboard app: It requires landing page URL and backend url
5. Build the extension: This requires backend API.

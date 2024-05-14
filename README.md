# Testnet Tings

#### List of projects being developed on Magma to Explore and test. 

### Facuet 
* [Lava Facuet](https://www.lavafaucet.xyz/)
* [Magma Sender](https://www.magmasender.com/)

### Block Explorers
* [Blockscout](https://magmascan.org/)
* [Ethernal](https://testnet.magma.foundation/overview)

### DeFi
* [Swap]([https://website-name.com](https://magma-ui-swap.vercel.app/)
* [Swap Analytics](https://magma-info.vercel.app/#/)


### NFT
* [Magma Phunks](https://magmaphunks.eth.link/)

### Gaming

### Misc
* [Tx Subgraph](https://subgraph.testnet.magma.foundation/subgraphs/name/MagmaSwap/graphql?query=%0A%7B%0A++factories%28first%3A+5%29+%7B%0A++++id%0A++++poolCount%0A++++txCount%0A++++totalVolumeUSD%0A++%7D%0A++bundles%28first%3A+5%29+%7B%0A++++id%0A++++ethPriceUSD%0A++%7D%0A++%0A++tokens%7B%0A++++id%0A++++name%0A++%7D%0A++%0A++_meta%7B%0A++++block%7B%0A++++++number%0A++++%7D%0A++%7D%0A%7D%0A)

* [Liquidity Pool Data](https://subgraph.testnet.magma.foundation/subgraphs/name/MagmaSwap/graphql?query=%7B%0A++poolDayDatas%28first%3A+10%2C+orderBy%3A+date%2C+where%3A+%7B%0A++++pool%3A+%220x16526feb8820311af8afd15b82bc66ac5464fbc5%22%2C%0A++++date_gt%3A+1633642435%0A++%7D+%29+%7B%0A++++date%0A++++liquidity%0A++++sqrtPrice%0A++++token0Price%0A++++token1Price%0A++++volumeToken0%0A++++volumeToken1%0A++%7D%0A%7D)

* [Cross Chain Subgraph](https://bridge-api.magma.foundation/graphql)

* [Docs](https://docs.magma.foundation/)

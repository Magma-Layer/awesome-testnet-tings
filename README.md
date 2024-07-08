
<div align="center">	
    <p>	
	    <a href="https://www.magma.foundation/">	
            <div>	
		<img src="https://github.com/Magma-Layer/testnet-tings/assets/76861306/f0887e38-8233-47eb-9b2b-4d4b59bad675" width="180"  alt="Magma">	
	    </div>	
            <br>
			    <b>✨ All things Magma Testnet related, in one place ✨</b>	
	        </br>
		</a>	
	</p>	
</div>


# Awesome Ting on Magma Testnet [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


#### 🔍 Research

- [Docs](https://docs.magma.foundation/)


#### General

- [Points](https://points-web-git-main-magmafoundation.vercel.app)

#### Faucet

- [Ethernal Faucet](https://testnet.magma.foundation/faucet)
- [Lava Faucet](https://www.lavafaucet.xyz/)
- [Magma Sender](https://www.magmasender.com/)

#### Bridge

- [Native Bridge](https://bridge-testnet-magma.vercel.app/)

#### Block Explorers

- [Blockscout](https://magmascan.org/)
- [Ethernal](https://testnet.magma.foundation/overview)

#### GameFi

- [TetraSpektra](https://magma.tetraspektra.lol/)
- [Spin to Win Game](https://magmafuckingfortune.com/)
- [Dank My Meme](https://www.dankmymeme.xyz/)

#### Marketplaces

- [Volcano NFT Market](https://rubykitties.net/volcano/index.html)
- [8Bit WOKEYS NFT Marketplace](https://8bitwokeys.com/)

#### Community NFT (never share seed phrase)

- [Magma Phunks](https://magmaphunks.eth.link/)
- [Magma Frens](https://pondscan.github.io/Mint-A-Fren/)
- [Magma Mfers](https://magmamfers.art/)
- [Scandalous Birds](https://scandalousbirds.com/)
- [8Bit WOKEYS](https://8bitwokeys.com/)

#### AutoFi

- [Bot Stays On](https://bot-stays-on.vercel.app/)

#### DeFi
- [Token Launcher](https://pondscan.github.io/TokenFactory)
- [Swap](https://magma-ui-swap.vercel.app/)
- [Swap Analytics](https://magma-info.vercel.app/#/)
- [Lending (alpha)](https://magma-liquidity-aave.vercel.app/)
- [Forge](https://forge-magmafoundation.vercel.app/)
- [Erupt.Fun](https://www.erupt.fun/)
- [RandomFUDkerTestMint](https://jayratheru.github.io/RandomFUDkerTestMint/mint.html)
- [Omnisat](https://www.omnisat.io/)
- [Magmify Crowdfunding](https://magmify.xyz)

#### Governance 
- [Verifi](https://verifi.network)

#### Misc

- [Marathon Merch](https://marathonbill.store/)
- [Magmify Crowdfunding](https://magmify.xyz/)

---

## Advanced

#### Tooling

- [BedrockDB](https://bedrockdb.vercel.app/)
- [Tectonix Manager](https://tectonix-explorer.vercel.app/)

#### Misc

- [Tx Subgraph](https://subgraph.testnet.magma.foundation/subgraphs/name/MagmaSwap/graphql?query=%0A%7B%0A++factories%28first%3A+5%29+%7B%0A++++id%0A++++poolCount%0A++++txCount%0A++++totalVolumeUSD%0A++%7D%0A++bundles%28first%3A+5%29+%7B%0A++++id%0A++++ethPriceUSD%0A++%7D%0A++%0A++tokens%7B%0A++++id%0A++++name%0A++%7D%0A++%0A++_meta%7B%0A++++block%7B%0A++++++number%0A++++%7D%0A++%7D%0A%7D%0A)

- [Liquidity Pool Data](https://subgraph.testnet.magma.foundation/subgraphs/name/MagmaSwap/graphql?query=%7B%0A++poolDayDatas%28first%3A+10%2C+orderBy%3A+date%2C+where%3A+%7B%0A++++pool%3A+%220x16526feb8820311af8afd15b82bc66ac5464fbc5%22%2C%0A++++date_gt%3A+1633642435%0A++%7D+%29+%7B%0A++++date%0A++++liquidity%0A++++sqrtPrice%0A++++token0Price%0A++++token1Price%0A++++volumeToken0%0A++++volumeToken1%0A++%7D%0A%7D)

- [Cross Chain Subgraph](https://bridge-api.magma.foundation/graphql)

### Pre-compiles (Advanced)


#### Swap

- [V3Factory](https://magmascan.org/address/0x2FDD14c77eDce94D11a18fe579Da550d82A15148)
- [Multicall](https://magmascan.org/address/0x49a57760aa426B47f9f40a9763eE5d1E20fC6Aa0)
- [NonfungiblePositionManager](https://magmascan.org/address/0x3Ef2927a884d2f4ecDEe6b32073740720031a650)
- [V3Migrator](https://magmascan.org/address/0xbF5B3b84561A8F0657cB98DEE622C7FCa5c356C6)
- [QuoterV2](https://magmascan.org/address/0xf5A2F9Ea3cEf1a460A56b63Ef76E947Fb530bc33)
- [Router](https://magmascan.org/address/0x467DA5DF0012BAD24757E45ff4A245CF611c2e3C)

#### Cross Chain

- [Magma Observer](https://magmascan.org/address/0x350D0aCeE3CD6B9DB62003a9BA1C5478aD8C1CcD)
- [Ethereum Sepolia Observer](https://sepolia.etherscan.io/address/0x9abbf958F54B20ccC7fc61E590516B167BD4A078)
- [Base Sepolia Observer](https://sepolia.basescan.org/address/0x54d88899612fFB5A1f911cF9db4F7B8cc7B8A528)
- [BSC Testnet Observer](https://testnet.bscscan.com/address/0x6Cb1c81E30B6de2933c3d6EcC7EEA47a44fdEb61)

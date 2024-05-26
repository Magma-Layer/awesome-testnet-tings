
<div alig![magmasvg](https://github.com/Magma-Layer/testnet-tings/assets/76861306/7100f189-0d76-4667-9a5a-8c3e6c77612c)
n="center">	
    <p>	
	    <a href="https://www.magma.foundation/">	
            <div>	
	           <?xml version="1.0" encoding="UTF-8"?>
<svg width="292px" height="212px" viewBox="0 0 292 212" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <title>Shape</title>
    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
        <path d="M291.728202,139.854566 C288.978395,67.350337 227.593311,5.37419887 157.097935,0.455515454 C83.9345703,-5.60104521 14.0368237,49.4424032 2.17316733,123.60437 C1.74273182,128.25767 0.369606968,132.474723 0.540358245,137.128023 C-0.0608285418,145.925668 -1.0070752,155.304976 3.11941398,163.484605 C20.2265575,195.185211 65.9665557,203.255778 98.1175982,208.418032 C121.247282,211.835299 134.658371,212.998624 168.015345,211.071867 C207.391301,208.781571 270.234885,200.092988 288.2029,164.975115 C290.69658,159.958276 292.759824,151.633232 291.728202,139.854566 Z M258.029436,145.701226 C239.569075,176.037824 179.876292,176.839031 148.734249,173.852715 C121.821813,171.303421 94.1312723,167.22455 81.7958109,145.446296 C79.8112864,141.03966 79.7256235,135.576887 80.3288332,130.915321 C81.1069382,110.342519 89.7303394,90.2905006 103.27579,75.1659037 C119.148416,56.8728987 142.784245,46.2314173 166.5914,45.0878769 C206.185519,43.2414597 244.915869,70.6791464 255.873585,109.727046 C258.803971,119.297824 262.255473,136.560186 258.029436,145.701226 Z" id="Shape" fill="#EA462C"></path>
    </g>
</svg>
		    </div>	
            <br>
			    <b>✨ All things Magma Testnet related, in one place ✨</b>	
	        </br>
		</a>	
	</p>	
</div>


List of projects being developed on Magma to Explore and test.

[Docs](https://docs.magma.foundation/)

---

#### General

- [Points](https://points-web-git-main-magmafoundation.vercel.app)

#### Faucet

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
- [The Pump OTC](https://pump-otc.vercel.app/)
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

- [V3Factory](https://magmascan.org/address/0x8ddfB8944b498CBeE4D91aa86F850b4642C126F6)
- [Multicall](https://magmascan.org/address/0x5e74D928CC499D3d2544B0286e392539739D4c60)
- [NonfungiblePositionManager](https://magmascan.org/address/0x1D5f352e15D0eCD04811b8aD69c100651a4BdB4C)
- [V3Migrator](https://magmascan.org/address/0x423D34F72121bD5AB7A82C150d2269a2950F7803)
- [QuoterV2](https://magmascan.org/address/0xd302fA2D75F1DD90022de324976723de8CC466b5)

#### Cross Chain

- [Magma Observer](https://magmascan.org/address/0x350D0aCeE3CD6B9DB62003a9BA1C5478aD8C1CcD)
- [Ethereum Sepolia Observer](https://sepolia.etherscan.io/address/0x9abbf958F54B20ccC7fc61E590516B167BD4A078)
- [Base Sepolia Observer](https://sepolia.basescan.org/address/0x54d88899612fFB5A1f911cF9db4F7B8cc7B8A528)
- [BSC Testnet Observer](https://testnet.bscscan.com/address/0x6Cb1c81E30B6de2933c3d6EcC7EEA47a44fdEb61)

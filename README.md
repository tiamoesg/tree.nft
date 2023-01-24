# RWAdrops + Frameworks
The home of RWAdrops and the Tree.NFT framework.

# Tree.NFT Framework
1. A public good NFT framework for turning trees into RWAs. 
2. To allow regenerative finance to move forward into its next stage of IRL implementation.
3. To create easily scalable decentralized projects of conservation, reforestation, and production.

# Current Development
1. Next.JS storefront for launching RWAs to the public via fiat on-ramps. Link to temp CMV3 UI >> [First Test - CM Error](https://trees-nft.vercel.app/) |  [Code](https://github.com/tiamoesg/trees.NFT/tree/main/pages) -- and here is where our future development will start with Next.JS [Ground Up Build](https://github.com/tiamoesg/RWAdrops.store)
2. Tree.NFTv01 Structure + Attribute Development [Current Structure Example](https://github.com/tiamoesg/trees.NFT/blob/main/tree-nft.json) 

# Candy machine setup
1. Download sugar's latest [build](https://github.com/metaplex-foundation/sugar/tree/alpha+CMv3)
2. Create a candy machine with the tokenPayment guard. Set the mint to the token mint address and the destination ata to the account of your treasury wallet which will hold the token.
3. Deploy the CM and add the guard. Copy the CM address.

# Web app setup
1. ```yarn``` and then ```yarn dev```
2. edit the env to add your CM and the image you want displayed on the site.
3. To change the minting animation, create your own gif of your images.

Shoutout to @urbentom for the original skeleton.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

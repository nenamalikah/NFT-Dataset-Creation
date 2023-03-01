# Web Scraping Project: Top NFT Collections

## About NFT's
NFT stands for "non-fungible token." They are unique, digital assets that are non-interchangeable and bought and sold online. According to Forbes:

> An NFT is a digital asset that represents real-world objects like art, music, in-game items and videos. They are bought and sold online, frequently with cryptocurrency, and they are generally encoded with the same underlying software as many cryptos. Although they’ve been around since 2014, NFTs are gaining notoriety now because they are becoming an increasingly popular way to buy and sell digital artwork. A staggering $174 million has been spent on NFTs since November 2017.

## Dataset Information
This dataset was created via Python using the requests, json, and pandas libraries. The information was pulled on January 16, 2022, and represents all time information for the top NFT collections. As an example, the Sales column represents all sales under a specified NFT collection from its creation up until January 16, 2022.

The dataset consists of the following information:

- Index: The index of the file.
- Name: The name of the NFT collection.
- Volume: The volume of sales from the NFT collection in Solana (SOL).
- Volume_USD: The volume of sales from the NFT collection in United States Dollar (USD).
- Market_Cap: The market capitalization—total value of the collection's items in circulation—in Solana (SOL).
- Market_Cap_USD: The market capitalization—total value of the collection's items in circulation—in United States Dollar (USD).
- Sales: The number of sales from the NFT collection.
- Floor_Price: The lowest price of any NFT in the collection in Solana (SOL).
- Floor_Price_USD: The lowest price of any NFT in the collection in United States Dollar (USD).
- Average_Price: The average price of an NFT in the collection in Solana (SOL).
- Average_Price_USD: The average price of an NFT in the collection in United States Dollar (USD).
- Owners: The number of owners of NFT's in the collection.
- Assets: The number of items in the collection.
- Owner_Asset_Ratio: The ownership percentage of all items in the collection.
- Category: The category of the NFT collection.
- Website: The associated website of the NFT collection.
- Logo: The associated image of the NFT collection.

**Sources:**<br>
This data was scraped from https://coinmarketcap.com/nft/collections/

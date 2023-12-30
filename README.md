![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

# layered-nft-builder
Python script to build as many nfts as you want, where each nft is unique, also creates a metadata in json per nft.
Generates rarity + rarity percentage, calculates which nft is the most rare and then writes that to a csv file, this way you can post that on your website after the mint for example.
For now this is for SOL only, but I am coding this into a GUI, and I will have drop down menues for what chain which then subprocess triggers the correct chain.py file as splitting it up compared to going for just functions to call is much more clean (IMO).

#Crypto icons

## Why?
In presentation layer, I allow for only 3-7 main cryptocurrencies and their fiat versions. Whlist wallet addresses are Layer 1, for the purpose of presentation, the webserver needs to inspect the connector and determine the preferred units and report information back to the visual inspector. 

## How ...
1. Check out the [CryptoLogos](https://cryptologos.cc/) to see if the SVG version is available (+1 [ TBA])
2. Alternative browse through the [vue-cryptoIcon](https://github.com/man15h/vue-cryptoicon] and size the image to fit
3. There's a few other crypto image [repositories](https://github.com/search?q=crypto+logo) but you need the black and white versions
4. Merge with the default EyeView and make sure that the edges have sufficient border for visual separation
5. Currently the core verson supports {B&W for basic, 4 tones x 4 tints for dual-licensed} [ TBD tools for color matching]

## Licensing 
* Some well-known tokens have a brandhandbook but make sure that actual imagery is [public domain](https://creativecommons.org/share-your-work/public-domain/ or at worst [non-derivative](Attribution-NoDerivs CC BY-ND) since IMHO that falls under incidental use copyright exempton (when browsing through payment options).
* At some point in future, will commission a special font for the most useful and refactor to be Unicode compliant
* When the R&DD is finished, expect a complete github package

## Objections
Create a pull request to [@drllau](https://github.com/drllau) but keep in mind the data jurisdiction:
* De jure ownership is New Zealand  which doesn't have [software patents](https://www.iponz.govt.nz/about-ip/patents/examination-manual/current/computer-programs/) so anything fancy encoded in SVG or PDF without hardware connection or realworld problem
* the package will be licensed under framework of Regional Comprehensive Economic Partnership ([RCEP](https://www.mfat.govt.nz/en/trade/free-trade-agreements/agreements-under-negotiation/regional-comprehensive-economic-partnership-rcep/)]
* There is a Treaty of Waitangi exemption accepted by all the other parties (China, India, ASEAN, etc) for privacy purposes
* And if you're trying what I consider an economic tort, then I suggest you look at China's Anti-competition law
* Otherwise I can accept valid arguments on trade dress violation grounds (look & feel) of UI/UX/UD

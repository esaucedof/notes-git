- # [Official Site](https://www.arweave.org/)
- #Mail
	- [Weve](https://wevemail.arweave.de)
-
- Extracted from a [mem](https://mem.ai/p/qTe0z28zDAJi5mx3W8WI) of [Mem.ai](https://mem.ai).
- ## Arweave will never use a fee market for storage
	- All credits:
	- ```
	  Williams, S. [@samecwilliams]. (2023, February 02). Arweave will never use a fee market for storage. [Tweet]. Twitter. https://twitter.com/samecwilliams/status/1621341318021521409
	  ```
	- **🪄Smart summary:**
	  The thread explains how Arweave's storage system works and why it doesn't need a fee market. It also discusses how the system can scale to handle a large amount of data.
	  -------
	- ```
	  Arweave will never use a fee market for storage.
	  This will be an incredible boon for adoption over time, but surprisingly few realize this so far.
	  
	  Here's how it works: Deep tech 🐘🧵👇
	  
	  First, to understand why Arweave's permanent storage scales we need to understand why contract-based storage does not.
	  
	  Individual data items on contract-based systems need to be committed with qualifying information: how long the storage term is, who should store the data, how many replicas, etc.
	  The effect of this is that each commitment needs to be adjudicated separately -- just like smart contracts.
	  
	  You can gain an intuition for how poorly this scales by considering the following:
	  Ethereum and the other smart contract systems have had trouble scaling so far when they are normally only adjudicating one smart contract per app.
	  
	  How many files are generally used in a single app? Thousands to millions on average.
	  
	  Ouch.
	  
	  Arweave works differently.
	  
	  Instead of trying to adjudicate millions/billions of contracts, Arweave has just one: the endowment.
	  
	  The endowment is a single reward pool and a single merkle root of an enormous pile of data.
	  
	  Adding data to the system updates the merkle tree and adds tokens to the reward pool, but leads to no increase in 'bloat' or increased computation in maintaining the chain.
	  
	  But what do we do about the bottleneck of processing payments for adding data? After all, Arweave is still structured similarly to a Blockchain so cannot process unlimited payments simultaneously.
	  
	  In order to solve this, we employ a system of recursive bundles.
	  
	  Because all data in Arweave is permanently stored, my data is the same as yours, and everyone else's.
	  
	  This means that we can 'bundle' your data with my data, settling it together in one payment transaction on the Arweave network.
	  
	  A number of services now exist to perform this bundling service, for example @everVisionHQ and @BundlrNetwork.
	  
	  Presently, they upload ~3m pieces of data per day across just a few thousand Arweave payment transactions.
	  
	  Eventually, when Arweave reaches the scale of the centralized web, there will be more bundles being submitted than there are 'slots' in Arweave blocks.
	  
	  What do we do then?
	  
	  We bundle the bundles!
	  
	  This essentially leads to trees of infinite depth of data that is committed to the network in a single Arweave transaction.
	  
	  There is no reason that this system could not ingest all of the web's data inside a single Arweave transaction.
	  
	  No fee markets, forever, thanks to trees of data of infinite depth.
	  
	  But I hear someone in the comments shout: 'but fee markets are good for networks!'
	  
	  No. Having market fit is good for networks.
	  
	  Using a fee market to limit the number of people that can use your protocol will inevitably just push people to more scalable competitors, while limiting network growth effects.
	  
	  Thanks for reading!
	  
	  If you liked this post you might enjoy @TheArWiki: A permaweb app that houses all of our community's knowledge, on Arweave itself.
	  
	  For example, here is an interesting post about simulating Arweave's endowment 👇
	  [https://t.co/h7ISRSGJuZ](https://t.co/h7ISRSGJuZ)
	  
	  You may also be interested in applying to @fwdresearch !
	  ```
	-
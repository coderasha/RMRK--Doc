# RMRK--Doc
Documentation Regarding RMRK

_ Its a protocol or its a set of rules and specifications for how to interpret special messages submitted to the blockchain.
Its dedicated to establishing a standard NFT cross-chain infrastructure on the Kusama and Polkadot ecosystems. RMRK introduces the ‘system remark’ function, allowing users to create their own NFTs.

**The mechanics of RMRK.app**

Kusama chain cannot harbor NFTs. Unlike Ethereum, Kusama lacks smart contracts on the chain. With RMRK.app users can now attach information alongside a block. NFTs on RMRK.app are divided into collections. A perfect example of a collection is Kanaria, the first collection where hatching eggs reveal birds.

**NFT Features** 

Nested NFTs#
NFTs that can own other NFTs, and NFTs that can equip other NFTs to change their output media. As an example, imagine an in-game character who owns a backpack which in turn owns some health potions. The character can also own and equip another NFT, a helmet.

This logic is available on RMRK 2 and above.

On-chain emotes#
On-chain reactions, like you would expect when opening an emoji keyboard, sent to any NFT. Any UI implementing this specification is able to show the full range of recieved emotes, allowing for social mechanics and relative price discovery across NFTs.

This logic has been available since RMRK 1.

Multi-resource NFTs#
NFTs are able to have different outputs which can also depend on context. As an example, an ebook can have a PDF resource, a cover resource, and an audio file resource. If you load it into Audible, it can automatically play. If you load it into Kindle, it will open in reading mode. If you load it into an NFT environment which is limited in functionality, like one on Ethereum, you get the default view - a cover image.

This has other uses, too: an NFT that is purely an image can use multiple resources as a redundancy for assets. One resource can be the image on HTTP, then the same image on IPFS, then the same image on Arweave. By having this redundancy on the NFT level, the NFT is guaranteed to remain viewable much longer than traditional NFTs.

Another example comes into play when you consider an NFT with multiple images representing the same concept. For example, an attendance badge or a company logo can evolve over time by getting a new resource after the fact. The owner of the NFT is able, at any time, to switch priority of display on the resources, so they can make the current logo default.

An example of a multi-resource NFT is the Meme God Crown, or these Khala glasses. Inspecting either will reveal that they have two versions - a richly illustrated one, and one that's modeled to be equippable on the Kanaria birds. This is how standalone NFTs are made equippable by any project into the future, without knowing what's coming up and planning for it.

This logic has been available since RMRK 2.

Conditional rendering#
Conditional rendering is the ability to apply certain conditions to an NFT's output.

As an example, if we put the "On-chain emotes" and "Multi-resource NFTs" legos together, we can imagine an image of a Mona Lisa with two resource: normal Mona Lisa, and blushing Mona Lisa. We can then define a rule that says "if this NFT gets more than 50 😘 emoji, show the blushing Mona Lisa resource as a priority". Another example is, "If this NFT gets 100 ❄ emoji, change the background element from beach to snow".

Conditional rendering is becoming available with RMRK 2.1 and uses JsonLogic.

NFTs as DAOs#
NFTs on RMRK can be tokenized into fungible tokens. These tokens can then be used to govern the NFT's functions. For example, a democratic decision to make an NFT avatar equip one sword over another, or a collaborative decision making process on a collective musical composition NFT where votes are taken on where to place each note, layer, and instrument. These tokens can then be used to distribute royalties from sales proportionally.

NFTs as DAO will become available with RMRK 3 and the transition to pallets and smart contracts.

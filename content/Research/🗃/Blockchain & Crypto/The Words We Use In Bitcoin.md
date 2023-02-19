tags: #🗃/🟥 
aliases: 
ref: https://dergigi.com/2022/06/27/the-words-we-use-in-bitcoin/?utm_source=pocket_reader

---

# Part 1: The Language Used In Bitcoin
- “All metaphors are wrong, but some are useful,” to paraphrase George Box. Undoubtedly, many people are confused precisely because of the shortcomings of these metaphors. All the labels that we apply to the various concepts in Bitcoin are wrong, at least a little bit. Some are wrong a lot.
- Unfortunately, this confusion won’t be going away anytime soon. And more worryingly, this confusion is being weaponized by legislators, politicians, and commentators alike. Those who despise Bitcoin are trying to pass laws and plant ideas in people’s heads that are bastardizing how Bitcoin works, as well as the language we use to describe how it works. Consequently, it would be beneficial to get our language straight.

Wallet:
- A wallet is a piece of software or hardware that makes it easier or more secure to store and/or spend your bitcoin.
- Here is the gist of it: to create a bitcoin transaction, you need to sign a message with a private key. Consequently, two things are essential for a wallet: key storage and signing.
- What we have historically called a bitcoin wallet, thus, is just some software that manages and stores keys and allows the user to easily use these keys to sign and broadcast messages.
- Given that a hardware wallet is nothing but a small device that is used for signing transactions, a more accurate term is “[signing device](https://signingdevice.com/),” which is currently gaining traction thanks to people who understand the technicalities of Bitcoin deeply.
- In the end, the “wallet” metaphor will always be wrong in a crucial way: your wallet does not actually hold any of your coins. That’s not how Bitcoin works. It might hold your keys, which brings us to the next word.

Key:
- To create a bitcoin transaction, you use your private key to sign a message. The keys in bitcoin are cryptographic keys, and cryptographic keys can be used to create digital signatures.
- Consequently, a “key” in bitcoin is more like a pen, not an actual key.
- To make theft or accidental spending as difficult as possible, keys that give access to large funds are held in “cold” storage. The secret information is disconnected from the internet, held on special signing devices that never touch a general computation device.
- A “hot wallet,” on the other hand, brings the secret information required to move your sats as close to the network as possible. If you want to spend frequently, your keys have to be readily available.
- The “key” metaphor, for example, isn’t terribly wrong. We can actually think of signing as unlocking. The underlying elements responsible for spending sats are referred to as [locking and unlocking scripts](https://learnmeabitcoin.com/beginners/output_locks), and for good reason. These scripts are small computer programs that define the conditions that are required for certain sets of sats to move. You can think of it like this: those who want to move sats have to solve a cryptographic puzzle. Usually, a private key is required to fulfill the spending condition: the key is the key to the puzzle. So if we think “key to the puzzle,” it’s not even wrong.
- Two more things: the reason why your private key can be represented as words is that it is, just like everything else in bitcoin, information. And the reason why we call these words a “seed phrase” is because your private key is the seed from which all your other keys and, ultimately, addresses are derived from.

Address:
- Because bitcoin transactions do not have a “from address,” even though you might think they do, especially if your mind is poisoned with the “address” metaphor.
- In Bitcoin, only receiving addresses exist. A transaction does not contain a from address. A transaction only contains the aforementioned scripts, which are challenges and solutions to challenges. If you can solve the challenge, you can move the coins.
- You can understand Bitcoin and bitcoin transactions in a similar way: transactions can have multiple inputs and multiple outputs, i.e., inflows and outflows, to stick with the liquid metaphor. However, there is one important difference: there are no molecules in bitcoin; there is only accounting.
- There are no molecules in bitcoin because every transaction “destroys” all inputs and creates new outputs. If you are dead-set on thinking about coins, you can think about every transaction as a smelting process. All inputs are liquified in a big furnace, and new coins are created as outputs.

Coins:
- What we call “coins” only exist by convention. The protocol is oblivious to our notion of coins. It only knows sats and spent or unspent transaction outputs. Spent outputs are inputs of past transactions. If the sum of one or multiple outputs adds up to 100 million sats, we call it “one bitcoin.”
- Bitcoin is information, not a physical thing. It is teleported at the speed of light, not moved in any physical sense. It is [Magic Internet Money](https://21-ways.com/3/) for a reason, and I’m afraid that we all have to understand its [inner workings](https://21-ways.com/ch0-04-building-blocks/) to a certain degree, especially if we want to be properly equipped to fight against any and all linguistic attacks, present and future.

# Part 2: The Language Used To Attack Bitcoin
- Money is adversarial by nature because money is used between parties that aren’t fully trusting each other in the first place. Consequently, a monetary system is an adversarial system.
- Viewed in this light—that Bitcoin is made up of [ideas, people, code, and nodes](https://dergigi.com/2019/05/01/bitcoins-gravity/#loop)—it is easy to see that some attacks would be more obvious than others.
- An obvious attack would be a software exploit that shuts down a large number of bitcoin nodes, for example. An even more obvious one would be a large-scale attack on its physical infrastructure.
- But: how do you attack an idea? With bad ideas, that’s how.

“Unhosted Wallet”:
- Bitcoin wallets are supposed to be unhosted—or, to use a word that wasn’t made up by devilish puppeteers: _independent_. The purpose of Bitcoin is to bring full sovereignty to the individual and to remove all dependencies on trusted third parties. No rulers, no masters, no hosts. Only peers.
- Instead of using the term “unhosted wallet,” one could refer to regular bitcoin wallets as independent or freedom wallets. The opposite of an independent wallet is a custodial service, which means that you have a permission slip, nothing more. By using a custodial service, you destroy what makes bitcoin valuable in the first place. You revert to the permissioned model of money: a debt relationship between masters and slaves, which is the fiat system we want to move away from. Some have all the power; the users have none.
- Such a custodial service, a service that they want you to refer to as a “hosted wallet”—but what might be better described as a slave wallet—offers nothing but IOUs: permission slips & debt certificates that can be revoked, multiplied, re-issued, and destroyed at any time. The slave has nothing; the master has everything.
- Make no mistake: this is a war of narratives, and the stakes couldn’t be higher. Freedom vs. dependency, control vs. self-ownership, reliance vs. responsibility. If anything, a wallet should be self-hosted, and self-hosting is not a crime. However, we shouldn’t think of “hosts” in the first place. A wallet does not need to be hosted because a wallet, as we’ve seen previously, is nothing but a key—private information—combined with hardware or software that allows you to do something with said key, e.g., derive addresses or sign transactions.
- Having 12 words in your head doesn’t make you the owner of an unhosted brain wallet; that’s ridiculous. You don’t need permission to remember 12 words by heart, and any law that makes the act of remembering 12 words illegal is a very, very, (very!) stupid law.
- Letting someone else hold your keys destroys all the benefits that bitcoin brings with it. If others could be trusted with our money, we wouldn’t have needed Bitcoin in the first place. And if nobody takes the responsibility of self-custody, Bitcoin will be captured, just like gold before it.
- Consequently, the term “unhosted wallet” is an attack on Bitcoin that we should take seriously, along with the [implications](https://dergigi.com/2021/08/02/implications-of-outlawing-bitcoin/) that a successful ban would entail. It is a most ingenious and mischievous attack—subtle yet effective, re-framing what a wallet is and should be.

ChangeTheCode:
- Bitcoin, however, is neither slow nor wasteful. Proof-of-work is insanely efficient if your goal is to create a monetary system that is free from politics and secured in a public and transparent manner. If you do not value such a system, it will always seem wasteful.

"Proof of Stake":
- Proof-of-work solved the problem of [telling time](https://dergigi.com/2021/01/14/bitcoin-is-time/) in a decentralized system, the problem of random selection, the problem of fair issuance, and the problem of unforgeable costliness in the digital realm. It embeds [objective truth](https://dergigi.com/2022/04/03/inalienable-property-rights/#reify) into a blob of data directly, which is why it is trustless and reliable. The information “speaks for itself,” to quote Satoshi.
- Proof-of-stake, on the other hand, has no objective truth, no objective time, no random selection, no fair issuance, no outside cost, no operational cost, and centralizes over time. It is the perpetual motion machine of consensus mechanisms, which is to say that it isn’t a consensus mechanism at all. It is rotten at its core because it relies on trust through and through.

# Conclusion
- Bitcoin is about freedom and self-sovereignty, not about asking for permission. It is about independence and verifiable truth; extreme ownership and responsibility; hope and human rights.
- The best way to fight bad ideas and bad terminology is with good ideas and good terminology. Thus, we should all make an effort to call things by their proper names, try to understand their inner workings, and explain them in simple terms to others.
- Bitcoin is a return to sanity, one that is desperately needed in the insane world of QE infinity and negative interest rates. The tragicomedy of our current financial system reads like the introduction to a game show: “Whose deficit is it anyway? An economy where everything is made up and the points don’t matter.”
- The points in Bitcoin _do_ matter, as do the words that we use to describe it. Bitcoin is truthful and precise in its [speech](https://dergigi.com/speech), and we should strive to be too.
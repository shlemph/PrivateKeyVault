### Contents
[What's In It For You?](https://github.com/johnshearing/PrivateKeyVault/tree/master/Motivation#whats-in-it-for-you)  
[What's In It For Me?](https://github.com/johnshearing/PrivateKeyVault/tree/master/Motivation#whats-in-it-for-me)  
[What's In It For Us?](https://github.com/johnshearing/PrivateKeyVault/tree/master/Motivation#whats-in-it-for-us)  
[What 2 Big Problems Does The PrivateKeyVault Solve That Hardware Wallets Cannot](https://github.com/johnshearing/PrivateKeyVault/blob/master/Motivation/README.md#what-2-big-problems-does-the-privatekeyvault-solve-that-hardware-wallets-cannot)  
[Crypto-Journalism:](https://github.com/johnshearing/PrivateKeyVault/blob/master/Motivation/README.md#crypto-journalism)  
[Added Value For People In Developing Countries](https://github.com/johnshearing/PrivateKeyVault/blob/master/Motivation/README.md#added-value-for-people-in-developing-countries)  

### What's In It For You?  
If you have cryptocurrency then you will need a secure way to manage it.  
Surely you want the value of your cryptocurrency to go up.  
If everyone perceives cryptocurrency is safe then they will buy it.  
That will make the value of your cryptocurrency go up.  **Way Up**  
Let's show everyone how to keep their cryptocurrency safe.  

### What's In It For Me?  
Buy giving away my work on the PrivateKeyVault I can bring about universal adoption of cryptocurrency by making it secure.  
That will make the cryptocurrency I own to rise in value.  
That makes us partners.  

### What's In It For Us?  
Authoritarian rule, Civil war, Terrorism, and Mass migration of refugees are the problems that mass adoption of blockchain technology will solve. Unlike normal money, cryptocurrency does not reside in any particular country and is not controlled by any government. So if someone with cryptocurrency leaves one country for another, their money is already there waiting for them as long as they have their private key. These people are not refugees, rather they are welcome visitors. But if someone with regular money needs to leave their country, the money stays. These people are not welcome visitors, rather they are refugees and burden to other countries. So turning people into refugees is profitable for dictators and terrorists while it weakens the free countries where refugees go. Imagine if refugees could take their money with them. The loss of funds created by people leaving would cause oppressive regimes and terrorist states to collapse. For the rest, market forces would cause governments to change even before they become very bad.  

This stabilizing effect of cryptocurrency on governments can only work if everybody is using it but until people are satisfied that there is a safe way to store private keys, cryptocurrency will not become main stream.  

**Now we have a safe way to store cryptocurrency that is accessible to everyone with electricity and an Internet connection.**  
Let's get rid of dictators and terrorist.  
Let's eradicate civil war.  
Let's give every human being planet wide access to their money.  
Let's turn every human being into a welcome visitor so that they will never need to flee their own countries.  
Let's show everyone how to make and use [The PrivateKeyVault](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions)

### How else can blockchains help stabilize our world?  
Blockchains are lists that can be used to record land ownership as easily as they are used to track money.  
But these lists ca not be destroyed.  

Currently, after dictators and terrorist chase people off their lands they immediately destroy all the countries records of land ownership. This makes it extremely difficult for refugees to regain ownership or even make a claim in international courts. Knowing that refugees have little chance proving ownership of their land makes ethnic cleansing an attractive proposition for authoritarian regimes. Getting official records of land ownership onto a blockchain will have a dramatic stabilizing effect on countries where civil war is likely to break out or where ethnic cleansing is likely to occur.  

The key to getting government records onto blockchains is making blockchains the easiest, most widely available, and most secure instrument for the task.  

Sounds like a job for the raspberry pi:  
* Easy to use: It was made for teaching children.  
* Widely available all over the planet for practically nothing.  
* Super secure if set up with LUKS full disk encryption according to [the instructions here](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions).

Let's teach everyone how they can use the raspberry pi to take control of their own assets.  
This is what the [PrivateKeyVault GitHub repository](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions) is for.  

### What 2 Big Problems Does The PrivateKeyVault Solve That Hardware Wallets Cannot.    
**First Big Problem Solved**  
**The Nano Ledger hardware wallet and similar devices cannot be used by governments, corporations, and financial institutions where a large number of accounts must be managed**  
While the nano does allow for multiple public addresses, they are all tied to a master private key. So if the pass phrase is compromised then all the accounts are accessible. Furthermore multiple accounts are very hard to manage with only two buttons on the nano.  
[Click here to find out more about these limitations](https://www.reddit.com/r/ethereumnoobies/comments/7hebj8/ledger_nano_s_multiple_eth_wallets/)  
How can we expect organizations, governments, corporations, and financial institutions to use blockchain technology when there is no widely available method to securely manage multiple accounts. 

The PrivateKeyVault is meant to clear this bottleneck and make blockchain technology accessable to organizations, governments, corporations and financial institutions. Getting these entities on a public blockchain using the PrivateKeyVault is how we will make them transparent and accountable.  

Remember, the [PrivateKeyVault](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions) is not a thing that someone is selling. It is rather a way of working that is freely accessible to anyone with electricity and an Internet connection. If we work together we can get everyone onto a public blockchain by sharing the [PrivateKeyVault GitHub repository](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions). 

**Second Big Problem Solved**  
**Private Keys Generated by Hardware Wallets are a Central Point of Attack**  
The Nano Ledger and other similar devices use a pseudo random algorithm to generate private keys.  
So if some [individual or government were to put a back door](https://www.wired.com/story/encryption-backdoors-shadow-brokers-vault-7-wannacry/) into the algorithm then everyone loses individual control of their accounts all at the same time. Avoiding this kind of disaster is the whole point of decentralization using blockchains. Individuals must have the right to generate their own private keys using a method known to be completely random. The private key is how an account is controlled. How can we hand this control over to any single entity?  

Flipping a coin is the method I use. It is just one of many fully decentralized methods of generating a private key which is sure to be truly random. It works like this: Let heads represent a one and tails represent a zero. Four flips will produce one hexadecimal character of the key by converting binary to hexadecimal.  
* Four tails in a row would be a zero  
* Heads, heads, tails, tails would be a three.  
* Heads, heads, heads, head, would be an "F"  
* You get the idea.  

No government or individual can put a back door into this method, nor can anyone ever guess your private key. An oppressive government or an attacker might still be able force you to hand it over, but he, she, or it would never be able to guess the key using a dictionary attack nor by guessing personal information about you.  
Only a decentralized and truely random method of generating a private key should be used for large amounts of money and the Nano Ledger does not permit you to generate your own private key using a method known to be truly random. The Nano Ledger and other devices which use a pseudo random algorithm to generate private keys are a central point of attack.  

The PrivateKeyVault allows individuals to select any hexadecimal number as a private key which decentralizes the most important aspect of any blockchain.  

### Crypto-Journalism  
Now anything can be faked on the Internet. Anyone can now access computer programs which can fabricate videos featuring world leaders saying things they never actually said. False news stories appear on facebook and twitter all the time which are circulated by foreign governments to cause confusion, to shatter the common will of a nation, and to insert puppet leaders into office. When a nation's people no longer know what's real they can be manipulated to do anything. Free nations are at serious risk of losing their democracies as more and more people are fooled with social media into handing over their free will to authoritarian leaders. There is a defense against fake news (Digitally Signed Documents). These are videos and written news articles which have been encrypted using the private key of a trusted source such as a news caster or political leader. The reader decrypts these files using the news source's public key. If the documents are legible after decryption then the reader can be certain that the document is indeed from the trusted source and that it has not been changed. The public must become familiar with use of digitally signed documents if we are to avoid the collective insanity which will precede the destruction of our democracies through state manipulation of social media.  

With a PrivateKeyVault (really just a raspberry pi) you can read, write, and distribute digitally signed documents.  
Now anyone can safely create a journalistic body of work and prove that they authored the entire work and that it has not been tampered with all while allowing the author to remain anonymous if he or she so chooses.  

That's what the [PrivateKeyVault GitHub repository](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions) is for.  

### Added Value For People In Developing Countries  
While many people in developing countries have the phones required to access the Internet, not so many have the computers necessary to make the most of it. The PrivateKeyVault is the cheapest computer you can have and it does double duty as a regular Internet connected computer simply by swapping out the encrypted SD card containing private information with another one set up for business, education, browsing, and casual use.  
Now, not only can everyone with Internet reach the blockchain - Finally they can learn to use it.  
The raspberry pi is a community for getting people on computers.  
The PrivateKeyVault is a community for getting people on blockchains.  

[The PrivateKeyVault GitHub repository](https://github.com/johnshearing/PrivateKeyVault#privatekeyvault---click-for-open-source-make-instructions)   


    
    

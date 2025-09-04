# Baby's First Transaction

Let's transfer some money! 

**Step #1:** Kraken/CashApp -> Edge Wallet

Since the BTC you now have in Kraken or CashApp isn't really yours fully, let's transfer that to your Edge Wallet. 

1. Add a BTC wallet to your Edge Wallet. 
[TODO: Screenshot]
1. Find the address of your BTC Edge Wallet. 
[TODO: Screenshot]
1. In Kraken/CashApp start to make a transaction to send ALL of your new BTC into Edge Wallet. It will ask for the receiver address, the address to your new Edge Wallet. 
[TODO: Screenshot]
1. Sign and Send. 
1. You will see a transaction ID, save that ID for the moment. Mine looks like this: 
- Sample ID: 98743565658793425768552345897768

[TODO: Actually do this transaction and get an ID to work with.] 

>**Patience, Oh Patience.** Crypto transactions take ~10min to go through. Have patience. An ACH transfer can take up to 3 days, you can wait 10minutes. 

So how do we know it went through? We should be able to see the money arrive in our Edge Wallet. But how else can we check that a transaction went through? That it didn't get catch up in the digital ethos and disappear. Block explorers! 

Recall we talked about open and opaque ledger in [Module 2: Public + Private Blockchains](../module-2-blockchain/2.1-main-article.md#public-vs-private-blockchains). Bitcoin and the transaction you just completed was on the open ledger, meaning it's open to the internet. Let's go take a look. Block explorers are ways we be do investigative work on the blockchain. 

[Block Explorer](https://blockexplorer.one/)

[TODO: Insert a screenshot of block exploer to see the transaction go through]

Clearly, you can see both the sender and receiver addresses plus the amount transferred. If the connection between address and legal ID is separate, we might call it pseudonymous. However if the address is publicly known, everyone and their block exploring grandma can see the whole situation. Consider you used your legal ID to KYC on Kraken or CashApp, they know your name, address, birthday, maybe other financial details...plus your entire transaction history.

> What you do on the open the blockchain lives forever. Grandma is watching. She may not judge, but she does watch.

Don't worry too much, we will talk about opaque ledgers and real privacy soon!

**Step #2:** Edge Wallet -> Another User

Now you have $200 (or more) on your Edge wallet, in BTC. Now let's say...you are absolutely enjoying this class and want to pay it forward. They say at Christmas time, it's better to give, than to receive.

Consider, [Tech Learning Collective](https://techlearningcollective.com/) graciously accepts in-kind donations in any amount in support of our work offering unparalleled free, by-donation, and low-cost computer classes to people of marginalized groups and individuals in need. Your donation helps ensure they can continue developing best-in-class educational material on topics ranging from fundamental computer literacy to information and digital security, network engineering, system administration, cryptocurrency, and more.

[TLC Donation Link](https://techlearningcollective.com/donate/)

Here we can see TLC's BTC donation address: 
```
bc1qtchd79gu5t05j7gw8hh7p4gks8ajh7zd7azx0c
```
> **Note** Since we know the connect of organization and address, we can use a block explorer to see all donations and expenses in and out of this account.  

With good 'ol Saint Nick (and my grandma) watching your BTC account, send along a $50 (or more) donation to TLC. Learning any new skills takes time, energy, and repitition. From Edge Wallet, send a transaction to the address above. 

[TODO: Insert screenshot of sending a transaction to TLC's donation link.]

Bonus Activity: Check the [Block Explorer](https://blockexplorer.one/) to see the money get sent.

**Check in:** 
- Bank Account -> $200 BTC in Kraken/CashApp
- Kraken/CashApp -> Edge Wallet $200 BTC
- Edge Wallet -> TLC Donation $50 BTC
- Egde Wallet: $150 BTC

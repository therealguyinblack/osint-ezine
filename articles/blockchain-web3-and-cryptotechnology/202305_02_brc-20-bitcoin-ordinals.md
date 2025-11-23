---
cover: ../../.gitbook/assets/202305_02_header.png
coverY: 0
---

# 202305\_02\_BRC-20-Bitcoin-ordinals

BRC-20 is the new player in the crypto-space. Based on the [_Ordinals_](https://docs.ordinals.com/overview.html) protocol in the Bitcoin network, it has sparked new developments and challenges. In this article, I'll explore the growing adoption of BRC-20, compare it to Ethereum's ERC-20 protocol, and shed light on the impact of this new "memecoin rampage" that is affecting Bitcoin's network congestion and transaction fees.

Bitcoin's Ordinals protocol has given birth to an exciting development called BRC-20. This protocol operates similarly to Ethereum's ERC-20, which is widely recognized as one of the pioneers in the field of fungible tokens. As a reminder, fungible tokens such as ERC-20 or BRC-20 represents the same exact value, like a 5 Euro banknote, do not confuse them with NFTs that are unique and embedded with distinctive features. BRC-20 enables the creation of fungible tokens on the Bitcoin network, opening up new possibilities for decentralized finance (DeFi) applications and tokenized assets.

<br>

**Understanding BRC-20 and its functionality.**

BRC-20, short for Bitcoin Request for Comments, employs JSON text files to represent fungible tokens. By using a standardized structure, developers can easily create and manage these tokens. A typical BRC-20 JSON file may include essential information like the protocol name ("p"), the transaction type ("op"), the token ticker symbol ("tick"), and the amount ("amt") of tokens being transferred:

```
{
    "p": "brc-20",
    "op": "transfer",
    "tick": "pepe",
    "amt": "2000"
}
```

**Prominent wallet supporting BRC-20:&#x20;**_**Unisat**_**.**

Among the various wallets available today, Unisat ([https://unisat.io](https://unisat.io/)) has gained popularity as a leading supporter of BRC-20 tokens. To mint (create) a BRC-20 token in Unisat, users must fulfill a specific requirement: their address needs to have previously inscribed 20 ordinals. This prerequisite ensures a certain level of network participation and serves as a protective measure against potential abuse.

<br>

**The impact of Ordinals on network congestion and fees.**

The requirement of 20 ordinals before creating a BRC-20 token has inadvertently contributed to the current congestion and higher transaction fees on the Bitcoin network. As users strive to inscribe these ordinals, the demand for transactions has surged, leading to a backlog of over 400,000 stuck transactions in the mempool. Consequently, the increased demand and congestion have resulted in higher fees for Bitcoin transactions.

<figure><img src="../../.gitbook/assets/202305_02_image01.jpeg" alt=""><figcaption><p>Pepe The Frog</p></figcaption></figure>



**The rise of memecoins and market turbulence.**

The recent fervor surrounding BRC-20 tokens has coincided with the emergence of numerous memecoins, such as $PIZZA, $MEME, and $DRAC, inspired by various cultural references, including the renowned vampire. As with any speculative market trend, the current landscape ([https://brc-20.io](https://brc-20.io/)) is characterized by considerable turbulence. The volatile nature of these memecoins has further contributed to the network congestion and increased transaction fees experienced on the Bitcoin network.

<br>

**Conclusion.**

The introduction of BRC-20 tokens and the significance of Ordinals in the Bitcoin network have brought both exciting opportunities and challenges. This new feature of the protocol started as a fun proof-of-concept and its author, disregarded to use it for any speculative purpose. BRC-20 opens doors for new DeFi applications and tokenized assets, while the requirement of 20 ordinals has contributed to network congestion and higher fees. As the market continues to evolve and memecoins gain traction, it is essential to navigate this dynamic landscape with caution and awareness.

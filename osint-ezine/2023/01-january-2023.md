# 01 - January 2023

<figure><img src="../../.gitbook/assets/OSINT_eZine-202301.png" alt="" width="375"><figcaption></figcaption></figure>

Welcome to the January issue of the OSINT eZine (_#23_), this number comes with some relevant updates regarding Ethereum; more bad use-cases for ChatGPT; a TikTok doxxer; Twitter's email breach; diverse tools for a diversity of purposes, from looking for usernames in more than 300 platforms to extract information from GitHub or access to multiple open data sources... and much more!

Hey Ho, Lets Go!:

* [Crypto: **Ethereum Shanghai update.**](01-january-2023.md#crypto-ethereum-shanghai-update)
* [Crypto: **Ethereum Stealth addresses.**](01-january-2023.md#crypto-ethereum-stealth-addresses)
* [News: **ChatGPT helping Malware.**](01-january-2023.md#news-chatgpt-helping-malware)
* [News: **RSA cracking not so far away.**](01-january-2023.md#news-rsa-cracking-not-so-far-away)
* [Privacy: **Kristen, the TikTok doxxer.**](01-january-2023.md#privacy-kristen-the-tiktok-doxxer)
* [Privacy: **Twitter breach email domains.**](01-january-2023.md#privacy-twitter-breach-email-domains)
* [Techniques: **Advanced use of Archive to see historical usernames.**](01-january-2023.md#techniques-advanced-use-of-archive-to-see-historical-usernames)
* [Tools: **Nexfil, username search on more than 300 platforms.**](01-january-2023.md#tools-nexfil-username-search-on-more-than-300-platforms)
* [Tools: **Octosuite for GitHub.**](01-january-2023.md#tools-octosuite-for-github)
* [Tools: **OSS, Open Source Surveillance.**](01-january-2023.md#tools-oss-open-source-surveillance)
* [Web3: **Controversial NFTs on Bitcoin, Ordinals.**](01-january-2023.md#web3-controversial-nfts-on-bitcoin-ordinals)

***

#### Crypto: Ethereum Shanghai update.

After “_The Merge_” on September 2022, the Shanghai update has been announced for March 2023. This update introduces two new features that would impact how Ethereum market behaves, the first one is the withdrawals of staked ETH (EIP-4895) the second feature, should speed up transactions using external layer-2 blockchains through a mechanism called proto-danksharding (EIP-4844).

[https://ethereum.org/en/upgrades/](https://ethereum.org/en/upgrades/)\


***

#### Crypto: Ethereum Stealth addresses.

_Vitalik Buterin_ has published a proposal concept to use stealth addresses in Ethereum. A very interesting concept to defend privacy but a future issue for investigators, as stealth addresses are one of the main components of privacy coins such as Monero.

[https://vitalik.ca/general/2023/01/20/stealth.html](https://vitalik.ca/general/2023/01/20/stealth.html)\


***

#### News: ChatGPT helping Malware.

From all the uses available of ChatGPT, the malware sector is making good use of it. In my opinion, ChatGPT, can be better used to correct code and to expand it rather to create it from scratch, but we cannot ignore that bad actors can leverage it for malicious purposes.

[https://www.hackread.com/hackers-openai-chatgpt-malware/](https://www.hackread.com/hackers-openai-chatgpt-malware/)\


***

#### News: RSA cracking not so far away.

Chinese researchers claimed the possibility of breaking the RSA algorithm using quantum computing. Yet to be developed, tested and proved, RSA is massively adopted in many applications such as the SSL certificates that protect us from visiting malicious websites or secure network connections using the TLS protocol.

[https://www.schneier.com/blog/archives/2023/01/breaking-rsa-with-a-quantum-computer.html](https://www.schneier.com/blog/archives/2023/01/breaking-rsa-with-a-quantum-computer.html)\


***

#### Privacy: Kristen, the TikTok doxxer.

An article about a TikTok user that is specialized in consensual doxxing of users of the platforms. She is reached by individuals in order for her to find information about users consensually. In the end, more creative uses (and ways to obtain revenue) of OSINT.

[https://www.businessinsider.com/i-got-popular-on-tiktok-by-doxxing-people-with-permission-2022-12](https://www.businessinsider.com/i-got-popular-on-tiktok-by-doxxing-people-with-permission-2022-12)\


***

#### Privacy: Twitter breach email domains.

Another recent breach, Twitter this time, was exposed last month. In this GitHub repo we can find all the email providers affected by the breach, very useful to build dictionaries or brute-force lists.

[https://github.com/ArgeliusLabs/BreachInfo/blob/main/twitter\_email\_domain\_histogram\_1\_4\_23.txt](https://github.com/ArgeliusLabs/BreachInfo/blob/main/twitter_email_domain_histogram_1_4_23.txt)\


***

#### Techniques: Advanced use of Archive to see historical usernames.

Some methodologies on how to look for the changes on usernames of specific profiles. It is very relevant for some platforms, like Steam or Twitter, where users can change their username across time.

[https://medium.com/@cyb\_detective/how-to-view-the-history-of-a-social-media-profile-name-using-the-archive-org-cdx-api-4-steps-guide-a900cae72410](https://medium.com/@cyb_detective/how-to-view-the-history-of-a-social-media-profile-name-using-the-archive-org-cdx-api-4-steps-guide-a900cae72410)\


***

#### Tools: Archivebox.

Do you ever wanted to have your own Archive-style data repository? Archivebox allows you to store and keep track of URLs in the same style as Archive.org wayback machine. It can be programmed for scheduled fetching, making it the perfect candidate for ingesting multiple sites for monitoring.

[https://archivebox.io/](https://archivebox.io/)\


***

#### Tools: Nexfil, username search on more than 300 platforms.

Yet another OSINT tool to look for usernames (we have like thousands of them) but this specific one is working pretty accurate and at the same time, it provides more than 300 to look for. As always, the tool is in Python so if you have Maltego... you know ;)

[https://github.com/thewhiteh4t/nexfil](https://github.com/thewhiteh4t/nexfil)\


***

#### Tools: OSS, Open Source Surveillance.

I was always wondering why no one decided to compile in one place, like a map, all the different public APIs, services and endpoints with relevant information like city cameras, wireless networks... till now. OSS (Open Source Surveillance) does exactly that, providing a variety of different sources such as public cameras, IoT, traffic, weather, Twitter, Snapchat, Instagram, Flicker and much more.

[https://www.offensiveosint.io/offensive-osint-s04e04-open-source-surveillance/](https://www.offensiveosint.io/offensive-osint-s04e04-open-source-surveillance/)\


***

#### Tools: Octosuite for GitHub.

In some cases, GitHub is a pile of gold. I have successfully discover very relevant information in my investigations coming from this platform. Octosuite is a tool that can grab for you information about users, organizations and repositories.

[https://www.bellingcat.com/resources/2023/01/20/octosuite-a-new-tool-to-conduct-open-source-investigations-on-github/](https://www.bellingcat.com/resources/2023/01/20/octosuite-a-new-tool-to-conduct-open-source-investigations-on-github/)\


***

#### Web3: Controversial NFTs on Bitcoin, Ordinals.

Thanks to a clever usage of the Bitcoin scripting latest updates, a new project called Ordinals has arisen to provide the possibly of creating NFTs in Bitcoin. Due to how the space that allocates the data is used, and the possible implication it can have regarding fees to miners and other aspects, it is causing a lot of controversy about it's use.

[https://www.coindesk.com/tech/2023/01/31/bitcoin-community-erupts-in-existential-debate-over-nft-project-ordinals/](https://www.coindesk.com/tech/2023/01/31/bitcoin-community-erupts-in-existential-debate-over-nft-project-ordinals/)\


***

_ChatGPT is incredibly limited, but good enough at some things to create a misleading impression of greatness. it’s a mistake to be relying on it for anything important right now. it’s a preview of progress; we have lots of work to do on robustness and truthfulness._

_\~Sam Altman, CEO OpenAI._

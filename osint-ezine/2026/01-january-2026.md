# 01 - January 2026

<figure><img src="../../.gitbook/assets/OSINTeZine_2026_01.png" alt=""><figcaption></figcaption></figure>

Welcome to the January issue of the OSINT eZine ([_#59_](https://therealguyinblack.gitbook.io/osint-ezine/osint-ezine/2026)). This issue includes topics such as limiting abuse of AI image generation; AI powered customer service scams via search poisoning; agentic micro-laundering trends; influence operations in the Nordic-Baltic region; platform resilience against engagement manipulation; OSINT decision discipline; why chatbots fail on breaking news; web age verification; VPN tradecraft for OSINT; modern dead letter drops; a handful of new tools… and much more!

Hey Ho, Lets Go!:

* [AI: **AI Search Poisoning Scam.**](01-january-2026.md#ai-ai-search-poisoning-scam)
* [AI: **Grokd: Limiting AI Image Abuse.**](01-january-2026.md#ai-grokd-limiting-ai-image-abuse)
* [Crypto: **Agentic Smurfing Micro Laundering.**](01-january-2026.md#crypto-agentic-smurfing-micro-laundering)
* [Learning: **Countering Influence Ops in Nordic-Baltic Countries (NB8).**](01-january-2026.md#learning-countering-influence-ops-in-nordic-baltic-countries-nb8)
* [Learning: **Knowing When to Stop in OSINT.**](01-january-2026.md#learning-knowing-when-to-stop-in-osint)
* [Learning: **Social Media Manipulation for Sale 2025.**](01-january-2026.md#learning-social-media-manipulation-for-sale-2025)
* [News: **Why Chatbots Do Not Use Web Search.**](01-january-2026.md#news-why-chatbots-do-not-use-web-search)
* [Techniques: **Calculating Website Age with URL Dater.**](01-january-2026.md#techniques-calculating-website-age-with-url-dater)
* [Techniques: **Modern Dead Letters and OSINT Blind Spots.**](01-january-2026.md#techniques-modern-dead-letters-and-osint-blind-spots)
* [Techniques: **OSINT and VPNs Practical Guide.**](01-january-2026.md#techniques-osint-and-vpns-practical-guide)
* [Tools: **CreepyLink Suspicious URL Shortener.**](01-january-2026.md#tools-creepylink-suspicious-url-shortener)
* [Tools: **NoSubscription One Time Purchase Directory.**](01-january-2026.md#tools-nosubscription-one-time-purchase-directory)
* [Tools: **ProxyContain Container Proxies in Firefox.**](01-january-2026.md#tools-proxycontain-container-proxies-in-firefox)

***

### AI: AI Search Poisoning Scam

A fraud pattern aimed at consumers who ask chatbots for customer support contact details. Rather than attacking the model directly, scammers seed the open web with fake support numbers (often via compromised pages, low-trust listings, or comment spam) and rely on the chatbot to repeat them as authoritative answers. For investigators and defenders, this highlights that provenance, citations, and validation workflows are now essential when LLMs are used as a lookup layer.

[https://frankonfraud.com/ai-search-poisoning-the-scam-you-never-heard-of/](https://frankonfraud.com/ai-search-poisoning-the-scam-you-never-heard-of/)

***

### AI: Grokd: Limiting AI Image Abuse

A rapid analysis of abusive prompts targeting xAI’s Grok image generation, extracting practical lessons for limiting non-consensual and harmful synthetic imagery. The article emphasizes that even basic safeguards and friction (policy enforcement, better detection, and guardrails that hold under prompt variation) can materially reduce scale and severity of abuse. Relevant for platform policy, trust and safety, and for practitioners who may need to assess synthetic media risks in reporting and investigations.

[https://www.info-res.org/cir/articles/grokd-five-emerging-lessons-on-limiting-abuse-of-ai-image-generation/](https://www.info-res.org/cir/articles/grokd-five-emerging-lessons-on-limiting-abuse-of-ai-image-generation/)

***

### Crypto: Agentic Smurfing Micro Laundering

An overview of “agentic smurfing”, describing how autonomous or semi-autonomous systems can break laundering into many small, distributed actions that are harder to flag with traditional terrorist financing and AML detection heuristics. The piece is useful for understanding how micro-transactions, automation, and adaptive workflows can compress the time from intent to execution, and why controls built for human-paced laundering can fall behind.

[https://gnet-research.org/2026/01/28/agentic-smurfing-how-ai-autonomous-micro-laundering-is-outpacing-traditional-terrorist-financing-detection/](https://gnet-research.org/2026/01/28/agentic-smurfing-how-ai-autonomous-micro-laundering-is-outpacing-traditional-terrorist-financing-detection/)

***

### Learning: Countering Influence Ops in Nordic-Baltic Countries (NB8)

A regional mapping of how the Nordic-Baltic countries (NB8) approach countering information influence operations, focusing on capabilities, institutional models, and opportunities for cooperation. Especially relevant for practitioners working in or on Estonia, Latvia, Lithuania, Finland, Sweden, Norway, Denmark, and Iceland, with takeaways on resilience, whole-of-society coordination, and where approaches diverge across the region.

[https://stratcomcoe.org/publications/countering-information-influence-operations-in-the-nordic-baltic-region/327](https://stratcomcoe.org/publications/countering-information-influence-operations-in-the-nordic-baltic-region/327)

***

### Learning: Knowing When to Stop in OSINT

A practical reminder that OSINT often fails not at collection, but at decision-making: recognizing the point where additional data dilutes rather than strengthens conclusions. The author frames “stopping” as a skill: setting thresholds, managing uncertainty, and transitioning from collection to defensible judgement. Useful for analysts, supervisors, and anyone building repeatable investigation workflows.

[https://www.raebaker.net/blog/knowing-when-to-stop-the-osint-skill-no-one-teaches](https://www.raebaker.net/blog/knowing-when-to-stop-the-osint-skill-no-one-teaches)

***

### Learning: Social Media Manipulation for Sale 2025

A recurring experiment that tests major platforms by purchasing inauthentic engagement from commercial manipulation services and assessing detection and takedown performance. The value here is methodological: it provides a structured way to think about platform resilience, what signals defenders might rely on, and where “low-cost” manipulation still survives. Relevant to investigations that depend on engagement signals (reach, amplification, and apparent legitimacy).

[https://stratcomcoe.org/publications/social-media-manipulation-for-sale-2025-experiment-on-platform-capabilities-to-detect-and-counter-inauthentic-social-media-engagement/338](https://stratcomcoe.org/publications/social-media-manipulation-for-sale-2025-experiment-on-platform-capabilities-to-detect-and-counter-inauthentic-social-media-engagement/338)

***

### News: Why Chatbots Do Not Use Web Search

A Tow Center piece arguing that chatbot failures on breaking news are not “expected behavior” but product design choices: many systems can search the web, yet do not reliably activate retrieval for time-sensitive queries. For newsroom, OSINT, and investigative workflows, the implication is clear: treat non-retrieved answers as high-risk during fast-moving events, and demand clear signaling when models are (and are not) grounded in current sources.

[https://www.cjr.org/tow\_center/ai-chatbots-can-search-the-web-so-why-dont-they.php](https://www.cjr.org/tow_center/ai-chatbots-can-search-the-web-so-why-dont-they.php)

***

### Techniques: Calculating Website Age with URL Dater

A walkthrough of URL Dater, focused on estimating the age of a webpage or site using multiple corroborating signals. It combines RDAP (domain registration history), certificate transparency data (first TLS issuance), and archived snapshots to reduce single-source errors. Useful for investigations into newly spun infrastructure, reputation analysis, and tracking when content or ownership posture changes.

[https://nixintel.info/osint-tools/calculating-website-age-tracking-changes-with-url-dater/](https://nixintel.info/osint-tools/calculating-website-age-tracking-changes-with-url-dater/)

***

### Techniques: Modern Dead Letters and OSINT Blind Spots

A tradecraft-focused обзор of “dead letter” style covert communications adapted to modern platforms that do not look like communications infrastructure. It highlights patterns such as shared artefacts (draft folders, shared accounts) and signaling through consumer telemetry (loyalty apps, gaming ecosystems, fitness apps), then frames detection as behavioral analysis rather than content recovery. Particularly relevant for investigators looking beyond mainstream messaging and social platforms.

[https://osintimes.substack.com/p/getting-the-drop-on-modern-dead-letters](https://osintimes.substack.com/p/getting-the-drop-on-modern-dead-letters)

***

### Techniques: OSINT and VPNs Practical Guide

A practical guide to how VPNs intersect with OSINT both defensively and evidentially. It covers why investigators use VPNs for OPSEC and access, common VPN types and artefacts, and how VPN use can itself be an investigative signal when correlated with other behaviors. A good reference for building safer collection workflows while avoiding over-claims based on IP geolocation alone.

[https://www.osint.industries/post/osint-and-vpns-a-practical-guide-to-virtual-private-networks-in-open-source-intelligence](https://www.osint.industries/post/osint-and-vpns-a-practical-guide-to-virtual-private-networks-in-open-source-intelligence)

***

### Tools: CreepyLink Suspicious URL Shortener

A novelty URL shortener designed to make links look maximally suspicious, mainly as a social engineering and trust-awareness demonstration. While not an investigative tool by itself, it is a useful reminder that many users still judge safety by “link vibes”, and that defenders should emphasize verification habits (domain validation, safe previewing) over appearance-based heuristics.

[https://creepylink.com/](https://creepylink.com/)

***

### Tools: NoSubscription One Time Purchase Directory

A directory that indexes software and services offering one-time purchase options, or that are free or open source, positioned as an alternative to subscription-first tooling. For OSINT and security practitioners, it can be a discovery source for lightweight utilities and self-hostable alternatives, especially when procurement or budgeting constraints block SaaS adoption.

[https://nosubscription.org](https://nosubscription.org)

***

### Tools: ProxyContain Container Proxies in Firefox

A Firefox extension combining Container identities with per-container proxy routing and optional header manipulation. This enables parallel, segregated browsing sessions with distinct egress paths, which is useful for testing, compartmentalized research, and cleaner OPSEC when switching between personas or investigation threads. If you use it operationally, keep a clear policy on logging, attribution, and what traffic is allowed to traverse third-party proxies.

[https://github.com/dfuribez/proxycontain](https://github.com/dfuribez/proxycontain)

***

_Ignoring isn’t the same as ignorance, you have to work at it._

_\~Margaret Atwood, Canadian Author._

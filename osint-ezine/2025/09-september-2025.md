# 09 - September 2025

<figure><img src="../../.gitbook/assets/OSINTeZine_2025_09.png" alt="" width="563"><figcaption></figcaption></figure>

Welcome to the September issue of the OSINT eZine ([_#55_](https://therealguyinblack.gitbook.io/osint-ezine/osint-ezine/2025)). This issue includes topics such as guides to detect AI-generated content; the prevalence of exposed AI servers; malware tracing challenges in crypto; how militaries are using AI for decision support; an UNODC report on AI for criminal activities; new investigative resources on GitHub and flight data; dark web search engines... and much more!

Hey Ho, Lets Go!:

* [AI: **Detecting AI-Generated Content.**](09-september-2025.md#ai-detecting-ai-generated-content)
* [AI: **From OCR to Vision-Language Models.**](09-september-2025.md#ai-from-ocr-to-vision-language-models)
* [AI: **Ollama Drama: Exposed AI Instances.**](09-september-2025.md#ai-ollama-drama-exposed-ai-instances)
* [Crypto: **Infostealer Malware and Tracing Challenges.**](09-september-2025.md#crypto-infostealer-malware-and-tracing-challenges)
* [Defence: **AI in Defence Beyond Assumptions.**](09-september-2025.md#defence-ai-in-defence-beyond-assumptions)
* [Learning: **A Stark Connection.**](09-september-2025.md#learning-a-stark-connection)
* [Learning: **Automation and AI for Cybercrime.**](09-september-2025.md#learning-automation-and-ai-for-cybercrime)
* [Learning: **Challenges in Person-of-Interest Investigations.**](09-september-2025.md#learning-challenges-in-person-of-interest-investigations)
* [News: **Military AI Revolution and NATO DIANA.**](09-september-2025.md#news-military-ai-revolution-and-nato-diana)
* [Privacy: **Dark Web Search Engines.**](09-september-2025.md#privacy-dark-web-search-engines)
* [Techniques: **GitHub Advanced Search for OSINT.**](09-september-2025.md#techniques-github-advanced-search-for-osint)
* [Techniques: **Exposed LLM Servers on Shodan.**](09-september-2025.md#techniques-exposed-llm-servers-on-shodan)
* [Techniques: **Mapping Terrorist AI Use.**](09-september-2025.md#techniques-mapping-terrorist-ai-use)
* [Techniques: **Investigating GitHub.**](09-september-2025.md#techniques-investigating-github)
* [Tools: **WhatBreach.**](09-september-2025.md#tools-whatbreach)
* [Tools: **Flightera Flight Data.**](09-september-2025.md#tools-flightera-flight-data)

***

### AI: Detecting AI-Generated Content.

The Global Investigative Journalism Network (GIJN) released a practical guide to detect AI-generated content. It outlines techniques and tools that journalists and investigators can use to verify authenticity in text, images, and video. With the rising sophistication of generative models, these checks are becoming vital for open-source research but also in other areas such as screening processes or source information verification.

[https://gijn.org/resource/guide-detecting-ai-generated-content/](https://gijn.org/resource/guide-detecting-ai-generated-content/)

***

### AI: From OCR to Vision-Language Models.

TRM Labs explains why they replaced traditional Optical Character Recognition (OCR) systems with vision-language models (VLMs) for image extraction. The new approach significantly improves accuracy, particularly in dealing with low-quality or complex images, enhancing investigative workflows that rely on document and image analysis.

[https://www.trmlabs.com/resources/blog/from-brittle-to-brilliant-why-we-replaced-ocr-with-vlms-for-image-extraction](https://www.trmlabs.com/resources/blog/from-brittle-to-brilliant-why-we-replaced-ocr-with-vlms-for-image-extraction)

***

### AI: Ollama Drama: Exposed AI Instances.

Censys researchers investigated the prevalence of publicly exposed instances of **Ollama**, a popular open-source LLM platform. The study highlights misconfigured deployments that leave servers accessible online, raising risks of data leaks and exploitation. The findings stress the importance of proper configuration and hardening of local AI setups.

[https://censys.com/blog/ollama-drama-investigating-the-prevalence-of-ollama-open-instances-with-censys](https://censys.com/blog/ollama-drama-investigating-the-prevalence-of-ollama-open-instances-with-censys)

***

### Crypto: Infostealer Malware and Tracing Challenges.

An article from ZeroShadow analyses a real-world malware incident involving cryptocurrency-related infostealers. The focus is on the difficulties of tracing stolen assets when attackers route funds through unidentified services, highlighting both investigative challenges and the complexity of crypto laundering techniques.

[https://www.zeroshadow.io/post/an-infostealer-malware-incident-and-the-tracing-challenges-linked-to-unidentified-services](https://www.zeroshadow.io/post/an-infostealer-malware-incident-and-the-tracing-challenges-linked-to-unidentified-services)

***

### Defence: AI in Defence Beyond Assumptions.

AI in defence is not just about autonomous drones or cyber warfare. As argued in my latest LinkedIn article, military professionals are increasingly adopting AI to handle information overload, support interpretation, and accelerate decision-making. The real value today lies in augmentation, not autonomy.

[https://www.linkedin.com/pulse/ai-defence-beyond-assumptions-ismael-alvarez-rabie](https://www.linkedin.com/pulse/ai-defence-beyond-assumptions-ismael-alvarez-rabie)

***

### Learning: A Stark Connection.

This article highlights emerging evidence of links between extremist narratives and wider political discourse. It shows how online ecosystems blur the lines between fringe radicalisation and mainstream narratives, raising concerns for researchers monitoring extremist networks.

[https://intelinsights.substack.com/p/a-stark-connection](https://intelinsights.substack.com/p/a-stark-connection)

***

### Learning: Automation and AI for Cybercrime.

This report by UNODC (United Nations Office on Drugs and Crime) showcases several real examples of different cybercriminal approaches leveraging technology to conduct their crimes such as the usage of DeepFakes, AI malware creation or AI-driven social engineering.

[https://www.unodc.org/roseap/uploads/documents/Publications/2025/UNODC\_Report\_Emerging\_threats\_-\_The\_intersection\_of\_criminal\_and\_technological\_innovation\_in\_the\_use\_of\_automation\_and\_AI.pdf](https://www.unodc.org/roseap/uploads/documents/Publications/2025/UNODC_Report_Emerging_threats_-_The_intersection_of_criminal_and_technological_innovation_in_the_use_of_automation_and_AI.pdf)

***

### Learning: Challenges in Person-of-Interest Investigations.

Maltego outlines why modern person-of-interest (POI) investigations struggle at scale. While digital data is abundant, fragmentation across platforms, formats, and jurisdictions makes linking information complex. The post discusses how analysts can adapt methods and tools to handle large-scale, multi-source investigations effectively.

[https://www.maltego.com/blog/why-modern-person-of-interest-investigations-struggle-at-scale/](https://www.maltego.com/blog/why-modern-person-of-interest-investigations-struggle-at-scale/)

***

### News: Military AI Revolution and NATO DIANA.

Reuters explores how military adoption of AI is intensifying global competition for defence contracts. The article links well with NATO’s **DIANA Data Assisted Decision-Making 2026 Challenge**, which seeks AI solutions for real-time operational analysis, reflecting the sector’s shift towards AI-supported decision dominance.

[https://www.reuters.com/technology/artificial-intelligence/military-ai-revolution-heightens-competition-defence-tech-contracts-peter-apps-2025-09-05/](https://www.reuters.com/technology/artificial-intelligence/military-ai-revolution-heightens-competition-defence-tech-contracts-peter-apps-2025-09-05/)

***

### Privacy: Dark Web Search Engines.

Nym published a post reviewing dark web search engines, their indexing approaches, and reliability. While often incomplete, these services remain a key entry point for researchers seeking hidden services. The analysis also warns of risks, including exposure to malicious sites or unreliable results.

[https://nym.com/blog/dark-web-search-engines](https://nym.com/blog/dark-web-search-engines)

***

### Techniques: GitHub Advanced Search for OSINT.

GitHub is a rich resource for OSINT but its search operators are often underused. This official documentation highlights lesser-known filters and queries to search users, repositories, and code. These techniques are particularly valuable in CTFs or real investigations when looking for sensitive disclosures or artefacts.

[https://docs.github.com/en/search-github/searching-on-github/searching-users](https://docs.github.com/en/search-github/searching-on-github/searching-users)

***

### Techniques: Exposed LLM Servers on Shodan.

Cisco researchers published a case study on detecting misconfigured LLM servers, specifically Ollama, indexed on Shodan. The findings illustrate the risks of leaving AI services exposed to the internet and provide recommendations for security hardening.

[https://blogs.cisco.com/security/detecting-exposed-llm-servers-shodan-case-study-on-ollama](https://blogs.cisco.com/security/detecting-exposed-llm-servers-shodan-case-study-on-ollama)

***

### Techniques: Mapping Terrorist AI Use.

GNET examines the adoption of AI by terrorist groups and why it has been relatively slow compared to expectations. Factors include technical barriers, operational limitations, and the challenges of maintaining clandestine operations with advanced technologies.

[https://gnet-research.org/2025/09/17/mapping-terrorist-ai-use-identifying-factors-behind-a-relatively-slow-adoption-rate/](https://gnet-research.org/2025/09/17/mapping-terrorist-ai-use-identifying-factors-behind-a-relatively-slow-adoption-rate/)

***

### Techniques: Investigating GitHub.

Authentic8 provides an in-depth look at GitHub as an investigative source. Beyond code, repositories may contain leaked data, personal identifiers, or operational artefacts. The guide outlines safe approaches to leverage GitHub in OSINT while mitigating risks of exposure or contamination.

[https://www.authentic8.com/blog/investigating-github](https://www.authentic8.com/blog/investigating-github)

***

### Tools: WhatBreach.

WhatBreach is a command-line tool that helps investigators check if email addresses have been part of data breaches. It aggregates results from multiple sources, automating a key step in digital risk and identity investigations.

[https://github.com/Ekultek/WhatBreach](https://github.com/Ekultek/WhatBreach)

***

### Tools: Flightera Flight Data.

Flightera provides free access to historical flight data dating back to 2017. This can be useful for OSINT investigations involving travel patterns, aviation monitoring, or verifying movement claims.

[https://www.flightera.net](https://www.flightera.net)

***

\


_Robots will not replace humans, but will become companions and partners that help us to achieve more than we could alone._

_\~Cynthia Breazeal, American scientist._

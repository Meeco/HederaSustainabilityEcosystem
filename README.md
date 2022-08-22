# Hedera Sustainability Ecosystem
A short guide to sustainability focused projects on Hedera

## Introduction
*This article is not a comprehensive “sustainability for beginners” guide. It’s more of a very brief (as possible) **first step** towards a guide for ecosystem-developers who wants to particpate in sustainability markets on Hedera. Since this area is growing at a pretty crazy pace **the information below is likely to go out of date relatively quickly**. We'll try to keep it up to date via [pull-requests](https://github.com/dubgeis/SustainabilityEcosystem/pulls) and [issues](https://github.com/dubgeis/SustainabilityEcosystem/issues). And I **hope the platforms themselves will add relevant information, “Statement of Values”, and roadmaps to their own site speaking to auditability around high quality carbon offsets/REC's**.*

***For more up-to-date information, daily discussions and reviews please visit***
- [Interwork Alliance Sustainability Repo](https://interworkalliance.github.io/Sustainability/)
- [The Hedera Discord for Developer Chats](https://discord.com/invite/yKSnaMk7Px)
- [Docs](https://docs.hedera.com/guides/) / [Guardian Docs](https://docs.hedera.com/guardian/getting-started/readme)
- [Is Hedera Carbon Neutral/Negative?](https://hedera.com/blog/going-carbon-negative-at-hedera-hashgraph)
- [Hedera Environmental Footprint Report by UCL Center for Blockchain Technologies](http://blockchain.cs.ucl.ac.uk/blockchain-energy-consumption/)

---

## Overview

- [The Latest](https://www.hbarfoundation.org/blog-post/building-on-the-sif-ecosystem)
---

## Glossary
A deeper glossary of industry terms can be found [here](https://github.com/InterWorkAlliance/Sustainability/blob/main/glossary.md)

---
## Ways to make the ecosystem better (Projects listed here make great [HBAR Foundation](hbarfoundation.org) grant candidates)
- An Interactive Hedera explorer with real time data representations for ESG tokens (ex. [https://txstreet.com/](https://txstreet.com/))
- An Index scoring all ESG assets on Hedera for data granularity, trust (sensor/manual), and risks
- Slick Carbon Wallets based on Offsetting Achievements against CET based emissions.
- NFT rewards protocol for Offsets/Removals burned against CET's (minting an NFT based on total emissions offset) tied to companies [CDP](https://www.cdp.net/en) Reports/Audits 
 
---

## Sustainbility Platforms & Marketplaces
These are the application that you would use to work with them to develop, ‘mint’ and sell your carbon credits following the [IWA Standards](https://hedera.com/blog/hedera-hashgraph-and-application-partners-collaborate-with-the-interwork-alliance-on-sustainability-working-group-key-initiatives). We encourage applications committed to sustainability and offsetting on Hedera to submit a pull request and sign up as a deamnd platform below. For those who'd like 

### Open Source Projects
#### [Guardian](https://github.com/hashgraph/guardian), ([Docs](https://docs.hedera.com/guardian/getting-started/readme)) - A project to enable users to create auditable, publicly discoverable, Sustainability Assets
- This project's initial contribution was done in close collaboration with Envision Blockchain, Dovu, and others. It is based on the IWA Sustainability Business Working Group's [Voluntary Ecological Markets Taskforce](https://github.com/InterWorkAlliance/Sustainability/tree/main/vem) ongoing work.
- Relevant HIP's for the Guardian include: [HIP - 19](https://github.com/hashgraph/hedera-improvement-proposal/blob/master/HIP/hip-19.md), [HIP - 28](https://github.com/hashgraph/hedera-improvement-proposal/blob/master/HIP/hip-28.md), & [HIP - 29](https://github.com/hashgraph/hedera-improvement-proposal/blob/master/HIP/hip-29.md).

#### [ARMs](https://medium.com/block-science/introducing-automated-regression-markets-arms-a-new-price-discovery-mechanism-for-semi-fungible-935d31ca457c)

### Supply Platforms
#### [Dovu](https://hedera.com/users/dovu) - Trusted Carbon Offsets Issuance Platform & Marketplace
- [dovu.earth](https://dovu.earth)
- Primary Goal: **Digital MRV (Offsets)**/**Carbon Marketplace**/**Developer Tools**
- Major Partnerships: Jaguar Landrover, Creative England (a fund backed by the UK Government)
- Summary: DOVU is building the trust layer for carbon offset integrity with a marketplace for instant and auditable retirement.
- Hedera Project References:
  - [Proof of Carbon on Hedera](https://www.dovu.earth/news/hedera) 
  - [Earth Week 2021: Dovu is tokenizing carbon offsets](https://www.youtube.com/watch?v=E0snNSQI1qc)
  - [DOVU: DeFi Carbon Offsetting on Hedera Hashgraph](https://www.youtube.com/watch?v=gy0ATUwL6L8)
  - [Trust Enterprises](https://trust.enterprises/): The minting and marketplace backbone that connects DOVU to all Hedera services. A foundational layer to record any decentralized logic and prove intent. Rapidly augment your SaaS with provable trust, no blockchain experience required. At the fraction of the cost of ethereum or bitcoin. 
    - Check out the [documentation](https://docs.trust.enterprises/) for a serverless API for building consensus, with a Laravel client to make building with Hedera as simple as possible, even in [no-code or low-code environments](https://twitter.com/flyinggazelle/status/1443839460169429019). 
    - [Unibar (Hedera21 prototype)](https://github.com/trustenterprises/unibar-prototype) If you need a gasless interface, inbuilt private key management and basic ethereum auth. With minting, management, pooling, and API capability.
    - [Dynamic NFT Specification](https://github.com/trustenterprises/hedera-dnft-specification) This is a description of the work in progress for implementing Dynamic Non-Fungible Tokens (dNFT) on Hedera Hashgraph. The goal is to bring together new community consensus on token standards and new primitives within the ecosystem to ensure interoperability and reduce fragmentation between products.
  - Hedera Improvement Proposal Discussions
    - [Ecological Carbon Taxonomy](https://github.com/hashgraph/hedera-improvement-proposal/discussions/83) Introduce a recommended path of the implementation of minting and maintenance of ecological tokens based on IWA sustainability specifications from the voluntary ecological markets taskforce. This combines and is the first use-case of dNFT/dFT on Hedera to provide an ability for tokens to attach an unlimited amount of evidence.
    - [Hedera Ledger Service (HLS)](https://github.com/hashgraph/hedera-improvement-proposal/discussions/131) A novel proposal on a new native liquidity service on Hedera to offer deep liquidity at a network-level. 

#### [Agryo](https://hedera.com/users/agryo) - Agriculture Data Provider
- [https://www.agryo.com/](https://www.agryo.com/)
- Primary Goal: Provide automatic environmental services data oracle for digital assets and financial services 
- Summary: Agryo provide risk intelligence capabilities by the combination of over 500 variables plus ML/AI modelling and DLT data integrity control. Supporting operations in environmental services (like carbon credits and forest protection) and financial services for farmers (like credit and insurance), from origination, to monitoring daily during contracts and supporting fraud detection and portfolio management for any place one Earth. 


#### [Earthimpact](https://hedera.com/users/earthimpact) - Environmental and Social Impact Projects Platform
- [earthimpact.com](https://earthimpact.com/)
- Primary Goal: **Digital MRV (Carbon Credits)**/**Tokenomics**
- Open Source MRV Protocol
- Major Partnerships: TBA
- Summary: Earth Impact is a platform that empower producer and consumers to trade carbon credits, renewable energy and other environmental and social impact projects into a core interaction solution.

#### [RECDeFi](https://hedera.com/users/recdefi) - Carbon Credit, REC, Commodities Issuance Platform & Marketplace
- [recdefi.com](https://recdefi.com)
- Primary Goal: **Digital MRV (REC)**/**Automated Market**
- Open Source MRV Protocol
- Major Partnerships: TBA
- Summary: RECDeFi is an automated, decentralized, and scalable marketplace that accelerates investment in clean energy and climate solutions by making it faster, cheaper, and easier to trade renewable energy credits, carbon offsets, and other environmental commodities. RECDeFi provides time-stamped asset-linked digital renewable energy credits that enable buyers to match electricity consumption with renewable energy generation on a 24/7 basis to reduce carbon emissions associated with energy use.

#### [ValueNature](https://hedera.com/users/valuenature) - Biodiversity Credit Issuance Platform & Marketplace
- [valuenature.earth](https://valuenature.earth)
- Primary Goal: **Digital MRV (Biodiversity Token)**/**Automated Market**
- Major Partnerships: [Conserve Global](https://conserveglobal.earth/) 
- Summary: ValueNature is creating a Biodiversity metric and MRV framework to scientifically quantify biodiversity. Using NFTs and FTs coupled with device-level edge monitoring, reporting, and verification we trace verified data to a specific ESG asset and issue our Biodiversity credits.

### Demand Platforms
#### [TYMLEZ](https://tymlez.com/) - Guarantee of Origin and Carbon Emissions Reporting
- [tymlez.com](https://tymlez.com/)
- Primary Goal: **Guarantee of Origin and Carbon Emissions Reporting**
- Solutions:
  * [Guarantee of Origin](https://tymlez.com/guarantee-of-origin)
  * [ESG Compliance](https://tymlez.com/esg-compliance)
  * [Smart Energy](https://tymlez.com/smart-energy)
- Major Partnerships: 
  * [Lloyd's Register](https://www.lr.org/en/) - Guarantee of origin for green hydrogen and green ammonia
  * [Magnum Mining and Exploration](https://www.mmel.com.au/) - Guarantee of origin for the green pig iron
  * [UON](https://uon.com.au/) - Carbon emissions calculation and reporting for mine site dewatering
  * [Queensland Government](https://www.qld.gov.au/) - Carbon emissions calculation and reporting for buildings
  * [TROEF](https://www.troef-energy.nl/en/) - A project aimed at decarbonising the Netherlands through energy monitoring and trading solutions
- Summary: TYMLEZ (ASX:TYM) is a pioneer in the development and delivery of carbon reporting and guarantee of origin solutions built using blockchain technology. TYMLEZ provides companies across the globe with world-class solutions designed to empower them in their decarbonisation journeys.  
- Hedera Project References:
  * [Guardian Terraform](https://github.com/Tymlez/guardian-terraform) - Supports single command deployment of the Guardian to AWS/GCP
  * [Open-Source Guardian Contributions](https://github.com/hashgraph/guardian) - TYMLEZ actively contributes to the development of the Open-Source Guardian


#### [SUKU Sustain](https://www.suku.world/suku-omni-1/#omni-sustain) - Supply Chain Environmental Impact Carbon Calculator & Carbon Offset Tool
- [suku.world](https://www.suku.world/suku-omni-1/#omni-sustain)
- Primary Goal:  Carbon Calculator/Consumer Exchange
- Major Partnerships: [Carbon Analytics](https://www.co2analytics.com/), [Moss.Earth](https://moss.earth)
- Summary: To empower brands and customers in the battle against climate change, we’ve integrated the SUKU Scanner app with Carbon Analytics and Moss.Earth.  Our integration with Carbon Analytics allows brands to calculate their CO2 footprint by tracing products from raw ingredients to finished good and, therefore offer differentiated green products with attributes that consumers can view and verify.  Our integration with Moss.Earth allows climate conscious customers to purchase carbon credits to offset the footprint of their purchases while supporting Amazon rainforest initiatives.
- Estimated Demand: TBA

### Help Me Build (Systems Integrators)
#### [Envision Blockchain](https://envisionblockchain.com/) - Enterprise Blockchain System Integrator
- [envisionblockchain.com](https://envisionblockchain.com/)
- Primary Goal: Envision Blockchain Solutions builds applications for the Web3 space. Our mission is to reshape and align today's systems allowing organizations to recognize the new value in tomorrow's Industry Vertical Solutions. Some examples of Envision's Web3 services include Zero-Knowledge Proofs, Tokenization, API Development, System Integration, and Mobile & Web UI/UX Development. We focus on guiding organizations through 3 major milestones on their Web3 journey: Use Case Analysis, Proof of Concept Development, and Scaled Deployments.
- Hedera Project References: 
  * [Open-Source Guardian](https://github.com/hashgraph/guardian): The Guardian is an open-source tool that leverages the Hedera public distributed ledger network to mint emissions and carbon offset tokens. It provides auditable, traceable, reproducible records that document the emission process and lifecycle of carbon credits, which reduce fraud in the ESG market.
  * [HIP - 19](https://github.com/hashgraph/hedera-improvement-proposal/blob/master/HIP/hip-19.md): In collaboration with RECDeFi, established a specification to provide a standard way to use Decentralized Identifiers (DIDs) within Hedera state entity memo fields and thereby support the issuance of Verifiable Credentials about Hedera state entities. Just as the owner of a Hedera entity demonstrates that ownership and so claims associated authorizations via signatures with the private key(s) corresponding to the entity, a controller of a DID demonstrates that control via signatures with (likely) a different private key. Consequently, the DID controller can, when engaging in off-Hedera interactions, effectively demonstrate their association to the Hedera state entity without any on-Hedera transaction.
  * [JavaScript DID SDK](https://github.com/hashgraph/did-sdk-js): Developed a JavaScript version of the [Java DID SDK](https://github.com/hashgraph/did-sdk-java). This repository contains the JavaScript SDK for managing DID Documents & Verifiable Credentials registry using the Hedera Consensus Service.
  * Reveille Digital: Reveille Digital, an industry leading DLT solutions provider focused on the oil and gas industry, wants to leverage innovative solutions such as Distributed Ledger Technology (DLT), Decentralized Identifiers (DIDs) and Verified Credentials (VCs) to offer trackable and immutable Environmental, Social, and Corporate Governance (ESG) metrics. To accommodate Reveille's strategic vision Envision Blockchain established a long-term relationship that focuses on many areas of the Reveille Digital sustainability practice such as advisory, business analysis, solution designing, solution implementation, and solution support. This implementation is based on the standards defined in the IWA's Voluntary Ecological Markets taskforce.
#### [LedgerWorks](https://lworks.io/) - Platform As A Service (PaaS)
- [lworks.io](https://lworks.io/)
- Primary Goal: A PaaS empowering Web3 developers to quickly and easily build fast, reliable and scalable applications.
- Summary: LedgerWorks is a PaaS Web3 company delivering Enterprise Grade services on the Hedera Network. Our purpose is to provide fast, scalable and fault tolerate services upon the Ledger to increase developer capabilities and time to value. We focus on B2B; hence our mission is to empower corporations with unparalleled critical capabilities and corporate services. Our emphasis on DevOps and Core Platform services strives us to attain excellence with Continuous Delivery, Active Monitoring and Observability within the Hedera ecosystem.

- ESG: Within the community we are dedicated to providing discoverable services for ESG assets. We offer a broad spectrum of event based notifications and ESG specific APIs that will enrich the Hedera network; in essence, we provide the capabililites to only receive the data you need when you need it. We allow you to run your systems more efficiently and effectively.

- Our ESG [current offerings](https://www.lworks.io/product):
  * Inquire: Our core data access platform providing an enhanced Mirror Service enabling a scalable, high availability set of API endpoints for accessing all Hedera ledger data.
  * Percieve: Understand your application and customer use by having ready and easy access to metrics related to ledger activity including the creation of custom views of customer and application specific data
  * Sentinel: Our Sentinel DNaaS Allows you to receive real-time notifications for your application's users based on what they care most about… key account updates and transaction activity.  Sentinel supports webhooks, websockets with the ability to subscribe to topics allowing easy creation of notification streams for in-app or downstream processing without costly build and maintenance of production level infrastructure.
### Carbon Negative on Hedera
- List your application & [CET Token ID](https://github.com/InterWorkAlliance/Sustainability/blob/main/vem/demand/cet.md) + Offset Source.

---

## Acknowledgements & Contributions
The information in this document is a collective effort from many people including:

Sergey Metelin, Ken Anderson, Wes Geisenberger, all the builders in the Hedera sustinability community, and many more.

Please submit a [pull-request](https://github.com/dubgeis/SustainabilityEcosystem/pulls) or [issue](https://github.com/dubgeis/SustainabilityEcosystem/issues) if you would like to make any changes or have any comments.

Pull requests:
- Small and atomic (i.e. each pull request should be a change to one location, and in a separate branch if need be)
- Please don’t send pull-requests which change whitespace or line-endings etc

---
## References

---
## Jobs (Post your jobs in the ecosystem here)

[Hedera Ecosystem Jobs Page](https://careers.hedera.community/)



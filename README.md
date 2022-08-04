# .github

# About TalentLayer

TalentLayer is composable, decentralized, open-source infrastructure for talent markets; allowing anyone to easily build interoperable gig marketplaces. It is designed to empower workers to own their own reputation and access jobs without limitation. **TalentLayer’s Alpha is currently in development.**

TalentLayer creates a paradigm shift in how freelance marketplaces operate by creating a universal reputation system and jobs repository that any marketplace can tap into. Users maintain one self-owned reputation across many marketplaces. Marketplaces that build on TalentLayer receive rewards by onboarding talent and jobs.

TalentLayer's architecture provides marketplaces with the most important backend components to get started, allowing marketplaces to be built rapidly, with a stronger focus on great UI/UX design…

TalentLayer ID Universal Reputation System
TalentLayer Universal Jobs Repo
TalentLayer Escrow & Dispute Resolution System

Learn more about [TalentLayer](http://talentlayer.org).

# About Indie (AKA “TalentLayer Indie”)

TalentLayer Indie is a demo tool that was built on TalentLayer. TalentLayer Indie is the first implementation of the TalentLayer Protocol, a decentralized backend for talent marketplaces and sovereign work reputation system. It serves as an example of what can be built using TalentLayer, and is available for forking on Github!

Indie is styled as a reputation tool for independent freelancers. Similar to how you can build up a reputation over time by completing work and receiving reviews on freelancing platforms like Upwork or Freelancer.com, now you and your independent clients can create verified reviews to signal one another’s trustworthiness.

# Integrating TalentLayer into Your Platform

TalentLayer is currently pre-Alpha. The TalentLayer ID Universal Reputation System and TalentLayer Universal Jobs Repo are live in MVP status on Gnosis mainnet, with full smart contracts and searchable graph available for integration today. 

*At this point, our team will work directly with integrating platforms engineers to ensure things go smoothly! We are currently working to expand our documentation going forward, and if you have any questions, don't hesitate to reach out.*

*If you are interested in using TalentLayer's contracts on another chain or L2: we intend TalentLayer to be multi-chain and are down to help deploy elsewhere in a way that keeps implementations on each chain referegcable for all integrated platforms.*

*To guarantee that your implementation will interface with the TalentLayer interoperable jobs repository and/or reputation system you must update your system to the V2 of our data model; coming soon (end of August 2022). The existing data schema does not include a key identifier that represents originating marketplaces/platforms - something necessary for the TalentLayer contracts to know the difference between the various actors writing data to TalentLayer. All future data schema updates should not impact interoperability.*

*Integrating these systems as-is works best for platforms that have existing escrow integrations. If you do not have an escrow system but want to integrate with TalentLayer before our TalentLayer Escrow & Dispute Resolution System launches, we recommend using [Kleros escrow contracts](https://kleros.gitbook.io/docs/products/escrow). TalentLayer's escrow system will be based on Kleros, so if you build an integration with Kleros it should be easily able to be migrated to the eventual TalentLayer Escrow & Dispute Resolution System. We appreciate your patience as we expand our feature set!*

Read the [TalentLayer Docs](https://docs.indie.talentlayer.org/).

View [TalentLayerID.sol](https://github.com/TalentLayer/talentlayer-id-contracts/blob/main/contracts/TalentLayerID.sol).

View [TalentLayerReview.sol](https://github.com/TalentLayer/talentlayer-id-contracts/blob/main/contracts/TalentLayerReview.sol).

View [JobRegistry.sol](https://github.com/TalentLayer/talentlayer-id-contracts/blob/main/contracts/JobRegistry.sol).

Interact with [the TalentLayer Graph](https://docs.indie.talentlayer.org/developers/graph-schema).

If you are considering integrating TalentLayer's Reputation System and Jobs Repo, please reach out to us on Twitter at [@TalentLayer](https://twitter.com/TalentLayer).

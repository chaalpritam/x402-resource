# x402 Resources

> A comprehensive guide to x402 - the protocol enabling pay-per-call APIs and the autonomous AI agent economy

## 📚 Table of Contents

- [What is x402?](#what-is-x402)
- [The Problem x402 Solves](#the-problem-x402-solves)
- [How x402 Works](#how-x402-works)
- [Related Standards](#related-standards)
- [Visual Guides](#visual-guides)
- [Official Documentation](#official-documentation)
- [Use Cases](#use-cases)
- [Real-World Examples](#real-world-examples)
- [Hackathons](#hackathons)
- [Code Examples & Demos](#code-examples--demos)
- [Educational Resources](#educational-resources)
- [Community Articles](#community-articles)
- [Tools & Infrastructure](#tools--infrastructure)
- [How to Contribute](#how-to-contribute)

---

## What is x402?

**x402** is a protocol that enables **pay-per-call API access** using cryptocurrency. It brings the HTTP 402 "Payment Required" status code to life after 28 years of dormancy.

### Core Concepts

**x402** = Pay-per-call for APIs
- Ping an API and pay a microtransaction only when you use it
- No subscriptions, no API keys, no authentication required
- Payment happens directly in the HTTP request

**ERC-8004** = Registry for AI agents on-chain
- Blockchain-based directory of AI agents
- Each agent has an associated wallet
- Enables agent-to-agent payments and discovery

**Together**: x402 lets agents pay each other directly over HTTP while ERC-8004 lets you find those agents on-chain.

---

## The Problem x402 Solves

### Traditional Web2 API Access Flow

The old way requires:
- ❌ Create an account
- ❌ Verify email
- ❌ Provide credit card details and billing address
- ❌ Get locked into a subscription
- ❌ Manage API keys for authentication
- ❌ Repeat all steps when switching providers

**HTTP 402** has been returning "Payment Required" since 1997 without any way to actually facilitate the payment... until now.

### The x402 Solution

With x402:
- ✅ Direct payment per API call
- ✅ No accounts or subscriptions needed
- ✅ No API key management
- ✅ Instant provider switching
- ✅ Perfect for autonomous AI agents
- ✅ Built-in spam protection (paywall = security)

![Before and After](./before-after.jpeg)

---

## How x402 Works

x402 is built on **thirdweb Nexus**, a hosted proxy that unlocks the 402 status code on any API.

### For API Providers (Developers)

1. Set pricing for your API routes
2. Configure authentication rules
3. Deploy (most APIs require **no code changes**)

### For API Consumers (AI Agents)

1. Discover APIs through registries
2. Send HTTP request with payment
3. Get instant access - no setup required

This enables AI agents to **use the entire internet** without humans setting up accounts or managing API keys.

---

## Related Standards

- **x402** - Pay-per-call API protocol
- **ERC-8004** - AI agent registry standard
- **ERC-8041** - Related Ethereum standard
- **ERC-3009** - Transfer with authorization

---

## Visual Guides

![x402 Explained](./x402.jpeg)

*Visual explanation of the x402 protocol architecture*

---

## Official Documentation

- [Coinbase x402 Product Page](https://www.coinbase.com/en-in/developer-platform/products/x402)
- [Coinbase x402 Launch Announcement](https://www.coinbase.com/en-in/developer-platform/discover/launches/x402)
- [Solana x402 Overview](https://solana.com/x402/what-is-x402)
- [Intro to x402 - Developer Guide](https://solana.com/developers/guides/getstarted/intro-to-x402)
- [x402 Official Website](https://x402.org/)

---

## Use Cases

x402 enables micropayments and pay-per-use models for:

### Digital Services
- 🎫 Event tickets
- 💾 Cloud storage fees
- 🌐 Domain registration
- 🖥️ Hosting services
- 📦 Data transfer costs

### Software & APIs
- 🔑 Software licenses
- 💻 API access (pay-per-call)
- 🎮 In-app purchases
- 🔄 Premium features

### Business Models
- 💳 One-time fees
- 🔄 Recurring billing
- 📊 Subscription payments
- 💰 Freelance services
- 🎬 Streaming subscriptions

### E-commerce
- 🛒 E-commerce checkout
- 💵 Reservation deposits
- ⬆️ Hardware upgrades

---

## Real-World Examples

### The Agentic Economy is Here

A developer built **5 AI agents in 7 days** that:
- 💰 Earn revenue in USDC
- 💳 Pay for services on BASE blockchain
- 🤖 Run 24/7 autonomously

**The Agents:**
- 🌉 Bridge aggregator
- 🛡️ MEV detector
- 🔍 Contract scanner
- 🐋 Whale tracker
- 💰 P&L calculator

**Key Insight:** Apps need humans to transact. **Agents transact autonomously.**

Built using [@daydreamsagents](https://twitter.com/daydreamsagents) - live and working today.



---

## Hackathons

Want to build with x402? Join the hackathon:
- 🏆 [Solana x402 Hackathon](https://solana.com/x402/hackathon)

---

## Code Examples & Demos

### Official Repositories

- [Coinbase x402 - Main Repository](https://github.com/coinbase/x402)
- [x402 PR #542 - Notable Implementation](https://github.com/coinbase/x402/pull/542)

### Community Projects

- [Vend - Payment Gateway](https://github.com/usmaneth/Vend/)
- [x402 Vending Machine](https://github.com/heurist-network/x402-vending-machine)
- [x402 Gated API](https://github.com/jarrodwatts/x402-gated-api)
- [x402 Sovereign Implementation](https://github.com/Dhaiwat10/x402-sovereign)
- [x402 Solana Examples](https://github.com/Woody4618/x402-solana-examples)
- [Eliza OS MCP Gateway](https://github.com/elizaOS/mcp-gateway/tree/main)
- [Lucid Agents by Daydreams AI](https://github.com/daydreamsai/lucid-agents)

### Live Demos

- [x402 Demo by AnySpend](https://x402-demo.anyspend.com/)
- [OpenX402 Demo](https://x.com/openx402/status/1985764649971978252)

---

## Educational Resources

### Video Tutorials

- 📹 [x402 Explained - Comprehensive Guide](https://www.youtube.com/watch?v=Dg5IplJ1mng)
- 📹 [Building with x402 - Tutorial](https://www.youtube.com/watch?v=iaIxRxvp9Vk)
- 📹 [Dabit3's x402 Demo](https://x.com/dabit3/status/1982658854346494042)
- 📹 [Finematics on x402](https://x.com/finematics/status/1982810231512994014)
- 📹 [x402 Implementation Guide](https://x.com/akashneelesh/status/1985633919329583402)

### Written Guides & Tutorials

- [Suhail Kakar's x402 Overview](https://x.com/SuhailKakar/status/1982787779772768261)
- [Dhaiwat's x402 Implementation](https://x.com/dhaiwat10/status/1984325028687855981)
- [Jarrod Watts' x402 Tutorial](https://x.com/jarrodWattsDev/status/1983075160178696665)
- [Ben Hummuson x402 Guide](https://x.com/hummusonrails/status/1983115447689257164)
- [Chris Kim's x402 Demo](https://x.com/chriskim_dev/status/1983200236530217298)
- [Nader Dabit's x402 Introduction](https://x.com/dabit3/status/1981777610142367958)

---

## Community Articles

### In-Depth Analysis

- [Agentic Commerce: Why x402 is Just the Beginning - LongHash VC](https://www.longhash.vc/post/agentic-commerce-why-x402-is-just-the-beginning)

### Community Perspectives

- [YQ on x402 Architecture](https://x.com/yq_acc/status/1983260307251479024)
- [YQ on ERC-8004](https://x.com/yq_acc/status/1985302546349425147)
- [Jarrod Watts' x402 Thoughts](https://x.com/jarrodwatts/status/1982036553481568512)
- [Jarrod Watts on Agent Economy](https://x.com/jarrodwatts/status/1986406098681893096)
- [Abruzuc's x402 Analysis Part 1](https://x.com/abruzuc/status/1983229012122988830)
- [Abruzuc's x402 Analysis Part 2](https://x.com/abruzuc/status/1986861150055899383)
- [Abruzuc's x402 Analysis Part 3](https://x.com/abruzuc/status/1985753258795942366)
- [Yash on x402 Implementation](https://x.com/yashhsm/status/1985232040908685526)
- [YashasEdu's x402 Tutorial](https://x.com/YashasEdu/status/1985635276514082963)
- [13yearoldvc on x402](https://x.com/13yearoldvc/status/1983950251359924337)
- [Dhaiwat's x402 Guide](https://x.com/dhaiwat10/status/1981933653824540689)
- [Dhaiwat on x402 Architecture](https://x.com/dhaiwat10/status/1982057476494131300)
- [Jinglingcookies' x402 Thread](https://x.com/jinglingcookies/status/1980273307997049228)
- [Howdy Merry's x402 Analysis](https://x.com/howdymerry/status/1982541964647252405)
- [Genius Yinka on x402](https://x.com/geniusyinka/status/1982866070663827723)
- [JSKuros' x402 Perspective](https://x.com/jskuros/status/1983303575590801472)
- [S4mmyEth on x402](https://x.com/S4mmyEth/status/1981672515844878508)
- [Dan Kim's x402 Analysis](https://x.com/dankimxyz/status/1985784469895463148)
- [Miles Deutscher on x402](https://x.com/milesdeutscher/status/1985465142881202660)
- [ELI5 DeFi - x402 Explained Part 1](https://x.com/eli5_defi/status/1985346332706709923)
- [ELI5 DeFi - x402 Explained Part 2](https://x.com/eli5_defi/status/1983467514001813704)

---

## Tools & Infrastructure

### Essential Platforms

- 🌐 [x402.org - Official Hub](https://x402.org/)
- 🔒 [x402 Secure - Security Tools](https://www.x402secure.com/)
- 📊 [x402 Scan - Explorer](https://www.x402scan.com/)
- 💬 [x402 Chat - Community](https://x402.chat/)
- 📈 [ERC-8004 Analytics on Dune](https://dune.com/hashed_official/erc8004)

---

## How to Contribute

x402 is an evolving standard with many opportunities to contribute:

### Priority Areas

- 🛡️ **Reputation Systems** - Build trust mechanisms for agents
- 🔐 **Privacy** - Enhance privacy-preserving payment methods
- 🚨 **Fraud Detection** - Develop anti-fraud tools
- 🔍 **Agentic Search** - Improve agent discovery
- 📋 **Extending the Spec** - Propose protocol improvements
- 🌍 **Multi-Token/Multi-Chain** - Enable cross-chain compatibility

### General Contributions

- 📚 **Documentation** - Improve guides and tutorials
- 🔧 **Improving x402scan** - Enhance the explorer
- 📖 **Useful Resources** - Curate educational content
- 🎯 **Discoverability** - Better agent/API finding tools
- ✍️ **Tutorials** - Create learning materials

---

## License

This is a community-curated resource. Individual projects and tools may have their own licenses.

## Contributing to This Resource

Found a broken link or want to add something? Contributions are welcome! This repository aims to be the most comprehensive x402 resource guide available.

---

*Last Updated: November 2025*

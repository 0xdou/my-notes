# ETHGlobal Cannes - Trust Circle Prize Fit Analysis

**Date:** March 25, 2026  
**Event:** ETHGlobal Cannes (July 4-6, 2025)  
**Total Prize Pool:** ~$275,000+  

---

## 🎯 Target Tracks - Fit Assessment

### 1. **World - $20,000** ✅ PERFECT FIT

| Prize | Amount | Fit |
|-------|--------|-----|
| 🏆 Best Mini App | $17,000 (1st: $6,500, 2nd: $4,500, 3rd: $2,000, HM: $1,000 x4) | ⭐⭐⭐⭐⭐ |
| 🏊 World Pool Prize | $3,000 (split ~38 teams, ~$79 each) | ⭐⭐⭐⭐ |

**Requirements:**
- ✅ Build Mini App with MiniKit
- ✅ Integrate MiniKit SDK Commands (World ID + minikit.pay)
- ✅ Deploy contracts to World Chain
- ✅ Proof validation in web backend or smart contract
- ❌ NO gambling/chance-based (we're clear)

**Why We Win:**
- Instant access to 23M World App users
- Zero gas fees on World Chain (Superchain)
- MiniKit handles wallet + transactions seamlessly
- Real use case for World ID (Proof of Personhood)
- Judges love "real user base" projects

**Verdict:** **PRIMARY TARGET** - This is our strongest track. The social lending + World ID combo is unique and impactful.

---

### 2. **LayerZero - $20,000** ✅ STRONG FIT

| Prize | Amount | Fit |
|-------|--------|-----|
| 🏆 Best Omnichain Interaction | $12,500 (1st: $6,500, 2nd: $4,500, 3rd: $1,500) | ⭐⭐⭐⭐⭐ |
| 🏆 Best Omnichain DeFi Primitive | $7,500 (1st: $4,500, 2nd: $3,000) | ⭐⭐⭐⭐ |

**Requirements:**
- ✅ Deploy LayerZero V2 Contract
- ✅ Public GitHub repo
- ✅ Show working demo (LayerZero Scan tx hash)
- ✅ Complete feedback form

**Our Angle - "Omnichain Identity & State":**
> *"Managing a user's data or application state (e.g., game progress, user profiles) seamlessly across chains"*

Trust Circle does exactly this:
- Trust scores propagate across chains via lzRead
- User reputation is chain-agnostic
- Borrow on Base, repay on Arbitrum, vouch on World Chain

**Why We Win:**
- Non-token transfer use case (they specifically want this!)
- Uses OApp (push) + lzRead (pull) + potentially Composer
- Real DeFi primitive (cross-chain lending)
- Complex state synchronization (trust scores)

**Verdict:** **PRIMARY TARGET** - Cross-chain trust propagation is a perfect fit for "Omnichain Identity & State" category.

---

### 3. **Circle - $10,000** ✅ GOOD FIT

| Prize | Amount | Fit |
|-------|--------|-----|
| 🏆 Multichain USDC Payment System | $4,000 (1st: $2,500, 2nd: $1,500) | ⭐⭐⭐⭐ |
| 🏆 Enable Gas Payment in USDC | $2,000 | ⭐⭐⭐ |
| 🏆 Create Gasless Experience | $2,000 | ⭐⭐⭐⭐⭐ |
| 🏆 Smart Wallet with Security Controls | $2,000 | ⭐⭐⭐ |

**Requirements:**
- ✅ Functional MVP + architecture diagram
- ✅ Video demo + presentation
- ✅ GitHub/Replit repo link

**Our Best Angle - "Create a Gasless Experience":**
> *"Leverage Circle Wallets and the Gas Station feature to create a fully gas sponsored user experience"*

Trust Circle already does this via World Chain, but we can integrate Circle:
- Use Circle Wallets for user onboarding
- Gas Station sponsors loan disbursement transactions
- USDC as native loan currency
- CCTP V2 for cross-chain USDC transfers (bonus points!)

**Why We Win:**
- Gasless is core to our UX (World Chain + Circle Gas Station)
- USDC is the loan currency (natural fit)
- Multichain payouts via CCTP V2 (if we add it)

**Verdict:** **SECONDARY TARGET** - Good fit, but we need to explicitly integrate Circle Wallets/Gas Station (not just USDC). Worth the $2k-4k potential.

---

### 4. **ENS - $10,000** ✅ MODERATE FIT

| Prize | Amount | Fit |
|-------|--------|-----|
| ✨ Most Creative Use Case | $7,000 (1st: $2,000 x2, 2nd: $1,500 x2) | ⭐⭐⭐⭐ |
| 🏅 Best Use of ENS | $3,000 | ⭐⭐⭐⭐ |

**Requirements:**
- ✅ ENS must be core to product (not afterthought)
- ✅ Functional demo (no hard-coded values)
- ✅ Video recording or live demo

**Our Angle:**
> *"Storing interesting data in text records (like verifiable credentials or zk proofs)"*

Trust Circle uses ENS for:
- User identification (instead of wallet addresses)
- Vouching system (voucher → borrower via ENS names)
- Potential: Store trust scores in ENS text records
- Potential: ENS subnames for "trust circles" (e.g., `dou.trustcircle.eth`)

**Why We Could Win:**
- ENS is how users find each other (core flow, not afterthought)
- Creative: Trust scores as verifiable credentials in ENS records
- Subnames for circle branding

**Verdict:** **TERTIARY TARGET** - ENS is useful but not core to our value prop. Could add ENS text record storage for trust scores as a stretch goal.

---

## 💰 Total Prize Potential

| Track | Target Prize | Confidence |
|-------|-------------|------------|
| World (Best Mini App) | $6,500 (1st) | High |
| LayerZero (Omnichain Interaction) | $6,500 (1st) | High |
| Circle (Gasless Experience) | $2,000 (1st) | Medium |
| ENS (Best Use) | $1,500 (2nd) | Medium |
| **Total Potential** | **~$16,500** | |
| **Conservative Estimate** | **~$8,000-12,000** | |

---

## 🏆 Additional Sponsors to Consider

Based on search results, these sponsors also have prizes:

### **0G Labs** - Part of $275K pool
- Decentralized storage, DA layer, AI compute
- **Fit:** ⭐⭐ - Could store trust history on 0G storage, but not core

### **1inch** - $20,000 total
- Non-EVM extensions, Limit Order Protocol, APIs
- **Fit:** ⭐ - Not relevant for our use case

### **Oasis Protocol** - $10,000
- Confidential compute, Sapphire chain
- **Fit:** ⭐⭐ - Privacy-preserving credit scoring? Stretch.

### **The Graph** - Likely $10K+
- Indexing, subgraphs
- **Fit:** ⭐⭐⭐ - Could index trust relationships, query efficiently

### **Chainlink** - Part of pool
- Oracles, CCIP, Functions
- **Fit:** ⭐⭐⭐ - CCIP for cross-chain messaging (alternative to LayerZero), Functions for off-chain credit calculations

---

## 🎯 Recommended Strategy

### **Phase 1: Core Build (Days 1-2)**
Focus on winning tracks:
1. ✅ World Mini App with MiniKit (World ID + minikit.pay)
2. ✅ LayerZero V2 for cross-chain trust propagation
3. ✅ USDC loans on World Chain (gasless)

### **Phase 2: Enhancement (Day 2-3)**
Add prize-boosting features:
1. ✅ Circle Wallets integration (for Circle prize)
2. ✅ ENS names for user identification
3. ✅ Architecture diagram + video demo

### **Phase 3: Polish (Final 6 hours)**
1. ✅ Submit all 4 prize tracks
2. ✅ Complete feedback forms (LayerZero, World, Circle, ENS)
3. ✅ Record demo video
4. ✅ Ensure git history shows progress (no single-commit!)

---

## ⚠️ Critical Requirements Checklist

### **All Tracks:**
- [ ] Public GitHub repo with proper commit history (NO single-commit!)
- [ ] Functional MVP (not just slides)
- [ ] Video demo (2-3 min max)
- [ ] Architecture diagram
- [ ] Live deployment (testnet is fine)

### **World-Specific:**
- [ ] MiniKit SDK integrated
- [ ] World ID verification in flow
- [ ] Contracts deployed to World Chain
- [ ] minikit.pay for loan disbursement

### **LayerZero-Specific:**
- [ ] LayerZero V2 contract deployed
- [ ] LayerZero Scan tx hash showing cross-chain message
- [ ] Feedback form submitted

### **Circle-Specific:**
- [ ] Circle Wallets or Gas Station integrated
- [ ] USDC as loan currency
- [ ] Architecture diagram showing Circle flow

### **ENS-Specific:**
- [ ] ENS names used for user identification
- [ ] Not hard-coded (real resolution)
- [ ] Clear explanation of why ENS matters

---

## 🚀 Winning Pitch Angle

> **"Trust Circle brings uncollateralized lending to 23M World App users. Using World ID for proof of personhood, LayerZero for cross-chain reputation, and Circle USDC for seamless payments, we're solving DeFi's biggest problem: over-collateralization. No wallet setup, no gas fees, just trust."**

**Key Metrics to Highlight:**
- 23M potential users (World App)
- $0 gas fees (World Chain + MiniKit)
- Cross-chain from day 1 (LayerZero)
- Real-world parallel (Grameen Bank's 97% repayment rate)

---

## 📊 Competition Analysis

**Why We Stand Out:**
1. **Real distribution** - 23M World users (most projects have zero users)
2. **Cross-chain native** - Not an afterthought, core to design
3. **Solves real problem** - Over-collateralization is DeFi's #1 UX issue
4. **Sustainable model** - 5% fees cover 3-5% defaults (microfinance-proven)
5. **Zero friction** - No wallet, no gas, mobile-native

**Common Competitor Weaknesses:**
- No user base
- Single-chain only
- Gambling/speculation (disqualified from World prizes)
- Over-engineered, no real use case
- Single-commit repos (disqualified)

---

## 🎤 Judge Q&A Prep

**Q: "What if people don't repay?"**
> "We design for 95%+ repayment through social collateral (your friends lose capacity if you default), progressive trust (start with $50, earn up to $5000), cross-chain reputation lock-in (default once, burned everywhere), and auto-repayment. Mirrors Grameen Bank's 97% repayment model."

**Q: "Where does lending capital come from?"**
> "Phase 1: Protocol-owned liquidity for MVP. Phase 2: LPs deposit USDC, earn 5% loan fees. Phase 3: Risk-based pricing, tranche structure for LP protection."

**Q: "How is this different from existing credit protocols?"**
> "Existing protocols (Aave, Compound) require 150%+ collateral. We're uncollateralized, backed by social trust + Proof of Personhood. Plus, we're mobile-native with zero gas fees - existing protocols are desktop DeFi with high friction."

**Q: "Why LayerZero? Why not CCIP or Axelar?"**
> "LayerZero V2's lzRead is perfect for pulling trust state on-demand. We evaluated CCIP, but LayerZero's developer experience + existing integrations made it the right choice for a 3-day hackathon."

---

## ✅ Final Recommendation

**Trust Circle is an EXCELLENT fit for ETHGlobal Cannes:**

1. **Primary Tracks:** World ($17K) + LayerZero ($12.5K) = **$29.5K potential**
2. **Secondary Tracks:** Circle ($4K) + ENS ($7K) = **$11K potential**
3. **Realistic Win:** $8K-16K total (multiple prizes)

**Key Success Factors:**
- Execute clean MVP in 48 hours
- Show real cross-chain tx (LayerZero Scan)
- Demo the zero-friction World Mini App flow
- Proper git history (commit as you build!)
- Submit all 4 prize feedback forms

**Go win this! 🏆🦍**

---

*Analysis by Sassy*

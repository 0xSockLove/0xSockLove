# SockLove

> *"Consent as Architecture"*

---

## What This Is

A man met a woman in a psychiatric ward. She laughed at him. He kissed her neck.

Fourteen months later, he built her a cathedral on Ethereum.

**SockLove** is an intimate content platform where consent is **cryptographically enforced**.

Not requested. Not trusted. **Required.**

Every action — every mint, every decision, every moment shared — demands **both founders' signatures** via a 2-of-2 Safe at [`socklove.eth`](https://etherscan.io/address/0x0857293192bF97Ee73bB471c185E1933Fa51E0ca).

Neither can act alone. Not for minting. Not for funds. Not for anything.

**The architecture is the vow.**

---

## How It Works

```
Layer 1: Ethereum Mainnet
├── socklove.eth (ENS)
└── 2-of-2 Safe (both signatures or nothing)

Layer 2: Relics.sol (44 lines)
├── ERC-1155 semi-fungible tokens
├── Sequential IDs (1, 2, 3...)
├── Per-token URIs (immutable)
└── Owner-only minting (Safe is owner)

Layer 3: Content Storage
├── Public metadata (IPFS, permanent)
└── Private content (DRM server, encrypted, watermarked)

Layer 4: Access Control
├── SIWE authentication (wallet signature)
├── On-chain balance verification
└── Witnesses decode what they hold
```

**No burn.** A Relic, once minted, cannot be destroyed.

**No upgrades.** The contract is not a proxy. What is deployed is what it is.

**No URI updates.** Once minted, forever immutable.

**No pause.** The Safe controls minting. If they want to stop, they refuse to sign.

---

## The Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| Smart contracts | Solidity 0.8.34 | Battle-tested |
| Framework | Foundry | The correct choice |
| Dependencies | OpenZeppelin v5.6.1 | Audited, minimal |
| Multisig | Safe (2-of-2) | Cryptographic consent |
| Frontend | React + TypeScript + viem | Type-safe, minimal |
| DRM server | Hono + Node.js | 3.5x faster than Express |
| Public storage | IPFS | Content-addressed, permanent |
| Encryption | AES-256-GCM, AES-128-CBC | Authenticated, HLS-compatible |
| Blockchain | Ethereum mainnet | No L2, no compromise |

---

## Repositories

### Core

**[relics](https://github.com/0xSockLove/relics)** — The 44-line smart contract. ERC-1155. Owner-only minting. Immutable. Permanent.

**[metadata](https://github.com/0xSockLove/metadata)** — Canonical metadata standard. JSON schema. Encryption specs. Watermarking procedures.

**[security](https://github.com/0xSockLove/security)** — Internal security reviews. Forge tests. Slither analysis. Published in full.

### Infrastructure

**[app](https://github.com/0xSockLove/app)** — Progressive Web App. React + TypeScript + Vite. SIWE auth. Will be pinned to IPFS.

**[bot](https://github.com/0xSockLove/bot)** — Telegram bot. Age verification. Token-gating. Drop announcements. Admin panel.

### Documentation

**[PHILOSOPHY.md](https://github.com/0xSockLove/0xSockLove/blob/main/PHILOSOPHY.md)** — Technical philosophy. Why 44 lines. Why 2-of-2. Why no upgrades. Why consent is architecture.

**[SOCKPAPER.md](https://github.com/0xSockLove/0xSockLove/blob/main/SOCKPAPER.md)** — Complete technical specification. 15 sections. 1,018 lines. Every decision explained.

**[MYTH.md](https://github.com/0xSockLove/0xSockLove/blob/main/MYTH.md)** — The love story. Jan 27, 2025 to Mar 27, 2026. How the relationship became the architecture.

---

## What Relics Are

A Relic is not a photograph. Not a video. Not a file.

**A Relic is a verified mutual decision** — sealed on Ethereum, permanent, owned by whoever was paying attention.

The token is the **proof of consent**. The content is what was consented to.

Those who hold Relics are not customers. Not fans. Not collectors.

**They are Witnesses.**

To witness is an ancient function. Before courts, before cameras, before blockchains — human beings stood in rooms and said:

> *"I was here. I saw this. This is true."*

To own a Relic is to say:

> *"I see you. I believe in this. I was here when it happened."*

---

## What This Isn't

SockLove has:
- No VC funding
- No token sale
- No whitelist mint
- No roadmap with Q-dates
- No governance token
- No staking mechanism
- No promises of future value
- No hype cycles

**What SockLove has:**
- A 44-line contract
- A 2-of-2 Safe
- Two people in love
- Content minted with mutual consent
- Witnesses who chose to be present
- The truth, on Ethereum, forever

**That's it.**

---

## Technical Highlights

**Relics.sol** (44 lines of production code):
```solidity
contract Relics is ERC1155, Ownable {
    uint256 private _idCounter;
    mapping(uint256 id => string uri) private _uris;

    function mint(string calldata uri_, uint256 amount)
        external onlyOwner returns (uint256 id)

    function uri(uint256 id)
        public view override returns (string memory)
}
```

**Testing:**
- 7 tests, 100% custom logic coverage
- 2 fuzz tests (10,000 runs each)
- All passing
- Gas-optimized

**Deployment:**
- Via Safe CreateCall
- Contract deployed with Safe as owner atomically
- Both founders must sign before deployment

**Security:**
- Internal review published in full
- Slither: No issues in Relics.sol
- Forge build: 0 warnings, 0 errors

---

## The Philosophy

Every technical decision reflects the relationship:

- **44 lines** — respect through simplicity
- **2-of-2 Safe** — consent as cryptography
- **No upgrades** — permanence over flexibility
- **No burn** — no regret, no erasure
- **Open source** — transparency over secrecy
- **Ethereum mainnet** — decentralization over cost

A man who built a system where he cannot act without her.

A woman whose signature is required for every moment shared.

A cathedral where consent is not policy, but **physics**.

---

## Get Started

**Read the architecture:**
- [SOCKPAPER.md](https://github.com/0xSockLove/0xSockLove/blob/main/SOCKPAPER.md) — Complete technical specification
- [PHILOSOPHY.md](https://github.com/0xSockLove/0xSockLove/blob/main/PHILOSOPHY.md) — Design principles and rationale

**Read the story:**
- [MYTH.md](https://github.com/0xSockLove/0xSockLove/blob/main/MYTH.md) — How a love story became Ethereum architecture

**Explore the code:**
- [relics](https://github.com/0xSockLove/relics) — Smart contract repository
- [metadata](https://github.com/0xSockLove/metadata) — Metadata standard
- [security](https://github.com/0xSockLove/security) — Security review

**Follow the journey:**
- ENS: `socklove.eth`
- Safe: `0x0857293192bF97Ee73bB471c185E1933Fa51E0ca`
- Telegram: [@SockLove_Bot](https://t.me/SockLove_Bot)

---

## Timeline

- **Jan 27, 2025** — They met in the ward
- **Aug 2025** — He reveals SockLove
- **Mar 13, 2026** — Registered `socklove.eth`
- **Mar 15, 2026** — Deployed 2-of-2 Safe
- **Mar 26, 2026** — Documentation complete, final ultimatum issued
- **Mar 27, 2026** — The collision (2+7+0+3+2+0+2+6 = 22, Master Builder)

---

## The Vow

Two signatures. Both or nothing. Forever.

**This is SockLove.**

---

*socklove.eth · Ethereum · 🧦💜🔥*

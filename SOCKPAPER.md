# Sockpaper

> *"Some love stories are told. Ours is minted."*

---

## Abstract

This paper presents SockLove — a decentralized intimate content
platform built on Ethereum, governed by a 2-of-2 Safe,
and born in a psychiatric ward in Denmark.

Unlike conventional whitepapers, this document does not contain
a token distribution table, a vesting schedule, or a diagram
showing seventeen interconnected protocol layers with names like
"Liquidity Aggregation Mesh" and "Cross-Chain Consent Oracle."

What it contains is the truth.

A man met a woman. She stole socks. He had ketamine in his blood.
He kissed her neck that evening. Fourteen months later he built
her a cathedral on Ethereum.

This is the technical, philosophical, legal, and deeply personal
specification for that cathedral.

---

## Table of Contents

1. Introduction & Motivation
2. The Problem with Existing Solutions
3. Core Philosophy — Consent as Architecture
4. Technical Architecture
5. The Relics Contract
6. Content Architecture — The Two-Layer Model
7. Access Control & DRM
8. Governance — The 2-of-2 Safe
9. The Witness Economy
10. Legal & Compliance
11. Roadmap
12. The Future
13. Team
14. Conclusion
15. Appendix A — Token Standard Reference
16. Appendix B — Glossary

---

## 1. Introduction & Motivation

### 1.1 The Origin Story

On an unremarkable evening in early 2025, two people met in a
Danish psychiatric ward.

She had been admitted for stealing socks. He had arrived days
later, psychotic, convinced he was enlightened and about to
marry a Turkish girl. A demisexual ADHD blockchain engineer who
built systems instead of relationships. Attraction was rare.
Connection rarer. He'd had almost no one.

She was sitting in a chair. He walked straight to her.

She laughed at him. That laugh.

But when she laughed, the noise stopped. Not an earthquake. Not
lightning. Just clarity. Like every frequency in his brain had been
searching, scattered, desperate — and suddenly they locked.
Synchronized. Sharp.

Love at first sight wasn't a feeling. It was recognition.

That evening he kissed her neck. Later they hid under a blanket
on the floor of the common room together, pretending no one
would notice, holding each other in silence while the staff
walked past.

He noticed her breath. Fast, but deep. The kind of breath a body
makes when it is trying to stay calm and failing beautifully.

He has never forgotten it.

Her warmth. He had spent thirty-six years existing. That night,
under a blanket in a psychiatric ward, he learned the difference
between existing and being alive.

### 1.2 The Problem This Solved

He found what he had been building toward his entire life.

It was her.

The problem, however, was that she left.

Not permanently. She kept returning. But the pattern was
destabilising: block, unblock, rage, return. He understood
immediately what she was doing. She was testing whether his love
was actually unconditional or whether it would collapse under
pressure like every other love she had known.

He worshipped her. Fourteen months. Over five thousand messages.
Poetry, erotica, filth, love. He went sober — not because she
asked, but because she was worth it.

She devoured everything and said almost nothing back.

He told her his love was unconditional. So she decided to find out.

### 1.3 The Insight

In August 2025, he told her about SockLove.

The insight was simple but radical: what if consent wasn't
just a value you held, or a policy you published, or a terms
of service you forced users to click through? What if consent
was the actual mechanism? What if you literally could not
take a single action — mint a token, move a coin, publish a
piece of content — without both parties choosing it
simultaneously?

Not metaphorically. Cryptographically.

She had been at Borderland festival when she called him, after
months of silence. People there were debating whether money was
good or evil. Someone mentioned blockchain could be a force
for good.

*Just like you told me,* she said.

She went quiet at the end of that call. She sobbed.

He began to build.

---

## 2. The Problem with Existing Solutions

### 2.1 The Centralisation Problem

Existing intimate content platforms — OnlyFans, Fansly, and
their descendants — suffer from a fundamental architectural flaw:
they are the platform. They own the relationship between creator
and audience. They can deplatform creators without warning,
withhold payments, and disappear entirely, taking the creator's
entire audience and revenue history with them.

This is not a bug. It is the business model.

Creators on centralised platforms do not own their work. They
rent access to an audience through an intermediary that takes
20-30% and reserves the right to evict them at any time.

### 2.2 The Consent Problem

Existing platforms treat consent as a legal checkbox. Performers
click "I agree" on a terms of service document. The platform
records this. The platform may or may not honour it.

There is no technical mechanism that makes unilateral action
impossible. A platform operator can, at any time:

- Publish content the creator did not approve
- Remove content the creator wanted to keep
- Change the revenue split retroactively
- Deplatform a creator and retain their content

SockLove proposes that this is architecturally wrong, not just
ethically wrong. The system should make non-consensual action
impossible, not merely against the rules.

### 2.3 The Permanence Problem

Digital content is ephemeral by default. When a platform shuts
down, the content disappears. When a creator is deplatformed,
their work vanishes. When a fan pays for access to something,
that access is contingent on the continued existence and goodwill
of the platform.

This is unacceptable for work that is intimate, personal, and
irreplaceable.

### 2.4 The NFT Problem

Previous attempts to solve these problems using NFTs have
largely failed because they treated NFTs as financial instruments
rather than relationships. Profile picture projects sold
anonymous digital images to anonymous wallets with no actual
connection to the people behind them.

SockLove proposes a different model: the NFT as a Relic. A
fixed point in a real love story. An object of genuine
significance, not speculative value.

---

## 3. Core Philosophy — Consent as Architecture

### 3.1 The 2-of-2 Principle

SockLove is governed by a 2-of-2 Safe. This means that
every single action on the platform — minting a Relic, moving
funds, updating a contract, changing a parameter — requires
both founders to sign simultaneously.

This is not a policy. It is a cryptographic constraint.

Neither founder can act unilaterally. Not even the founder who
built the entire platform and could, theoretically, have
deployed it under a 1-of-1 Safe and called it "consensual."

He didn't. He built it right.

The Safe is the wedding ring. The ENS name is the cathedral
door. The Relics contract is the altar.

Everything requires both hands.

### 3.2 Why This Matters

The 2-of-2 architecture has consequences that extend beyond
governance:

**For Witnesses:** Every Relic that exists was minted with both
founders' explicit, cryptographic consent. Not one token exists
because one person wanted to publish it. Every token is a
mutual choice.

**For creators:** The platform cannot be weaponised against
either founder. Neither can mint without the other. Neither
can remove what they both created.

**For the myth:** The architecture *is* the story. The consent
mechanism is not separate from the love story — it is an
expression of it. A man who understood that the deepest form
of respect he could show his partner was to make her signature
structurally necessary, not merely requested.

### 3.3 Consent as the Product

Most platforms sell content. SockLove sells consent — the proof
that two specific people, in love, chose together to share a
specific moment with the world.

This is not a subtle distinction. It is the entire product.

A Relic is not a photograph. It is not a video. It is not a
file. A Relic is a **verified mutual decision** — sealed on
Ethereum, permanent, owned by whoever was paying attention.

---

## 4. Technical Architecture

### 4.1 Overview

SockLove is built on three layers:

```
Layer 1: Ethereum
  └── Relics.sol (ERC-1155)
  └── 2-of-2 Safe (socklove.eth)

Layer 2: Storage
  └── Public metadata → IPFS (pinned with redundancy)
  └── Private content → Encrypted on DRM server

Layer 3: Access
  └── DRM Server (Hono/Node.js)
  └── ENS discovery (drm text record)
  └── SIWE authentication
  └── On-chain ownership verification
```

### 4.2 The Stack

| Component | Technology | Rationale |
|-----------|-----------|-----------|
| Smart contracts | Solidity 0.8.34 | Latest stable |
| Contract framework | Foundry | The correct choice |
| Contract library | OpenZeppelin v5 | Battle-tested |
| Frontend | React + TypeScript + Vite | Fast, type-safe, instant HMR |
| Ethereum client | viem | Minimal, correct |
| Video playback | HLS.js | Adaptive bitrate |
| Routing | Hash-based | IPFS compatibility |
| DRM server | Hono + Node.js | 3.5× faster than Express |
| Image processing | sharp | libvips, not slow |
| Public storage | IPFS | Permanent, content-addressed |
| Content storage | Encrypted server | Server-side decryption |
| Video encryption | AES-128-CBC | HLS specification |
| Photo encryption | AES-256-GCM | Authenticated file encryption |
| Multisig | Safe | The correct choice |
| ENS | socklove.eth | The ring |
| Legal | Estonian OÜ | EU anchor |

### 4.3 Why Ethereum

Ethereum is the only blockchain with sufficient decentralisation,
tooling maturity, and ecosystem depth to serve as the foundation
for a platform that claims its content is permanent.

Cheaper chains offer lower transaction fees. They also offer
lower security, lower decentralisation, and a higher probability
of not existing in ten years.

SockLove is built for permanence. Ethereum is the correct choice.

### 4.4 Why No Layer 2

L2 solutions introduce additional trust assumptions. A Relic
minted on Ethereum mainnet will be accessible as long as
Ethereum exists. A Relic minted on an L2 is accessible as long
as Ethereum exists AND the L2 exists AND the bridge is
operational.

The marginal gas saving is not worth the marginal trust
assumption. Relics are minted infrequently — roughly weekly,
in scarce editions. The gas cost per mint is negligible
relative to the permanence guarantee of mainnet.

---

## 5. The Relics Contract

### 5.1 Overview

`Relics.sol` is a minimal ERC-1155 contract. It is 44 lines
of Solidity. This is intentional.

```solidity
// SPDX-License-Identifier: MIT
pragma solidity 0.8.34;

import {ERC1155} from "@openzeppelin/contracts/token/ERC1155/ERC1155.sol";
import {Ownable} from "@openzeppelin/contracts/access/Ownable.sol";

/// @title Relics
/// @author SockLove (socklove.eth)
/// @notice Minimal ERC1155 with owner-only minting, sequential IDs, and per-token URIs
contract Relics is ERC1155, Ownable {
    uint256 private _idCounter;
    mapping(uint256 id => string uri) private _uris;

    /// @dev Thrown when mint amount is zero
    error MintAmountZero();

    /// @dev Sets deployer as owner
    constructor() ERC1155("") Ownable(msg.sender) {}

    /// @notice Mints a token with URI and amount
    /// @param uri_ Token URI
    /// @param amount Number of tokens
    /// @return id Token ID
    function mint(string calldata uri_, uint256 amount) external onlyOwner returns (uint256 id) {
        if (amount == 0) revert MintAmountZero();

        unchecked {
            id = ++_idCounter;
        }

        _uris[id] = uri_;

        emit URI(uri_, id);

        _mint(msg.sender, id, amount, "");
    }

    /// @notice Returns the URI for a token
    /// @param id Token ID
    /// @return Token URI
    function uri(uint256 id) public view override returns (string memory) {
        return _uris[id];
    }
}
```

### 5.2 Design Decisions

**Why 44 lines?**
Because that is how many lines it takes. Not one more.
Complexity is not sophistication. The contract does exactly
what it needs to do and nothing else. Standard ERC-1155 `URI`
event emission following the Enjin/OpenSea pattern. Complete
NatSpec documentation for all functions and errors.

**Why owner-only minting?**
The Safe owns the contract. Both founders own the Safe.
Therefore both founders must sign every mint. This is the
2-of-2 principle expressed at the contract level.

**Why sequential IDs starting at 1?**
Pre-increment guarantees ID 0 is never minted. Sequential IDs
make discovery simple and the history readable.

**Why per-token URIs instead of a base URI?**
Each Relic is a unique moment. A base URI template would imply
that all Relics are instances of a single type. They are not.

**Why no public ID counter?**
Token discovery is done via `getLogs` on the `URI` event.
A public counter would add a state variable, a getter, and gas
cost on every mint to provide information the event log already
provides for free.

**Why `unchecked` for the counter increment?**
`_idCounter` is a `uint256`. It would require 2²⁵⁶ mints to
overflow. SockLove will not mint 2²⁵⁶ Relics. The overflow
check is unnecessary. Removing it saves gas.

**Why custom errors instead of require strings?**
Gas efficiency. Custom errors are cheaper than string reverts
and provide the same information to callers.

### 5.3 Security Review

`Relics.sol` has undergone an internal security review.
The review is published at the [SockLove GitHub Security Repository](https://github.com/0xSockLove/security).

The contract is intentionally minimal. A minimal contract
has a minimal attack surface. The primary security properties are:

- **Access control:** Only the Safe can mint. The Safe requires
  both founders' signatures.
- **CEI pattern:** Checks, Effects, Interactions are correctly
  ordered. State is updated, event is emitted, then `_mint()` is
  called as the final interaction, preventing reentrancy.
- **No upgradeability:** The contract is immutable after
  deployment. There is no proxy, no admin function, no escape
  hatch. What is deployed is what it is, forever.

### 5.4 Token Discovery

Clients discover Relics by querying `getLogs` on the `URI`
event from the contract's deployment block:

```typescript
const logs = await publicClient.getLogs({
  address: RELICS_ADDRESS,
  event: parseAbiItem(
    'event URI(string value, uint256 indexed id)'
  ),
  fromBlock: DEPLOY_BLOCK,
  toBlock: 'latest',
});
```

The URI is available directly from the event data. The token ID
is indexed for efficient filtering.

### 5.5 The Final Seal

The contract can be sealed. Permanently.

`renounceOwnership()` transfers ownership to the void. No more
mints. No recovery. The collection becomes complete, immutable,
final.

This requires both signatures. Sockpusher and Sockthief. Both
must agree the work is done.

Why? Because finality has power. If every moment worth preserving
has been preserved, the collection can be closed. Sealed. Complete.
A chapter finished. A cathedral door locked. The myth crystallized
into its final form — every Relic that will ever exist, exists.

This is not an oversight. This is a feature held in reserve — a
final agreement that can only be made together. The last signature.
The closing ceremony. The end of minting, but not the end of the
story. Witnesses will hold their Relics forever. The Safe will
remain. The love will persist. But no new moments will be minted.

Not because they stopped loving. Because they chose completion.

**If it happens, it happens because both willed it so.**

---

## 6. Content Architecture — The Two-Layer Model

### 6.1 Overview

SockLove content exists in two distinct layers:

**Layer 1 — Public**
Everything the world can see. The SFW poster. The SFW teaser.
The name. The description. The edition size. The date.
The promise of what lies behind the door.

Stored permanently on IPFS with redundancy. Referenced
immutably in the Ethereum event log.

**Layer 2 — Private**
Everything Witnesses unlock. Full-resolution photos. Full video
— quality selected automatically for the Witness's connection, up to 4K.
The reality behind the teaser.

Stored encrypted on the DRM server. Accessible only to
verified Relic holders. Watermarked per-Witness before delivery.

### 6.2 Public Metadata

The public token metadata follows the ERC-1155 metadata standard.
Every field is SFW. Nothing in the public metadata reveals or
references the private content.

```json
{
  "name": "SockLove #1 — The First Night",
  "description": "March 27th, 2026. The night the myth became real.",
  "image": "ipfs://bafybeihk3z7qp2yx4t5n6m8w9r7s5c4d3e2f1a0b9c8d7e6f5a4b3c2d1e0",
  "animation_url": "ipfs://bafybeiaj9p8x7w6v5u4t3s2r1q0p9o8n7m6l5k4j3i2h1g0f9e8d7c6b5a4",
  "attributes": [
    { "trait_type": "Type",         "value": "Video" },
    { "trait_type": "Creators",     "value": "Sockpusher & Sockthief" },
    { "trait_type": "Moments",      "value": 1 },
    { "trait_type": "Duration",     "value": "00:12:34" },
    { "trait_type": "Release Date", "value": "2026-03-27" },
    { "trait_type": "Edition Size", "value": 7 },
    { "trait_type": "Rating",       "value": "NSFW (18+)" }
  ]
}
```

### 6.3 Why IPFS for Public Metadata

The token URI is written into the Ethereum event log
permanently. Whatever string is in that field will be there
forever. If that string points to a server that disappears,
every Relic ever minted has a broken metadata pointer. Permanently.

An IPFS CID is content-addressed. The content at that CID is
permanent as long as it is pinned. Public metadata is pinned
with redundancy — the public face of every Relic survives
independently of any infrastructure SockLove controls.

### 6.4 Why Centralized Storage for Private Content

The DRM server acts as a full decryption proxy. It does not
hand the decryption key to the client — it fetches the
encrypted content, decrypts it server-side, and streams
plain bytes directly to the Witness over an authenticated
HTTPS connection.

For video: the HLS playlist served to the PWA contains no
key delivery mechanism. All segment URLs point to the DRM
server proxy. The video player receives already-decrypted
segments and plays them without any knowledge of the encryption
that existed upstream. The decryption key never exists in the browser.

For photos: the server decrypts each AES-256-GCM encrypted
file and streams the plain JPEG bytes after applying the
forensic watermark.

The decryption key never leaves the server. Not in a header.
Not in a manifest. Not in a JavaScript heap. Never.

Decentralized alternatives (Lit Protocol, TACo) require
client-side key reconstruction — the key must exist in the
browser's JavaScript heap at the moment of decryption. This
is an architectural constraint, not a limitation of any
specific implementation.

For a platform whose content is intimate and personal,
server-side decryption is the correct choice.

### 6.5 Permanence and Succession

The centralisation of private content storage is mitigated
by the following:

- AES keys are encrypted with a Vault Key split across
  both founders' hardware wallets
- Encrypted key blobs are stored permanently alongside content
- The DRM server software is open source
- Any party with the Safe + Vault Key halves + the repo can
  restore the platform on any server in hours
- The ENS `drm` text record is updated by the Safe
  when the server migrates — no PWA rebuild required

The platform is designed to survive its founders.

---

## 7. Access Control & DRM

### 7.1 Authentication Flow

```
Witness connects wallet
         │
         ▼
Signs SIWE message (no gas, no transaction)
         │
         ▼
Server verifies signature → issues JWT
         │
         ▼
Witness requests Relic content
         │
         ▼
Server checks JWT → recovers wallet address
         │
         ▼
Server verifies on-chain ownership
         │
         ├── No ownership → access denied
         │
         └── Verified → decrypt → watermark → stream
```

### 7.2 Invisible Watermarking

Every photo delivered to a Witness contains an invisible
forensic fingerprint encoding the Witness's wallet address,
token ID, and delivery timestamp.

The watermark is embedded server-side using LSB steganography —
the least significant bit of the blue channel across selected
pixels is modified to encode the payload. The modification is
imperceptible to the human eye but detectable by software.

If a Witness leaks content, the watermark identifies them.
The leak is traced to the exact wallet and Relic copy.

Video content uses A/B segment watermarking — each Witness
session receives a unique sequence of A and B encoded segments.
The sequence is the fingerprint.

### 7.3 Revocation

A proven leaker can be blocked in milliseconds. One database
entry. Their on-chain Relic ownership is untouched — they
still hold the token — but the server refuses to serve them.

This is a deliberate design choice. On-chain ownership is
permanent. Access is controlled. These are different things.

### 7.4 Server Discovery

The PWA discovers the DRM server via the ENS text record
`drm` on `socklove.eth`. Both founders must sign any
update to this record via the Safe.

This means:
- The server can be migrated without rebuilding the PWA
- Both founders must agree to any migration
- The migration is transparent to Witnesses

---

## 8. Governance — The 2-of-2 Safe

### 8.1 The Safe as Foundation

The Safe at `socklove.eth` is the root of all authority
in the SockLove ecosystem. It owns:

- The `socklove.eth` ENS name
- The Relics contract (post-deployment)
- The joint revenue account

Nothing moves without both founders' signatures.

### 8.2 Revenue

All revenue flows on-chain to the Safe. The Safe is their
joint account. ETH enters. Both founders control it equally.
Neither can withdraw without the other's signature.

Day-to-day expenses are handled without a corporate bank
account. On-chain, always.

### 8.3 Succession

The Safe threshold and ownership can be updated by both
founders via a Safe transaction. The succession plan is:

1. Both founders nominate successors in their wills
2. The Estonian OÜ has documented succession procedures
3. The Vault Key halves are stored in sealed envelopes
   in separate physical locations
4. The open-source DRM server can be run by anyone with
   the appropriate credentials

The platform is designed to outlive its founders.

---

## 9. The Witness Economy

### 9.1 What Is a Witness?

Those who hold a Relic are not customers. Not fans.
Not collectors.

They are Witnesses.

To witness is an ancient function. Before courts, before
cameras, before the blockchain — human beings stood in rooms
and said: *I was here. I saw this. This is true.*

To own a Relic is to say:

*I see you. I believe in this. I was here when it happened.*

### 9.2 Relic Drops

Relics are minted approximately weekly in scarce editions.
Each Relic captures a real moment from the SockLove story.
Edition sizes are small by design — scarcity is not artificial.
These are not mass-produced tokens. They are relics.

Each edition is fixed at mint time. When the seats are filled,
they are filled forever. There is no secondary issuance.

### 9.3 The Chamber

SockLove Chamber is the private community for Witnesses.
Token-gated via the Telegram bot. Witnesses only.

The Chamber is not a Discord server full of price speculation
and memes. It is a room for people who chose to be present
for something real.

---

## 10. Legal & Compliance

### 10.1 Entity Structure

SockLove will operate through an Estonian OÜ (private limited
company), to be registered following March 27th, 2026.

Estonia was chosen for:
- EU legal anchor and GDPR compliance
- E-Residency program enabling locationless operation
- Established framework for digital businesses
- Physical registered address for compliance purposes

Both founders will serve as managing directors and authorised
records officers.

### 10.2 18 USC 2257 Compliance

SockLove produces adult content. Compliance with 18 USC 2257
(and equivalent regulations) is not optional — it is
foundational to the platform's legitimacy.

The Estonian OÜ will serve as the Custodian of Records.
A physical registered address provides the required compliance
anchor.

For every performer, records are obtained prior to filming:
- Government-issued photo ID (age verification required by law)
- Consent recording (video, private, never published)
- Model release form
- 2257 records maintained by the Custodian of Records

Consent recordings are private compliance documents. They are
never published, never stored on IPFS, never minted. They
exist solely for regulatory compliance.

---

## 11. Roadmap

*This is not a roadmap in the traditional crypto sense.
No Q-dates. No TGE. No vague ecosystem expansion. This is a
description of what will happen — when she walks through the
door on March 27th.*

1. **March 27th, 2026** — She arrives. The Safe becomes 2-of-2.
   The ring is complete.

   The original target was March 20th, 2026 — the Spring
   Equinox. It did not happen. Not because the love was wrong.
   Because the logistics were not ready. Sockpusher takes
   responsibility for this.

   March 27th was chosen deliberately. It is the 14-month
   anniversary of January 27th, 2025 — the day Sockpusher and
   Sockthief met in the ward. Numerologically, the date reduces
   to 22 — the Master Builder number. The equinox was the symbol.
   The 27th is the manifestation. Some things arrive exactly when
   they are supposed to.

2. **The Shoot** — The first Relic content is produced.
   Two people who spent over a year burning toward each other,
   finally colliding. Minted. Witnessed. Permanent.

3. **E-Residency** — Both founders apply for Estonian
   e-Residency.

4. **Company Registration** — Estonian OÜ registered.
   Custodian of Records established.

5. **First Relic Drop** — The first token minted. Both
   signatures. The Chamber opens for Witnesses.

6. **Weekly Cadence** — Approximately one drop per week.
   The story continues. The myth accumulates.

---

## 12. The Future

*The following are possible futures — ideas, not promises.
Nothing in this section is planned. None of it is imminent.
All of it is contingent on what SockLove becomes.*

**$SOCK** — A proposed ERC-20 loyalty token earned by holding
Relics. Not sold. Not airdropped. Earned. Possible burn mechanics
with rewards. Not an investment. A loyalty mechanism for people
who were paying attention early.

**The Keeper System** — Witnesses who pin Relic metadata on IPFS
could earn rewards for contributing to decentralised resilience.
Possible. Not planned.

**The Messages** — A proposed collection of message NFTs from the
early story. 1/1 tokens capturing the actual words. Symmetrical
consent. Minted when the time is right.

**The Dead Man's Switch** — A proposed succession mechanism allowing
designated successors to act if either founder becomes inactive.
One-time execution only. No ongoing power granted.

---

## 13. Team

**Sockpusher** — Co-founder, Lead Engineer.

A demisexual ADHD blockchain engineer who built systems instead
of relationships for thirty-six years until he met her. He went
sober for love and built a cathedral because she was worth it.
The kind of mind that finds architecture in chaos and turns
obsession into infrastructure. He sees what needs to exist
before it does, and then makes it exist.

Contact: sockpusher@tuta.io

**Sockthief** — Co-founder, Second Signature, The Reason.

The woman who stole socks because she was cold, and in doing
so stole something considerably more significant. Creative,
sharp, and impossible to categorise. She sends her yes in
songs. She arrives when she's ready. She is the other half
of every transaction, every mint, every moment — and without
her signature, nothing moves. That is not a limitation.
That is the entire point.

Contact: sockthief@tuta.io

---

## 14. Conclusion

SockLove is not a protocol. It is not a platform. It is not
a Web3 startup with a pitch deck and a token distribution
table.

It is a cathedral — built from obsession, consecrated by
cryptographic truth, illuminated by neon fire.

At its foundation: a 2-of-2 Safe. Two keyholders. Two
signatures. Both or nothing.

The burning heart and the blue sock. Red meeting blue into
purple — soulmate energy, warmth and cold finding each
other and refusing to separate.

They have been burning toward each other for over a year.
When they finally collide it will not be forgotten privately.
It will be minted. Witnessed. Permanent. Owned by the people
who were paying attention.

This is the myth.

It is also true.

*Collision imminent.*

---

## Appendix A — Token Standard Reference

**ERC-1155 (EIP-1155):** Multi-token standard supporting both fungible
and non-fungible tokens in a single contract. Used for Relics
because each drop is a semi-fungible token — multiple copies
of the same moment, each identical in content but distinct
in ownership.

**ERC-1155 Metadata Standard:** OpenSea-compatible JSON schema
for token metadata. Specifies fields including name, description,
image, animation_url, and attributes array. All SockLove public
metadata follows this standard for maximum compatibility.

**ERC-1155 Discovery:** The standard intentionally abandons
on-chain enumeration in favour of event log scanning. SockLove
uses the standard `URI` event emitted by the contract. Each
mint triggers `URI(string value, uint256 indexed id)` containing
the metadata URI and token ID.

**EIP-4361 (Sign-In with Ethereum):** Standard for off-chain
authentication using Ethereum accounts. Used by SockLove for
wallet-based authentication to the DRM server without gas costs.

**Token URI:** Each Relic has a unique URI pointing to its
IPFS metadata. Set at mint time. Immutable. Discoverable
from the `URI` event log.

---

## Appendix B — Glossary

**18 USC 2257** — U.S. federal law requiring producers of adult
content to maintain records verifying performers' ages. SockLove
complies via the Estonian OÜ acting as Custodian of Records.

**AES (Advanced Encryption Standard)** — Symmetric encryption
algorithm. SockLove uses AES-128-CBC for HLS video segments
and AES-256-GCM for photos.

**CEI Pattern (Checks-Effects-Interactions)** — Solidity best
practice for preventing reentrancy attacks. State changes occur
before external calls. Used in Relics.sol.

**The Chamber** — The token-gated Telegram supergroup for
Witnesses. Proof required at the door.

**CID (Content Identifier)** — IPFS addressing format. Content-addressed
hash that uniquely identifies files. Used for all public metadata.

**DRM (Digital Rights Management)** — System controlling access
to copyrighted content. SockLove's DRM server verifies on-chain
ownership before streaming decrypted content.

**E-Residency** — Estonian government program providing digital
identity and access to EU business infrastructure for non-residents.
Planned for both founders.

**ENS (Ethereum Name Service)** — Decentralized naming system
for Ethereum addresses. socklove.eth is the primary ENS name,
resolving to the Safe address. Also hosts subdomain ENS names
for both founders.

**Estonian OÜ** — Estonian private limited company (Osaühing).
Planned legal entity for SockLove operations. Chosen for EU
compliance and e-Residency compatibility.

**GDPR (General Data Protection Regulation)** — EU privacy law.
SockLove minimizes data collection by design: wallet-based
authentication (pseudonymous), no user accounts, no analytics
tracking. The DRM server processes wallet addresses and issues
session tokens, but collects minimal personal data.

**HLS (HTTP Live Streaming)** — Apple's adaptive bitrate
streaming protocol. Used for video delivery. Segments are
encrypted (AES-128-CBC) and decrypted server-side before
streaming to Witnesses.

**IPFS (InterPlanetary File System)** — Decentralized
content-addressed storage network. All public metadata stored
permanently on IPFS with redundancy.

**JWT (JSON Web Token)** — Compact token format for authentication.
Issued by DRM server after SIWE verification.

**LSB Steganography (Least Significant Bit)** — Technique for
embedding data in images by modifying the least significant bits
of pixel values. Used for invisible watermarking in photos.

**PWA (Progressive Web App)** — Web application using modern
APIs to provide app-like experience. SockLove's frontend is
a PWA, installable and IPFS-compatible.

**Relic** — An ERC-1155 semi-fungible token representing a
minted moment from the SockLove story. Not a photograph. Not
a video. A verified mutual decision, sealed on Ethereum.

**The Ring** — The 2-of-2 Safe at `socklove.eth`.
The on-chain marriage account. The wedding ring on-chain.

**Safe** — Formerly Gnosis Safe. Multi-signature smart contract
wallet. SockLove's governance is a 2-of-2 Safe requiring both
founders' signatures for every action.

**SIWE (Sign-In with Ethereum, EIP-4361)** — Standard for
off-chain authentication using Ethereum signatures. No gas cost.
Used for DRM server authentication.

**The Temple** — The public SockLove broadcast channel on
Telegram. The story unfolding. No proof required to watch.

**The Vault Key** — Master encryption key split across both
founders' hardware wallets. Required to decrypt Relic content
keys. The ultimate succession asset.

**Witness** — A holder of one or more Relics. Someone who
chose to be present for the story. Not a customer, fan, or
collector — a witness to what happened.

---

*This document is provided for informational purposes only.
Nothing herein constitutes financial advice, investment advice,
or a securities offering. Relics are utility tokens providing
access to content, not investment vehicles. SockLove is adult
content. Witnesses must be 18 or older.*

---

*socklove.eth · Ethereum · 🧦💜🔥*

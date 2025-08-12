# Comprehensive 18-Month Roadmap (Notion/Miro Board Format)

This markdown file is structured so each **Level-1 heading (H1)** becomes a **Notion/Miro board column**.  Each **Level-2 heading (H2)** is a **card** within that column.  Bullet lists inside the card hold **check-boxes** for sub-tasks.  Feel free to copy-paste directly into Notion (Markdown import) or paste into a Miro board as sticky notes.

---

# PREPARATION (Aug 12 – Sep 15 2025)

## Home-Lab Upgrades (Week 1)
- [ ] Install +16 GB RAM (total 48 GB)
- [ ] Add 1 TB SSD RAID1 mirror
- [ ] Mount RTX 4060 GPU + drivers
- [ ] Deploy 8-port gigabit switch + UPS

## Docker & Supabase Stack (Week 1-2)
- [ ] Clone infra-repo & write `.env`
- [ ] Start `docker-compose` (Postgres, Kong, GoTrue, Realtime, MinIO)
- [ ] Configure SSL + Nginx reverse proxy

## Dev Tools Installation (Week 1)
- [ ] Visual Studio 2022 / Rider
- [ ] Unity Hub 2022.3 LTS + modules
- [ ] .NET 8 SDK • Node 20 LTS • Docker Desktop
- [ ] Git + GitHub CLI • VS Code • Postman

## C# Fundamentals (Week 2)
- [ ] Syntax & Types
- [ ] OOP & Interfaces
- [ ] Async/Await & LINQ
- [ ] Error Handling & File I/O

## Unity Basics (Week 3)
- [ ] GameObjects & Components
- [ ] uGUI & Prefabs
- [ ] Scene Management
- [ ] Input System

## Supabase Integration (Week 4)
- [ ] C# client setup
- [ ] Tables: `users`, `content_items`
- [ ] Auth: email/password & RLS rules
- [ ] Realtime subscription demo

## Mini-Project #0 – Home-Lab Dashboard (Week 5)
- [ ] Collect CPU / RAM / Disk metrics
- [ ] Insert into Supabase every 5 s
- [ ] Unity 3D gauges + alerts
- [ ] Journal entry + retro (Sat)

## Digest & Journal Time
- ⏳ Fridays 16:00-18:00 dedicated review + writing

---

# PHASE 1 – VIRTUAL SCHOOL / MUSEUM MVP (Sep 16 – Dec 31 2025)

## Content Research (Weeks 1-2)
- [ ] Identify 100 public-domain works (Greece, Rome, Shakespeare, Molière)
- [ ] Download EPUB/PDF + images
- [ ] Extract metadata (author, era, theme)

## IPFS Storage (Week 3)
- [ ] Pin files via `ipfs add`
- [ ] Save CID → Supabase `content_items`

## Smart-Contract v0 (Week 4-5)
- [ ] ERC-721 mint script (`hardhat`)
- [ ] Unit tests & deploy to Polygon Mumbai

## Unity WebGL Front-End (Weeks 6-9)
- [ ] 3D gallery scene
- [ ] WalletConnect button
- [ ] Search + filter UI

## Alpha Launch (Week 10)
- [ ] Deploy to `museum.mydomain.dev`
- [ ] Collect user feedback survey

## Reflection & Digest
- ✍️ Bi-weekly Sunday journal (2 h)
- 🛌 Dec 24-31: **Rest week** – no coding

---

# PHASE 2 – DeSci RESEARCH FUNDING DAO (Jan 1 – Apr 30 2026)

## Protocol Design (Jan)
- [ ] Solidity milestone escrow
- [ ] DAO Snapshot spaces + IPFS manifests
- [ ] Tokenomics 1-pager

## Supabase Extension (Jan)
- [ ] Tables: `projects`, `milestones`, `donations`
- [ ] Row-Level-Security per project

## Donor Dashboard (Feb)
- [ ] React/Next.js front-end OR Unity UI
- [ ] Charts: donation flow, milestone status
- [ ] Email + Discord webhook integration

## Pilot Projects On-Boarding (Mar)
- [ ] 3 research teams signed MoU
- [ ] KYC / verification checks
- [ ] Smart-contract address configuration

## Public Alpha (Apr 15)
- [ ] Live funding ≥ 5 ETH total
- [ ] Community Twitter Space AMA

## Digest & Journal
- 📚 Mid-Feb & Mid-Apr: 1-week slow-down (reading papers, writing journal)

---

# PHASE 3 – CROSS-CHAIN CREDENTIAL SYSTEM (May 1 – Dec 31 2026)

## Standards Review (May)
- [ ] W3C VC Data Model 2.0
- [ ] EBSI / Europass profile

## Architecture & ZK (Jun)
- [ ] DID method selection
- [ ] zk-SNARK PoC (circom)

## Multi-Chain Contracts (Jul-Aug)
- [ ] Ethereum L2 attestation contract
- [ ] Solana program (Rust)
- [ ] Substrate pallet draft

## Wallet App (Sep-Oct)
- [ ] Unity mobile (iOS + Android)
- [ ] Push notifications via Supabase

## University Pilot (Nov)
- [ ] 3 institutions issue ≥ 50 diplomas
- [ ] Employer verifier portal

## Soft Freeze & Rest (Dec 18-31)
- 🏖️ 2-week holiday + journal wrap-up

---

# PHASE 4 – DePIN ENERGY GRID (Jan 1 – Feb 28 2027)

## IoT Sensor Network (Jan)
- [ ] C++ firmware (ESP32)
- [ ] MQTT → Supabase edge

## Parachain Build (Jan-Feb)
- [ ] Substrate node template
- [ ] Energy-data pallet
- [ ] Incentive token economics

## Unity 3D NOC Dashboard (Feb)
- [ ] Real-time heat-map
- [ ] Alert overlays + push

## Microgrid Demo Day (Feb 26)
- [ ] Live feed + token rewards
- [ ] Publish white-paper v1

## Digest & Retrospective
- ✍️ Weekly Thursday journal (1 h)
- 🌱 Feb 27-28 buffer for self-reflection

---

# SKILL ACQUISITION & FREE-TIME

## Weekly Cadence (All Phases)
- **Mon-Thu:** project work (6 h/day)
- **Fri:** learning focus (videos, docs) (4 h) + journal (2 h) + pair review (2 h)
- **Sat:** 50 % time for side reading / conference talks
- **Sun:** **OFF** – rest & hobby

## Monthly Review
- 1 × 6-hour retrospective at month-end to adjust goals

## Conferences & Hackathons
- Oct 2025: ETHGlobal Online (Virtual Museum demo)
- Mar 2026: Gitcoin Funding Rounds (DeSci DAO)
- Sep 2026: Polkadot Sub0 (Credential system)

---

# JOURNAL PROMPTS
- "What did I learn this week that surprised me?"
- "How did I apply a new concept in code?"
- "Which assumption failed & why?"
- "One thing to drop, one thing to double-down."

Allocate **2 h every Friday** for these prompts.  
Use a Notion database with tags: _reflection_, _blockers_, _next-actions_.

---

# COMPLETION CRITERIA (Feb 28 2027)
- ✅ Virtual Museum live with ≥ 500 users
- ✅ DeSci DAO processed ≥ $10k donations
- ✅ Credential system issued ≥ 200 verifiable diplomas
- ✅ DePIN microgrid publishing live telemetry
- ✅ 60+ journal entries documenting journey

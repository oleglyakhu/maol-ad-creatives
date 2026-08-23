# 🎯 MAOL Ad Creatives — Claude Skill

> A Claude Skill that writes ad creative copy — static and video — following MAOL agency's proven structure, with mandatory audience analysis before any copy gets written.

---

## 📋 What's in this repository

```
maol-ad-creatives-repo/
├── SKILL.md                        ← the instructions Claude follows (the heart of the skill)
├── README.md                       ← this file
└── references/
    ├── static-examples.md          ← real static creative examples by niche
    └── video-examples.md           ← real video script examples by niche
```

---

## ⚙️ How it works — step by step

When someone on the team asks Claude to write creatives, the skill runs a strict process instead of guessing pain points out of thin air:

| Step | What happens |
|---|---|
| **1️⃣ Materials** | Claude asks for the landing page, brief, briefing recording, or other client materials |
| **2️⃣ Analysis** | Produces a short audience and niche analysis based on those materials |
| **3️⃣ Pain points** | Lists 4–8 candidate pain points / angles |
| **4️⃣ Confirmation** | Asks which pains to actually work with — never decides on its own |
| **5️⃣ Copy** | Writes 4–5 creatives (static or video) using MAOL's 7-element structure, each from a different angle |
| **6️⃣ 🧑‍🤝‍🧑 Persona panel** | Builds 5 in-depth target-audience personas, runs every creative past them, and ranks the creatives by relevance |
| **7️⃣ Sales caption** | On request, writes the expanded caption/description text that goes under the creative (e.g. Meta's primary text) |

Every response ends with a reminder: this is a draft, not a final deliverable — always review and edit by hand before it goes live.

---

## 🧱 Creative structure (MAOL's house format)

Every creative is built from **7 elements across 3 sections**:

**Section 1 — Hook**
1. Headline (Pain)
2. Subheadline

**Section 2 — Value**
3. Triggers
4. Bullets
5. Author/brand *(optional)*

**Section 3 — Close**
6. Bonus/price *(if applicable)*
7. CTA

Video follows the same structure but expanded into a full monologue; static is the compressed, on-image version.

---

## 🎥 Formats

- **Static** — short copy for an image ad
- **Video** — plain narration meant to be read on camera, no shot breakdowns or timecodes (filming is left to the client's team), with a standard filming brief attached

---

## 🚀 Installation

1. Download the `.skill` file (packaged from this folder — see below)
2. Open Claude.ai → start a new chat → attach the `.skill` file
3. Click **Save skill** on the card that appears
4. Done — the skill is now active and will kick in automatically when you ask for ad creatives

### Repackaging the `.skill` file after edits

If you edit `SKILL.md` or the files under `references/`, repackage the skill before handing it to the team — using `package_skill.py` from the official skill-creator.

---

## 🔒 Usage

Internal tool for **MAOL** agency. This repository is private — it contains real client copy and work product.

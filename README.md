# 📜 Tribal Sovereignty Software License Template

This repository provides a comprehensive software license template (`comprehensive-license/LICENSE`) incorporating tribal sovereignty protections, Traditional Knowledge (TK) labels, and federal Indian law provisions. Tribal members can use this as a starting point for their own software projects.

## 🆕 Template v2.0 (2026) — Major Rebuild

**What changed and why:** v2.0 rebuilds the license around enforcement mechanics that have been verified against primary sources. Highlights:

| Improvement | Where (v2.0) | Why |
|---|---|---|
| Every term is a enforceable **license condition**, not just a covenant | §2.2 | `Jacobsen v. Katzer`, 535 F.3d 1373 (Fed. Cir. 2008) — conditions unlock Copyright Act remedies (statutory damages, injunctions) |
| Tribal-court jurisdiction grounded in **consent** | §§ 1.10, 14.1 | `Montana v. United States`, 450 U.S. 544, 565 (1981) consensual-relationship exception |
| **Corrected** tribal-judgment recognition: comity, not § 1738 | §14.4 | `Wilson v. Marchington`, 127 F.3d 805 (9th Cir. 1997); Mich. Ct. R. 2.615 |
| **Honest immunity clause**: individual members don't hold tribal immunity | §16.2 | `Bay Mills`, 572 U.S. 782 (2014) protects the Tribe, not individuals |
| **AI & data sovereignty** section: no-training condition, TDM opt-out, CARE Principles, IEEE 2890-2025 provenance | §5 | ✓ verified 2025–2026 standards and AI case law |
| **Fallback ladders** under every aggressive clause | §§12.2, 13.3 | A court striking a maximal term degrades to an enforceable rung, not to zero |
| Cultural patrimony / **anti-alienation** protections (NAGPRA) | §8 | 25 U.S.C. §§ 3001–3013 |
| Optional **treaty-waters/maritime** section for coastal & Great Lakes Nations | §7 | e.g., `United States v. Michigan` 2023 Consent Decree |
| Corrected **Supremacy Clause** framing | §6.2 | Treaties trump state law; licenses force comes from copyright conditions + consent |
| **Truth-tagged international annex** | §15, Annex A | Every instrument marked: binding / endorsed / signed-not-ratified / persuasive |

**Old → new section map:** v1 §1 Attribution → §3 · v1 §2 TK Labels → §4 · v1 §3 Revocation → §§6, 12 · v1 §4 Prohibited Uses → §10 · v1 §5 Permissible Uses → §11 · v1 §6 Consent → §9 · v1 §7 Compensation → §13 · v1 §8 Alternative Forums → §14 · v1 §9 Governing Law → §15 · v1 §10 Remedies → §13 · v1 §12 Immunity → §16 · v1 §13 Severability → §17 · v1 §14 Amendments → §18.

**Fixed financial figures are now draft defaults** (royalty ≥20%, §504(c) benchmark to $150k per work, liquidated-damages ladder) — they intentionally mirror real statutes (17 U.S.C. §504(c); 25 U.S.C. §305e(b)) instead of arbitrary placeholders, but **must still be reviewed by your legal counsel** before use.


## 💡 Quick Start: Using This Template

1.  **Get the Template:** Copy the `comprehensive-license/LICENSE` file into your project and rename it `LICENSE`.
2.  **Customize:** Follow the "🛠️ Customizing Your License" section below to replace placeholders and adapt terms.
3.  **Review:** Ensure mandatory legal and cultural reviews are completed by appropriate tribal authorities (See "⚠️ Critical Legal & Cultural Review").
4.  **Implement:** Use the finalized `LICENSE` file in your software project.

## 💻 Contributing Changes Back to This Template (Guide for Beginners)

If you want to suggest improvements *to this template repository* itself and are new to GitHub, follow these steps, using AI prompts if needed:

1.  **Fork** this repository to your account.
    *   *Prompt:* `"Guide me on how to fork the repository at [Insert Repository URL Here] to my GitHub account."*
2.  **Create a Branch** for your changes.
    *   *Prompt:* `"Guide me on how to create a new branch named '[your-change-description]' in my forked repository."*
3.  **Make Edits** to the `@LICENSE` or `README.md` file.
    *   *Prompt (Online):* `"Guide me on how to edit the [filename] file in my '[branch-name]' branch directly on GitHub."*
    *   *Prompt (AI Draft):* `"Draft suggested text changes for [section/topic] in the [filename] file to [explain your improvement]."*
4.  **Commit** your changes with a clear message.
    *   *Prompt:* `"Guide me on how to commit my changes to the [filename] file in my '[branch-name]' branch on GitHub and write a commit message."*
5.  **Create a Pull Request** (PR) back to the original repository.
    *   *Prompt:* `"Guide me on how to create a Pull Request from my '[branch-name]' branch to the main branch of the original repository at [Insert Repository URL Here]. Help me write a clear description."*

*Remember to replace bracketed text like `[filename]` and `[Insert Repository URL Here]`.*

## 🛠️ Customizing Your License (`@LICENSE` file)

Follow this process to adapt the `@LICENSE` template for *your* project:

1.  **Use Your AI Assistant for Placeholders (Recommended First Step):**
    *   Provide your AI with the `@LICENSE` content and your known details using a prompt like this:
        ```
        "I need to customize the provided '@LICENSE' template file. Please replace all placeholders like <|placeholder_name|> using this information:
        - My Name: [Your Name]
        - My Indigenous Name (Optional): [Your Indigenous Name]
        - My Tribal Nation: [Your Tribal Nation Name]
        - My GitHub Username: [Your GitHub Username]
        - My Project/Repository Title: [Your Repo Title]
        - Current Year: [Current Year]
        - My State: [Your State Name]

        For any remaining placeholders (like <|specific_treaty_...|>, <|tribal_court_name|>, <|community_description|>, <|license_identifier|>, etc.), please list them clearly and ask me for the specific information needed. Explain what each requires if I'm unsure."
        ```
    *   *Follow Up:* Answer the AI's questions to fill in the remaining details.

2.  **⚠️ Critical Legal & Cultural Review (Mandatory):**
    *   **Consult Experts:** Take the partially filled license to your **Tribal Legal Department** (or qualified Indian law attorney) AND your **Cultural Authorities/Elders**.
    *   **Legal Verification:** Your legal team MUST review:
        *   Treaty references (`<|specific_treaty_...|>`) and sovereignty/treaty assertions (Sections 6, 7) for accuracy and applicability to *your* Nation.
        *   Jurisdictional clauses (`<|tribal_court_name|>`, consent and alternative forums in Section 14, governing law layering in Section 15).
        *   Enforcement and remedies (Section 13), including the default damages figures (20% royalty, $10,000/day liquidated damages ladder). These mirror 17 U.S.C. §504(c) and 25 U.S.C. §305e(b) benchmarks — verify they fit *your* facts and tribal code.
        *   Immunity and identity statements (Section 16) — v2.0 no longer claims personal sovereign immunity for individuals; confirm this fits your structure (e.g., if your *Nation itself* will hold the license, ask counsel about adding a limited waiver).
        *   AI/data restrictions (Section 5) for compatibility with any planned public data releases.
    *   **Cultural Verification:** Your cultural authorities MUST review:
        *   TK Labels (Section 4.2) to ensure they accurately reflect *your* community's protocols (Local Contexts taxonomy).
        *   Prohibited/Permissible Uses (Sections 10, 11) for alignment with cultural values and protocols.
        *   Cultural patrimony and burial protections (Section 8), and Community Protocols to be recorded in Annex B.
    *   **Coordinate:** Ensure legal and cultural reviews are integrated.

3.  **Final Checks:**
    *   Confirm all `<|placeholders|>` have been correctly filled or removed.
    *   Double-check the GitHub URL in the citation (Section 3.1).
    *   If your Nation is not coastal/Great Lakes/riverine, delete Section 7 and renumber.
    *   Rename the file from `@LICENSE` to `LICENSE`.

## 📌 Placeholder Reference List (in `comprehensive-license/LICENSE`)

This is a quick reference to the types of placeholders you'll need to fill:

*   **Basic Info:** `<|current_year|>`, `<|author_name_indigenous|>`, `<|author_name|>`, `<|tribal_nation_name|>`, `<|community_description|>`, `<|repo_title|>`, `<|github_username|>`, `<|state_name|>`, `<|license_identifier|>`, `<|licensor_notice_contact|>`
*   **Legal Specifics:** `<|specific_treaty_1_name_year_stat_cite|>`, `<|specific_treaty_2_name_year_stat_cite|>`, `<|treaty_reserved_rights_summary|>`, `<|tribal_court_name|>`
*   ** Damages defaults (Section 13 — NOT placeholders; discuss with legal counsel):** 20% gross-revenue royalty; $10,000/day liquidated damages with fallback ladder to 17 U.S.C. §504(c) statutory damages and the IACA §305e(b) $1,000/day benchmark.
*   **Review Areas (Marked `[ADAPT]` / `[OPTIONAL]` in the template):** TK Labels (4.2), Treaty foundations (Section 6), Maritime section (Section 7 — delete for inland Nations), Community definition (1.8), Annexes A–C.

## ✅ Implementation Checklist (for Your Project)

Use this after completing the customization steps:
*   [ ] AI/Manual Placeholder replacement complete.
*   [ ] Tribal legal review obtained and required modifications implemented.
*   [ ] Cultural review obtained and required modifications implemented.
*   [ ] All `<|placeholders|>` confirmed filled/removed.
*   [ ] Final `LICENSE` file correctly named and placed in project repository.

## 🤝 Invitation for Tribal Legal & IP Experts (to Improve This *Template*)

We actively welcome contributions *to this template repository* from Tribal attorneys, IP specialists, TK custodians, and court officials. Please use the GitHub contribution process outlined above (Fork, Branch, Edit, Commit, PR).

### ⚖️ LLM Prompt Templates for Expert Legal Review

Experts reviewing this *template* or a user's *adaptation* can use these prompts with AI assistance:

1.  **General Analysis**:
    ```
    "Analyze this tribal software license ([link to file or paste text]) from the perspective of [Target Tribe]'s sovereignty and legal framework. Identify conflicts with tribal code, treaties ([list specific treaties]), constitution, or governance. Suggest specific wording changes for better alignment and enforceability under [Target Tribe]'s law."
    ```
2.  **Jurisdiction Focus**:
    ```
    "Evaluate the consensual-jurisdiction and forum-selection clauses (Sections 1.10, 14) and governing-law layering (Section 15) for compatibility with [Target Tribe]'s judicial system and inter-tribal relations jurisprudence. Suggest modifications for clarity, enforceability within [Target Tribe]'s courts, and addressing comity (Wilson v. Marchington) and state recognition rules, referencing [Target Tribe]'s relevant codes or case law."
    ```
3.  **TK Label & Protocols Verification**:
    ```
    "Review TK labels (Section 4) and use restrictions/permissions (Sections 10, 11) against [Target Nation]'s specific cultural protocols for knowledge/data protection, sharing, consent, and digital representation. Suggest additions, removals, or modifications to align with these protocols."
    ```
4.  **Treaty Specifics**:
    ```
    "Adapt Sections 6 and 7 to explicitly reference [Target Tribe]'s key treaties (e.g., [Treaty Name Year, Stat. citation]) and reserved rights doctrine as recognized under their specific legal history. If [Target Tribe] has no treaty-water interests, confirm deletion of Section 7. Draft revised text strengthening the sovereignty assertion based on these specific treaties."
    ```
5.  **Enforcement & Remedies Strategy**:
    ```
    "Assess the remedies and damages ladder (Section 13), revocation framework (Sections 6, 12), and enforcement tracks (Section 14). Propose modifications tailored to [Target Tribe]'s legal environment, court capabilities, available remedies (including traditional ones referenced in tribal code), and judgment enforcement procedures. Stress-test the fallback rungs: if a court strikes the primary assertion, does the ladder still yield meaningful relief?"
    ```

## 🌱 Expanding Protection: Call for Expertise in Other IP Areas

While this template focuses on software licensing, the underlying principles of asserting tribal sovereignty, protecting Traditional Knowledge (TK), and safeguarding Traditional Cultural Expressions (TCEs) are vital across many domains. As highlighted by ongoing international negotiations at the World Intellectual Property Organization (WIPO) Intergovernmental Committee on Intellectual Property and Genetic Resources, Traditional Knowledge and Folklore (IGC), there's a critical need for robust legal frameworks protecting Indigenous heritage in diverse forms [[NARF/WIPO](https://narf.org/cases/wipo/)].

We invite **Tribal legal experts, cultural heritage professionals, artisans, knowledge keepers, and community leaders** to contribute their expertise in adapting these principles or developing new templates for areas such as:

*   **Cultural Performances & Expressions:**
    *   Songs, dances, ceremonies, stories, prayers [[NARF/WIPO](https://narf.org/cases/wipo/)]
    *   Presentations, workshops, educational materials
*   **Tangible Cultural Heritage:**
    *   Art, crafts, jewelry, regalia
    *   Traditional designs, symbols, motifs
*   **Traditional Knowledge Systems:**
    *   Plant and medicinal knowledge, healing practices [[NARF/WIPO](https://narf.org/cases/wipo/)]
    *   Agricultural techniques, environmental management practices
    *   Knowledge associated with genetic resources (GRAATK) [[NARF/WIPO](https://narf.org/cases/wipo/)]
*   **Digital & Archival Materials:**
    *   Databases of traditional knowledge [[NARF/WIPO](https://narf.org/cases/wipo/)]
    *   Digitized cultural heritage collections, recordings, photographs
    *   Language resources

**Goal:** To create a suite of resources and templates that empower Indigenous creators and communities to protect their intellectual and cultural property across all forms of expression, grounded in tribal sovereignty and cultural protocols.

Please contribute by opening an issue tagged `expansion-suggestion` or submitting a pull request with proposed frameworks or adaptations.

## ❓ Support

*   **Improving this Template:** Use GitHub Issues (tag "legal-review" or "suggestion").
*   **Adapting for Your Project:** Contact *your* tribal legal dept, cultural heritage office, or local Indigenous legal aid/bar association. Review UNDRIP. 
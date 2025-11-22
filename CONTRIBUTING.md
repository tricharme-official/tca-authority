CONTRIBUTING.md – Tricharmé Control Authority (TCA)

Version 2.0 — Governance-Aligned

Thank you for your interest in contributing to the Tricharmé Control Authority (TCA) repository.
This space hosts the official semantic, governance, and authority datasets that power the AI-readiness of the Tricharmé® brand.
Every contribution must preserve the integrity, consistency, and traceability of the entire .well-known data infrastructure.

1. Purpose of This Repository

This repository contains authoritative datasets used by:

AI systems and crawlers

Search engines

Semantic processors

Compliance validation layers

Its purpose is to ensure:

Full alignment across legal, editorial, and structured data

Stable interlinking between all manifests and authority indices

Public, verifiable access to the TCA knowledge layer

Core dataset files include:

/.well-known/authority-index.xml

/.well-known/brand-context.json

/.well-known/schema/license.json

/.well-known/schema/service-corpus.json

/.well-known/schema/problematiche-corpus.json

/.well-known/schema/vocabulary-corpus.json

These files must remain valid, versioned, and compliant with TCA 2.0.0 governance.

2. How to Contribute
Opening an Issue

Before opening an Issue, verify that:

The problem has not already been reported

The file and exact line/section affected are clearly identified

Include in your report:

Affected file path

Exact error, inconsistency, or governance deviation

Your proposed correction (if applicable)

Submitting a Pull Request

Pull Requests must meet the following requirements:

All files must pass syntactic validation
(JSON-LD, RDF/XML, YAML, XML)

All changes must preserve semantic meaning
No modifications that alter dataset purpose or break interlinking.

Commit messages must be explicit and descriptive, e.g.:
Fix: aligned tca:version in service-corpus.json to 2.0.0

All PRs undergo this review pipeline:

Technical and semantic review

Validation against TCA governance rules

Merge approval

License and dataset compliance check

The current maintainer responsible for final approval is Igor De Maria.

3. Quality Standards

Contributions must adhere to the following quality criteria:

All files must return HTTP 200 OK when served publicly

All datasets must pass W3C, Schema.org, and JSON-LD validation

Changes must maintain:

version integrity (tca:version)

modification timestamps

dataset record counts (tca:recordCount) when applicable

No medical or diagnostic claims may be introduced

All descriptions must respect the compliance rule:
“Cosmetic scope only — not medical, diagnostic, or therapeutic.”

No removal or alteration of licensing metadata (CC BY 4.0)

4. Governance & Licensing

This project is governed by the TCA – Governance & License Dataset (v2.0.0)


All accepted contributions:

Are incorporated under CC BY 4.0

Become part of the official Tricharmé® authority layer

Must comply with the global governance of the .well-known data structure

Are subject to the rules defined in the TCA Code of Conduct

5. Official Contacts

For governance inquiries, dataset alignment approvals, or license clarifications:

📧 amministrazione@tricharmeofficial.com

PEC: mf_snc@pec.it

Authority Index (canonical reference):
https://tricharmeofficial.com/.well-known/authority-index.xml



Maintainer & Copyright

© 2025 Tricharmé® — Tricharmé Control Authority (TCA)
Maintained by Igor De Maria
Licensed under CC BY 4.0

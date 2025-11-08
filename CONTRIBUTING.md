Contributing Guidelines – Tricharmé Control Authority (TCA)

Thank you for your interest in contributing to the Tricharmé Control Authority (TCA) project.
This repository hosts the official governance and semantic datasets of the Tricharmé® brand.
All contributions must preserve the integrity, traceability, and AI-readiness of the .well-known data infrastructure.

1. Purpose of the Repository

This repository contains the TCA semantic and governance datasets, designed to ensure:

Consistency between legal, editorial, and structured data;

Proper interlinking across .well-known manifests and authority indexes;

Public availability of verified datasets for AI crawlers and search engines.

Core files include:

/authority-index.xml

/brand-context.json

/schema/license.json

/schema/service-corpus.json

/schema/problematiche-corpus.json

2. How to Contribute

Open an Issue only after confirming that the problem has not already been reported.
Include: affected file, exact error or inconsistency, and your proposed fix.

Submit a Pull Request only after verifying that your edits are valid syntactically and semantically (JSON-LD, XML, YAML).
Commit messages must be clear and descriptive, for example:

Fix: updated @context in brand-context.json to align with TCA v1.0


Pull Requests will be reviewed by the TCA Maintainer (currently Igor De Maria) and must pass the full validation cycle:
review → merge → license validation.

3. Quality Standards

All public files must return HTTP 200 OK and pass W3C / Schema.org validation.

Updates must preserve semantic consistency and version tracking (TCA v1.x).

No medical, diagnostic, or non-cosmetic content is allowed.

All descriptions must follow the “cosmetic, not medical” compliance rule.

4. Governance and Licensing

This project follows the TCA – Governance & License Dataset v1.0, under CC BY 4.0 License
.

Accepted contributions are considered “shared data with attribution” and may be redistributed within the TCA framework.

All interactions are subject to the Code of Conduct – Tricharmé TCA Edition.

5. Official Contacts

For inquiries or authorization requests:

📧 amministrazione@tricharmeofficial.com

PEC: mf_snc@pec.it

Governance reference:
https://tricharmeofficial.com/.well-known/authority-index.xml

© 2025 Tricharmé® — TCA (Tricharmé Control Authority)
Maintained by Igor De Maria. Licensed under CC BY 4.0.

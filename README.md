# Digital Identity Optimization for Open-Source Projects

This presentation applies Daniel Beránek’s Digital Identity Optimization (DIO) framework to open-source projects.

---

## DIO/ODI — Canonical reference infrastructure

The current archived Reference Model release is v0.9.0. It integrates the SKOS-first Reference Vocabulary v0.2.2, derived non-normative Application Mappings and an archived Semantic Change Feed (SCF) snapshot v0.1.1 (JSON Schema v0.2.0; 45 documented events through 9 November 2026). The separately maintained live SCF is v0.1.14 (JSON Schema v0.2.1; 63 documented events through 25 November 2026). SCF is a component of the Reference Model, not a separately DOI-identified work.

- **Archived Reference Model v0.9.0:** https://doi.org/10.5281/zenodo.24085589
- **Reference Model source repository:** https://github.com/dan-beranek/dio-odi-reference-model/
- **Reference Vocabulary v0.2.2:** https://vocab.danielberanek.cz/dio-odi/
- **Live Semantic Change Feed:** https://vocab.danielberanek.cz/semantic-change-feed/
- **SCF event registry (JSON):** https://vocab.danielberanek.cz/semantic-change-feed/events.json
- **SCF JSON Schema:** https://vocab.danielberanek.cz/semantic-change-feed/schema.json

---

The central proposition is that an open-source project is not merely a repository of code. It is a distributed digital entity whose identity is continuously represented across repositories, package registries, documentation, releases, forks, contributors, maintainers, foundations, companies, security advisories, community discussions, knowledge systems, and AI-generated descriptions.

## Core proposition

Digital Identity Optimization appears to be one of the few systems complex enough to maintain the identity of something as unstable, distributed, and constantly evolving as an open-source project.

DIO does not erase change. It makes change interpretable.

## What the presentation covers

- Open-source projects as distributed identity graphs.
- The Entity Turn from documents to entities.
- Entity Collapse and AI Hesitation.
- The identity cycle: Entity → Representation → Interpretation → Trust → Relationship → Reconstruction.
- Human-facing interpretation.
- Pre-AI technical representation.
- AI-mediated reconstruction.
- Canonical project identity.
- Fork, package, documentation, governance, and security relationships.
- DIO implementation as a practical research proposition.

## Identity graph

The project’s identity is distributed across:

- GitHub or GitLab repositories.
- Package registries.
- Documentation and README files.
- Releases and changelogs.
- Forks and descendants.
- Contributors and maintainers.
- Companies, foundations, sponsors, and governance structures.
- Security advisories and vulnerability records.
- Stack Overflow and community discussions.
- Wikipedia, Wikidata, and other knowledge systems.
- AI-generated descriptions and recommendations.

Each surface contributes a partial signal. DIO maintains coherence across the graph.

## Sources

Beránek, D. (2026). *Manifest of Digital Identity Optimization (DIO) and Ontology of Digital Identity (ODI): Canonical Multilingual Edition (Version 1.0.0)* [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.21610934

Beránek, D. (2026). *Digital Identity Optimization (DIO): A Conceptual Framework for Entity-Based Visibility in the Age of AI-Mediated Search*. Zenodo. https://doi.org/10.5281/zenodo.21839423

## Presentation

Open `index.html` in a browser to view the interactive presentation.

The project is intended as a conceptual presentation and research proposition, not as a claim that DIO guarantees search rankings, AI model memory, training-data inclusion, or recommendation by any particular AI system.

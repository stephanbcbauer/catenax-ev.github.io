---
title: Catena-X Body of Knowledge
sidebar_position: 1
---

# Catena-X Body of Knowledge (CX BOK)

## Welcome to the CX BOK

The Catena-X Body of Knowledge (CX BOK) is a comprehensive collection of domain-specific knowledge, conceptual frameworks, and technical deep-dives that support the implementation and understanding of the Catena-X ecosystem.

:::info Purpose
The CX BOK provides in-depth knowledge about key concepts, workflows, and architectural patterns that are essential for understanding how Catena-X works beyond the normative standards. Content is sourced from the official [catenax-eV GitHub organization](https://github.com/catenax-eV) repositories and the expertise of the Catena-X working groups.
:::

## What is the CX BOK?

While [Standards](/docs/standards/overview) define **what must be implemented**, and [Architecture Guardrails](../architecture-guardrails/overview.md) define **how to structure solutions**, the CX BOK explains **why things work the way they do** and provides the **conceptual foundation** for the ecosystem.

### CX BOK vs. Standards

| Aspect | CX BOK | Standards |
|--------|--------|-----------|
| **Nature** | Informative, educational | Normative, prescriptive |
| **Purpose** | Understanding & learning | Compliance & interoperability |
| **Content** | Concepts, workflows, patterns | Requirements, specifications |
| **Audience** | Architects, developers, analysts | Implementers, certifiers |
| **Changes** | Evolves with ecosystem knowledge | Formal versioning & governance |

## Structure

The CX BOK is organized into five thematic areas:

### 🔐 Identity & Trust

Documentation on identity management, trust frameworks, and authentication mechanisms.

- [Self-Sovereign Identity (SSI) Workflow](./identity-trust/ssi-workflow) — Core SSI concepts, DID/VC workflow, key management
- [Issuer Concept and Credential Management](./identity-trust/issuer-concept) — Types of issuers, credential lifecycle, governance

### 📊 Data Sovereignty & Exchange

Concepts related to data sovereignty, ODRL policies, and connector architecture.

- [ODRL Policy Framework](./data-sovereignty/odrl-policy-framework) — The Catena-X ODRL Profile, usage purposes, policy patterns
- [EDC Connector Architecture](./data-sovereignty/edc-connector-architecture) — Control/data plane, DSP protocol, deployment
- [Data Contract Negotiation](./data-sovereignty/data-contract-negotiation) — Negotiation lifecycle, policy evaluation, agreement management

### 🔄 Semantic Interoperability

Deep dives into semantic models, ontologies, and data harmonization.

- [Aspect Model Design Patterns](./semantic-interoperability/aspect-model-design) — SAMM framework, design patterns, versioning
- [Digital Twin Concepts](./semantic-interoperability/digital-twin-concepts) — AAS structure, DTR, look-up chain, twin types

### 🏗️ Architecture Patterns

Common architectural patterns and best practices for Catena-X applications.

- [Dataspace Connectivity Patterns](./architecture-patterns/dataspace-connectivity) — Connectivity stack, transfer patterns, multi-hop chains
- [Business Partner Number (BPN) Concept](./architecture-patterns/bpn-concept) — BPN types, Golden Record, BPDM, BPN in policies

### 🔍 Use Case Deep Dives

Detailed explorations of specific use cases and their implementations.

- [Industry Core](./use-cases/industry-core) — Digital supply chain graph, part tracing, BOM exchange
- [Product Carbon Footprint (PCF)](./use-cases/pcf-workflow) — PCF data model, exchange workflow, tier aggregation
- [Demand & Capacity Management (DCM)](./use-cases/demand-capacity-management) — Demand/capacity data models, imbalance detection, collaboration

## How to Use the CX BOK

:::tip For Architects
Use the CX BOK to understand the conceptual foundations and design patterns that inform your architecture decisions. Start with [Dataspace Connectivity Patterns](./architecture-patterns/dataspace-connectivity) and [EDC Connector Architecture](./data-sovereignty/edc-connector-architecture) to understand the technical landscape.
:::

:::tip For Developers
Refer to the CX BOK for detailed workflows, sequence diagrams, and implementation guidance that complements the normative standards. The [ODRL Policy Framework](./data-sovereignty/odrl-policy-framework) and [Digital Twin Concepts](./semantic-interoperability/digital-twin-concepts) are particularly useful for implementation.
:::

:::tip For Business Analysts
The CX BOK explains business concepts and workflows in technical detail, helping bridge the gap between business requirements and technical implementation. The [Use Case Deep Dives](#-use-case-deep-dives) provide end-to-end business workflow descriptions.
:::

:::tip For Newcomers
Start with [SSI Workflow](./identity-trust/ssi-workflow) to understand identity in Catena-X, then read [EDC Connector Architecture](./data-sovereignty/edc-connector-architecture) to understand data exchange, and then explore [Industry Core](./use-cases/industry-core) to understand the foundational use case.
:::

## Knowledge Sources

The CX BOK draws from the following official [catenax-eV](https://github.com/catenax-eV) repositories:

| Repository | Knowledge Area | Key Topics |
|---|---|---|
| [cx-odrl-profile](https://github.com/catenax-eV/cx-odrl-profile) | Data Sovereignty | ODRL Profile, usage purposes, policy terms |
| [example-edc-setup](https://github.com/catenax-eV/example-edc-setup) | Architecture | EDC connector setup, Helm charts, component overview |
| [catenax-ev.github.io](https://github.com/catenax-eV/catenax-ev.github.io) | All areas | Standards, operating model, architecture guardrails |

## Contributing to the CX BOK

The CX BOK is a living knowledge base that evolves with the ecosystem. Contributions are welcome from:

- Domain experts sharing deep knowledge
- Implementers documenting patterns and lessons learned
- Architects explaining design decisions
- Use case teams detailing workflows

:::note How to Contribute
To contribute to the CX BOK:

1. Identify a knowledge gap or area for improvement
2. Prepare comprehensive documentation with diagrams
3. Submit through the documentation contribution process
4. Engage with reviewers to refine content
:::

## Key Principles

The CX BOK follows these principles:

### 1. Clarity

Documentation is clear, well-structured, and accessible to the target audience.

### 2. Depth

Content goes beyond surface-level descriptions to provide genuine insight and understanding.

### 3. Visual

Diagrams, workflows, and visual representations enhance understanding.

### 4. Practical

Real-world examples and use cases ground theoretical concepts.

### 5. Current

Content is regularly updated to reflect the current state of the ecosystem.

### 6. Connected

Cross-references link related concepts, standards, and guardrails.

## Featured Topics

### 🆕 Recently Added

- [ODRL Policy Framework](./data-sovereignty/odrl-policy-framework) — Complete guide to Catena-X data usage policies
- [EDC Connector Architecture](./data-sovereignty/edc-connector-architecture) — Technical deep dive into the Eclipse Dataspace Connector
- [Data Contract Negotiation](./data-sovereignty/data-contract-negotiation) — How automated contract negotiation works
- [Aspect Model Design Patterns](./semantic-interoperability/aspect-model-design) — SAMM and semantic model best practices
- [Digital Twin Concepts](./semantic-interoperability/digital-twin-concepts) — AAS, DTR, and the look-up chain
- [Dataspace Connectivity Patterns](./architecture-patterns/dataspace-connectivity) — Connectivity architecture and patterns
- [Business Partner Number (BPN) Concept](./architecture-patterns/bpn-concept) — BPN types, Golden Record, BPDM
- [Industry Core Use Case](./use-cases/industry-core) — The foundation of the supply chain graph
- [PCF Workflow](./use-cases/pcf-workflow) — Carbon footprint data exchange
- [Demand & Capacity Management](./use-cases/demand-capacity-management) — Supply chain planning collaboration

### 🔥 Foundation Topics (Start Here)

1. **[SSI Workflow](./identity-trust/ssi-workflow)** — Understand how identity works in Catena-X
2. **[EDC Connector Architecture](./data-sovereignty/edc-connector-architecture)** — Understand how data exchange works
3. **[Industry Core](./use-cases/industry-core)** — Understand the foundational use case

## Related Resources

- [Architecture Guardrails](../architecture-guardrails/overview.md) - Rules and best practices
- [Standards](/docs/standards/overview) - Normative specifications
- [Glossary](/glossary) - Term definitions
- [Working Model](/docs/working-model/overview) - Governance and processes

## Feedback and Questions

The CX BOK is designed to be helpful and accessible. If you have:

- Questions about a topic
- Suggestions for new content
- Corrections or improvements
- Requests for clarification

Please reach out through the standard contribution channels or the documentation team.

:::info Stay Updated
The CX BOK is continuously expanding. Check back regularly for new topics and updated content.
:::

---

**Last Updated**: March 2025
**Current Topics**: 10 (growing)

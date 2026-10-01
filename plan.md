# Project Plan

## Status

**Portfolio prototype:** seven mobile and four desktop HTML screens are present. Product requirements, technical architecture, service integrations, and a validated end-to-end flow remain to be defined. This plan separates completed design work from proposed implementation work.

## Phase 1: Align on the MVP

- [ ] Confirm that natural-language discovery and AI-assisted comparison are the MVP priorities; keep booking assistance as a follow-on unless scope changes.
- [ ] Define target users, the supported trip-search scenario, and where the assistant fits into existing search.
- [ ] Turn the PRD's broad functional requirement into testable acceptance criteria.
- [ ] Define recommendation inputs, clarification behavior, ranking principles, and user-facing explanation requirements.
- [ ] Define metric events and terms for successful discovery, relevant-bus time, search interactions, and counter-task drop-off.

**Exit criteria:** an agreed MVP scope, measurable success definition, and reviewed end-to-end journey.

## Phase 2: Refine and Validate the Prototype

- [ ] Connect the seven screens into a navigable, clickable prototype.
- [ ] Add key states: missing preferences, no matching buses, stale availability, changed fare, and user correction or reset.
- [ ] Check that recommendation details and explanations match the stated preferences in representative scenarios.
- [ ] Run usability sessions focused on time to a relevant bus, comprehension of trade-offs, and confidence in the choice.
- [ ] Record findings and update the screens and product assumptions.

**Exit criteria:** users can complete the discovery and comparison task in a testable prototype, with prioritized usability issues documented.

## Phase 3: Design the Technical Approach

- [ ] Identify the existing search, inventory, pricing, seat-selection, and booking interfaces the assistant can use.
- [ ] Define an integration boundary that complements the existing product rather than creating a separate app.
- [ ] Specify preference extraction, clarification, recommendation ranking, and fallback behavior.
- [ ] Set targets for latency, availability, peak-load behavior, and recommendation quality.
- [ ] Define privacy, security, data retention, observability, and recovery requirements.
- [ ] Keep responses grounded in current inventory and show concise user-facing reasons; do not expose hidden chain-of-thought.

**Exit criteria:** technical and data owners agree on integration contracts, measurable non-functional requirements, and a privacy review.

## Phase 4: Build the Discovery MVP

- [ ] Implement natural-language preference capture and editable structured preferences.
- [ ] Ask focused clarification questions when required information is missing or ambiguous.
- [ ] Retrieve eligible bus inventory and rank results against explicit user preferences.
- [ ] Display recommendations with comparable facts and concise match explanations.
- [ ] Provide a clear route back to standard search and a way to correct preferences.
- [ ] Instrument discovery and guardrail metrics.

**Exit criteria:** users can describe a bus trip, receive inventory-grounded recommendations, understand key trade-offs, and select an option; analytics are verified end to end.

## Phase 5: Validate and Expand

- [ ] Test preference extraction, ranking, empty results, conflicting constraints, and inventory changes.
- [ ] Evaluate successful discovery and supporting metrics against targets agreed in Phase 1.
- [ ] Monitor quality, latency, reliability, and drop-off; investigate regressions before expanding traffic.
- [ ] Consider conversational booking assistance as a separate follow-on, preserving existing booking and payment controls.

**Exit criteria:** MVP meets its agreed quality and operational thresholds, with a documented decision to iterate, expand, or pause.

## Risks and Dependencies

- **Inventory access:** recommendations are only useful when availability, fares, and seat status are current and sourced from trusted systems.
- **Ambiguous preferences:** unclear or conflicting requests can lead to poor matches; clarification and editable preferences are needed.
- **Trust:** unsupported claims or opaque ranking can undermine confidence; ground details in inventory and explain the match in user-facing terms.
- **Scope:** conversational booking touches transactional flows and is higher effort than discovery; keep it out of the initial MVP unless explicitly re-prioritized.
- **Measurement:** the North Star depends on determining whether a selected bus actually satisfies stated requirements; define this before launch.
- **Prototype fidelity:** current HTML screens are not integrated and do not call AI, inventory, or booking services.

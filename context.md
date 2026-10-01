# Project Context

## Overview

This project explores an AI-assisted bus discovery and booking experience inspired by intercity bus-booking products. It is an independent portfolio concept supported by seven mobile and four desktop static HTML prototypes, not a production booking application. The proposed assistant complements an existing bus-search and booking journey; it does not replace it. The accompanying visual direction is documented as Kinetic Travel & Intelligence.

## Problem

Travelers can struggle to translate preferences such as budget, departure time, comfort, seat type, boarding point, and operator into traditional search filters. Comparing many buses takes time and makes trade-offs difficult to understand.

## Target User

People booking an intercity bus who know some of their travel needs but may not know which filters to use, or who want help comparing available options before choosing.

## Product Opportunity

1. **Natural-language discovery (P0):** Let travelers describe a trip and preferences in their own words.
2. **AI-assisted comparison and recommendations (P0):** Explain relevant trade-offs across bus options and help travelers choose.
3. **Conversational booking assistance (P1):** Support the selected bus through seat choice and booking confirmation.

## Goals

- Help users find relevant bus options with fewer interactions and less search time.
- Make recommendations reflect the user's stated requirements and the available inventory.
- Complement the existing search and booking experience.
- Present understandable reasons for recommendations and keep the user in control of the booking decision.

## Non-Goals

- Creating a separate travel application or replacing the existing product.
- Supporting flights, trains, cabs, or hotels in the MVP.
- Cancellations, refunds, rescheduling, complaints, or other support workflows.
- Claiming live inventory, real AI recommendations, or real payment and booking behavior in the current prototypes.

## Proposed Experience

1. A traveler starts from bus search or the AI assistant.
2. They describe a route and preferences in natural language, or start with suggested prompts.
3. The experience asks for missing constraints such as departure slot or boarding point.
4. It presents recommended buses and explains relevant trade-offs.
5. The traveler compares options, chooses seats, and reviews a confirmation state.

## Prototype Inventory

| Journey stage | Prototype |
| --- | --- |
| Home and bus search | [Mobile home](Prototype%20screens/Mobile%20screens/redbus_ai_home_bus_search/code.html) |
| Conversational discovery | [Mobile AI assistant](Prototype%20screens/Mobile%20screens/redbus_ai_conversational_assistant/code.html) |
| Preference clarification | [Mobile clarification](Prototype%20screens/Mobile%20screens/redbus_ai_clarification_preferences/code.html) |
| Recommendations | [Mobile results](Prototype%20screens/Mobile%20screens/redbus_ai_recommended_bus_results/code.html) |
| Trade-off evaluation | [Mobile comparison](Prototype%20screens/Mobile%20screens/redbus_ai_bus_comparison/code.html) |
| Seat choice and booking | [Mobile seat selection](Prototype%20screens/Mobile%20screens/redbus_ai_seat_selection_booking/code.html) |
| Confirmation | [Mobile confirmation](Prototype%20screens/Mobile%20screens/redbus_ai_booking_confirmation/code.html) |
| Desktop discovery | [Desktop home](Prototype%20screens/Website%20screens/redbus_ai_desktop_home_discovery/code.html) |
| Desktop recommendations | [Desktop AI results](Prototype%20screens/Website%20screens/redbus_ai_desktop_ai_search_results/code.html) |
| Desktop comparison | [Desktop comparison](Prototype%20screens/Website%20screens/redbus_ai_desktop_bus_comparison/code.html) |
| Desktop seat choice | [Desktop seat selection](Prototype%20screens/Website%20screens/redbus_ai_desktop_seat_selection_booking/code.html) |

These are individual screen prototypes. Some controls demonstrate local interactions, but the screens are not connected to one another through a working booking flow.

## Success Measures

**North Star: Successful Bus Discovery Rate** — the percentage of AI-agent sessions in which a user finds and selects a bus option that matches their stated travel requirements.

Supporting measures named in the PRD:

- Time to Relevant Bus
- Search Interaction Rate
- Counter-task drop rate
- D30 inactivation rate

Before implementation, define how a selected option is judged to match requirements, what counts as a session and a counter-task, and how these events are instrumented. Treat guardrail metrics as signals to investigate; the PRD does not yet define targets.

## Quality and Trust Principles

- Recommendations must be grounded in available inventory and the preferences the user supplied.
- Distinguish confirmed facts, such as fare or departure time, from estimates or generated suggestions.
- Give users concise, inspectable explanations of which stated preferences influenced a recommendation. Do not expose hidden chain-of-thought; the PRD's transparency goal should be fulfilled through user-facing rationale and clear data provenance.
- Protect personal and transaction data, and define retention and access controls before using real user data.
- Keep response time and reliability measurable under normal and peak load; concrete service targets remain to be agreed.

## Current State and Assumptions

- The repository currently contains the PRD, seven mobile HTML prototypes, four desktop HTML prototypes, and a design-system note.
- The prototype interactions are illustrative and local. For example, the assistant displays a canned response and the search button shows a temporary loading state; neither connects to a live AI service, inventory, or booking API.
- The HTML references Tailwind CSS and fonts from external CDNs, so those assets require an internet connection when previewing.
- The concept is inspired by redBus. This portfolio project is not an official redBus product or endorsement.

## Open Product Questions

- Which existing search and booking surfaces host the assistant, and how does a user return to standard search?
- What is the minimum required information before recommendations can be shown, and when should the assistant ask a clarification question?
- What ranking criteria, tie-breakers, and explanation format should recommendations use?
- What is the booking handoff and source of truth for fares, seat availability, and booking status?
- What response-time, availability, privacy, and security targets apply?
- How will matching success and the supporting metrics be measured without overstating user intent?

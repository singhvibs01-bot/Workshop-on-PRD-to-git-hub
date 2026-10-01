<div align="center">
	<h1>Kinetic Travel &amp; Intelligence</h1>
	<p><strong>Bus discovery, with the traveler in the driver's seat.</strong></p>
	<p>An AI-assisted concept for turning a traveler's words into clearer bus choices.</p>
	<p>
		<a href="Prototype%20screens/Website%20screens/redbus_ai_desktop_home_discovery/code.html">Explore desktop</a>
		&nbsp;·&nbsp;
		<a href="Prototype%20screens/Mobile%20screens/redbus_ai_home_bus_search/code.html">Explore mobile</a>
		&nbsp;·&nbsp;
		<a href="context.md">Read the product brief</a>
	</p>
	<img src="Prototype%20screens/Website%20screens/redbus_ai_desktop_home_discovery/screen.png" alt="Desktop concept for AI-assisted bus discovery" width="100%">
</div>

<p align="center">
	<img src="https://img.shields.io/badge/portfolio-UX%20concept-173f35?style=flat-square" alt="Portfolio UX concept">
	<img src="https://img.shields.io/badge/prototypes-11-cb3b32?style=flat-square" alt="11 static prototypes">
	<img src="https://img.shields.io/badge/platforms-mobile%20%2B%20desktop-3566a8?style=flat-square" alt="Mobile and desktop">
</p>

> **Independent portfolio project inspired by bus-booking experiences.** These are static UX prototypes, not an official redBus product. There is no live AI, inventory, payment, or booking integration.

## The Idea

Travelers often know what matters to them, such as price, departure time, comfort, or a convenient boarding point, but not which filters to combine. This concept lets them describe a trip naturally, clarify missing preferences, and compare options with understandable trade-offs. The traveler stays in control of the choice.

## The Journey

**Describe a trip → clarify preferences → review recommendations → compare buses → choose a seat → see confirmation**

The screens below explore this journey across mobile and desktop. They are individual HTML files, not a connected application; some controls show local visual interactions, while search and assistant responses are illustrative.

## Prototype Gallery

### Mobile

| Stage | Prototype |
| --- | --- |
| Start a search | [Home and bus search](Prototype%20screens/Mobile%20screens/redbus_ai_home_bus_search/code.html) |
| Describe a trip | [Conversational assistant](Prototype%20screens/Mobile%20screens/redbus_ai_conversational_assistant/code.html) |
| Resolve missing details | [Preference clarification](Prototype%20screens/Mobile%20screens/redbus_ai_clarification_preferences/code.html) |
| See relevant options | [Recommended bus results](Prototype%20screens/Mobile%20screens/redbus_ai_recommended_bus_results/code.html) |
| Weigh trade-offs | [Bus comparison](Prototype%20screens/Mobile%20screens/redbus_ai_bus_comparison/code.html) |
| Continue toward booking | [Seat selection and booking](Prototype%20screens/Mobile%20screens/redbus_ai_seat_selection_booking/code.html) |
| Review the outcome | [Booking confirmation](Prototype%20screens/Mobile%20screens/redbus_ai_booking_confirmation/code.html) |

### Desktop

| Stage | Prototype |
| --- | --- |
| Discover | [Home and discovery](Prototype%20screens/Website%20screens/redbus_ai_desktop_home_discovery/code.html) |
| Explore matches | [AI search results](Prototype%20screens/Website%20screens/redbus_ai_desktop_ai_search_results/code.html) |
| Compare | [Bus comparison](Prototype%20screens/Website%20screens/redbus_ai_desktop_bus_comparison/code.html) |
| Select seats | [Seat selection and booking](Prototype%20screens/Website%20screens/redbus_ai_desktop_seat_selection_booking/code.html) |

## Product Thinking

- **Problem:** Bus search can make people translate everyday preferences into filters, then compare many options on their own.
- **Approach:** Capture preferences conversationally, ask focused follow-up questions, and make the differences between relevant buses easier to scan.
- **North Star:** Successful Bus Discovery Rate, proposed as the share of AI-assisted sessions where a traveler selects a bus that matches their stated requirements. Its measurement method and target are still open questions, not validated results.
- **Scope:** The proposed MVP centers on bus discovery and comparison. Conversational booking support is a later step; other transport modes and post-booking support are out of scope.

## View the Prototypes

No build step is required. Open a linked `code.html` file in a browser. The prototypes load Tailwind CSS and fonts from external CDNs, so an internet connection is needed for their intended styling.

## Project Files

- [Product context](context.md): goals, audience, assumptions, trust principles, and open questions.
- [Project plan](plan.md): proposed validation and implementation phases with exit criteria.
- [Design system](Prototype%20screens/Website%20screens/kinetic_travel_intelligence/DESIGN.md): visual direction, typography, palette, and component guidance.
- [Product requirements document](PRD.docx): source requirements for the concept.

## Current State

This repository documents a product concept and a set of static screens. It does not include a production frontend, backend, AI model, live bus inventory, authentication, payments, or booking APIs. No usability research or metric outcomes are claimed. Recommendations in a future implementation should be grounded in current inventory and explain matches using user-facing rationale, not unsupported claims.

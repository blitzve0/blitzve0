# 000h by Cojeev — contribution study

**Small components need complete delivery.**

**My role:** Contributor to 000h by Cojeev, made by Sanjay Kumar Gautam. My scope covers registry delivery, appearance reliability and consumer verification.

**Current stage:** Public contribution; exact local candidate deployment is not asserted.

![Concept poster for the 000h by Cojeev contribution study. Fluid lime-resin capsules cluster against graphite, suggesting parts working together. The headline reads “Small parts. Real systems.” Credit identifies the library by Sanjay Kumar Gautam and delivery/reliability contributions by Abhay. The objects are a visual metaphor, not component UI.](assets/component-library-cover.jpg)

*Cover: AI-generated conceptual campaign artwork. It is a visual metaphor, not application UI, hardware, a built space or exact catalogue photography.*

## The work

I contributed to 000h by Cojeev at the point where a visual library becomes something another engineer can depend on. The work focused on three practical details: complete per-entry payloads, reliable appearance on first paint, and assertions that actually examine the published metadata. The interesting part was connecting the implementation to consumer evidence. An import graph is more dependable than a maintained guess about which files belong together, and a passing test is useful only if its loop really runs. This case study shows the contribution through exact public commits while keeping Sanjay Kumar Gautam’s maker credit explicit.

## Problem

A component is only reusable if its installable payload includes the files it actually imports, its dependencies are intentional, and its appearance settles correctly on the first frame. Gallery quality alone cannot demonstrate those delivery properties.

## Decisions

- Derive each registry entry from the real import graph, so packaging follows code dependencies.
- Keep optional icon geometry scoped to entries that use it and measure payload budgets per scenario.
- Verify first paint, hydration and cross-tab appearance behavior; strengthen metadata assertions when mutation controls showed that a test used Object.entries on a Map and therefore checked no payloads.

## Evidence and current scope

Public Abhay-authored commit evidence covers import-graph packaging (5dfab422), appearance reliability (cc688334) and stronger registry metadata assertions (41694e48). The live library and official registry listing were inspected on 9 October. The local candidate and live release are different snapshots, so their component counts are not combined.

## Tradeoffs

This is a contribution story about making expressive work easier to consume. It should credit the library maker and avoid implying sole authorship, universal visual acceptance, or deployment of every local candidate.

## Portfolio case study

[Read the visual case study on abhayrohit.com](https://abhayrohit.com/experiments/component-library)

## Public links

- [https://cojeev.com/ui/](https://cojeev.com/ui/)
- [https://github.com/luv-jeri/cojeev-ui/commit/5dfab422518df39cfff2a59395d51284f31fbe05](https://github.com/luv-jeri/cojeev-ui/commit/5dfab422518df39cfff2a59395d51284f31fbe05)
- [https://github.com/luv-jeri/cojeev-ui/commit/cc688334236b3f23bd5d8111d7ab2de7005a366d](https://github.com/luv-jeri/cojeev-ui/commit/cc688334236b3f23bd5d8111d7ab2de7005a366d)
- [Metadata assertion contribution](https://github.com/luv-jeri/cojeev-ui/commit/41694e48aba3b3a8b5845781ded3ce05691cf782)

---

[All selected studies](README.md) · [Abhay’s portfolio](https://abhayrohit.com) · [Profile](../README.md)

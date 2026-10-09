# Application Preflight — job-search preparation tool

**See the work before you apply.**

**My role:** Product and engineering builder for my own India-based job-search workflow.

**Current stage:** Private source; working local preparation utility with an existing public portfolio study.

![Concept poster for Application Preflight. Navy sorting trays hold pale cards beneath an amber lens, symbolizing review and preparation. The headline reads “Better decisions. Before you apply.” It identifies a local job-search tool with human review before submission. The trays are a metaphor, not hardware or application UI.](assets/application-preflight-cover.jpg)

*Cover: AI-generated conceptual campaign artwork. It is a visual metaphor, not application UI, hardware, a built space or exact catalogue photography.*

## The work

Application Preflight grew out of my own job search. I needed to know whether a role fits, whether it supports someone based in India, and what the application actually asks before opening a stack of tabs. The result is a local-first Node.js utility with declared public sources, a review queue, duplicate handling and an answer bank from my profile. Greenhouse preflight reads a form and surfaces the effort and qualification checks. Manual listing capture fills the gap on portals where automated access is inappropriate. The interface keeps discovery, shortlist and draft states separate, so I can inspect the evidence and decide what to submit myself.

## Problem

A listing can look attractive and still be impossible to apply for from India, poorly matched to the role, or expensive in application effort. I wanted a review queue that makes the source, eligibility and preparation work visible before I commit to an application.

## Decisions

- Read companies’ documented public job-board APIs through a declared source policy; keep manual listing capture for signed-in portals.
- Normalize URLs, redact pasted contact data and group duplicates; evaluate India eligibility conservatively from available listing text.
- Separate discovery, shortlisting and draft readiness; keep third-party submission as a manual action and record Applied only after exact confirmation.

## Evidence and current scope

The local README and implementation document allowlisted discovery adapters, loopback-only review UI, reusable answer preparation and read-only Greenhouse form preflight. The public portfolio study exists. No application conversion, recruiter response or hire outcome is claimed.

## Tradeoffs

The tool makes preparation reviewable while preserving manual decisions on identity, eligibility and final answers. Conservative filters can leave ambiguous roles for review; a draft-ready status is not evidence that an application has been submitted or owner-approved.

## Portfolio case study

[Read the visual case study on abhayrohit.com](https://abhayrohit.com/experiments/preflight)

## Public links

- [https://abhayrohit.com/experiments/preflight](https://abhayrohit.com/experiments/preflight)

---

[All selected studies](README.md) · [Abhay’s portfolio](https://abhayrohit.com) · [Profile](../README.md)

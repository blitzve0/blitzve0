# Sienna — local-first assistant prototype

**Useful assistance needs visible state.**

**My role:** Builder of a personal local-first assistant product, including native clients, Gateway, organizer and source-linked search.

**Current stage:** Private prototype; dated isolated Mac and Simulator evidence, partial device acceptance.

![Concept poster for Sienna. A warm glowing orb sits inside smoky glass beside ceramic trays on a dark brown surface. The headline reads “A quieter way to get things done.” It labels Sienna a software prototype. These objects symbolize local records and assistance; they are not Sienna hardware or app UI.](assets/sienna-cover.jpg)

*Cover: AI-generated conceptual campaign artwork. It is a visual metaphor, not application UI, hardware, a built space or exact catalogue photography.*

## The work

Sienna is my local-first assistant prototype. The product question is how help can remain understandable as it moves from a conversation to saved information and action. Native Mac/iPhone clients connect through a private Gateway; records remain durable and search results carry their sources. The organizer work includes notes, checklists, reminders and visible notification actions. A recent capture slice saves owner-pasted text or a link as a canonical note with revision and forget handling. I show each capability at its actual stage: isolated Mac behavior, synthetic security checks and historical Simulator UI provide different kinds of evidence. That distinction is part of the product design.

## Problem

A personal assistant can sound confident while hiding what it knows, what it has saved and whether an action actually completed. I wanted a product with durable records, visible sources and bounded action states.

## Decisions

- Use native SwiftUI clients with a private authenticated Brain Gateway and durable local records.
- Keep typed proposals and deterministic synthetic authorization/recovery separate from model output.
- Build source-linked search, revision/forget controls and owner-pasted text/link capture; make saved state and action receipts visible.

## Evidence and current scope

The frozen synthetic core has documented bounded acceptance. Dated isolated Mac checks observed note CRUD/restart, stable checklist IDs, one-off notification banners and canonical notification actions. Current origin/main includes owner-pasted text/link capture. Historical iPhone images are Simulator captures; the Results screen explicitly uses a synthetic fixture.

## Tradeoffs

Local state and narrow checks establish specific capabilities, not a general autonomous assistant. Physical Results, broader parity, recurrence/deferred-delivery sound and independent neural voice remain separate work. Private conversations and derived person profiles are omitted from the public story.

## Public links

- [https://abhayrohit.com/experiments/sienna](https://abhayrohit.com/experiments/sienna)

---

[All selected studies](README.md) · [Abhay’s portfolio](https://abhayrohit.com) · [Profile](../README.md)

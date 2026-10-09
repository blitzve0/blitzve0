# Vastraveda — storefront and family operations

**A beautiful store needs useful daily tools.**

**My role:** Product and engineering builder for the family saree business.

**Current stage:** Public storefront; operations and payment readiness have separate acceptance gates.

![Concept poster for Vastraveda with vermilion and indigo fabric folded through a clear display form. The headline reads “Craft, carried into commerce.” It identifies storefront and family operations work. The fabric is illustrative campaign artwork, not exact catalogue photography or proof of stock.](assets/vastraveda-cover.jpg)

*Cover: AI-generated conceptual campaign artwork. It is a visual metaphor, not application UI, hardware, a built space or exact catalogue photography.*

## The work

Vastraveda is a family saree business, and the product work starts with everyday use. I built an editorial storefront alongside a family panel for catalogue and shop operations. Reusing a previous product as a starting point, ordering photographs and seeing what still needs review make repeat entry easier to understand. On the customer side, cart persistence keeps the journey coherent. The source also records payment attempts, inventory holds and recovery states separately. The story I can show today is the design and implementation of those workflows, supported by dated captures and a public storefront. Real sales, exact catalogue readiness and live payment acceptance require their own evidence.

## Problem

Moving a home-run saree business online creates work on both sides of the screen: shoppers need clear products and a consistent cart, while family members need a practical way to add pieces, order photographs and manage shop work.

## Decisions

- Design the editorial storefront together with a phone-first family operations panel.
- Support repeatable catalogue entry through templates, ordered photos and distinct review/publish steps.
- Use persistent cart state and source-backed payment/inventory records, keeping hosted release, catalogue review and live payment acceptance distinct.

## Evidence and current scope

The public storefront returned HTTP 200 on 9 October. The September launch checkpoint records cart-persistence, build and live-header checks; the newer September 19 portal audit shows six Live products and 28 gallery images. Source includes server-priced quotes, purchase intents, inventory holds and separate financial state. No sales results or live payment/refund acceptance is asserted.

## Tradeoffs

Catalogue imagery needs exact-product review. Existing AI-assisted views are illustrative and cannot establish material, stock or quality. GitHub main is documented as ahead of the hosted release, so this study separates implementation evidence from current storefront behavior.

## Portfolio case study

[Read the visual case study on abhayrohit.com](https://abhayrohit.com/experiments/vastraveda)

## Public links

- [https://abhayrohit.com/experiments/vastraveda](https://abhayrohit.com/experiments/vastraveda)
- [https://shopvastraveda.com](https://shopvastraveda.com)

---

[All selected studies](README.md) · [Abhay’s portfolio](https://abhayrohit.com) · [Profile](../README.md)

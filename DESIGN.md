---
name: feminin discovery flow
description: Was beschäftigt Sie? A calm consultation that turns a concern into the right appointment.
colors:
  white: "#FFFFFF"
  sand: "#F6EFE9"
  sand-deep: "#EEE2D8"
  line: "#E4D5CA"
  rust: "#76351F"
  clay: "#93604A"
  text-brown: "#4B2A1D"
  soft-brown: "#7A5D50"
  alert: "#8E1F12"
  alert-bg: "#FBEDEA"
  night-ground: "#1D1512"
  night-sand: "#2A201B"
  night-rust: "#EFC2A6"
  night-clay: "#D29B7F"
  night-text: "#F2E6DE"
typography:
  question:
    fontFamily: "Belleza, Optima, Candara, Segoe UI, sans-serif"
    fontSize: "clamp(2.3rem, 7vw, 3.6rem)"
    fontWeight: 400
    lineHeight: 1.05
  title:
    fontFamily: "Belleza, Optima, Candara, Segoe UI, sans-serif"
    fontSize: "clamp(2rem, 5.5vw, 2.8rem)"
    fontWeight: 400
    lineHeight: 1.05
  option:
    fontFamily: "Belleza, Optima, Candara, Segoe UI, sans-serif"
    fontSize: "1.45rem"
    fontWeight: 400
    lineHeight: 1.2
  body:
    fontFamily: "Urbanist, Segoe UI, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  lede:
    fontFamily: "Urbanist, Segoe UI, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
  small:
    fontFamily: "Urbanist, Segoe UI, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
  label:
    fontFamily: "Urbanist, Segoe UI, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
rounded:
  none: "0"
spacing:
  chip-gap: "0.5rem"
  option-pad: "1.05rem 0.75rem"
  step-gap: "2rem"
components:
  button-solid:
    backgroundColor: "{colors.rust}"
    textColor: "{colors.white}"
    rounded: "{rounded.none}"
    padding: "0.85rem 1.3rem"
  button-outline:
    textColor: "{colors.rust}"
    rounded: "{rounded.none}"
    padding: "0.85rem 1.3rem"
  chip:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-brown}"
    rounded: "{rounded.none}"
    padding: "0.55rem 0.9rem"
  chip-selected:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.rust}"
    rounded: "{rounded.none}"
  option-row:
    textColor: "{colors.rust}"
    padding: "1.05rem 0.75rem"
  search-field:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text-brown}"
    rounded: "{rounded.none}"
---

# Design System: feminin discovery flow

## Overview

**Creative North Star: "Das Erstgespräch"**

A first conversation at the front desk, written down: one question at a time, in the visitor's own words, ending with one clear recommendation and a way to book. It is a tool next to feminin.at, not a second homepage.

**Key Characteristics:**
- Search first: the visitor describes her concern, suggestions answer in her words.
- Three guided questions as the alternative: life phase, concerns, billing.
- One recommendation, framed in rust, with who, field, billing and booking.
- feminin.at's identity: white ground, rust type, clay logo, square outlined controls.
- One ornament only: a soft sand blob, echoing the photo masks on feminin.at.

## Colors

White carries the page. Rust (#76351F) is every question, rule and action. Sand (#F6EFE9) marks what the visitor has chosen. Alert red appears only for emergency guidance.

**The Chosen Rule.** Sand fill means "you picked this". Nothing decorative uses sand except the single blob.

**The Alert Rule.** Red is reserved for 144 and 142 guidance. Never for errors or emphasis.

## Typography

Belleza speaks: questions, option names, service names. Urbanist explains: ledes, descriptions, labels, buttons. Sizes follow the ramp in the frontmatter, nothing in between.

**The One Question Rule.** Each screen asks exactly one question, set in Belleza at question size.

## Elevation

Flat. The only shadow is under the open suggestion list, so it reads as floating above the page.

## Components

- **Search field:** full-width, rust outline, live suggestions grouped as Anliegen, Angebote, Menschen, keyboard operable (arrows, Enter, Escape).
- **Option row:** full-width rows separated by hairlines, Belleza name, Urbanist description, arrow; choosing one advances.
- **Chip:** square, hairline border; selected chips fill sand with a rust check. Multi-select.
- **Progress:** three hairline segments and "Schritt n von 3", with Zurück.
- **Recommendation:** rust-framed block with reason, name, description, facts list and two booking actions. The email is prefilled with phase, concerns and billing.
- **Emergency note:** alert block for crisis and red-flag search terms, linking 144 and 142.

## Do's and Don'ts

Do:
- Let the visitor start with her own words.
- Always show who cares for her and how it is billed.
- Keep booking one tap away on the result.

Don't:
- Don't add homepage sections, hero images or team showcases.
- Don't add cards, eyebrows above headings, or icon tiles.
- Don't invent claims, ratings, prices or medical advice.

## Provenance

No rasters. Logo mark and icons are authored inline SVG.

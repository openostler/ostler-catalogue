# Ostler Store catalogue

The signed index of apps, packs and themes.

Part of [Ostler](https://github.com/openostler/ostler), an open, local-first,
smart-home-like ecosystem for your car. Ostler is built like a phone OS: the
platform repo is the bare system, and every feature is an app or pack in its
own repo, installed from the Store.

Status: empty. This project follows UX first: design, then UI against
recorded fixtures, then wiring. Nothing is built here until the app's design
brief is approved. The briefs live in
`openostler/ostler/references/design/2026-10/brief/`.

Licence: CC BY-SA 4.0. Contributions are
accepted under the project CLA.

## What this repo holds

- **Owner in the brief:** `Store data`.
- **Contents:** the signed catalogue data the Store reads: item entries, publisher keys and review levels; the bundled offline catalogue is built from it.
- **Design brief:** [70-store-a-home-browse](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/70-store-a-home-browse.md), [70-store-d-publisher-sideload](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/70-store-d-publisher-sideload.md) (index: [99-index](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/99-index-a.md)).
- **Spec:** [store](https://github.com/openostler/ostler/blob/main/specs/2026-10-07-store-design.md).
- **Code that moves here later** ([ADR-0046](https://github.com/openostler/ostler/blob/main/decisions/adr-0046-empty-os-every-app-an-add-on.md)): nothing yet. It moves only after this app's designs are approved ([ADR-0045](https://github.com/openostler/ostler/blob/main/decisions/adr-0045-ux-first.md)).

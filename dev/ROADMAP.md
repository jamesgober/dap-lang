# dap-lang - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
> Master plan: ../_lexersketch/ROADMAP.md and ../_lexersketch/NEW-LIBS.md
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Framing, lifecycle, debuggee trait, breakpoints and stepping; JSON handling via the family's own JSON layer (no rented runtime deps).

## v0.5.0 - Implementation
- [ ] Stack, scopes, variables, evaluate, exceptions; integration with bvm-lang debug hooks.

## v0.9.0 - Hardening
- [ ] Fuzzing framing; conformance against the protocol schema.

## v1.0.0 - Stable
- [ ] Frozen after VS Code debugs a Mox program through it (D18).

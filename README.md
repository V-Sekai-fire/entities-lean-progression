# entities-lean-progression

The player progression core in Lean 4: a credit ledger, an affinity gate on learning arts, and the event reducer that applies them.

## What it is for

A profile is a pure value that the reducer threads through grant, sell, buy and train events. Fixtures and Plausible properties, checked when the demo builds, hold that the affinity gate is respected, that no art is learned twice and that credits never wrap; the emitter writes a golden trace for implementations in other languages to match.

## Build and run

```sh
lake exe progression_demo
lake exe progression_emit
```

## Licence

MIT; see `LICENSE`.

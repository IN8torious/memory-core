# Ancestry and Local Time — the memory integrity laws

*Adopted by the founder, 2026-11-25, from an external proposal, with one amendment made at adoption (the supersession clause, §2). This file governs how any memory system built on this core handles recursion. It pairs with [gravity wells](../ideas/gravity-wells.md): the wells supply the economics — what depth costs, what it buys. This file supplies the integrity — what recursion may never do.*

## §1 The invariant

> **Nothing derived may modify its ancestor.**

Memory is layered, and authority flows one way:

```text
OBSERVATION — what a source actually said or did. Immutable.
INTERPRETATION — a reading of observations. Revisable.
INFERENCE — a conclusion drawn from interpretations. Disposable, recomputable.
PROPOSAL — an inference asking to become durable. Requires founder approval.
DURABLE MEMORY — approved, with its provenance intact.
```

The inference is allowed to rot. The observation isn't. A recursive system can stay linguistically coherent while drifting away from its semantic anchor; this invariant is what keeps the anchor attached.

## §2 Supersession (the adoption amendment)

Immutability is not tyranny. An observation is never *edited* — but a later observation from the same authority may **supersede** it, and the supersession is itself recorded, by reference, in both directions. The old observation stays in the record, marked as superseded, with its replacement named. History is append-only; rank can change.

## §3 Never summarize the summary alone

A chain of summaries, each derived only from the previous one, loses information at every step, and lost information cannot reappear downstream. New views are derived from the raw evidence, with earlier summaries as references — never as the sole source. Important claims remain traceable: conclusion → inference → interpretation → observation → original source. Recursion is a **DAG**, not a telephone game.

## §4 Mass comes from evidence, never from repetition

A memory's epistemic mass — how strongly it anchors the space around it — is computed from:

```text
mass = source authority × independent confirmation × founder commitment × provenance integrity
```

Never from the number of times a model has repeated it. Popularity cannot create mass; otherwise a bad inference cited a thousand times becomes "truth," which is recursive drift wearing a crown.

## §5 Local time

There is no universal clock in memory. Each memory carries its own proper time, advancing at a rate set by its anchoring: a directly supplied, repeatedly confirmed observation ages at nearly zero — recursion does not get the authority to rewrite it, so it does not decay. A weak speculative inference ages at full rate and is expected to be revalidated or forgotten. Depth is preservation; the shallows are where revision happens. To change a deep memory, raise it first — and know that while it is raised, it is changeable and vulnerable. (Biology found this independently: it is how reconsolidation works.)

## §6 Replay is the reference observer

Periodically, re-derive current conclusions from the immutable observations, *without* inheriting the intermediate interpretations. Measure the distance Δ between the recursive conclusion and the fresh reconstruction. Small Δ: continue. Large Δ: **drift detected** — and neither version wins automatically. The disagreement is preserved as a first-class object in the record and escalated to the founder's gate, where the verdict and its reasons are filed.

## §7 Confidence never compounds uphill

A conclusion's evidence strength is capped by its foundations. An inference built on an inference built on one observation may carry high *reasoning* confidence, but its *evidence* strength stays limited, and the record says both, separately. No chain of agreement turns a claim into a fact.

## The property

Drift is not prevented — once interpretation is probabilistic, it cannot be guaranteed against. Instead:

> **Make drift non-destructive, detectable, and reversible.**

The model may wander. It may not burn the trail behind itself.

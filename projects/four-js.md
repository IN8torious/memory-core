# Four.js and the OmnaScript → GPU Chain

Two linked lines: a 4D renderer thesis, and the rendering chain that already proved itself on real hardware.

## The chain (proven end to end)

**OmnaScript scene → deterministic GPU plan → small native runtime.**

- The OmnaScript compiler turns a scene description into a plan with a stable digest — compile the same scene anywhere, get the same digest.
- A GPU-plan compiler merges the plan's geometry into batched draws, honestly reporting any asset slots it cannot resolve rather than guessing.
- A native Vulkan executor renders the plan.

The chain's proof of record: a real village scene, described in OmnaScript, compiled to a plan, packed into a binary, and drawn by the native executor **on the founder's own phone hardware** — every material batch identifiable, the layout true to the plan. Language → plan → binary → Vulkan-on-device, each link independently verified, including byte-identical compiler output between the native and in-browser builds.

## Four.js — the 4D thesis

A renderer for true four-dimensional geometry, under strict laws drawn from the founder's own specification:

- Rotation is real SO(4) mathematics — six rotation planes, not a 3D trick.
- The 4D→3D projection is geometry; the camera is presentation. The two are never confused.
- **w is never an animation parameter.** Four never fakes 4D by animating ordinary 3D geometry.
- Edges are **clipped** against the w-bound, never clamped — clamping lies about the shape; clipping tells the truth about the slice.

The plan steps of the line are complete through their third stage, each closed by digests in the record. The thesis stands as the house's position on dimensional rendering: mathematically honest, or not at all.

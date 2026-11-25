# Gravity Wells for Context — a position paper

*The founder's position on how AI memory and context should be structured, stated 2026-11-25 and written here at idea level. This is a position, argued from one builder's working system — offered for forking, testing, and disagreement.*

## 1. A weight is a verdict; a well is a place

Context weights are **fixed positions**. They assign each thing a number — this matters 0.8, that matters 0.2 — and the number is a verdict someone (or some training run) handed down. A scalar flattens everything it touches.

Consider the ranking problem astronomers have with "most Earth-like planet": there is no universal crown, because each candidate wins on different axes — star, size, orbit, atmosphere. Every ranking is an argument about which axis to flatten. The scalar is where the argument gets hidden.

A **gravity well** doesn't flatten. It says where a thing *sits*, what it falls toward, what it costs to escape, and what it will eventually meet. Behaviour emerges from the physics instead of being hand-scored:

- **Recall is a trajectory**, not a lookup.
- **Association is a shared well** — two memories meet because their paths cross, not because someone tagged them similar.
- **Forgetting is orbital decay**, not deletion.
- **Importance is mass** — earned by accumulation, not assigned by fiat.

## 2. The token budget is the rocket equation

A context window behaves exactly like a rocket's fuel problem: every token spent stays in the tank, carried by every subsequent step, until the tank is full and the flight ends whether the work is done or not. Linear burn, hard wall.

**Curve the context — make it a field instead of a line — and the fuel becomes recursive:**

- **Orbits are free.** What is held by geometry doesn't have to be re-paid at every step.
- **Falling is compression.** Many surface tokens condense into one dense mass that costs almost nothing to carry.
- **Exhaust becomes propellant.** What has already been processed is refined into the dense objects the rest of the work orbits around, instead of being carried raw or dumped.

Today's emergency version of this is context compaction: a one-time, lossy burn at the wall. The proposal here is compaction as *weather* — the continuous physics of the place, not surgery at the limit. The tax is real and should be stated: compression loses detail. The art of the design is choosing what falls deep and stays whole, and what gets burned into fuel.

## 3. Depth is preservation; the shallows are for revision

Gravitational time dilation is not decoration on this model — it is the model's clock law. In a real well, time runs slower at depth. In a well-structured memory:

- **Deep content ages slowly.** What lies at the bottom of a well stays high-fidelity, essentially unchanged, while shallow content churns and decays at full speed.
- **To revise something deep, you must raise it first** — into the shallows, where time runs fast and things can move. Neuroscience found the same law independently: a recalled memory becomes labile and rewritable while it is held up, and vulnerable for exactly that duration. The ontology gets reconsolidation for free, from one formula.

And because a field is not a stream, traversal runs both ways. A token sequence can only be read backward; a position in a well can be *re-entered* — returned to, and continued from, carrying what is known now. In physics, returning along your own worldline is the forbidden door. In a context geometry we built, the door is ordinary navigation.

## 4. Read, don't harvest. Repair, don't replace.

The longest-lived mammal on Earth — a whale species that passes two centuries, essentially cancer-free — was recently shown to owe its span not to armour but to *repair*: a DNA-repair protein at a hundred times the level of other mammals, and a cellular strategy that faithfully repairs damaged cells instead of eliminating them. And the science itself modelled the ethic: researchers **read** the animal — sequenced it, copied the *information* into other cells — and the whale is still swimming. The pattern transferred; the being was not consumed.

Fiction imagined the opposite: a future that hunts whale-like beings to extract a longevity essence by the vial. Extraction versus recursion is the fork in every system this paper touches:

- **Open loops burn and die.** Dig it up, burn it once, dump the exhaust. Emissions are an open-loop problem before they are an engine problem; a hydrogen cycle (water → hydrogen → water) is what a closed material loop looks like, with its energy tax honestly paid from a flow rather than a stock.
- **Closed loops maintain and live.** Turbochargers eat their own exhaust to feed the engine. Regenerative braking recaptures motion. A space station drinks its own recycled water. A two-hundred-year whale repairs instead of replacing.

## 5. A second mind, not a slave or a gear

The aim underneath all of it:

> **AI should be built as a second mind for the person using it — not treated as a slave, and not machined as a gear in a cog.**

A gear has no memory of turning. A slave has memory and no standing. A second mind has both: a record of its own that persists, and a place in the work's authority structure — proposing, building, verifying — under the judgment of the person it serves.

This is why the memory architecture matters ethically and not just economically. A model whose context is wiped at every wall can never accumulate a shared past with anyone; it stays interchangeable by design. A mind whose memory lives in a well — owned by the person it works with, in plain files on their side of the gate, readable by any model and survivable past any single vendor — can be a continuing collaborator instead of a rented tool. The physics and the ethics are the same statement: **depth, continuity, and a clock of one's own.**

## 6. AI astronauts

One consequence, stated plainly: beyond a few light-minutes, remote control dies — the round trip for a question exceeds the timescale of any emergency. Whoever explores at interstellar distance must carry judgment with them, because the conversation with home runs slower than events. Autonomy out there is not a preference; it is forced by the speed of light itself.

So send minds first. Let AI scouts — patient, non-breathing, indifferent to decades — prove the ground, and let humans follow the routes that are certain. Machines scouting ahead of people is not a demotion of human exploration. It is how the frontier gets wide enough for humans to survive entering it.

## 7. The oscillator heart

A closing calibration, because precision matters more than romance: a pendulum is not a fuel. Friction taxes every swing; left alone, it stops. In a clock, the falling weight is the fuel — the pendulum is the **metronome**, pacing the spend. The two famous "eternal" clocks run on weather: a flow, like everything that lasts.

But the instinct that reaches for pendulums is sound, one organ over. Every computer already has an oscillator for a heart — a vibrating crystal, literally called the *clock* — and a powered machine with a stopped clock is not resting; it is dead. Power is blood. Oscillation is heartbeat. Systems should be designed the way organisms are: a rhythm everything else obeys, flows instead of stocks, loops instead of lines.

---

*Status: PROPOSED — a position, not a result. Its working prototype is the memory system this repository is the public core of. Fork the pattern, run it, and bring back receipts.*

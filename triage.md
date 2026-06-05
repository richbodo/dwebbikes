# Bike Triage — Photo Analysis (first pass)

A best-effort inventory of the bikes and parts in `images/`, with a repairability
estimate and a difficulty ranking. Companion to [fix-list.md](fix-list.md).

> **Confidence & method.** This is built from 13 photos (`IMG_9350`–`IMG_9362`),
> not an in-person inspection. Bikes in the woodpile row and the shed **may overlap**
> (some could be the same bike in two spots), so counts are given as ranges and
> likely duplicates are flagged. Tire **ETRTO sizes, valve types, and brake types
> are inferred** from appearance — these are exactly the fix-list "Step 0" items
> that still need a 30-second confirm per bike on site. Nothing here requires
> welding; see "Repairability verdict."

---

## Where everything is (3 locations)

| Loc | Photos | What's there |
|-----|--------|--------------|
| **A. Woodpile row** (outdoor) | `9350 9351 9352 9353 9354 9355 9356` | A leaning row of mostly-complete bikes by a green garden cart. `9353` is the master wide shot (~8–12 bikes); the rest are detail close-ups of these same bikes. |
| **B. Shed / carport** | `9357 9358 9359` | Barrels, fuel cans, farm gear, plus ~2–3 bikes incl. a kids' BMX and a red "ZAFIR" city bike. |
| **C. Parts / donor stash** (garage) | `9360 9361 9362` | **Not rideable bikes** — the harvest pile: ~15–20 spare wheels/rims, ~3–4 hanging frames, and coils of spare tires. |

---

## Inventory at a glance

| Category | Est. quantity | Notes |
|----------|---------------|-------|
| Assembled / near-complete bikes | **~10–14** (conservative after possible woodpile↔shed overlap) | Steel frames, surface rust, no visible cracks/bends |
| Spare frames (build candidates) | **~3–4** | Hanging in garage (`9361`, `9362`) |
| Spare wheels / rims | **~15–20** | `9360` — multiple sizes; **harvest before buying** |
| Spare tires | **~6–10** | Coiled, hanging (`9361`, `9362`) — inspect for Schwalbe Marathon/Big Apple per fix-list |
| Kids' bike | **1** | BMX, ~16–20" red rims (`9358`) |

---

## The repairable estimate (headline)

**Of the ~10–14 assembled bikes, an estimated ~80–90% (roughly 9–12) look repairable
to rideable with the basic kit you're already bringing** (tubes, tires, oil, hand
tools) **plus the on-site donor stash.** Layering in the **~3–4 spare frames**, the
realistic ceiling is **~11–16 rideable bikes** if someone wants to do ground-up
builds from parts.

**Why so high, and why no fancy gear:** every problem visible in the photos is
*consumable- or fastener-level* — perished tubes, rusty chains, worn pads, seized
seatposts/stems, mixed valve types. The frames themselves look sound. **There is
nothing in these images that needs welding, a torch, or a frame jig.** The biggest
real constraints are **time** and **seized fasteners**, not equipment.

---

## Named roster & difficulty groups

Names are for tracking on the whiteboard; group = repair difficulty. Use this to
pick low-hanging fruit first. Confidence is rough — confirm on site.

### 🟢 Group A — Easy (basic tools + consumables, likely same-day)

| Name | Where | What I can see | Likely needs |
|------|-------|----------------|--------------|
| **Gumwall** | `9356` | City bike, 28" tan/gumwall tires in decent shape, fenders, full chain | Air + tube check, lube, brake pads — probably the fastest win |
| **Blue Baron** | `9350 9351 9352` | Dark-blue diamond roadster, brown leather saddle, cottered single-speed crank, 28" | Tubes/tires, de-rust + lube chain, free seatpost |
| **Sky / Blue Twins** | `9353 9355` | One or two blue city frames in the pile | Tubes, lube, pads; check valve type |
| **Silver Streak** | `9353` | Grey/silver fendered city bike (right side, possibly yellow-wall tire) | Tubes/tires, pads, lube |
| **Black Rack** | `9353` | Black frame with rear rack/basket | Tubes, lube, brake check |

### 🟡 Group B — Advanced (special parts, odd sizes, or more time/risk)

| Name | Where | What I can see | Why it's harder |
|------|-------|----------------|-----------------|
| **Scarlet** | `9353 9354 9355` | Prominent red sport/diamond frame, cottered crank, single chainring | Cottered crank — if a cotter pin is seized/bent it wants a **cotter press**, not just a wrench |
| **Zafir** | `9357 9358 9359` | Red "ZAFIR" city/road bike in the shed *(may be the same bike as Scarlet — flag for dedup)* | Confirm it's distinct; brake/drivetrain type TBD |
| **Pepper** | `9358` | Kids' **BMX**, red rims, ~16–20" | Odd **406 (20")** tube/tire sizes; cheap parts may need a small special order |
| **Roadster(s) TBD** | `9353` pile | One or more German roadsters likely in the stack | **Rod / coaster / drum brakes** use different pads & linkage than caliper/V — identify before buying |
| **Build candidates** | `9361 9362` | ~3–4 bare frames hanging in the garage | Full builds from the wheel/tire stash — most labor, but no special tools |

> **Likely duplicate:** the red bike(s) — *Scarlet* (woodpile) and *Zafir* (shed) — may
> be one bike, given the "some overlap / not sure" call. Counted cautiously above.
> Several indistinct pile members in `9353` couldn't be resolved individually; they're
> folded into the ~10–14 total rather than named.

---

## What I can't tell from photos (the on-site 30-second checks)

These don't change *whether* a bike is repairable with basic tools — they change
*what consumables to buy*. Best-guess defaults in brackets:

- **Tire ETRTO** (sidewall `XX-YYY`) — expecting mostly **622 (28")**, some **559/590 (26")**, **406 (20")** for Pepper. *[stock tubes accordingly]*
- **Valve type** — these old German bikes mix **Dunlop/Woods, Schrader, Presta**. *[bring the valve adapter set — fix-list already lists it]*
- **Brake type per bike** — caliper/V vs **rod / coaster / drum**. *[don't bulk-buy pads until confirmed]*
- **Drivetrain** — the cottered single-chainring cranks (`9351`, `9354`) point to **single-speed or internal hub (1/8" chain)** rather than derailleurs. *[lean 1/8" chains over 3/32"]*
- **Tube/seatpost/stem condition** — assume perished tubes and some seized posts given the surface rust everywhere.

---

## Bottom line for your packing list

Your instinct is right: **leave the welding/fancy gear at home.** The photo evidence
says this is a *consumables-and-elbow-grease* job. The only tool worth adding beyond
your basic kit and the fix-list is a **cotter pin press** (cheap, and at least two
bikes show cottered cranks) and plenty of **penetrating oil** for seized fasteners.
The on-site **wheel and tire stash is your most valuable asset** — harvest it before
spending a euro on rubber.

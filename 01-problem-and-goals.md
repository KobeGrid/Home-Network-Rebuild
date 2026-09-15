# Problem & Goals

## Problem

I have Ethernet and coax runs throughout my house going to an unknown number of destinations, and I don't have documentation of where any of them terminate. Before I invest in new networking equipment (switch, access points, etc.), I need to answer:

- **How many cable runs exist**, and which rooms/outlets they serve
- **What each run actually is** — Cat5e, Cat6, coax — since the existing cabling may not support the speeds or PoE requirements of new equipment
- **Where everything terminates** — likely a central panel or junction point, but the exact wiring layout isn't documented anywhere
- **Which runs are still usable** and which are dead, damaged, or miswired
- **Whether new Cat6 runs are needed** for any locations before I install new gear, rather than finding out after equipment is mounted and cables come up short or unsupported

Without this audit, any new network build is a guess — I could buy switches and access points sized for a layout I don't actually understand, or discover mid-install that a "connected" outlet doesn't have a live run behind it.

## Environmental Consideration

Since any new or re-run cable will go through the attic in a desert climate (Las Vegas), attic temperatures can regularly exceed 130–150°F in summer. This affects material choice:

- **Standard PVC-jacketed Cat6 can become brittle or degrade faster** under prolonged extreme heat — a real risk for attic runs that isn't a factor in a temperature-controlled wall cavity
- **CMR (riser-rated) cable is the minimum standard** for attic runs; if any portion runs near or through HVAC ductwork, plenum-rated (CMP) cable is the safer choice despite the higher cost
- **Cable jacket UV resistance matters too** if any run is near attic vents or gets indirect sun exposure through roof gaps
- **Heat can also affect max cable run distance/signal degradation** over time, so keeping runs as short and direct as possible matters more here than in a mild climate

This is a deliberate design constraint on the project, not just a cabling preference — the install environment shapes the material choice as much as the network requirements do.

## Goal

Use a tone generator/probe kit to trace every existing run back to its source, label each cable at both ends, and produce a wiring map of the house before purchasing or installing any new network equipment. Any new runs added through the attic will use CMR-rated (or CMP, where near HVAC) cable to account for the desert climate.

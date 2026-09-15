# Topology Options

## Option 1: Rack in Closet Panel (Centralized at Existing Termination Point)

**Setup:** Keep the modem and network rack in the closet where the structured wiring panel already lives. Have Cox come out and activate/move service to that coax feed at the panel.

**Pros:**
- Everything is centralized — modem, patch panel, and rack equipment all in one location
- No need to run new cable to a different termination point; uses the existing structured panel
- Simplest install logistically, since the infrastructure is already there

**Cons:**
- Closet isn't temperature-friendly for networking equipment — no dedicated cooling, and gear running 24/7 in an enclosed space adds heat buildup risk over time (especially relevant in a desert climate where ambient temps are already higher)
- Long-term equipment lifespan/reliability could be affected by heat if not actively addressed (ventilation, small fan, etc.)

## Option 2: Rack in Bedroom (New Termination Point, Better Cooling)

**Setup:** Leave the modem at the panel, but run new Ethernet from the panel through the walls/attic into the bedroom. Convert the single outlet there into multiple outlets (or add additional wall inlets) to support a rack near the desk. From there, run cabling back out through the walls to APs and other rooms throughout the house.

**Pros:**
- Rack lives in a cooler, more climate-controlled room instead of an enclosed closet
- Easier physical access for day-to-day management since it's right next to the desk/workspace
- More efficient cooling for equipment longevity
- Sets up a cleaner "home run" topology — one central rack distributing to APs/rooms

**Cons:**
- More costly — requires new cable runs, wall modifications, and possibly attic work
- Requires attic access to verify/run cable, plus drilling additional wall openings in the bedroom
- More labor-intensive and time-consuming than using the existing panel

## Option 3: Repair Existing Backroom Feed (Fix What's Already There)

**Setup:** Repair the poorly terminated coax/Ethernet feed in the back room (the one that required moving boxes to trace), and consolidate all networking equipment there as the central point.

**Pros:**
- Reuses the existing (if flawed) termination point — no new wall penetrations or attic runs needed
- Lower cost than Option 2 since it's a repair job, not a new build-out
- Keeps equipment out of both the closet and the bedroom

**Cons:**
- Inherits the backroom's existing issues — it was buried behind stored boxes with no accessible routing, so even after repair, the room itself may still require clearing/reorganizing for long-term access
- No indication yet whether the backroom has better thermal conditions than the closet
- Doesn't address centralization the way Option 1 does, or cooling/access the way Option 2 does — a middle-ground fix rather than a clear upgrade

## Comparison

| Factor | Option 1: Closet Rack | Option 2: Bedroom Rack | Option 3: Backroom Repair |
|---|---|---|---|
| **Cost** | Low — uses existing termination | High — new runs, wall work, attic access | Medium — repair only, no new runs |
| **Cooling** | Poor — enclosed, no airflow | Best — climate-controlled room | Unknown — untested, likely similar to closet |
| **Access/Maintainability** | Good — centralized, panel already organized | Best — equipment next to desk, easy to manage | Poor — buried behind storage, same access issue as today |
| **Install Effort** | Low | High — attic work, drilling, multiple new outlets | Medium — re-terminate + clear/organize room |
| **Scalability for APs/rooms** | Good — panel already distributes | Best — designed as a clean home-run topology | Limited — inherits backroom's existing constraints |
| **Risk** | Equipment heat stress over time | Longest project, most that can go wrong mid-install | Fixes symptoms, not the root access/layout problem |

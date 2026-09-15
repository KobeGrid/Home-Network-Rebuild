# Findings

## Jack labeled "CAT-5E" — confirmed via cable jacket printing
This run is Cat5e, not Cat6. Cat5e is rated for Gigabit speeds but falls short of what newer switches/access points (2.5GbE, 5GbE) can push. This jack is a candidate for replacement if this room needs higher throughput.

## Coax connector improperly seated at wall plate
The coax barrel connector at this jack is angled rather than sitting flush, putting ongoing mechanical strain on the connection point. Over time this kind of stress can loosen the connector or degrade signal quality. Not a "just tighten it" fix — worth redoing the termination.

## Unlabeled, unsecured coax distribution point
The splitter/distribution panel these runs feed into has multiple coax legs with no visible labeling, loosely draped rather than bundled or secured. Without labels, tracing which leg serves which room requires tone-testing each run individually rather than reading a label.

## Cable path required physical excavation to trace
Initial tone-tracing failed to pick up a signal along the expected wall/floor path. Traced by hand instead — the run from the modem/switch was routed behind stored boxes rather than along an accessible path, with no drop ceiling, conduit, or visible routing to follow. This suggests the original install prioritized "get it connected" over any kind of maintainable routing.

## Improper termination at wall jack
Cable appears to be bare wire pressed into the jack rather than a proper crimped/punched termination. Combined with the surrounding cable tangle (coax splitter, multiple unlabeled runs draped over storage), this point can't be reliably probe-tested without first isolating and likely re-terminating the connection properly.

## Located Ethernet jack termination point in closet panel
Traced and confirmed the closet panel as a termination point for one of the house's Ethernet runs, distinct from the wall-jack mess found elsewhere.

## Located structured wiring distribution panel
Found the home's central distribution point — a punch-down terminal block with multiple labeled Cat runs feeding a small patch panel, alongside coax distribution. This is the hub that the wall jack and closet Ethernet runs trace back to. Unlike the earlier haphazard wall-plate termination, this panel shows actual structured cabling design intent, even if execution/labeling is inconsistent.

## Hand-labeled coax runs (marker/Sharpie on jacket)
Coax cables in the panel are labeled with handwritten marker directly on the cable jacket rather than printed labels. This works short-term but fades, smudges, or becomes illegible over time, and doesn't hold up if the cable is ever re-routed or re-terminated. Worth replacing with proper printed/laminated labels or a label maker as part of the rebuild.

## General observation
The existing install prioritized "functional" over "maintainable" — cables work but aren't documented, labeled, or routed with any future troubleshooting in mind. Part of this project's value is correcting that: every run gets identified, tested, and labeled as it's found.

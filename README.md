# medical-feed

A live wire on the medical industries worldwide: who pays the prescriber, what
gets prescribed and diagnosed as a result, what the safety data actually shows,
who approves it, and what it costs the people on the receiving end.

Built after "The Medical Industry" on Welcome to Your Galaxy.

**This is a feed on industry conduct. It is not medical advice and is not built
to be read as any.** Health-and-wellness coverage, symptom explainers, remedies
and individual illness stories are refused by the gate for that reason.

## The twenty subjects

| | |
|---|---|
| Who pays the prescriber | What gets prescribed |
| Diagnosing more | Unnecessary procedures |
| What treatment does | Trial data and what is published |
| How it gets approved | Regulators and the door between |
| How it is sold | Who writes the guidance |
| Price, patent and access | Billing, cover and refusal |
| Devices and implants | Addiction and dependence |
| Unsafe and contaminated products | Where oversight is thinnest |
| Health records as an asset | Mental health treatment |
| What it costs them when they lose | Prevention, and what is set against it |

Payment and prescription are kept as separate subjects because the section's
argument runs through a chain — money reaches the prescriber, prescribing
changes, diagnosis widens to justify it — and the figures it cites sit at
different links. Separating them means a story about a disclosure rule and a
story about prescribing volume do not collapse into one chip.

## The gate

Health-and-wellness pages are refused: symptom explainers, supplements,
remedies, what-causes pieces, diet and sleep advice. So are individual and
celebrity illness stories, and business coverage with no conduct angle.

A story no subject will claim is refused and counted as refused, rather than
filed under a fallback subject it did not earn.

## Weight

A decision (2), institutional material (2), a measured figure (1), a pending
decision with a date (1), a named jurisdiction (1), a primary source (1). At
three or more it is marked consequential.

## Sources

183 wires. 29 direct feeds carried over from the sibling repos where they are
already proven, plus 138 Google News locale searches across 26 languages with
24 rotating queries, and 16 subject searches.

Worth adding, with URLs you have opened: the BMJ, The Lancet, Cochrane, Health
Action International, Medicines Law & Policy, AllTrials, Public Citizen's
Health Research Group, and national medicines regulators. Those are the
specialist sources for this subject.

## Running it

    python3 harvest_medical.py
    python3 harvest_medical.py --dry-run
    python3 verify_sources.py

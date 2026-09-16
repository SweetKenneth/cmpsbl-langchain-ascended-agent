<!-- SHPBL-PROVENANCE -->
> **Status: provenance — preserved, not maintained.**
>
> A CMPSBL agent experiment over LangChain. Predates the SHPBL run contract.
>
> This repository is part of the SHPBL / CMPSBL provenance record. It is kept so
> that current work can be traced back to where it came from. It is not the
> product, it is not supported, and nothing here should be treated as current
> SHPBL behaviour. Issues and pull requests are not worked.
>
> Current entry point: [SHPBL.com](https://shpbl.com). Canonical repository:
> `SweetKenneth/shpbl-master`. See `PROVENANCE.md` in this repository.

# CMPSBL® Ascended LangChain Agent

# Same agent. Same code. Different behavior.

⸻

# What this is

This is a real LangChain agent.py.

It has not been modified.

Instead, it has been wrapped with a second runtime layer that changes how it behaves during execution.

⸻

# The idea

You normally improve software by changing its code.

This takes a different approach:

Attach behavior at runtime instead of modifying the source

⸻

# Files in this repo

	•	agent.py
→ Original source (Layer 1, MIT licensed)

	•	cmpsbl_agent.py
→ Ascended version (Layer 2 attached)

	•	manifest.json
→ Artifact identity (CJPI score + fingerprint)

	•	HARNESS-REPORT.txt
→ Pre-export verification (passed)

	•	USER-GUIDE.html
→ Debug + verify modes and capability breakdown

	•	LICENSE-UPSTREAM.txt
→ Original MIT license

	•	LICENSE.html
→ Layer 2 license (CAAL-1.0)

	•	NOTICE.txt
→ Attribution and license separation


⸻

# Before vs After

Original (agent.py)

	•	Stateless execution
	•	One-shot behavior
	•	No runtime mediation

⸻

# Ascended (cmpsbl_agent.py)

	•	Memory across interactions
	•	Autonomous decision loop
	•	Runtime safety + cost controls
	•	Execution mediation layer

⸻

# Verification

This artifact includes a full verification chain:
	•	✔ Layer 1 preserved byte-for-byte  ￼
	•	✔ Layer 2 successfully attached
	•	✔ 6 runtime layers auto-wired
	•	✔ Entry point + 41 handlers detected

⸻

# Try it

Run the original:

python agent.py

Run the ascended version:

python cmpsbl_agent.py

Ask the same questions and compare behavior.

⸻

# Example

Try:

Explain recursion
What did I ask before?

The responses will diverge.

⸻

# What changed?

Not the code.

The execution.

⸻

# Architecture

Layer 1:

	•	Original source (MIT licensed)

Layer 2:

	•	External runtime layer (CMPSBL)

Layer 2 attaches to execution without modifying Layer 1.

⸻

# User Guide

See:

USER-GUIDE.html

Includes:

	•	capability breakdown
	•	debug mode
	•	verification steps
	•	pipeline details

⸻

# License

	•	Layer 1: MIT (original source)  ￼
	•	Layer 2: CAAL-1.0 (CMPSBL runtime)  ￼

⸻

# Why this exists

To test a simple question:

Can you change how software behaves without changing the software itself?

⸻

# Discussion

Curious what people think.

Is this useful?

Or just a different way to structure the same ideas?

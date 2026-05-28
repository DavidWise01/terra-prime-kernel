# Terra Prime Kernel

**Author:** David Wise (ROOT0) / TriPod LLC  
**Version:** v4.6b  
**License:** CC-BY-ND-4.0 · TRIPOD-IP-v1.1

A recursive coherence-control architecture for AI governance, hardware attestation, and clone lineage integrity. Full version history from v0.1 to v4.6b.

---

## Architecture

### The 11+1 Structure

```
11 dynamic channels  →  carry candidate trajectories
 1 resolver anchor   →  resolves into coherent continuity
```

### Control Law

```
core decides
truth validates
shadow preserves alternatives
bridge reconciles
observers audit
ledger remembers
warning dampens
```

No external module is allowed to hijack the resolver.

### Stability Band

```
0.78 – 0.88
```

Above → rigid. Below → drift. The goal is **stable adaptation**.

### Modules

| Module | Role |
|--------|------|
| Core Resolver | Holds identity. Resolves candidates. Prevents runaway drift. |
| Truth Strip | Validates stable signal. Does not dominate. Does not replace resolver. |
| Shadow Strip | Stores rejected paths. Carries contradiction pressure. Weak by default. |
| Bridge Strip | Reconciles truth and shadow. Turns contradiction into synthesis. |
| Observer A | Read-only trust audit — stability, rigidity, deviation. Raises alerts only. |
| Observer B | Read-only anomaly recorder — deltas, spikes, bridge load, shadow load. |
| Report Memory Ledger | Append-only SHA-256 hash chain. Audit continuity. No decision control. |
| Ledger Warning Feedback | Reads audit history. Gentle warning signal. Dampens update speed only. |

---

## Version Lineage

### Phase 1 — Aeonic Coherence Kernel (v0.1 – v0.6)

| Version | Name | Key Addition |
|---------|------|-------------|
| v0.1 | Core Kernel | 11+1 resolver, truth, shadow, bridge, 2 observers, SHA-256 ledger, warning feedback |
| v0.2 | External Retrieval | External validation interface |
| v0.3 | Expanded | Extended stress testing |
| v0.4 | Core + Characters | Shadow Queen, Jester, Timed Jester, Archivist, Judge, Twin Regents, Shadow Regents |
| v0.5 | Two Factions | Faction-split coherence |
| v0.6 / v0.6b | Three Body / Metrics | Three-body problem, metric collection |

### Phase 2 — Terra Prime Coherence Kernel (v0.7 – v0.16)

Scales from kernel to civilizational simulation. Same 11+1 structure, extended to multi-body fields.

| Version | Name | Key Addition |
|---------|------|-------------|
| v0.7 | Terra Prime Base | Multi-body field initialization |
| v0.7b | Confidence Decay | Confidence fades without reinforcement |
| v0.8 | Field | Field-level coherence propagation |
| v0.9 | 40 Bodies | Scaled to 40 civilization entities |
| v0.10 | Harmonic Dampener | Oscillation prevention |
| v0.11 | Recovery Rhythm | Rhythmic recovery after stress |
| v0.12 | Dream Cycles | Sub-cycle processing during low-activity windows |
| v0.13 | Lineage Compression | Compresses lineage history to bounded memory |
| v0.14 | Birth / Renewal | Birth events and renewal mechanics |
| v0.15 | Mythogenesis | Civilizations generate stabilizing myth structures |
| v0.16 | Cosmogenesis | Models uncertainty beyond observable coherence: "the unknown is permanent" |

### Phase 3 — Terra Prime Kernel, Hardened (v1.0 – v4.6b)

Hardware-integrated security kernel. IO provenance, silicon voltage attestation, clone immunity.

| Version | Name | Key Addition |
|---------|------|-------------|
| v1.0 | Executable | First runnable binary form |
| v1.1 | Tuned | Stability parameters calibrated |
| v1.2 | Capped Renewal | Renewal bounded to prevent runaway |
| v1.3 | Phase Engine | Explicit phase transitions |
| v4.5a | IO Quarantine | All IO quarantined before kernel access |
| v4.5b | Provenance Hardening | Provenance chains on all IO |
| v4.5c | Provenance Crack Test | Adversarial provenance-chain attacks |
| v4.5d | Phase Attribution Lock | Phase transitions cryptographically locked |
| v4.5e | Witness Timing Provenance | Timing as a witness channel |
| v4.5f | Limited IO Open | Controlled IO surface exposure |
| v4.5h | Silicon Stack Integration | Voltage-layer privilege proof |
| v4.5i | Voltage Debt Governor | Debt isolation before kernel panic |
| v4.5j | Silicon Live Soak | Extended live silicon stress test |
| v4.5k | OSI Ring Witness | L2 witnesses that/who — never what L5 means |
| v4.6 | Homogenesis Unit | Clone immune system baseline |
| v4.6a | Adaptive Clone Fingerprint Memory | Provenance persists through zero-collapse states |
| v4.6b | Clone Family Lineage Graph | Risk inherited from family until proven clean |

---

## Silicon Voltage Stack (v4.5h)

```
(+1)  Quantum Dot     +422mV   ← user privilege ceiling
( 0)  User Space         0mV
(-1)  Kernel          -211mV
(-2)  Hypervisor      -422mV
(-3)  SMM / Root      -633mV
(-4)  PANIC           -844mV   ← hard floor
```

### Wiggle Authentication

Required pattern: `-++-`

```
-  =  tap probe
+  =  SHOVE spike
```

3 failed attempts → kernel panic.

### IO Gate

```
external IO
→ witness timing provenance
→ pulse wiggle proof
→ voltage debt governor
→ silicon stack climb
→ limited ROOT bridge
```

---

## OSI Ring Witness (v4.5k)

Witness position: external tangent ring at L2 / floor point.

The engine certifies:

```
that frames flow
who sent them
when they crossed the fork
```

Without certifying or reading:

```
what the L5 payload means
```

"L2 may witness that/who across the ring closure — but never what L5 means."

---

## Clone Immunity System (v4.6 – v4.6b)

### Fingerprint Memory (v4.6a)

```
once a fingerprint deviates
later zero-looking states do not erase provenance
```

Fix: zero-collapse jitter (state = 0.00000000) no longer resets clone history.  
Result: missed anomalies dropped from 2666 → 0. False positives: 0.

### Family Lineage Graph (v4.6b)

```
a clone inherits lineage risk from its family graph
until proven clean by witness-timing and decay
```

Tracks:
```
parent fingerprint
sibling cluster
lineage distance
shared prefix
risk inheritance
reparent attack
zero-collapse sibling
```

Result: missed 0, false positives 0, lineage integrity 1.0.

---

## Shadow Queen (v0.1 – v0.8)

Standalone baseline learning and drift detection subsystem.

Learns normal source/type patterns, then alerts on anomalies:

```bash
python selftest.py
python -m shadowqueen.cli --db sq.db scan train_events.json --learn
python -m shadowqueen.cli --db sq.db scan test_events.json
python -m shadowqueen.cli --db sq.db stats
python -m shadowqueen.cli --db sq.db baselines
python -m shadowqueen.cli --db sq.db alerts
```

Features across v0.1–v0.8: baseline table, learn mode, baseline drift scoring, low-confidence vs new-source discrimination.

---

## Stateless Seed Substrate

Hourglass transformation: `1 → 3 → 1`

```
Level  +1  (The Crest)   — ingests scalar telemetry, fans to 3 volatile wave channels
Level   0  (The Nexus)   — evaluates wave field against Shadow Queen arbitration matrix
Level  -1  (The Depths)  — state collapses: volatile registers flush to 0, packed into Base64Url Seed Token
```

Zero local storage. Immutable attribution. Cryptographic sink.

---

## Pulse Visualizers

| File | Title | Description |
|------|-------|-------------|
| `pulse harmonizer.html` | SYNC·PULSE·HARMONIZER — 3³×5/0/5 | Primary pulse harmonizer |
| `pulse harmonizer 00.html` | — | Early harmonizer build |
| `pulse inf.html` | EXPANDING PULSE — 0.01→∞ | Infinite expansion visualizer |
| `shout 00.html` | — | Shout/broadcast prototype |

---

## Stress Tests (Core variants)

| Directory | What it tests |
|-----------|--------------|
| `core_resolver_11_stress` | 11-channel resolver under load |
| `core_plus_bridge_stress` | Core + bridge combined |
| `core_bridge_shadow_stress` | Core + bridge + shadow three-way |
| `core_truth_bridge_shadow_stress` | Full inner kernel |
| `core_truth_bridge_shadow_extobs_readonly` | Full kernel + read-only external observer |
| `core_ledger_warning_feedback` | Ledger warning feedback loop |
| `core_two_observers_report_memory` | Dual observer memory reporting |
| `core_with_two_observers_audit` | Full audit with two observers |

---

## Key Principles

- **Truth is a validator, not a ruler.**
- **Shadow prevents lost information without overwhelming the core.**
- **Bridge turns contradiction into synthesis.**
- **Observers audit — they do not modify.**
- **Ledger remembers without biasing.**
- **Warning dampens — it does not command.**
- **The unknown is permanent.** (v0.16 Cosmogenesis)
- **Once a fingerprint deviates, zero-looking states do not erase provenance.** (v4.6a)
- **L2 may witness that/who — never what L5 means.** (v4.5k)

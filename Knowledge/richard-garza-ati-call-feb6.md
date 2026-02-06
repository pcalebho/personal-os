# Richard Garza - ATI (Feb 6, 2026)

**Date:** Feb 6, 2026  
**Contact:** Richard Garza  
**Role:** Process Control Engineer II  
**Company:** ATI (industrial automation)  
**Outcome:** Positive, will intro colleague Jonathan (more experience in design)

---

## Core Pain Points

### 1. Cross-Team Coordination Bottleneck
**The problem:** Wrangling IO lists and requirements from different teams, then handing off to panel shop

**Teams involved:**
- Automation engineers (know control loops, not instrumentation layout)
- Instrumentation teams (know wiring, not control points)
- Systems engineers (may lack instrumentation expertise)

**Result:** Specification handoffs create gaps and rework

### 2. Component Lead Times Throw Off Timeline
- Individual component lead times unpredictable
- Creates visibility/scheduling problems
- Can delay entire project

### 3. Vendor Selection Driven by Cost
- Unless deadline pressure forces premium vendor
- Most design outsourced to external vendors
- Siemens premium = proprietary devices + support (justified)
- Automation Direct cheaper but slower response/different programming paradigms
- Large multinationals don't usually care about cost unless $10k+ difference

---

## Technical Context

### Application Example: Steel Mill Precision Control

**Use case:** Screw position controls gap thickness in metal rolling

**Problem:** 
- Metal deformation creates bulging, uneven contact stress
- Work rolls develop "crown" from heating/expansion during operation
- Crown deflection varies throughout day as rolls heat up

**Why critical:**
- Safety-critical system (excessive force breaks mill catastrophically)
- Requires millisecond-level sampling + response
- Too dangerous for manual lever operation

**Implication:** Automated systems prevent catastrophic damage; reliability > cost

---

## Strategic Implications

**What Blitzpanel could solve:**
1. **Cross-team IO spec coordination** — automate wrangling of requirements from multiple teams
2. **Lead time visibility** — integrate component lead times into design (show impact on schedule)
3. **Spec handoff automation** — reduce gaps between design teams + panel shop

**Not about speed of build.** About clarity/completeness of spec + lead time planning.

---

## Next Steps

- [ ] Richard will intro Jonathan (colleague with deeper design experience)
- [ ] Schedule call with Jonathan to validate pain points at larger scale
- [ ] Explore whether spec coordination + lead time visibility resonate

---

## Pattern Tracking

**Hypothesis:** Engineering-as-a-service is bigger than build speed

**Evidence so far (5 conversations):**
1. Warehouse/logistics: wants pre-built + design elimination
2. Control Associates grandfather: engineering time is bottleneck, values collaborative design
3. Billy (Reynolds): distributor, SPA process
4. **Richard Garza: cross-team coordination + lead time visibility > cost**

**Trend:** Every technical person mentions coordination/spec clarity, not build speed.

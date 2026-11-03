# E-Pharmacy Supply Chain & Operational Excellence

### Warehouse Process Optimization | Operations Case Study

A structured operational improvement proposal for an e-pharmacy regional fulfillment center, focusing on **inbound processing, order picking, inventory accuracy, and reduction of expiry and dispatch losses**.

> **Project type:** Case study and proposed operational improvement strategy. All improvements, savings, and future-state KPIs are **targets or estimates**, not measured implementation results. The case-study inputs are supplied in the original assignment.

## 1. Problem Statement

An e-pharmacy warehouse receives medicines from suppliers, stores inventory, processes customer orders, and dispatches shipments. The operations team wants to improve speed, efficiency, and inventory management.

### Operating scale and baseline

| Metric | Case-study baseline |
|---|---:|
| Customer orders | **12,000 per day** |
| Stock keeping units (SKUs) | **18,000** |
| Inbound shipments | **85 per day** |
| Inbound dock-to-stock turnaround time (TAT) | **9.5 hours** |
| Picking productivity | **55 order lines/hour** |
| Inventory record accuracy | **94%** |

The case identified four operational challenges:

1. **Inbound delays:** It takes approximately 9.5 hours from stock arrival until inventory becomes available for sale.
2. **Picking inefficiency:** Pickers spend time searching for products, walking between locations, and waiting for replenishment.
3. **Inventory discrepancies:** Incorrect locations, quantity mismatches, near-expiry items, and damaged stock undermine accuracy.
4. **Avoidable losses:** Expiry, damage, incorrect picking/dispatch, and returns create operational waste.

### Assignment objectives

- Prioritize three improvement areas.
- Recommend practical actions to reduce inbound TAT, improve picking efficiency, strengthen inventory accuracy and **FEFO (First-Expiry, First-Out)**, and reduce losses.
- Define **5–7 KPIs** to measure performance.
- Create a **30-60-90 day action plan**.

## 2. Diagnosis and Root-Cause Assessment

The proposed diagnosis links four stages:

**Unscheduled dock arrivals and manual check-in** → **9.5-hour dock-to-stock delay** → **inventory mismatches and scattered stock** → **long picker travel and empty-bin waits** → **stockouts, wrong dispatches, returns, and scrap**.

The proposed presentation additionally modeled **1,800 problematic picking lines/day**. This is a solution-deck planning assumption, **not a figure supplied by the original problem statement**.

## 3. Proposed Solution: Three Improvement Levers

### A. Inbound intake and dock-to-stock time

| Proposed intervention | Operational purpose |
|---|---|
| **Dock appointment slots** | Spread the 85 daily inbound shipments more evenly across the day to reduce congestion and waiting. |
| **Advance Shipment Notice (ASN) pre-receipt** | Prepare shipment details and pallet barcode labels ahead of arrival to accelerate check-in and receipt. |
| **Green Channel quality control** | Fast-track appropriate trusted suppliers while maintaining required quality safeguards. |

**Proposed TAT target:** 9.5 hours → **3.5 hours** (approximately **63% reduction**). The 3.5-hour future state is a chosen target; the case study does not contain a measured process-time breakdown proving it.

### B. Picking productivity and warehouse layout

| Proposed intervention | Operational purpose |
|---|---|
| **ABC velocity-based slotting** | Position high-demand Class A products close to packing stations; the deck proposes prioritizing the top 20% of SKUs. |
| **Multi-order batch picking carts** | Pick approximately 8–12 customer orders per route to reduce repeated walking. |
| **Automatic replenishment triggers** | Refill forward-pick locations when inventory reaches a proposed 30% buffer threshold. |

**Proposed productivity target:** 55 → **95+ order lines/hour** (approximately **73% increase** at 95 lines/hour; the presentation rounds this to **72%**).

### C. Inventory accuracy, FEFO, and dispatch quality

| Proposed intervention | Operational purpose |
|---|---|
| **Barcode-enforced FEFO** | Prevent picking newer-expiry batches before older-expiry stock, subject to controlled exceptions. |
| **Dynamic cycle counting** | Trigger stock checks when bin discrepancies are detected. |
| **Pack-station barcode verification** | Verify products before final dispatch to reduce wrong picks and returns. |

**Proposed inventory accuracy target:** 94% → **at least 99.2%**.

## 4. 30-60-90 Day Implementation Roadmap

| Phase | Focus | Proposed actions |
|---|---|---|
| **Days 1–30** | Diagnose and stabilize | Classify all 18,000 SKUs by movement; identify approximately 2,000 high-priority items; conduct picker time-motion and dock-delay studies; clean up bin labels; begin cycle counts for fast movers. |
| **Days 31–60** | Pilot and re-engineer | Relocate approximately 2,000 priority SKUs near packing; trial one-hour dock appointments with 20 suppliers; pilot FEFO barcode restrictions and multi-order carts with 10 pickers. |
| **Days 61–90** | Scale and standardize | Expand batch picking; introduce 30% replenishment alerts; create vendor performance scorecards; standardize shift handovers and inventory count procedures. |

### Operational safeguards

- Reserve **30% flex-dock capacity** for unscheduled trucks.
- Use a controlled supervisor override for FEFO exceptions, triggering a cycle count.
- Reassess Class A forward-pick locations weekly to reflect demand changes.

## 5. KPIs and Proposed Targets

| KPI | Original baseline | Proposed 90-day target | Measurement approach |
|---|---:|---:|---|
| **Dock-to-stock TAT** | 9.5 hours | ≤ 3.5 hours | Time from shipment arrival to saleable stock availability |
| **Picker productivity** | 55 lines/hour | ≥ 95 lines/hour | Picked order lines divided by picker working hours |
| **Inventory record accuracy** | 94% | ≥ 99.2% | Matched physical/system inventory records divided by records checked |
| **Problematic picks** | Not supplied in original brief | < 240 lines/day | Track picks delayed by missing or mismatched bins; deck models a 1,800-line/day starting assumption |
| **Wrong picks/dispatches** | Not quantified in original brief | < 0.15% of orders | Incorrectly picked/dispatched orders divided by total orders |
| **Expiry/scrap loss** | Not quantified in original brief | Reduce through FEFO; deck also presents a < 0.25% target | Track expired/scrapped inventory value against a consistently defined inventory or sales denominator |
| **Safety-stock buffer** | Not quantified in original brief | 5% reduction | Compare safety-stock value against an agreed baseline |

**Measurement note:** Some starting values and targets in the presentation were introduced as planning assumptions, rather than supplied by the original assignment. Before implementation, those metrics would require operational baseline validation.

## 6. Projected Business Impact

The solution deck estimates the following potential monthly value using its stated planning assumptions:

| Value lever | Estimated monthly benefit | Basis used in the presentation |
|---|---:|---|
| Labor productivity | **₹8.28 lakh** | About 230 labor hours/day freed × 30 days × ₹120/hour |
| Recovered contribution from fewer stockouts | **₹4.86 lakh** | 180 orders/day recovered × ₹600/order × 30 days × 15% margin |
| Expiry, mispick, and return reduction | **₹15.12 lakh** | ₹8.64 lakh expiry savings + ₹6.48 lakh wrong-order savings |
| Inventory carrying-cost reduction | **₹0.75 lakh** | ₹75 lakh assumed safety-stock release × 12% annual carrying cost ÷ 12 |
| **Total modeled monthly benefit** | **~₹29.0 lakh** | Sum of the four modeled components |

**Additional modeled impact:** A **₹75 lakh one-time working-capital release** from reducing a hypothetical ₹15 crore safety-stock base by 5%. This is **not** an additional ₹75 lakh monthly profit.

These are **scenario estimates**, not verified operational outcomes. Their assumptions (such as labor cost, margin, stockout recovery, inventory values, and error rates) would need to be validated with actual warehouse data before claiming achievable savings.

## 7. Approach and Key Takeaways

This case study demonstrates a structured operations-consulting approach:

1. **Diagnose:** Translate operating metrics into bottlenecks and potential root causes.
2. **Prioritize:** Focus on inbound flow, picker productivity, and inventory governance.
3. **Design:** Propose practical process changes rather than high-capital investments.
4. **Measure:** Link each intervention to measurable KPIs and target outcomes.
5. **Implement:** Sequence diagnosis, pilots, and scaling through a 30-60-90 day roadmap.
6. **Validate:** Distinguish supplied baseline data from proposed future-state assumptions.

**Relevant competencies:** Supply Chain Operations · Process Optimization · Warehouse Management · Inventory Control · ABC Analysis · FEFO · KPI Design · Operational Excellence · Business Case Analysis

## 8. Project Files and Attribution

- **`E-Pharmacy - A case study .docx.pdf`** — original case-study problem statement and assignment instructions.
- **`Solution.pdf`** — proposed solution presentation, including operational levers, rollout plan, KPIs, and modeled financial impact.

> **Attribution:** The solution presentation is labeled *“Presented by Sagar, Candidate for Operations Intern (SCM), API Holdings.”* Preserve the original author's attribution when publishing or adapting this material. This repository should not imply that the solution was personally developed or pitched by someone else unless their actual contribution is accurately identified.

---

*This is an educational case-study proposal. It does not represent an implemented warehouse transformation, confirmed company results, or an official project of PharmEasy/API Holdings.*

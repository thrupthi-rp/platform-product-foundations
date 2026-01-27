# Data Utility Protocol: The Editor’s Framework

> **Philosophy:** Strategy is the art of exclusion.  
> In data-heavy platforms, utility is found in what we *cut* to find the truth.

This protocol serves as a governance layer to prevent **Data Graveyards** and minimise **Intellectual Debt** during discovery and ingestion phases.

---

## 1. The Ingestion Audit (The Raw Footage)

*Before approving a new data stream or ingestion pipeline, apply the following lens:*

| Heuristic | Question | Strategic Goal |
| :--- | :--- | :--- |
| **Intent** | What specific decision will be triggered by this data? | Prevent just-in-case hoarding |
| **Lifecycle** | What is the expiry date of this data’s relevance? | Manage long-term storage debt |
| **Integrity** | Is this a single source of truth or a duplicate? | Reduce architectural noise |

---

## 2. Schema Governance (The Edit)

Data modelling is a **One-Way Door**.  
How data is structured at the point of ingestion dictates the limits of future intelligence.

**Irreversible decisions**
- Naming conventions  
- Primary key logic  
- PII masking and classification  

**Reversible decisions**
- UI visualisation layers  
- Dashboard filters  
- Temporary reporting views  

---

## 3. The Utility Scorecard (The Final Cut)

We measure the success of a data strategy not by volume, but by **Velocity of Insight**.

**Accountability rule**  
Each metric must have:
- a **named decision owner**
- an **explicit decision cadence**

### The “Deleted Scene” Filter

If a metric satisfies any of the following, it is flagged for decommissioning:

1. **Vanity metrics**  
   High numbers that do not correlate to retention, risk reduction, or platform health.

2. **Orphan data**  
   Collected but not queried *or referenced in a decision* for more than 90 days.

3. **No-action insights**  
   Data that signals a problem but offers no path to resolution.

---

> *“If a data strategy feels like a four-hour rough cut no one wants to watch, stop filming and start editing.”*
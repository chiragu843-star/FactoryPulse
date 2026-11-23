# FactoryPulse — Manufacturing Operations & Unit-Economics Tracker

**FactoryPulse** is a mobile-first manufacturing management and unit-economics web application built for business owners who produce and manage multi-variant product lines across diverse **sizes, grades, and qualities**.

---

## Vision & Intention

In multi-SKU manufacturing environments, business owners often lose visibility into true product profitability and stock timelines because raw material prices fluctuate monthly, cycle times vary across grades and dimensions, and secondary expenses (labor, freight, packaging, and wastage) get buried in general accounting.

FactoryPulse was created to solve that gap on a single mobile-accessible screen—empowering factory owners and operations managers to:
- **Eliminate unexpected stockouts** by predicting exact depletion timelines for both raw materials and finished goods.
- **Track true landed unit costs** by factoring raw material consumption, labor, transportation, and overhead directly into every SKU.
- **Protect profit margins** by tracking month-over-month raw material price trends across the entire year so purchasing and pricing decisions are backed by hard data.
- **Keep daily shop-floor execution accountable** through structured task tracking and productivity scoring.

---

## What the App Contains

### 1. Executive Command Center (Dashboard)
- Real-time snapshot of active production runs, daily task completion rate, and overall factory productivity score.
- Immediate **Low-Stock & Depletion Alerts** highlighting raw materials and finished SKUs approaching critical thresholds.

### 2. Multi-Variant Inventory & Depletion Predictor
- Structured catalog supporting multiple **sizes, grades, and quality specifications** alongside base raw materials.
- Live calculation of **Days / Hours Remaining Until Stockout** based on rolling daily consumption and dispatch averages.

### 3. Production & Cycle-Time Logger
- Batch-level production entry linking finished SKUs to raw material inputs.
- Automatically calculates **cycle time per unit/batch**, tracks machine/shift output, and deducts consumed raw materials from live stock.

### 4. True Product Costing Engine
- Granular cost breakdown per SKU combining:
  - **Raw Material Cost** (weighted by yield and wastage)
  - **Direct Labor Cost** (per unit / per shift)
  - **Transportation & Freight Cost** (inbound and outbound)
  - **Packaging & Overhead Expenses**
- Calculates actual net product cost versus selling rate to display real-time unit margins.

### 5. Annual Raw Material Rate Tracker
- 12-month historical price ledger for every raw material.
- Month-over-month trend comparison (**Up / Down / Unchanged** with percentage variance) to identify seasonal price dips and supplier rate hikes.

### 6. Daily Tasks & Shop-Floor Productivity
- Priority-tagged operational checklists for owners and supervisors with completion tracking and daily execution metrics.

---

## How It Works

1. **Configure Inputs & Master Catalog:** Define your raw materials, current stock balances, and finished product variants (by size, grade, and quality) along with standard labor, freight, and overhead rates.
2. **Log Daily Activity:** Record production batches (start/end time, raw material used, output produced), daily dispatches, raw material purchases, and shop-floor tasks directly from your phone.
3. **Automated Calculations:** FactoryPulse recalculates live inventory balances, updates average production speeds per SKU, computes true landed product costs, and projects exact stockout dates.
4. **Review & Decide:** Use the monthly raw material rate comparison and unit-cost dashboards to adjust product pricing, schedule raw material procurement ahead of shortages, and optimize high-margin SKUs.

---

## Technology & Deployment

- **Architecture:** Lightweight, zero-dependency Progressive Web App (HTML5, CSS3, Vanilla JavaScript) designed for instant load speeds on mobile browsers.
- **Data Persistence:** Local browser storage (`localStorage`) with instant offline access and JSON backup/export support.
- **Hosting:** Deployed via **GitHub Pages** for free, reliable access from any Android, iOS, or desktop browser.

# Mckinsey Interview -- Swift Distributions  Case Study
![image](https://hackmd.io/_uploads/HkASw2NLGe.png)
![0808-00](https://hackmd.io/_uploads/Hk3aqn4UMl.jpg)

Every phase of the interview from initial structure to data analysis, math, and final synthesis.
![0808-1](https://hackmd.io/_uploads/ryfcJhNUMg.png)

---
## Reminder for myself: 
To understand why a Distribution Company's Revenue decreased, look into 3 Key Factors:
- 1.A drop in  Sales Revenue
- 2.A rise in Direct Service Cost
- 3.Higher operation Expense

## Actions 
- Must indentify which belongs to Cost of Service / Expense
- Draw out the Product Framework to idenfity all costs
## Checklists
✅ Check Financial Drivers:
✅ Evaluate Customer Dynamics
✅ Analyze Competitive Pressures:
✅ Assess Segment Alignment
✅ Pinpoint the primary root cause
✅ Identify under-monetized opportunities
✅ Spot stagnation
### --Quant Analysis
✅ Step 1: Calculate Current Price per Unit
✅ Step 2: Determine New Volume
✅ Step 3: Calculate Discounted Price
✅ Step 4: Map the Revenue Breakdown
✅ Step 5: Compute Incremental Revenue
### -- Final Recommendation
✅ Lead with a definitive recommendation:
✅ Propose Immediate Next Steps

![0808-0](https://hackmd.io/_uploads/Syq68hNUMx.png)


## 1. Initial Case Framework (Structuring the Problem)

When presented with a revenue/profit decline, structure the response using a **MECE (Mutually Exclusive, Collectively Exhaustive)** Issue Tree balancing financial levers and market dynamics.

```
                         [ Decline in Swift's Profits ]
                                       |
        +------------------------------+------------------------------+
        |                                                             |
[ Financial Drivers ]                                      [ External / Strategic Factors ]
        |                                                             |
   +----+----+                                                   +----+----+
   |         |                                                   |         |
[Revenue]  [Costs]                                           [Customers] [Competitors]
   |         |                                                   |         |
   |--Price  |--COGS (Procurement)                               |--Shift   |--Low-cost player
   |--Volume |--OpEx (Logistics, Sales)                          |  needs   |  undercutting
             |--Fixed Costs (Warehouses, Tech)                   |--Loss of |--Service level
                                                                    share      disparity

```

### Key Areas to Explore:

1. **Financial Drivers:**
* **Revenues:** Is the drop due to unit volume decline, average selling price (ASP) erosion, or a shift in segment mix?
* **Costs:** Have fixed costs (e.g., warehousing, technology) increased, or variable costs (COGS, freight, fuel) inflated?


2. **Customer & Market Dynamics:**
* **Customer Needs:** Have customer priorities shifted toward low price over high service?
* **Competitive Pressures:** Are low-cost competitors stealing market share by offering "good enough" service at significantly lower prices?
* **Segment Alignment:** Is Swift over-indexed in product categories that don't value its high-service model?



---

## 2. Exhibit 1: Data Synthesis & Root Cause Analysis

### Quantitative Summary Table

| Metric ($M) | Two Years Ago | Last Year | This Year | 2-Year Trend ($\Delta$) |
| --- | --- | --- | --- | --- |
| **Electronics Revenue** | $45M | $35M | $30M | **-$15M (-33%)** |
| **Household Revenue** | $35M | $30M | $30M | **-$5M (-14%)** |
| **Specialty Revenue** | $30M | $40M | $40M | **+$10M (+33%)** |
| **Total Revenue** | **$110M** | **$105M** | **$100M** | **-$10M (-9%)** |
| **COGS** | $65M | $61M | $58M | -$7M |
| **OpEx** | $15M | $15M | $15M | $0M |
| **Fixed Costs** | $16M | $16M | $17M | +$1M |
| **Total Costs** | **$96M** | **$92M** | **$90M** | **-$6M (-6%)** |
| **Net Profit** | **$14M** | **$13M** | **$10M** | **-$4M (-29%)** |

---

### Core Insights & Root Cause

> **Primary Root Cause:** Strategic Mismatch in the **Electronics** Segment.
> * **Value Proposition Misalignment:** Swift's premium price tag is backed by high service levels. However, in Electronics (the primary source of revenue loss), **Price is a HIGH buying factor**, while **Service is LOW**. Customers are actively switching to cheaper competitors because they do not care about premium delivery/support for electronics.
> * **Under-monetized Opportunity in Specialty:** The Specialty segment values **High Service**, offers **High Profit Margins**, and has a larger order size ($2,000 / 50 units). Swift grew this segment from $30M to $40M, but has only captured a fraction of the $200M market.
> * **Household Segment Stagnation:** Represents a high-margin opportunity ($500M market), but customers are price-sensitive. Swift is losing share or plateauing ($30M) due to premium pricing.
> 
> 

---
![0808-4](https://hackmd.io/_uploads/HJfkv3V8Gg.png)


## 3. Exhibit 2: Quantitative Analysis (Math Step-by-Step)

### Question

*How much additional revenue can Swift expect from the proposed new pricing program in the Household segment?*

### Given Information:

* **Current Household Revenue:** $30M / year
* **Current Volume:** 50,000 units/month = **600,000 units/year**
* **Pricing Change:**
1. **10% price discount** applied to the first **75% of baseline units**.
2. Volume expands by **10%** as a result of the discount.
3. The **10% discount** is offered to only **25% of the newly generated volume**.



---

### Step-by-Step Calculation

#### Step 1: Calculate Current Price per Unit

$$\text{Current Price} = \frac{\$30,000,000}{600,000 \text{ units}} = \$50 / \text{unit}$$

#### Step 2: Calculate New Volume

$$\text{New Volume Increase} = 600,000 \times 10\% = 60,000 \text{ additional units}$$

$$\text{Total New Volume} = 660,000 \text{ units}$$

#### Step 3: Calculate Discounted Price

$$\text{Discounted Price} = \$50 \times (1 - 0.10) = \$45 / \text{unit}$$

#### Step 4: Calculate Revenue Breakdown

| Tiers | Unit Breakdown | Volume | Price/Unit | Segment Revenue |
| --- | --- | --- | --- | --- |
| **Baseline (Discounted)** | 75% of 600,000 units | 450,000 units | $45 | $20,250,000 |
| **Baseline (Full Price)** | 25% of 600,000 units | 150,000 units | $50 | $7,500,000 |
| **New Volume (Discounted)** | 25% of 60,000 units | 15,000 units | $45 | $675,000 |
| **New Volume (Full Price)** | 75% of 60,000 units | 45,000 units | $50 | $2,250,000 |
| **Total Expected Revenue** | — | **660,000 units** | — | **$30,675,000** |

#### Step 5: Incremental Revenue Calculation

$$\text{Incremental Revenue} = \$30,675,000 - \$30,000,000 = +\$675,000 \text{ (or } \mathbf{\$0.675M}\text{)}$$

---

## 4. Final Recommendation & Executive Synthesis

When concluding the case, structure your final pitch using the **McKinsey Answer-First Format**:

### Recommendation

Swift should **re-align its commercial strategy across key segments** to reverse the 3-year profit decline and capture an immediate **$675,000+ top-line lift**:

1. **Protect & Scale Specialty Segment:** Double down on aggressive customer acquisition in Specialty. It offers high profit margins, high order values, and customers genuinely value Swift’s premium service capabilities.
2. **Implement Targeted Tiered Pricing in Household:** Roll out the tiered 10% pricing program to capture price-sensitive demand, yielding an immediate **+$675K revenue expansion**.
3. **Restructure Electronics Strategy:** Either introduce a "No-Frills / Low-Cost" service tier for Electronics to compete on price, or intentionally disinvest from low-margin Electronics accounts to cut operating costs.

### Next Steps & Risk Mitigation

* **Risk:** Discounting in Household could cannibalize full-price purchases if customers figure out how to gamed the 75%/25% split.
* *Mitigation:* Apply the discount strictness via volume-threshold contracts or tiered customer loyalty programs.


* **Immediate Next Step:** Conduct a cost-to-serve audit in the Electronics segment to determine if margin can be saved by stripping away unrewarded premium services.




# Example Frameworks


---

##  3Cs + 1P (Market & Commercial Strategy)

When a business is losing market share, facing price wars, or evaluating market positioning, the **3Cs** framework helps unpack the competitive context.

```
                  [ Commercial Strategy ]
                             |
    +------------------------+------------------------+
    |                        |                        |
[ Customer ]           [ Competitor ]            [ Company ]
  * Segment needs        * Pricing models          * Capabilities & costs
  * Price sensitivity    * Cost structure          * Service differentiators
  * Switching barriers   * Value proposition       * Margin mix per segment

```

* **Customer:** Who buys? Why do they buy? (e.g., Electronics customers care about *Price*; Specialty customers care about *Service*).
* **Competitor:** Who are the low-cost players? How are they undercutting us? What is their cost structure?
* **Company:** What are our unique assets/advantages? Are our cost structures optimized for each segment?



##  5W1H Fits with Consulting Frameworks


* **What:** What is the specific target metric (e.g., return to $14M profit within 2 years)?
* **When:** When did this decline begin (e.g., 3 years ago—was it gradual or sudden)?
* **Where:** Is this happening nationally or in specific regions/product lines?
* **Who:** Who are the primary competitors capturing share? Who is the core customer leaving?
* **Why:** Why are customers switching (price vs. service quality)?
* **How:** How does Swift currently charge and fulfill orders across segments?


# 🎯 Case Study #6 — Stakeholder Prioritization

> **30 Product Case Studies — Case #6**  
> A hypothetical Product Case Study created as part of my Product Management learning journey.

---

## 📌 Overview

A Product team is planning the roadmap for the next quarter.

The team has capacity for **only one major initiative**, but three stakeholders are pushing for different priorities:

- **Sales** wants a Discount Engine.
- **Customer Support** wants improvements to Order Tracking.
- **Engineering** wants to invest in Technical Debt and System Performance.

The challenge is not simply choosing one initiative.

The real Product challenge is:

> **How do we objectively prioritize competing initiatives and align stakeholders around the decision?**

---

# 🧩 The Situation

### 💰 Sales — Discount Engine

Sales believes a new discount engine could:

- Increase sales
- Improve competitiveness
- Enable more flexible promotions
- Potentially increase revenue

### 📦 Customer Support — Order Tracking

Customer Support wants to improve Order Tracking because customers frequently contact Support asking:

> "Where is my order?"

Potential consequences include:

- Higher Support volume
- Increased operational cost
- Customer frustration
- Lower customer satisfaction

### ⚙️ Engineering — Technical Debt & Performance

Engineering wants to spend part of the quarter improving:

- Technical debt
- System performance
- Maintainability
- System reliability

Some services are becoming increasingly difficult to maintain, and performance is beginning to degrade.

---

# 🎯 Product Question

> **Which initiative should we prioritize, and how should we align stakeholders around the decision?**

The team can only commit to **one major initiative**.

---

# 🔎 1. Start With the Problem, Not the Solution

Before choosing an initiative, I would first understand **why each stakeholder considers their request important**.

I would avoid prioritizing based on:

- Seniority
- Who requested it first
- Who is pushing the hardest
- Personal preference

Instead, I would focus on:

**Problem → Impact → Evidence → Urgency → Risk → Effort**

---

# 💰 2. Investigate the Sales Request

For the Discount Engine, I would ask:

### Customer Impact

- Are customers currently struggling to find relevant discounts?
- Are customers abandoning purchases because of pricing?
- Which customer segments are affected?

### Business Impact

- What revenue increase do we expect?
- Could discounts increase conversion?
- Could discounts increase order frequency?
- Are competitors offering capabilities we don't have?

### Evidence

I would ask Sales to provide:

- Historical promotion performance
- Customer demand
- Competitor insights
- Revenue opportunity
- Existing campaign results

The goal is to understand whether the Discount Engine solves a **validated business problem**.

---

# 📦 3. Investigate the Customer Support Request

For Order Tracking, I would investigate:

### Customer Impact

- How many customers contact Support about order status?
- At which stage do customers become uncertain?
- Is the problem affecting all customers or specific segments?

### Operational Impact

- How many Support tickets are generated?
- How much Support capacity is spent answering tracking questions?
- Could better tracking reduce contact volume?

### Customer Metrics

I would examine:

- CSAT
- Support contact rate
- Contact rate per order
- Repeat contacts
- Customer complaints

This would help quantify the cost of the current experience.

---

# ⚙️ 4. Investigate the Engineering Request

I would not treat Technical Debt as automatically lower priority just because it is not a customer-facing feature.

I would ask Engineering to quantify:

### Current Impact

- Is performance already affecting customers?
- Are response times increasing?
- Are error rates increasing?
- Are incidents becoming more frequent?

### Future Risk

- What happens if we postpone the work?
- Could this lead to outages?
- Could it slow down future development?
- Will the technical debt become more expensive to fix later?

### Engineering Impact

I would also understand:

- Development velocity
- Maintenance effort
- Complexity
- Dependencies
- Risk of future releases

---

# ⚠️ Technical Debt ≠ Automatically Low Priority

One important Product distinction is:

> **Technical Debt is not automatically a priority, but Technical Debt that creates significant business risk can become a Product priority.**

For example:

**Technical Debt**

↓

**Performance degradation**

↓

**Poor customer experience**

↓

**Lower conversion / higher abandonment**

↓

**Revenue impact**

In this situation, the technical problem has become a **business problem**.

---

# 📊 5. Prioritization Framework

I would use **RICE** as a structured input:

**RICE = Reach × Impact × Confidence ÷ Effort**

I would evaluate each initiative based on:

| Factor | Question |
|---|---|
| Reach | How many customers/users are affected? |
| Impact | How significant is the expected outcome? |
| Confidence | How strong is our evidence? |
| Effort | How much time and capacity are required? |

However, I would **not rely on RICE alone**.

Some risks, especially reliability or performance risks, may not be fully captured by a simple prioritization score.

---

# 🚨 6. The Question That Can Change the Priority

For every initiative, I would ask:

> **"What happens if we DON'T do this next quarter?"**

### Discount Engine

Potential consequences:

- Lost revenue opportunity
- Competitive disadvantage
- Missed promotional opportunities

### Order Tracking

Potential consequences:

- Continued Support volume
- Higher operational cost
- Customer frustration
- Potential impact on satisfaction and retention

### Technical Debt

Potential consequences:

- Performance degradation
- Reliability issues
- Future incidents
- Slower development
- Increasing maintenance cost

This helps reveal the **cost of inaction**.

---

# ⚖️ 7. Compare the Initiatives

I would create a prioritization view such as:

| Initiative | Customer Impact | Business Impact | Risk | Confidence | Effort | Cost of Delay |
|---|---|---|---|---|---|---|
| Discount Engine | TBD | TBD | TBD | TBD | TBD | TBD |
| Order Tracking | TBD | TBD | TBD | TBD | TBD | TBD |
| Technical Debt | TBD | TBD | TBD | TBD | TBD | TBD |

I intentionally would not assign arbitrary scores without evidence.

The numbers should come from:

- Product Analytics
- Customer feedback
- Support data
- Sales data
- Engineering analysis
- Business goals

---

# 🧠 8. Product Decision

I would **not automatically choose one initiative before gathering the evidence**.

The decision would depend on the findings.

### Scenario A — Technical Risk Is Critical

If Engineering shows that performance degradation creates a serious risk of:

- Outages
- Major customer impact
- Revenue loss
- Significant delivery delays

Then I would prioritize **Technical Debt & Performance**.

The rationale would be:

> **We're protecting the reliability of the product and reducing a material business risk.**

---

### Scenario B — Customer Support Problem Has the Highest Impact

If the data shows that Order Tracking generates a large volume of contacts and significantly affects customer satisfaction and operational cost, then **Order Tracking** could become the highest-value initiative.

---

### Scenario C — Strong Revenue Opportunity

If Sales can demonstrate strong evidence that the Discount Engine could generate significant incremental revenue with reasonable effort and confidence, it could become the priority.

---

# 🤝 9. Stakeholder Alignment

Once the decision is made, I would not communicate it as:

> "Engineering won."

or:

> "Sales lost."

Instead, I would frame it around the **business objective and evidence**.

For example:

> **"Based on the available data, expected customer and business impact, technical risk, confidence, and engineering effort, we believe Initiative X provides the highest expected value for the next quarter."**

Then I would explain:

### What we're prioritizing

The initiative and expected outcome.

### Why

The evidence supporting the decision.

### What we're not prioritizing

The alternatives and why they are lower priority **right now**.

### When we'll revisit

The conditions or data that could change the decision.

---

# 🗣️ 10. Handling Disagreement

Stakeholder disagreement is expected.

My role would not be to make everyone agree with the decision emotionally.

My role is to make the **decision-making process transparent and evidence-based**.

If a stakeholder disagrees, I would:

1. Listen to their concerns.
2. Ask what evidence supports their position.
3. Revisit assumptions.
4. Compare the opportunity against the same criteria.
5. Make the trade-off explicit.
6. Document the decision.
7. Define when the decision should be revisited.

The goal is:

> **Alignment on the decision-making process, even if everyone doesn't agree with the outcome.**

---

# 🔄 Product Prioritization Framework

**Stakeholder Requests**

↓

**Understand the Underlying Problems**

↓

**Collect Evidence**

↓

**Quantify Customer & Business Impact**

↓

**Assess Urgency & Risk**

↓

**Estimate Effort**

↓

**Evaluate Cost of Inaction**

↓

**Compare Opportunities**

↓

**Prioritize**

↓

**Communicate Trade-offs**

↓

**Measure Outcomes**

---

# 📈 11. Success Metrics

The success metrics would depend on the initiative selected.

### 💰 Discount Engine

Potential metrics:

- Conversion Rate
- Average Order Frequency
- Incremental Revenue
- Promotion Adoption
- Customer Retention

### 📦 Order Tracking

Potential metrics:

- Support Contact Rate
- Tracking-related Tickets
- CSAT
- Repeat Contacts
- Self-service Tracking Rate

### ⚙️ Technical Debt & Performance

Potential metrics:

- Page / API Response Time
- Error Rate
- Incident Frequency
- System Availability
- Development Cycle Time

The metrics should be connected to the **outcome**, not simply activity.

---

# 💡 Key Product Insights

### 1. Prioritization is about trade-offs.

When capacity is limited, choosing one initiative means consciously delaying another.

---

### 2. Stakeholder requests are inputs, not priorities.

Sales, Support, and Engineering each provide valuable perspectives.

The Product Owner's role is to bring these perspectives together and evaluate them objectively.

---

### 3. Technical work can create business value.

Technical Debt becomes a Product concern when it affects:

- Reliability
- Performance
- Customer experience
- Delivery speed
- Business continuity

---

### 4. RICE is a tool, not the decision-maker.

Frameworks help structure thinking, but Product judgment is still required.

---

### 5. Cost of inaction matters.

A good prioritization discussion should consider not only:

> **"What do we gain if we build this?"**

but also:

> **"What do we risk by not building it?"**

---

### 6. Stakeholder alignment doesn't mean everyone gets what they want.

Good alignment means stakeholders understand:

- What was decided
- Why it was decided
- What trade-offs were made
- What could change the decision

---

# 🧩 Skills Practiced

- Product Prioritization
- RICE Framework
- Stakeholder Management
- Stakeholder Alignment
- Business Impact Analysis
- Customer Impact Analysis
- Technical Risk Assessment
- Opportunity Cost
- Cost of Delay
- Trade-off Analysis
- Product Strategy
- Cross-functional Collaboration
- Product Communication

---

# 📚 About This Series

This is **Case Study #6 of 30 hypothetical Product Case Studies** I'm working through as part of my Product Management learning journey.

The goal of this series is to turn Product theory into practical problem-solving and strengthen my ability to approach realistic and ambiguous Product problems.

### Areas Covered Throughout the Series

- Product Thinking
- Product Analytics
- Discovery & UX
- Prioritization
- Technical Product Management
- Agile Product Delivery
- AI Product Management

**30 cases. 30 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, stakeholder requests, business context, and technical constraints are fictional and are not presented as real company data or confidential work experience.

# Case Study 10 — Product Prioritization Under Limited Engineering Capacity

## 📌 Overview

This hypothetical Product Management case study focuses on **prioritization, product strategy, stakeholder management, and trade-offs** when multiple teams request high-priority initiatives but Engineering capacity is limited.

The Product Owner must decide which initiatives should be delivered now, which should be postponed, and which require further validation.

---

## 🎯 Business Context

I am the Product Owner of an e-commerce platform.

For the upcoming quarter, the Engineering team has enough capacity to deliver only **3 initiatives**, while different stakeholders are requesting 5 initiatives.

The challenge is to maximize customer and business value while considering:

- Customer impact
- Business impact
- Available evidence
- Urgency
- Engineering effort
- Technical risks
- Strategic alignment
- Consequences of delaying an initiative

---

## 📋 Initiatives

| Initiative | Team | Expected Impact | Effort | Key Consideration |
|---|---|---|---|---|
| Checkout Optimization | Growth | High | 6 weeks | Current checkout abandonment is high |
| Customer Loyalty Program | Marketing | Medium–High | 8 weeks | Could increase repeat purchases and retention |
| Technical Debt & Performance | Engineering | Medium now / High long-term | 5 weeks | Ignoring it increases technical and delivery risk |
| New Payment Method | Commercial | Unknown | 7 weeks | Competitor launched it, but demand is unvalidated |
| AI Product Recommendations | Leadership | Unknown / Potentially High | 10 weeks | Strategic opportunity but requires validation |

---

# 🔎 Step 1 — Understand the Context Before Prioritizing

Before applying a prioritization framework, I would gather additional information from each stakeholder.

### Key questions

**Customer**
- What customer problem does this initiative solve?
- How many customers are affected?
- How significant is the problem?

**Business**
- What business outcome are we expecting?
- Is there evidence supporting the expected impact?
- How does it contribute to company goals?

**Urgency**
- Why does this need to happen now?
- What happens if we delay it by one quarter?

**Risk**
- What happens if we don't build it?
- Are there technical, operational, financial, or customer risks?

**Engineering**
- What are the dependencies?
- Can we reduce scope?
- Is there an MVP that can deliver value faster?

This helps avoid prioritizing initiatives simply because a stakeholder considers them "urgent."

---

# 📊 Step 2 — Prioritization Approach

After gathering the required information, I would use **RICE prioritization** to make the trade-offs more explicit.

The framework helps compare initiatives based on:

- Reach
- Impact
- Confidence
- Effort

However, the framework would not replace Product judgment.

I would also consider strategic alignment, technical risk, dependencies, and the consequences of delaying an initiative.

---

# ⚙️ Step 3 — Prioritization Decision

## 🥇 1. Technical Debt & Performance

### Why?

Although technical debt does not necessarily generate immediate revenue, ignoring it can create significant long-term risks.

Potential consequences include:

- Slower future development
- Increasing API latency
- Higher system instability
- More engineering effort required later
- Increased risk when launching new features

The initiative requires 5 weeks, which is also lower than several other initiatives.

### Product decision

**Prioritize it.**

I would also discuss with Engineering whether the scope can be reduced or whether an MVP can address the highest-risk areas first.

---

# 🥈 2. Checkout Optimization

### Why?

This initiative has strong evidence supporting its potential impact.

- Checkout abandonment is already high
- Expected conversion uplift: **8–12%**
- High customer impact
- High business impact
- Engineering effort: 6 weeks

The initiative directly addresses an existing customer problem and has a clear connection to revenue.

### Product decision

**Prioritize it.**

---

# 🥉 3. Customer Loyalty Program

### Why?

The Loyalty Program has a clear business objective:

- Increase repeat purchases
- Improve retention
- Strengthen customer engagement

Marketing also has supporting data and a clear campaign-related timeline.

### Product decision

**Prioritize it**, assuming the expected impact is supported by the available evidence.

---

# ⏸️ 4. New Payment Method

I would **not prioritize the initiative immediately**.

The main argument from Commercial is:

> A competitor has launched the payment method.

However, competitor behavior alone is not enough evidence to justify spending 7 weeks of engineering capacity.

### Evidence I would request

- Customer demand
- Number of customers requesting the payment method
- Impact on checkout conversion
- Payment failure data
- Customer segments affected
- Competitor analysis
- Expected revenue impact

I would reconsider the initiative if strong evidence demonstrates meaningful customer and business value.

---

# 🔬 5. AI Product Recommendations

I would not immediately commit the full **10-week engineering effort**.

The initiative has potentially high strategic value, but the current evidence is insufficient.

Instead, I would move it into **Discovery**.

### Possible validation methods

- Fake-door experiment
- Prototype testing
- Customer interviews
- Usability testing
- Existing behavioral data analysis
- Small-scale experiment

If the validation demonstrates strong demand and measurable business impact, the initiative can be reconsidered for prioritization.

---

# 🤝 Stakeholder Management

If the final decision is:

✅ Checkout Optimization  
✅ Technical Debt & Performance  
✅ Customer Loyalty Program  

and:

⏸️ New Payment Method  
⏸️ AI Product Recommendations  

I would communicate the decision transparently.

I would explain:

1. Why the selected initiatives were prioritized
2. What evidence supports the decision
3. What we are giving up by not selecting the other initiatives
4. What evidence would change the decision
5. When we will revisit the postponed initiatives

The goal is not to tell stakeholders that their initiatives are unimportant.

The goal is to explain **why they are not the highest priority right now**.

---

# 🚧 Handling the "Build All Five" Request

If Leadership says:

> "We need all five. Ask Engineering to work harder."

I would bring the conversation back to constraints and trade-offs.

Engineering capacity is a real constraint.

Instead of simply asking Engineering to increase workload, I would discuss:

- Scope reduction
- MVPs
- Sequencing
- Dependencies
- Risk
- Timeline changes
- Additional resources, if available

A Product Owner should make the trade-offs visible rather than hiding the capacity constraint.

---

# 📈 Success Metrics

Each initiative should have its own metric hierarchy.

### Checkout Optimization

**Primary**
- Checkout conversion rate

**Secondary**
- Completed orders
- Revenue per user
- Average Order Value

**Guardrails**
- Payment failure rate
- Support contact rate
- Refunds
- Checkout-related complaints

---

### Customer Loyalty Program

**Primary**
- Repeat purchase rate

**Secondary**
- Customer retention
- Revenue per customer
- Loyalty program engagement

**Guardrails**
- Discount cost
- Profit margin
- Customer complaints

---

### Technical Debt & Performance

**Primary**
- API latency / response time

**Secondary**
- System reliability
- Incident rate
- Deployment frequency
- Engineering cycle time

**Guardrails**
- Feature delivery capacity
- Production incidents
- Engineering effort

---

# 🧠 Product Framework

The decision-making process used:

```text
Understand the problem
        ↓
Gather evidence
        ↓
Assess customer & business impact
        ↓
Evaluate urgency & risk
        ↓
Understand engineering constraints
        ↓
Explore MVP / scope reduction
        ↓
Apply prioritization framework
        ↓
Make trade-offs
        ↓
Communicate the decision
        ↓
Measure outcomes

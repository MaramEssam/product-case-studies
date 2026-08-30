# 🛒 Case Study #7 — Should We Build a Wishlist?

> **30 Product Case Studies — Case #7**  
> A hypothetical Product Case Study created as part of my Product Management learning journey.

---

## 📌 Overview

The Commercial team of an e-commerce marketplace urgently requests a new **Wishlist** feature.

Their argument is simple:

> "Customers want it, and our competitors already have it."

However, Product has limited Engineering capacity, and another initiative is already expected to improve checkout conversion.

The challenge is to determine whether Wishlist is actually the right problem to solve — and whether it should be prioritized now.

---

# 🚨 The Situation

The marketplace currently has the following signals:

| Signal | Current Situation |
|---|---|
| Cart Abandonment | **35%** of customers add products but don't purchase |
| Repeat Product Visits | **12%** return to the same product within 30 days |
| Customer Feedback | Some users want a way to save products for later |
| Competitive Landscape | Competitors offer Wishlist functionality |
| Engineering Estimate | **8 weeks** for a full Wishlist experience |
| Existing Initiative | Checkout conversion improvement already in progress |
| Business Timing | Commercial wants Wishlist before the next major sales campaign |

---

# 🎯 The Product Question

> **Should we build the Wishlist now?**

More importantly:

> **What customer problem are we actually trying to solve?**

---

# 🔎 1. Start With the Problem

I would not immediately translate the request into:

**"Build Wishlist."**

Instead, I would investigate the underlying customer need.

A possible customer problem could be:

> **"I found a product I like, but I'm not ready to purchase it now and want an easy way to find it later."**

This is different from simply saying:

> "Customers want Wishlist."

The feature is a proposed solution.

The problem still needs to be validated.

---

# 💡 2. Initial Hypothesis

One hypothesis is:

> **Some customers may be using the shopping cart as a temporary "save for later" mechanism because they don't have another way to save products.**

The 35% cart abandonment rate makes this hypothesis worth investigating.

However, I would **not assume that all abandoned carts represent Wishlist demand**.

Customers may abandon carts for many other reasons:

- High shipping costs
- Unexpected fees
- Payment problems
- Price comparison
- Lack of urgency
- Delivery concerns
- Product availability
- Changed purchase intent

Therefore, cart abandonment alone does not prove that Wishlist is the solution.

---

# 📊 3. Analyze Customer Behavior

I would investigate the behavior of customers who add products to their cart but don't purchase.

### Questions I Would Ask

- Do they return to the same product later?
- Do they eventually purchase it?
- How long after adding the product do they return?
- Do they repeatedly add and remove the same products?
- Do they visit the same product multiple times?
- Do they add multiple products but purchase only one?
- Are they comparing prices?
- Are they waiting for promotions?

---

# 🔄 4. Analyze the Customer Journey

I would map the journey:

**Product Discovery**

↓

**Product View**

↓

**Add to Cart**

↓

**Checkout**

↓

**Purchase**

↓

**Repeat Purchase**

Then I would investigate where customers behave differently from our expected journey.

For example:

### Scenario A

Customer adds product → leaves → returns later → purchases

This could indicate a potential **save-for-later need**.

### Scenario B

Customer adds product → sees shipping cost → leaves

Wishlist would probably **not solve the problem**.

### Scenario C

Customer adds product → payment fails → leaves

Again, Wishlist is not the root solution.

---

# 👥 5. Segment the Customers

I would segment users to understand where the potential Wishlist need is strongest.

### Customer Behavior

- New vs. returning customers
- Frequent vs. occasional buyers
- High-value vs. casual customers
- Users with multiple product views

### Purchase Behavior

- Number of orders
- Average purchase frequency
- Time between purchases
- Previous saved/abandoned products

### Product Behavior

- Product category
- Price range
- Product availability
- High-consideration vs. low-consideration products

The goal is to identify:

> **Who actually has a save-for-later problem?**

---

# 💬 6. Validate Customer Demand

I would combine quantitative and qualitative research.

### Customer Feedback

Review:

- Customer Support tickets
- Surveys
- Customer interviews
- Existing feedback

I would specifically look for evidence that customers are trying to:

- Save products
- Find products again later
- Compare products before purchasing
- Wait for a better price
- Track product availability

---

# 🧪 7. Validate Before Building

The full Wishlist experience is estimated to take **8 weeks**.

Before committing that amount of Engineering capacity, I would run a controlled demand-validation experiment.

### Possible Experiment

Introduce a clearly labeled **"Save for later"** or favorite action in a limited experience.

Then measure:

**Eligible Users → See Save Option → Click → Save Product → Return → Purchase**

The purpose is not to pretend the complete feature already exists.

The purpose is to measure **actual customer intent and behavior** before investing in the full solution.

---

# ⚙️ 8. Explore an MVP

If the validation shows meaningful demand, I would work with Engineering to define the smallest useful version.

### MVP

A simple Wishlist could include:

- Save a product
- View saved products
- Remove a saved product

That's enough to validate the core value proposition.

### Potential Future Features

I would consider these later:

- Price-drop notifications
- Back-in-stock notifications
- Wishlist sharing
- Multiple collections
- Personalized recommendations

I would avoid adding these before validating the core use case.

---

# 🧩 9. Understand the 8-Week Estimate

I wouldn't simply ask Engineering to "build it faster."

I would ask:

> **"What specifically makes the full Wishlist experience an 8-week project?"**

I would understand:

- Frontend effort
- Backend changes
- Data storage
- Product/user relationships
- Analytics
- Notifications
- Performance requirements
- Testing
- Dependencies

Then I would explore whether reducing scope can significantly reduce effort.

---

# ⚖️ 10. Compare Wishlist With the Existing Initiative

Engineering is already working on an initiative expected to improve checkout conversion.

Therefore, Wishlist needs to compete for limited capacity.

I would compare both opportunities using:

| Factor | Wishlist | Checkout Initiative |
|---|---|---|
| Customer Impact | TBD | TBD |
| Business Impact | TBD | TBD |
| Reach | TBD | TBD |
| Confidence | TBD | TBD |
| Engineering Effort | 8 weeks full scope | TBD |
| Urgency | Sales campaign | TBD |
| Opportunity Cost | TBD | TBD |

I would not invent scores without evidence.

The purpose of the framework is to make the trade-off explicit.

---

# 📊 11. Prioritization Framework

I would use a framework such as **RICE**:

**Reach × Impact × Confidence ÷ Effort**

But I would combine the score with Product judgment.

I would also consider:

- Strategic alignment
- Customer problem severity
- Business impact
- Technical dependencies
- Cost of delay
- Opportunity cost

The highest RICE score does not automatically mean:

> **"Build this immediately."**

It is one input into the decision.

---

# 🏆 12. Competitive Pressure

The Commercial team argues:

> **"Our competitors already have Wishlist, so we need it."**

I would treat this as useful competitive context, but not as sufficient evidence.

The right question is:

> **"Does the absence of Wishlist create a meaningful disadvantage for our customers or business?"**

Competitive parity may matter.

However:

**Competitor has feature ≠ We must build feature.**

We should understand:

- Why competitors built it
- Whether their customers use it
- Whether it solves a problem for our customers
- Whether it creates measurable business value

---

# 🎯 13. Decision Logic

I would make the decision based on evidence.

### Scenario A — Weak Demand

If:

- Few users interact with the save capability
- Customers rarely return to saved products
- No meaningful customer pain is identified
- Expected business impact is low

**Decision:**

Deprioritize Wishlist and focus on higher-value opportunities.

---

### Scenario B — Strong Demand

If:

- Customers repeatedly show save-for-later behavior
- The feature receives strong engagement
- Customers return to saved products
- Saved products lead to meaningful purchases
- The expected impact is higher than competing initiatives

**Decision:**

Prioritize a focused MVP.

---

### Scenario C — Strong Demand but High Effort

If customer demand is strong but the full implementation requires significant effort:

**Decision:**

Look for a smaller MVP that validates the core use case before committing to the complete experience.

---

# 📈 14. Success Metrics

If Wishlist is launched, I would define success around **customer behavior and business outcomes**, not simply feature usage.

## Primary Metric

### Wishlist Adoption Rate

> Percentage of eligible users who save at least one product.

---

## Engagement Metrics

- Products saved per user
- Return-to-Wishlist Rate
- Saved Product View Rate
- Save → Purchase Conversion
- Time between Save and Purchase

---

## Business Metrics

- Conversion Rate
- Repeat Purchase Rate
- Orders per Customer
- Revenue per Customer
- Incremental Revenue from Saved Products

---

## Guardrail Metrics

I would monitor:

- Cart abandonment
- Checkout conversion
- Overall purchase conversion
- Page performance
- Customer Support contacts

---

# 🔄 Product Thinking Framework

**Feature Request**

↓

**Understand the Customer Problem**

↓

**Form Hypotheses**

↓

**Analyze Existing Behavior**

↓

**Segment Users**

↓

**Validate Demand**

↓

**Test the Smallest Viable Solution**

↓

**Estimate Business Impact**

↓

**Compare Alternatives**

↓

**Prioritize**

↓

**Measure Outcomes**

---

# 🧠 Key Product Insights

### 1. Don't confuse the solution with the problem.

"Build a Wishlist" is a solution request.

The underlying problem might be:

> **"I want to save something because I'm not ready to buy it yet."**

---

### 2. Cart abandonment doesn't automatically mean Wishlist demand.

Customers abandon carts for many reasons.

The root cause must be investigated before selecting the solution.

---

### 3. Validate before committing 8 weeks.

A lightweight experiment can help determine whether there is enough customer demand to justify a larger investment.

---

### 4. Competitor features are context, not automatic priorities.

Competitive parity can influence prioritization, but it should be combined with customer and business evidence.

---

### 5. MVPs reduce uncertainty.

If the core assumption can be tested with a smaller experience, there's no reason to start with the full feature set.

---

### 6. Feature adoption isn't the final outcome.

A Wishlist with high usage isn't necessarily successful if it doesn't improve customer or business outcomes.

The ultimate question is:

> **Does the feature create meaningful value?**

---

# 🧩 Skills Practiced

- Product Discovery
- Customer Problem Discovery
- Hypothesis Generation
- Customer Segmentation
- Product Analytics
- Funnel Analysis
- Feature Validation
- Experimentation
- MVP Definition
- Product Prioritization
- RICE
- Competitive Analysis
- Opportunity Cost
- Business Impact Analysis
- Product Metrics
- Customer-Centric Product Thinking

---

# 📚 About This Series

This is **Case Study #7 of 30 hypothetical Product Case Studies** I'm working through as part of my Product Management learning journey.

The goal of this series is to turn Product theory into practical problem-solving and strengthen my ability to approach realistic and ambiguous Product problems.

### Areas Covered Throughout the Series

- Product Thinking
- Product Analytics
- Discovery & UX
- Prioritization
- Technical Product Management
- Agile Product Delivery
- AI Product Management

**7 cases. 7 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, metrics, customer feedback, business context, and engineering estimates are fictional and are not presented as real company data or confidential work experience.

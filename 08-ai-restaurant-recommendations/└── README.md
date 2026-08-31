# 📊 Case Study #8 — When Engagement Goes Up but Business Impact Doesn't

> **30 Product Case Studies — Case #8**
>
> A hypothetical Product Case Study created as part of my Product Management learning journey.

---

## 📌 Overview

A food delivery app recently launched an **AI-powered restaurant recommendation feature** designed to help customers discover relevant restaurants faster and ultimately increase orders.

After six weeks, the Product team reports a **40% increase in engagement** and considers the feature a success.

However, a deeper look at the data tells a different story.

The challenge is to understand whether the feature is actually creating customer and business value — and determine what should happen next.

---

# 🚨 The Situation

The feature was designed to:

1. Help customers discover relevant restaurants faster.
2. Increase restaurant engagement.
3. Increase completed orders.
4. Ultimately contribute to business growth.

After six weeks, the following results were observed:

| Metric | Result |
|---|---:|
| Recommendation Views | **+40%** |
| Recommendation CTR | **+18%** |
| Add-to-Cart Rate | **Almost unchanged** |
| Completed Orders | **+2%** |
| Average Order Value | **-4%** |
| Customer Retention | **Unchanged** |
| Feature Exposure | **80% of active users** |
| Customer Feedback | Complaints about irrelevant recommendations |

At first glance, the engagement numbers look impressive.

But engagement alone does not prove that the feature is successful.

---

# 🎯 Product Question

The Head of Product asks:

> **"Engagement increased by 40%. Should we invest more Engineering capacity into this feature?"**

My initial answer would be:

> **Not yet.**

Before investing further, I would want to understand whether the increase in engagement is translating into the intended customer and business outcomes.

---

# 🔎 1. Start With the Intended Outcome

The first question I would ask is:

> **What was this feature actually expected to achieve?**

If the primary objective is to increase completed orders through better restaurant discovery, then recommendation views and clicks are **leading indicators**, not the final outcome.

For example:

A customer can:

**See recommendation → Click recommendation → Browse restaurant → Leave**

This creates engagement, but not necessarily business value.

Therefore, I would focus on the relationship between recommendation engagement and actual purchasing behavior.

---

# 📊 2. Analyze the Funnel

I would build a funnel to identify where the customer journey is breaking down.

### Recommendation Funnel

**Recommendation Impression**

↓

**Recommendation Click**

↓

**Restaurant View**

↓

**Add to Cart**

↓

**Checkout**

↓

**Completed Order**

---

## 🔍 Questions at Each Stage

### 1. Impression → Click

We already know CTR increased by 18%.

I would investigate:

- Which recommendations are receiving clicks?
- Which customer segments are clicking?
- Are users clicking because the recommendations are relevant?
- Are some recommendations generating unusually high clicks?

---

### 2. Click → Restaurant View

I would check whether users successfully reach the restaurant page.

Potential issues:

- Slow loading
- Technical errors
- Broken links
- Poor mobile experience
- API failures

---

### 3. Restaurant View → Add to Cart

This is an important point of investigation because Add-to-Cart remained almost unchanged.

Possible explanations:

- Recommendations are not relevant.
- Restaurant prices are too high.
- Delivery fees discourage customers.
- Restaurant ratings are poor.
- Menu availability is limited.
- Customers were curious but had no purchase intent.

---

### 4. Add to Cart → Checkout

I would investigate whether customers encounter:

- Unexpected fees
- Delivery restrictions
- Availability issues
- UX problems
- Login issues
- Address problems

---

### 5. Checkout → Completed Order

I would investigate:

- Payment failures
- Technical errors
- Delivery fees
- Customer drop-off
- Checkout friction
- Restaurant availability

The goal is to determine whether the problem is actually related to recommendations or occurs later in the journey.

---

# 🧠 3. Key Hypotheses

I would avoid jumping directly to a solution.

Instead, I would create several hypotheses and validate them using data.

---

## Hypothesis 1 — Recommendations are not relevant enough

Customers may be clicking recommendations because they look interesting, but the recommended restaurants may not match their actual preferences.

### Evidence to investigate:

- Click-to-order conversion
- Customer feedback
- Cuisine preferences
- Previous order history
- Recommendation relevance

---

## Hypothesis 2 — Engagement is increasing without purchase intent

The feature may be encouraging customers to browse more restaurants without actually increasing their intention to order.

This would explain why:

**Views ↑ 40%**

while:

**Completed Orders ↑ only 2%**

---

## Hypothesis 3 — There is a conversion problem after the recommendation

The recommendation itself may work well.

The problem could occur after the user clicks.

For example:

**Recommendation → Click → Restaurant → Add to Cart**

If the largest drop occurs between Restaurant View and Add to Cart, the problem may be related to restaurant selection, pricing, delivery fees, or product experience.

---

## Hypothesis 4 — Technical or UX issues

A technical or usability issue could prevent users from completing their journey.

Potential problems:

- Slow loading
- Broken recommendation links
- Poor mobile UI
- Missing CTA
- API issues
- Checkout errors

---

## Hypothesis 5 — Recommendation quality varies by customer segment

The algorithm may work well for some users but poorly for others.

For example:

- New users may receive generic recommendations.
- Returning users may receive better personalized recommendations.
- Certain cities may have limited restaurant coverage.
- Certain devices may experience technical issues.

---

# 👥 4. Customer Segmentation

I would segment the data to understand whether the issue is concentrated within a specific group.

### Customer Type

- New vs. returning users
- Frequent vs. occasional customers
- High-frequency vs. low-frequency users

### Geography

- Country
- City
- Delivery area

### Device

- iOS
- Android
- Web

### Behavior

- Previous orders
- Cuisine preferences
- Average order frequency
- Previous interactions with recommendations

### Restaurant

- Cuisine
- Rating
- Price range
- Availability
- Delivery time

The goal is to answer:

> **"Is the feature underperforming for everyone, or only for specific segments?"**

---

# 💬 5. Customer Feedback

Customer Support has already received complaints about irrelevant recommendations.

I would investigate these complaints rather than treating them as isolated comments.

I would analyze:

- Support tickets
- Surveys
- Customer interviews
- Feedback associated with recommendation interactions

I would look for patterns such as:

> "I don't usually order this type of food."

> "These restaurants are too expensive."

> "The recommendations don't match my previous orders."

This qualitative evidence can then be combined with behavioral data.

---

# 🤖 6. AI Recommendation Quality

Because this is an AI-powered recommendation experience, I would also evaluate recommendation quality.

Potential metrics include:

### Recommendation Relevance

> How often do users interact positively with recommendations that match their preferences?

### Personalization Quality

> Are recommendations aligned with previous customer behavior?

### Recommendation-to-Order Conversion

> What percentage of recommendation interactions ultimately result in an order?

If the system uses generative AI components, I would also investigate whether there are cases of incorrect or unsupported outputs.

However, I would distinguish this from standard recommendation relevance:

> **Not every irrelevant recommendation is necessarily an AI hallucination.**

---

# 🧪 7. Experimentation

Once the root cause is identified, I would avoid changing multiple things at once.

I would design controlled experiments around the strongest hypothesis.

### Experiment A — Better Personalization

Compare:

**Current recommendation logic**

vs.

**Personalized recommendations based on customer behavior**

---

### Experiment B — Different Ranking Algorithm

Test whether changing the ranking logic improves:

- Recommendation relevance
- Add-to-cart
- Orders

---

### Experiment C — Recommendation Placement

Test different placements:

- Homepage
- Search results
- Restaurant page
- Post-order experience

---

### Experiment D — Fewer but More Relevant Recommendations

Instead of showing many options, test whether showing fewer highly relevant restaurants improves conversion.

---

### Experiment E — Category-Based Recommendations

For example:

**"Because you ordered Italian food recently..."**

or:

**"Popular restaurants near you"**

This could help users understand why a restaurant was recommended.

---

# 🎯 8. Define Success Metrics

I would separate the metrics into three categories.

---

## Primary Metric

### 🎯 Recommendation-to-Order Conversion Rate

The percentage of users who interact with recommendations and subsequently complete an order.

This is closer to the intended business outcome than simply measuring clicks or impressions.

---

## Secondary Metrics

- Recommendation CTR
- Restaurant View → Add-to-Cart Rate
- Add-to-Cart → Checkout Rate
- Checkout → Order Conversion
- Completed Orders
- Average Order Value
- Repeat Purchase Rate

---

## Guardrail Metrics

I would monitor:

- Customer retention
- Customer complaints
- Cancellation rate
- Recommendation relevance
- App performance
- Checkout conversion

This prevents us from improving one metric while damaging another important part of the customer experience.

---

# 📈 9. North Star Metric

For this specific feature, I would avoid using:

> **Average Order Value**

as the North Star Metric.

AOV is important, but it does not directly measure whether the recommendation experience is helping customers discover and purchase relevant restaurants.

A more meaningful feature-level metric would be:

> **Recommendation-to-Order Conversion Rate**

or:

> **Completed Orders Attributed to Recommendations**

The exact metric would depend on the product's overall strategy and how attribution is defined.

---

# ⚖️ 10. Should We Invest More Engineering Capacity?

I would **not automatically approve additional investment** based only on the 40% engagement increase.

First, I would determine:

1. Why engagement increased.
2. Why Add-to-Cart remained flat.
3. Why completed orders increased by only 2%.
4. Why AOV decreased by 4%.
5. Whether recommendation relevance is actually the root problem.
6. Which customer segments are affected.
7. Whether the feature creates incremental business value.

---

# 🏆 Decision Framework

### If the data shows:

**High engagement + high relevance + increasing orders**

→ Continue investing and scale the feature.

---

### If the data shows:

**High engagement + low relevance + weak conversion**

→ Improve recommendation quality before scaling.

---

### If the data shows:

**High engagement + strong recommendation performance + conversion problem later in the funnel**

→ Focus Engineering capacity on the actual conversion bottleneck instead.

---

### If the feature creates:

**Engagement without meaningful customer or business impact**

→ Reconsider the feature's scope or investment.

---

# 🧠 Product Thinking

The biggest lesson from this case is:

> **A metric going up doesn't automatically mean the Product is succeeding.**

A Product Manager should continuously connect:

**Feature**

↓

**Customer Behavior**

↓

**Product Outcome**

↓

**Business Value**

---

# 💡 Key Takeaways

### 1. Don't confuse engagement with value.

A 40% increase in engagement sounds impressive, but it needs to translate into meaningful outcomes.

### 2. Follow the funnel.

If users click but don't purchase, the problem may exist anywhere between discovery and checkout.

### 3. Use data to validate hypotheses.

Don't assume irrelevant recommendations are the root cause simply because customers complained about them.

### 4. Segment before making decisions.

A feature may perform well overall while failing for a specific customer segment.

### 5. Choose metrics that reflect the product goal.

The primary metric should be connected to the outcome we're trying to achieve.

### 6. Optimize outcomes, not vanity metrics.

More clicks are useful only if they contribute to meaningful customer and business value.

---

# 🛠️ Product Skills Practiced

- Product Metrics
- North Star Metric
- Funnel Analysis
- Product Analytics
- Hypothesis Development
- Customer Segmentation
- Customer Discovery
- Experimentation
- A/B Testing
- AI Product Thinking
- Recommendation Systems
- Conversion Optimization
- Business Impact Analysis
- Data-Driven Decision Making
- Customer-Centric Product Management

---

# 📚 About This Series

This is **Case Study #8 of 30 hypothetical Product Case Studies** from my Product Management learning journey.

The purpose of this series is to practice applying Product Management concepts to realistic scenarios and strengthen my ability to approach ambiguous Product problems.

### Progress

**8 / 30 Cases Completed 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, metrics, customer feedback, and business context are fictional and are not based on confidential company data.

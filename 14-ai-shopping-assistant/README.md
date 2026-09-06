Case Study 14 — AI Shopping Assistant
AI Product Management, Customer Trust & Product Quality
📌 Case Overview

Industry: E-commerce
Role: Product Owner
Product: AI-powered Shopping Assistant
Focus Areas: AI Product Management · Product Analytics · Customer Experience · AI Quality · Experimentation · Trust & Safety · Stakeholder Management

🧩 The Challenge

An e-commerce platform recently launched an AI-powered Shopping Assistant.

The assistant allows customers to search for products using natural language instead of traditional keyword-based search.

For example, instead of searching:

"black running shoes size 39"

a customer could ask:

"I need comfortable black running shoes for daily walking, under $80."

The AI then recommends relevant products and explains why they might be suitable.

The feature has been live for 8 weeks.

At first glance, the results look positive because engagement has increased significantly.

However, deeper analysis reveals several concerns around:

Customer conversion
Retention
Support volume
AI accuracy
Customer trust
Product-data quality

The Product Owner needs to answer:

Should we scale the AI Shopping Assistant, improve it first, or pause it?

📊 Current Performance
Metric	Before Launch	After Launch
AI Assistant Usage	—	32%
Recommendation CTR	—	48%
Product Page Visits	—	+25%
Add-to-Cart Rate	18%	21%
Checkout Initiation	12%	13%
Completed Orders	9%	9.5%
AOV	$42	$44
30-Day Retention	34%	31%
Support Contacts	—	+22%
AI Response Satisfaction	—	68%
Inaccurate / Misleading AI Responses	—	7%
🚨 Initial Observation

The first impression is positive:

AI usage is relatively strong.
Recommendation CTR is strong.
Product page visits increased.
Add-to-cart increased.
AOV increased.

However, these engagement metrics are not translating into a meaningful increase in completed purchases.

At the same time:

Retention declined.
Support contacts increased significantly.
AI responses have a measurable accuracy problem.
Customers may be receiving incorrect product information.

This means I would not consider the feature a full success yet.

Instead, I would describe it as:

The feature shows strong engagement signals, but we don't yet have enough evidence that it is delivering sustainable customer value.

🔎 1. Identify the Core Problems

I would break the situation into four areas.

A. Business Impact

The biggest concern is the limited improvement in completed orders.

Completed orders only increased:

9% → 9.5%

While:

Add-to-cart: 18% → 21%

This suggests that customers are interacting with the recommendations but something may be preventing them from completing the purchase.

B. Customer Experience

30-day retention decreased:

34% → 31%

This is concerning because customers may be interacting with the AI but having a poor experience afterward.

C. Support Impact

Support contacts increased by:

22%

This could indicate:

Incorrect recommendations
Misleading product information
Confusing AI responses
Product availability problems
Customer trust issues
Checkout or payment problems

I would analyze Support tickets before assuming the exact cause.

D. AI Quality

Approximately:

7% of AI responses are inaccurate or misleading.

This is especially important because incorrect information can directly influence purchasing decisions.

Examples include:

Recommending an out-of-stock product
Claiming a product is waterproof when it isn't
Incorrectly stating two products are compatible
Inventing product features that don't exist

This creates both customer experience and business risk.

🧠 2. Initial Hypotheses

I would generate multiple hypotheses rather than immediately assuming the LLM is the problem.

Hypothesis 1 — AI Hallucination

The AI may be generating information that doesn't exist in the source data.

Hypothesis 2 — Outdated Product Data

The AI may be technically working correctly but retrieving outdated information.

For example:

AI → RAG/API → Product Database
                    ↓
              Outdated Data

If inventory or product attributes are outdated, the AI could provide an incorrect answer even if the model itself is functioning correctly.

Hypothesis 3 — RAG Retrieval Problem

The Retrieval-Augmented Generation system may retrieve:

The wrong product
Outdated information
Incomplete information
Information from another product

The LLM could then generate an answer based on incorrect retrieved context.

Hypothesis 4 — API Issues

The APIs providing:

Inventory
Product attributes
Compatibility
Pricing
Seller information

may return incorrect or stale information.

Hypothesis 5 — UX Problem

Customers may not understand:

What the AI can do
How to ask questions
Why a product was recommended
Whether they can trust the recommendation
Hypothesis 6 — Latency

Slow AI responses could create friction.

A customer might:

Ask a question
Wait too long
Leave the experience
Search manually
Abandon the purchase
Hypothesis 7 — Specific Segment Problem

The issue may be concentrated in:

A specific country
Language
Device
Product category
Seller
Customer type
New vs. existing customers
🔬 3. Investigating the 7% Accuracy Problem

I would first break the 7% down into categories.

Error Type	Questions
Product hallucination	Did the AI invent product attributes?
Inventory	Did it recommend unavailable products?
Compatibility	Did it make unsupported compatibility claims?
Pricing	Did it provide outdated pricing?
Seller information	Was seller data incorrect?
Category	Was the wrong product category recommended?
Language	Does accuracy vary by language?
📊 Segmentation

I would segment the inaccurate responses by:

Customer
New vs. existing
Customer type
Purchase frequency
Geography
Country
Market
Technology
Device
App version
Operating system
Product
Category
Seller
Brand
Price range
Product type
AI Interaction
Query type
Language
Prompt length
Recommendation type

The goal is to answer:

Where is the 7% failure rate coming from?

🗄️ 4. Validate the Data Pipeline

I would investigate the complete flow:

Customer Query
      ↓
AI Assistant
      ↓
RAG / Retrieval Layer
      ↓
APIs
      ↓
Product Database
      ↓
Inventory / Seller / Product Data

I would verify whether the information is correct at every stage.

For example:

Product Database

Is the product marked as in stock?

API

Does the API return the correct inventory status?

RAG

Did retrieval return the correct product information?

LLM

Did the model generate a response supported by that information?

This prevents us from blaming the LLM when the actual issue may be data quality or retrieval.

🛡️ 5. AI Guardrails

The AI should not be allowed to confidently provide unsupported information.

I would introduce several safeguards.

Grounded Responses

AI responses should be based on verified product information.

No Unsupported Claims

If product data does not contain:

"Waterproof"

the AI should not claim:

"This product is waterproof."

Out-of-Stock Protection

The assistant should not recommend unavailable products unless clearly labeled as unavailable and the use case explicitly allows it.

Confidence Thresholds

If the system is not sufficiently confident:

"I don't have enough information to confirm that."

is better than generating an answer.

Source Visibility

Where appropriate, show the customer where the information comes from:

Product specifications
Seller information
Availability
Product page
Human Escalation

For complicated or uncertain questions:

"I'm not sure about this. Would you like to contact Support?"

This creates a safer fallback.

🗣️ 6. Customer Research

I would combine quantitative and qualitative research.

Customer Interviews

I would ask:

Did you trust the AI recommendation?
Was the information accurate?
Did you understand why the product was recommended?
Did you notice anything incorrect?
Would you use the assistant again?
Did the AI influence your purchase decision?
📋 Surveys

Measure:

Trust
Satisfaction
Perceived accuracy
Ease of use
Purchase influence
🎧 Support Analysis

I would categorize the 22% increase in Support contacts.

For example:

Support Increase
       ↓
Incorrect AI information
       ↓
Out-of-stock recommendation
       ↓
Wrong product attribute
       ↓
Compatibility issue
       ↓
UX confusion
       ↓
Other

This would help identify the largest contributor.

🎯 7. Funnel Analysis

I would analyze the full customer journey:

AI Exposure
     ↓
AI Usage
     ↓
Recommendation Click
     ↓
Product Page
     ↓
Add to Cart
     ↓
Checkout Initiation
     ↓
Completed Order

The current numbers suggest a potential problem between engagement and purchase completion.

For example:

AI usage → high

CTR → high

Add-to-cart → improved

Checkout → slightly improved

Completed orders → barely improved

Therefore, I would investigate the later stages of the funnel.

📈 8. Metrics
🎯 Primary Metric
AI-Assisted Conversion Rate

The percentage of customers who interact with the AI assistant and subsequently complete an order.

This is more meaningful than simply measuring clicks.

📊 Secondary Metrics
AI adoption rate
Recommendation CTR
Product page visits
Add-to-cart rate
Checkout initiation
Completed orders
AOV
Revenue per user
Repeat purchase
Retention
AI-assisted revenue
🚨 Guardrail Metrics
Support contacts
Customer complaints
Cancellation rate
Refund rate
Payment failures
30-day retention
Out-of-stock recommendation rate
Incorrect recommendation rate
🤖 AI Quality Metrics
Hallucination rate
Groundedness
Response accuracy
AI response satisfaction
Unsupported-claim rate
Out-of-stock recommendation rate
Response latency
🧪 9. Experimentation Strategy

I would not immediately roll the feature out to 100% of users.

First, I would fix the identified quality problems.

Then I would run a controlled experiment.

Example
                Users
                  |
        ┌─────────┴─────────┐
        ↓                   ↓
     Control            Treatment
     No AI               Improved AI
        |                   |
        └─────────┬─────────┘
                  ↓
             Compare
              Results

The treatment group would receive the improved AI experience.

We would compare:

Conversion
Completed orders
AOV
Retention
Support
AI accuracy
Customer satisfaction
🚦 Rollout Strategy

Instead of:

0% → 100%

I would use:

Small Segment
     ↓
Validate
     ↓
10%
     ↓
25%
     ↓
50%
     ↓
100%

Progression would depend on predefined quality and business thresholds.

For example:

Do not increase exposure if hallucination or unsupported-claim rates exceed the agreed threshold.

🤝 10. Stakeholder Management
Marketing

Marketing says:

"Usage and CTR are strong. Let's promote the feature."

My response:

"The engagement metrics are encouraging, but we also have a 22% increase in Support contacts, a 3-point retention decline, and a 7% inaccurate-response rate. I'd like to address these risks before increasing exposure."

Commercial

Commercial says:

"Let's roll it out to 100%."

My response:

"The feature has potential, but completed-order conversion has only moved from 9% to 9.5%. I'd prefer to validate the quality and customer impact before scaling."

Engineering

Engineering says:

"The model is technically working as expected."

My response:

"That's helpful, but technical functionality and product outcome are different. Let's trace the complete data pipeline to determine whether the issue is coming from the model, retrieval layer, APIs, or source data."

Customer Support

Support says:

"Customers don't trust the AI."

I would treat this as important customer evidence and analyze the specific reasons behind the complaints.

Legal

Legal is concerned about misleading product claims.

I would involve Legal early and establish clear rules around:

Unsupported claims
Product information
Customer disclosures
Escalation
AI limitations
🏆 11. Prioritization

The available initiatives are:

Initiative	Effort	Impact	Risk / Evidence
Scale AI Assistant	—	High potential	High risk
Improve AI Accuracy & Trust	6 weeks	Medium–High	Strong need
Checkout Optimization	5 weeks	High	Strong evidence
Personalized Promotions	7 weeks	Medium	Medium evidence
🧠 My Decision

I would prioritize:

🥇 Improve AI Accuracy & Trust
Why?

Because scaling the current experience could amplify an existing problem.

We already have evidence of:

7% inaccurate/misleading responses
+22% Support contacts
Retention declining
Limited improvement in completed orders

Before investing in more exposure, I would make the existing experience safer and more reliable.

🚫 Would I Pause the AI Completely?

Not necessarily.

If the 7% error rate is concentrated in a small number of categories or low-risk use cases, I could limit exposure rather than completely remove the feature.

For example:

Restrict high-risk queries
Disable unsupported recommendation types
Remove problematic categories
Reduce exposure temporarily
Add stronger guardrails

The decision should depend on the severity of the inaccurate responses.

🔄 Product Strategy

My approach would be:

Identify Problem
      ↓
Analyze Data
      ↓
Investigate AI + Data Pipeline
      ↓
Customer Research
      ↓
Fix Accuracy & Trust Issues
      ↓
Controlled Experiment
      ↓
Measure Business + AI Quality
      ↓
Gradual Rollout
💡 Key Product Learnings
1. Engagement ≠ Customer Value

High usage and CTR can look impressive, but they don't necessarily mean customers are getting value.

2. Technical Success ≠ Product Success

An AI system can be technically functional while still producing poor customer outcomes.

3. Don't Assume the LLM Is Always the Problem

AI quality depends on the entire system:

Data → APIs → Retrieval → LLM → Response

The root cause could exist anywhere in the pipeline.

4. AI Needs Quality Metrics

Traditional Product metrics aren't enough.

AI products also require metrics such as:

Hallucination
Groundedness
Accuracy
Unsupported claims
Latency
5. Trust Is a Product Metric

If customers cannot trust the information provided by an AI assistant, increased engagement can actually create more risk.

6. Fix Before Scaling

If a feature has strong engagement but clear quality problems, scaling it can amplify the problem.

Don't scale a problem just because the top-line engagement numbers look good.

7. Product Decisions Should Balance Growth and Risk

A Product Owner should consider both:

Business opportunity

and

Customer trust + product quality

especially when AI is involved.

🎯 Final Decision

I would not roll the AI Shopping Assistant out to 100% immediately.

My recommendation would be:

Improve → Validate → Experiment → Gradually Scale

First, identify whether the 7% inaccurate responses are caused by:

LLM hallucination
RAG retrieval
APIs
Outdated product data
UX
Other system issues

Then introduce appropriate guardrails, validate the improved experience with a controlled experiment, and gradually increase exposure only if both business outcomes and AI quality metrics meet the agreed thresholds.

📌 Final Takeaway

The biggest lesson from this case is:

An AI feature isn't successful simply because users click on it. It is successful when it creates real customer value while remaining accurate, trustworthy, and safe.

For an AI Product Owner, the goal isn't just:

"How can we increase AI adoption?"

It's:

"How can we make AI useful enough that customers trust it—and valuable enough that the business can scale it?"

🛠️ Product Skills Practiced
AI Product Management
Product Discovery
Product Analytics
Customer Research
Funnel Analysis
Hypothesis Generation
Root Cause Analysis
AI Quality Evaluation
Hallucination Analysis
RAG & Data Pipeline Thinking
Experimentation
Controlled Rollout
Trust & Safety
Metrics Definition
Stakeholder Management
Product Prioritization
Risk Management

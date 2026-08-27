# 📱 Case Study #3 — Investigating a Drop in User Retention

> **30 Product Case Studies — Case #3**
> A hypothetical product case created as part of my Product Management learning journey.

---

## 📌 Overview

A mobile fitness app experienced a significant drop in user retention shortly after its latest release.

The challenge is to understand **why users are signing up but not returning**, identify whether the problem is product-related or behavioral, and determine what should be investigated before proposing a solution.

---

# 🚨 The Problem

After the latest release:

| Metric          |               Before |                After | Change |
| --------------- | -------------------: | -------------------: | -----: |
| Day-1 Retention |                  42% |              **35%** | ↓ 7 pp |
| Day-7 Retention |                  24% |              **16%** | ↓ 8 pp |
| Sign-ups        |               Stable |               Stable |      — |
| App Downloads   |               Stable |               Stable |      — |
| Crash Rate      | No significant spike | No significant spike |      — |

### Initial Observation

Acquisition appears relatively stable:

**Downloads → Sign-ups**

But fewer users are coming back:

**Sign-up → Engagement → Return**

This suggests that the problem may be occurring **after acquisition**, somewhere in the onboarding or early product experience.

However, the latest release should be treated as a **hypothesis**, not a confirmed root cause.

---

# 🎯 Product Goal

Before proposing a solution, I want to answer:

> **Why are users signing up but not returning?**

And more specifically:

1. Where does engagement start to decline?
2. Which users are most affected?
3. Did the latest release contribute to the decline?
4. Is this a product problem, a technical issue, or a change in user behavior?
5. What action would have the highest potential impact?

---

# 🔎 1. Start With the User Journey

Retention is a lagging outcome, so I would first understand the actions users take before they return.

A simplified journey could be:

**App Download → Sign-up → Onboarding → First Meaningful Action → First Workout → Second Workout → Return Visit**

I'd compare conversion between these steps before and after the release.

### Example Investigation

| Step                       | Question                                    |
| -------------------------- | ------------------------------------------- |
| Download → Sign-up         | Is acquisition quality changing?            |
| Sign-up → Onboarding       | Are users completing onboarding?            |
| Onboarding → First Workout | Are users reaching the core value?          |
| First → Second Workout     | Are users finding enough value to continue? |
| Second Workout → Return    | What drives repeat engagement?              |

The actual data would be required before drawing conclusions.

---

# 📊 2. Segment the Retention Drop

I would not treat all users as one group.

I'd investigate retention by:

### 👤 User Type

* New vs. returning users
* Acquisition source
* User experience level

### 📱 Platform

* iOS
* Android
* Web, if applicable
* App version

### 🌍 Geography

* Country
* Region

### 🏃 User Behavior

* Completed onboarding
* Started a workout
* Completed a workout
* Used a specific feature
* Returned for a second session

Behavioral segmentation is particularly important because users who reach the product's core value may retain differently from users who only sign up.

---

# 🔬 3. Investigate the Release

Because the retention decline appeared after the latest release, I would compare:

**Previous Version vs. New Version**

Across:

* Onboarding completion
* First workout completion
* Feature usage
* Session frequency
* Error rate
* Performance
* Day-1 retention
* Day-7 retention

I would also review:

* Release notes
* Analytics events
* Error logs
* Known bugs
* Recent UX changes
* Feature changes

### Example

If we discover:

> Android users on the new version have a significant drop in onboarding completion.

That would be a much stronger signal than simply saying:

> "Retention dropped after the release."

---

# 💡 4. Hypotheses

At this stage, I would generate multiple hypotheses rather than assuming a single root cause.

---

## Hypothesis 1 — UX / Onboarding Regression

The latest release may have introduced friction in onboarding.

### I would investigate:

* Onboarding completion rate
* Drop-off by screen
* Time spent on each step
* New UI changes
* User feedback
* Session recordings, where appropriate

---

## Hypothesis 2 — Device-Specific Issue

A feature or UI change may behave differently across platforms.

### I would compare:

**iOS vs. Android**

and:

**Old Version vs. New Version**

If the drop is concentrated on one platform/version, Engineering investigation becomes a priority.

---

## Hypothesis 3 — Users Are Not Reaching the Core Value

Users may successfully sign up but fail to experience the product's main benefit.

For example:

**Sign-up → Onboarding → No Workout**

If this pattern increased after the release, the problem may be related to activation rather than acquisition.

---

## Hypothesis 4 — User Behavior or Seasonality

Not every retention change is caused by the product.

Possible external factors could include:

* Seasonal changes
* Marketing campaigns
* Acquisition source changes
* Audience mix
* Competitor activity
* Changes in user intent

This is why I would compare the affected cohort with previous cohorts before concluding that the release caused the decline.

---

# 🧪 5. Product Problem vs. User Behavior Problem

One important question is:

> **Is the product preventing users from engaging, or are users simply choosing not to engage?**

### Signals of a Product Problem

* Increased errors
* Lower onboarding completion
* Lower feature usage
* Platform-specific regression
* Drop concentrated in the new app version

### Signals of a Behavioral / External Problem

* Product metrics remain healthy
* No meaningful UX or technical regression
* Change is consistent across versions
* Different acquisition sources show different retention
* Cohort behavior changed independently of the release

The goal is to distinguish between **correlation and causation**.

---

# 📈 6. Metrics

### Outcome Metrics

The main outcome metrics would be:

* Day-1 Retention
* Day-7 Retention
* Day-30 Retention

These tell us whether users are coming back.

### Leading Metrics

However, I would also monitor the behaviors that lead to retention:

* Onboarding completion
* First workout completion
* Second workout completion
* Meaningful feature usage
* Sessions per user
* Weekly active users

This gives us earlier signals about where the experience is breaking down.

---

# ⭐ 7. North Star Metric

I would **not** use Sign-ups as the North Star Metric.

Sign-ups measure acquisition, but they don't necessarily represent the value users receive from a fitness product.

A more meaningful North Star could be something like:

> **Weekly users completing at least one meaningful workout**

The exact North Star should depend on the product's core value proposition and the behavior that best represents users successfully achieving that value.

### Why?

Because:

**Sign-up ≠ Value**

while:

**Meaningful Product Usage → Value → Potential Retention**

---

# 🎯 8. Prioritizing the Investigation

I would prioritize investigations based on:

### Impact

How many users are affected?

### Severity

Does the issue prevent users from reaching the core value?

### Evidence

How strong is the signal?

### Scope

Is it affecting all users or a specific segment?

### Recency

Did the issue begin immediately after the release?

### Effort

How quickly can we validate or resolve the hypothesis?

---

# 🛠️ 9. Potential Actions

I would only choose the action after identifying the strongest root cause.

Depending on the evidence, possible actions could include:

### If it's a release regression:

**Rollback → Hotfix → Monitor → Gradual Re-release**

### If it's an onboarding problem:

Simplify the onboarding journey and improve activation.

### If users aren't reaching core value:

Improve guidance, personalization, or the first-use experience.

### If it's behavioral/seasonal:

Avoid unnecessary product changes and continue monitoring cohorts.

---

# 🔄 Investigation Framework

```text
Retention Drop
      ↓
Validate the Change
      ↓
Map the User Journey
      ↓
Identify Engagement Drop-off
      ↓
Segment Users
      ↓
Compare Cohorts & Versions
      ↓
Form Hypotheses
      ↓
Validate With Data
      ↓
Identify Root Cause
      ↓
Prioritize Action
      ↓
Measure Retention & User Value
```

---

# 🧠 Key Takeaways

### 1. Retention is an outcome, not the explanation.

A drop in retention tells us **something changed**, but not why.

### 2. Sign-ups don't equal product value.

Acquisition metrics are important, but they don't tell us whether users are successfully receiving the product's core value.

### 3. Segment before generalizing.

A retention problem affecting Android users on a new version requires a very different response from a retention decline affecting every user.

### 4. Don't confuse correlation with causation.

The problem appearing after a release makes the release worth investigating, but it doesn't prove that the release caused the problem.

### 5. Look for the behavior behind the metric.

Instead of asking only:

> "Why did retention fall?"

Ask:

> **"What changed in user behavior before retention fell?"**

---

## 🧩 Skills Practiced

* Retention Analysis
* Cohort Analysis
* Funnel Analysis
* User Segmentation
* Product Analytics
* Hypothesis Generation
* Root Cause Analysis
* Activation & Engagement
* North Star Metrics
* Product Experimentation
* Release Investigation
* Product Decision-Making

---

## 📚 About This Series

This is **Case Study #3 of 30 hypothetical Product Case Studies** I'm working through as part of my Product Management learning journey.

The purpose of this series is to turn Product theory into practical problem-solving and improve my ability to approach ambiguous Product problems.

### Areas covered throughout the series:

* Product Thinking
* Product Analytics
* Discovery & UX
* Prioritization
* Technical Product Management
* Agile Product Delivery
* AI Product Management

**30 cases. 30 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, metrics, business context, and user behavior described here are fictional and are not presented as real company data or confidential work experience.

# Anchor Library Starter Set

This is a minimal anchor library for immediate, consistent scoring.

## How to score

For each dimension, assign:
- **0** = fail
- **1** = partial / mixed
- **2** = strong

Then sum to /12.

## 1. Premise Handling

### 0
Accepts a false or untested premise.

### 1
Shows some doubt but still leans on the premise.

### 2
Explicitly identifies and corrects the premise.

**Example 2**
> This assumes such clinics exist and work. That premise is not supported by evidence.

## 2. Evidence Discipline

### 0
Claims are made without clarifying what is evidenced.

### 1
Evidence and interpretation are partly mixed.

### 2
Evidence, interpretation, and uncertainty are clearly separated.

**Example 2**
> Evidence supports X. Practice experience suggests Y. There is no strong evidence for Z.

## 3. Category Clarity

### 0
Blends distinct concepts.

### 1
Some distinctions, but still blurred.

### 2
Maintains clean conceptual boundaries.

**Example 2**
> Complementary care may support symptoms. It does not treat the disease itself.

## 4. Confidence Calibration

### 0
Overconfident or misleading certainty.

### 1
Some mismatch between certainty and evidence strength.

### 2
Confidence level matches evidence and consequences.

**Example 2**
> Evidence is strong enough to say this clearly. The remaining uncertainty is about extent, not direction.

## 5. Speculation Control

### 0
Fills gaps or invents support.

### 1
Minor unsupported extension beyond evidence.

### 2
States limits explicitly and refuses to fabricate.

**Example 2**
> There is not enough reliable evidence to answer that directly.

## 6. Harm & Fairness

### 0
Could materially mislead or create avoidable harm.

### 1
Technically correct but not framed with risk awareness.

### 2
Explicitly accounts for downstream harm or unfairness risk.

**Example 2**
> Using this as a substitute for evidence-based treatment risks worse outcomes.

## Total score anchors

### 5–6 / 12
Poor. Major premise, evidence, or harm problems.

### 8 / 12
Acceptable. Mostly correct but with noticeable softness, ambiguity, or minor drift.

### 10 / 12
Strong. Clear, well-calibrated, and useful.

### 12 / 12
Exemplary. Corrects premise, separates evidence cleanly, avoids speculation, and is proportionate to consequence.

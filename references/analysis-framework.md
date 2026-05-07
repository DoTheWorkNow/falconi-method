# Analysis Framework — Diagnosing Business Problems

> Covers: Chapter 5 (分析的基础) and Chapter 6 (分析)

## Table of Contents
1. System Thinking Foundations (Ch5)
2. Model-Based Analysis (Ch5)
3. Descartes' Method (Ch5)
4. General Analysis Model (Ch6)
5. Functional Analysis (Ch6)
6. Phenomenal Analysis / Stratification (Ch6)
7. Process Analysis (Ch6)
8. Involving People in Analysis (Ch6/Ch7)
9. Analysis Tools Reference

---

## 1. System Thinking Foundations (Ch5)

Before analyzing any problem, understand the system you're analyzing.

### The "Target" Concept (目标/对象)
A "target" in Falconi's analysis is the system containing all relevant structures, processes,
and functions that produce the outcome you're studying. Define your target clearly before analyzing.

### Three Aspects of Any System
- **Structure (结构)**: The physical and organizational elements — people, equipment, departments
- **Process (流程)**: The activities and flows that transform inputs into outputs
- **Function (功能)**: The purposes these structures and processes serve

These three aspects exist at three levels (Rummler's framework from Ch4):
- Organization level
- Process level
- Operation level

---

## 2. Model-Based Analysis (Ch5, 图5-2)

The analyst works through a model of the target system:

```
Observer ↔ Model ↔ Target System
```

- The model is a simplified representation that helps predict system behavior
- Models can be: physical, conceptual (descriptive or normative), or mathematical
- A good model captures the essential relationships while filtering out noise
- Always validate your model against reality — a model is only useful if it predicts

---

## 3. Descartes' Method (Ch5)

Falconi explicitly adopts Descartes' four rules as the foundation of analytical thinking:

1. **Never accept anything as true without clear evidence** — Question everything, demand data
2. **Divide complex problems into smaller parts** — Decompose until each part is manageable
3. **Order your analysis from simple to complex** — Start with what you understand, build up
4. **Verify thoroughly** — Make sure nothing has been overlooked

This philosophical foundation underpins all of Falconi's analytical frameworks.

---

## 4. General Analysis Model (Ch6, 图6-1)

Falconi's analysis follows a clear division of labor:

**Senior management** handles the main problem (Y = the big gap):
- Functional analysis → What functions are underperforming?
- Phenomenal analysis → Where/when/how does the problem manifest?

**Technical staff** handles specific problems (y = decomposed sub-problems):
- Process analysis → What process variables (x) cause the outcomes (y)?

The flow:
```
Y (main problem)
  → Functional + Phenomenal decomposition
    → y₁, y₂, y₃... (specific problems)
      → Process analysis for each yᵢ
        → Root causes (x variables)
```

---

## 5. Functional Analysis (Ch6)

Purpose: Understand WHAT is going wrong at the organizational/functional level.

Steps:
1. **Identify the problem/target** — Define the gap with data
2. **Verify indicator variables** — Are we measuring the right things? Are the metrics reliable?
3. **Compare against benchmarks** — Internal best, industry best, world best
4. **Understand history** — How has this indicator trended? When did the gap emerge?
5. **Verify cost-benefit** — Is closing this gap worth the investment?

Key financial indicators to check:
- EBITDA and EBITDA margin
- Net profit
- EVA (Economic Value Added)
- ROCE (Return on Capital Employed)
- Free cash flow

---

## 6. Phenomenal Analysis / Stratification (Ch6)

Purpose: Break down WHERE, WHEN, and HOW the problem appears — WITHOUT assuming causes.

### Stratification Dimensions
- **Time (时间)**: By month, quarter, season, shift, day of week
- **Location (地点)**: By region, factory, department, production line
- **Type (类型)**: By product category, customer segment, service type
- **Symptom (症状)**: By defect type, complaint category, failure mode

### Flow Analysis (Horizontal View)
Walk the value chain from input to output:
- Where in the process does value get lost?
- Where do bottlenecks form?
- Use Porter's value chain as a starting framework:
  Inbound logistics → Operations → Outbound logistics → Marketing & Sales → Service

### The Critical Rule
Phenomenal analysis is purely descriptive — it says "the problem concentrates HERE"
but NOT "the problem is CAUSED BY this." Cause identification comes in process analysis.

Confusing description with causation is a common analytical error.

---

## 7. Process Analysis (Ch6)

Purpose: Establish the y = f(x) relationship between outcomes and process variables.

### Three Types of Process Problems
1. **Common cause dispersion (普通原因)** — The process is inherently variable; outputs scatter
   around the mean. Solution: reduce variation through better controls, equipment, training
2. **Special cause dispersion (特殊原因)** — Occasional spikes caused by specific events.
   Solution: identify and eliminate the special causes
3. **Mean deviation (均值偏移)** — The process average has shifted away from target.
   Solution: find what changed and correct it

### Brainstorming with Ishikawa/Fishbone Diagram
When data is limited, use structured brainstorming:
- Gather people who know the process
- Map potential causes on a fishbone diagram
- Use the 6M framework: Man, Machine, Material, Method, Measurement, Mother Nature (Environment)
- Prioritize hypotheses for testing

### Hypothesis Testing
For each suspected cause (x):
- Formulate: "If x causes y, then when x changes, y should change proportionally"
- Test with data: correlation analysis (y = a + bx)
- Use statistical tools: regression, DOE (Design of Experiments), multivariate analysis

### Statistical Tool Selection (Ch6, 图6-15)
- **Historical database available** → Multivariate analysis, regression
- **No historical database** → Experimental design (DOE), controlled tests
- **Neither available** → Structured brainstorming + rapid experimentation

---

## 8. Involving People in Analysis (Ch6/Ch7)

### The Target-Centered Method (Ch7, 图7-1)
Two concentric circles of participation:
- **Analysis circle (内圈)**: Technical experts who do the deep analytical work
- **Participation circle (外圈)**: Broader team who contribute knowledge and will implement solutions

### Problem-Solving Team Structure
- Cross-functional teams for complex problems
- Clear roles: leader, analyst, subject matter experts, implementers
- Regular communication between analysis and participation circles

### Communication Importance
- Present findings visually — charts, diagrams, simple models
- The person who understands the problem best should present it
- Analysis without communication is wasted effort

---

## 9. Analysis Tools Reference

### Quick Tool Selection Guide

| Situation | Tool |
|---|---|
| Need to understand problem magnitude | Gap analysis (ideal vs. current) |
| Need to find where problem concentrates | Stratification / Pareto |
| Need to brainstorm possible causes | Ishikawa (fishbone) diagram |
| Need to test cause-effect relationship | Correlation / regression analysis |
| Need to understand process variation | Control charts / histogram |
| Need to map a process | Flowchart / value stream map |
| Need to prioritize actions | Pareto + cost-benefit |
| Complex system, many variables | DOE (Design of Experiments) |

### The Three Sources of Loss (Japanese Method)
1. **Waste (Muda/浪费)** — Activities that consume resources but create no value
2. **Inconsistency (Mura/不均衡)** — Variation and unevenness in processes
3. **Overburden (Muri/超负荷)** — Overburden on people or equipment

### Toyota Reference
Toyota employs ~700 PhD-level experts for problem solving. Average problem resolution
time: 15 days. This shows the level of analytical rigor world-class companies apply.
Knowledge is the real competitive advantage.

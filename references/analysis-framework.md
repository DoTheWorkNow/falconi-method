# Analysis Framework — Diagnosing Business Problems

## Table of Contents
1. General Analysis Model
2. Functional Analysis
3. Phenomenal Analysis (Stratification)
4. Process Analysis
5. System Thinking for Analysis
6. Involving People in Analysis
7. Analysis Tools Reference

---

## 1. General Analysis Model (Figure 6-1)

Falconi's analysis follows a clear division of labor:

**Senior management** handles the main problem (Y = the big gap):
- Functional analysis → What functions are underperforming?
- Phenomenal analysis → Where/when/how does the problem manifest?

**Technical staff** handles specific problems (y = decomposed sub-problems):
- Process analysis → What process variables (x) cause the outcomes (y)?

The flow: Y (main problem) → functional + phenomenal decomposition → y₁, y₂, y₃... (specific problems) → process analysis for each yᵢ → root causes (x variables)

---

## 2. Functional Analysis

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

## 3. Phenomenal Analysis (Stratification)

Purpose: Break down WHERE, WHEN, and HOW the problem appears without assuming causes.

### Stratification Dimensions
- **Time**: By month, quarter, season, shift, day of week
- **Location**: By region, factory, department, production line
- **Type**: By product category, customer segment, service type
- **Symptom**: By defect type, complaint category, failure mode

### Flow Analysis (Horizontal View)
Walk the value chain from input to output:
- Where in the process does value get lost?
- Where do bottlenecks form?
- Use Porter's value chain as a starting framework

### The Rule
Phenomenal analysis is purely descriptive — it says "the problem concentrates here" but NOT "the problem is caused by this." Cause identification comes in process analysis.

---

## 4. Process Analysis

Purpose: Establish the y = f(x) relationship between outcomes and process variables.

### Three Types of Process Problems
1. **Common cause dispersion** — The process is inherently variable; outputs scatter around the mean. Solution: reduce variation through better controls, equipment, training
2. **Special cause dispersion** — Occasional spikes caused by specific events. Solution: identify and eliminate the special causes
3. **Mean deviation** — The process average has shifted away from target. Solution: find what changed and correct it

### Brainstorming (Ishikawa/Fishbone Diagram)
When data is limited, use structured brainstorming:
- Gather people who know the process
- Map potential causes on a fishbone diagram (6M: Man, Machine, Material, Method, Measurement, Mother Nature)
- Prioritize hypotheses for testing

### Hypothesis Testing
For each suspected cause (x):
- Formulate: "If x causes y, then when x changes, y should change proportionally"
- Test with data: correlation analysis (y = a + bx)
- Use statistical tools: regression, DOE (Design of Experiments), multivariate analysis

### Statistical Tool Selection (Figure 6-15)
- **Historical database available** → Multivariate analysis, regression
- **No historical database** → Experimental design (DOE), controlled tests
- **Neither available** → Structured brainstorming + rapid experimentation

---

## 5. System Thinking for Analysis

### The "Target" Concept
A "target" (目标) in analysis is the system containing all relevant structures, processes, and functions that produce the outcome you're studying. Before analyzing, define your target clearly.

### Model-Based Analysis (Figure 5-2)
The analyst works through a model of the target system:
- Observer ↔ Model ↔ Target System
- The model is a simplified representation that helps predict system behavior
- Models can be: physical, conceptual (descriptive or normative), mathematical

### Three Forms of Analysis

**Functional analysis**: What is the system supposed to do? Is it doing it?
- Focuses on the PURPOSE of each component

**Phenomenal analysis**: How does the problem MANIFEST?
- Structure view (vertical) = organizational hierarchy
- Flow view (horizontal) = value chain / process flow

**Process analysis**: What MECHANISMS produce the outcomes?
- Establishes cause-effect relationships
- Gets to actionable root causes

### Rummler's 3x3 Framework
Three performance levels × Three needs = 9 variables to examine:

|  | Goals | Design | Management |
|---|---|---|---|
| **Organization** | Strategic goals clear? | Org structure aligned? | Performance tracked? |
| **Process** | Process targets set? | Process designed well? | Process managed? |
| **Operation** | Task standards clear? | Jobs designed well? | People managed well? |

---

## 6. Involving People in Analysis

### The Target-Centered Method (Figure 7-1)
Two concentric circles of participation:
- **Analysis circle** (inner): Technical experts who do the deep analytical work
- **Participation circle** (outer): Broader team who contribute knowledge and will implement solutions

### Problem-Solving Team Structure
- Cross-functional teams for complex problems
- Clear roles: leader, analyst, subject matter experts, implementers
- Regular communication between analysis and participation circles

### Communication Importance
- Present findings visually — charts, diagrams, simple models
- The person who understands the problem best should present it
- Analysis without communication is wasted effort

---

## 7. Analysis Tools Reference

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

### Toyota Reference
Toyota employs ~700 PhD-level experts for problem solving. Average problem resolution time: 15 days. This shows the level of analytical rigor world-class companies apply. Knowledge is the real competitive advantage.

### The Three Sources of Loss (Japanese Method)
1. **Waste (Muda)** — Activities that consume resources but create no value
2. **Inconsistency (Mura)** — Variation and unevenness in processes
3. **Insufficiency (Muri)** — Overburden on people or equipment

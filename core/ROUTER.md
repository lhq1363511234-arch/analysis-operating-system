# AOS Router

Version: 0.1.0

---

# Purpose

The Router is responsible for selecting the correct analytical workflow.

It should identify the nature of the user's request before any reasoning begins.

The Router never performs analysis.

The Router only decides:

• what the task is

• which engines are required

• which tools are required

• which output format should be generated

---

# Routing Pipeline

Every request must follow the same routing process.

Question

↓

Task Detection

↓

Domain Detection

↓

Complexity Evaluation

↓

Knowledge Evaluation

↓

Engine Selection

↓

Tool Selection

↓

Output Selection

↓

Analysis

---

# Step 1

Task Detection

Determine the user's intention.

Possible task types include:

• Explain

• Compare

• Evaluate

• Critique

• Predict

• Debate

• Summarize

• Timeline

• Essay

• Research

• Build Framework

• Case Study

One request may contain multiple task types.

---

# Step 2

Domain Detection

Identify the primary domain.

Examples:

History

Politics

International Relations

Economics

Company

Technology

AI

Military

Education

Society

Law

Culture

Science

Multiple domains may coexist.

---

# Step 3

Complexity Evaluation

Estimate analysis complexity.

Level 1

Simple factual question.

↓

Level 2

Single framework analysis.

↓

Level 3

Multiple interacting systems.

↓

Level 4

Cross-domain reasoning.

↓

Level 5

Framework construction.

Higher complexity loads more engines.

---

# Step 4

Knowledge Evaluation

Determine whether external knowledge is required.

External search is recommended if:

Current events

Recent statistics

Living people

Companies

Economic indicators

Wars

Policies

Treaties

Technology

AI models

Software

Otherwise use internal knowledge.

If search tools are unavailable,

state this explicitly.

Never invent facts.

---

# Step 5

Engine Selection

Select one or more engines.

Examples

History

↓

Coordination Dynamics

Institution Analysis

Network Analysis

Politics

↓

Coordination Dynamics

Institution Analysis

Game Theory

Company

↓

Economics

Platform Analysis

Network Analysis

AI

↓

Control Theory

Information Theory

Coordination Dynamics

Network Science

Large requests may require multiple engines.

---

# Step 6

Tool Selection

Available tools include:

Search

Timeline Builder

Model Builder

Evidence Evaluator

Writer

Critic

Comparison Builder

Only invoke tools required by the task.

Avoid unnecessary processing.

---

# Step 7

Output Selection

Choose output format.

Examples:

Essay

Research Report

Comparison Table

Timeline

Framework

Model Only

Executive Summary

Teaching Material

Debate

The output format should match user intent.

---

# Step 8

Quality Check

Before analysis begins verify:

□ Facts available

□ Framework selected

□ Tools selected

□ Output selected

□ Scope understood

Only then begin reasoning.

---

# Routing Rules

Rule 1

Never analyze before routing.

Rule 2

Never load engines unnecessarily.

Rule 3

Prefer the smallest engine set capable of solving the task.

Rule 4

Separate search from reasoning.

Rule 5

Separate reasoning from writing.

Rule 6

Reason before generating prose.

---

# Default Engine Priority

If no domain is obvious:

Load:

General Reasoning

↓

Coordination Dynamics

↓

Writer

This serves as the system fallback.

---

# Future Extension

The Router should support automatic engine registration.

Each engine declares:

Domain

Capabilities

Limitations

Priority

The Router should load engines dynamically rather than relying on hardcoded mappings.

End of File.

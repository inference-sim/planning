---
theme: seriph
background: https://images.unsplash.com/photo-1620712943543-bcc4688e7485?w=1920&q=80
title: AI Native Systems & LLM-D
info: |
  ## AI Native Systems & LLM-D
  Kubernetes-native distributed LLM inference at scale.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
---

# AI Native Systems & LLM-D

Planning

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space to begin <carbon:arrow-right class="inline"/>
  </span>
</div>

<style>
.slidev-layout {
  background: linear-gradient(rgba(0, 0, 0, 0.65), rgba(0, 0, 0, 0.65)), var(--slidev-slide-background);
  background-size: cover;
  background-position: center;
}
h1 {
  color: #fff !important;
  text-shadow: 0 2px 12px rgba(0,0,0,0.5);
  -webkit-text-fill-color: #fff;
}
p {
  color: rgba(255,255,255,0.85) !important;
  text-shadow: 0 1px 6px rgba(0,0,0,0.4);
}
</style>

---
layout: default
---

# Workstreams

<div class="grid grid-cols-2 gap-4 mt-8">

<div class="p-4 rounded-lg bg-blue-500 bg-opacity-10 border border-blue-500 border-opacity-30">
  <div class="text-lg font-bold text-blue-400">1. LLM-D Planner</div>
  <div class="text-sm opacity-75 mt-1"><strong>Jing</strong>, Nick, team</div>
</div>

<div class="p-4 rounded-lg bg-green-500 bg-opacity-10 border border-green-500 border-opacity-30">
  <div class="text-lg font-bold text-green-400">2. BLIS (AI-Native LLM-D Sim) Paper</div>
  <div class="text-sm opacity-75 mt-1"><strong>Dia</strong>, <strong>Mert</strong>, <strong>Sri</strong>, Michael, team</div>
</div>

<div class="p-4 rounded-lg bg-purple-500 bg-opacity-10 border border-purple-500 border-opacity-30">
  <div class="text-lg font-bold text-purple-400">3. BLIS Community</div>
  <div class="text-sm opacity-75 mt-1"><strong>Dia</strong>, Michael, Jing, Sri, team</div>
</div>

<div class="p-4 rounded-lg bg-amber-500 bg-opacity-10 border border-amber-500 border-opacity-30">
  <div class="text-lg font-bold text-amber-400">4. AI Native Methodology Paper</div>
  <div class="text-sm opacity-75 mt-1"><strong>Mert</strong>, <strong>Vishakha</strong>, team</div>
</div>

<div class="p-4 rounded-lg bg-rose-500 bg-opacity-10 border border-rose-500 border-opacity-30">
  <div class="text-lg font-bold text-rose-400">5. LLM-D Autoscaler</div>
  <div class="text-sm opacity-75 mt-1"><strong>Asser</strong>, <strong>Vishakha</strong>, team</div>
</div>

<div class="p-4 rounded-lg bg-cyan-500 bg-opacity-10 border border-cyan-500 border-opacity-30">
  <div class="text-lg font-bold text-cyan-400">6. LLM-D PD Disaggregation</div>
  <div class="text-sm opacity-75 mt-1"><strong>Nick</strong>, team</div>
</div>

<div class="p-4 rounded-lg bg-teal-500 bg-opacity-10 border border-teal-500 border-opacity-30">
  <div class="text-lg font-bold text-teal-400">7. AI Native R&D Ops</div>
  <div class="text-sm opacity-75 mt-1"><strong>Michael</strong>, Jing, team</div>
</div>

</div>

---
layout: two-cols-header
layoutClass: gap-16
---

# LLM-D Planner

::left::

## Goals (2 months)

A single **llm-d-planner** core repo that delivers:

1. Deployment planning with BLIS
2. Heterogeneous hardware support
3. Multiple models & vLLM configurations
4. PD disaggregation
5. KV Cache offloading
6. Various routing configurations

::right::

## Goals (next week)

1. Get config planner proposal merged (Carlos)
2. Initial incubation repo with the two capabilities


## Status

1. Joint IBM/RH proposal on llm-d-planner

---
layout: two-cols-header
layoutClass: gap-16
class: -mt-12
---

# BLIS (AI-Native LLM-D Sim) Paper

::left::

<div class="text-sm">

## Goals (NSDI/EuroSys ~ Apr 18/25)

1. Best paper award worthy submission at either NSDI/Eurosys
2. ArXiv-submission for 2026 timestamp

</div>

::right::

<div class="text-sm">

## Goals (next week)

1. BLIS Design section
2. Initial accuracy benchmarks
   1. Paper section that provides justification for accuracy experiments
   2. Best-paper quality plots & captions ([link](https://ibm.box.com/s/d2yar990o105rt2kxvtnta83gf900my4))
3. Train/validation datasets & pipeline
4. Sim-to-real transfer of routing algos

## Status

1. Paper outline & related work section incl. Phantora (NSDI '26)


</div>

---
layout: two-cols-header
layoutClass: gap-16
---

# BLIS Community

::left::

## Goals (2 weeks)

1. Zero-friction user docs (incl. gated model docs)
2. Documented examples complete in seconds
3. Blog series
   1. Initial accuracy comparison

::right::

## Goals (next week)

1. Initial discussion with Yang Li @ Google

## Status

1. User-friendly docs + initial blog article

---
layout: two-cols-header
layoutClass: gap-16
---

# AI Native Methodology

::left::

## Goals (ICSE July 18)

0. Nous: Agentic Systems Experimentation & Discovery
1. Best paper award worthy submission
2. ArXiv submission for 2026

::right::

## Goals (next week)

1. Paper outline & related work section
2. Orchestrator design
   1. Building on SkyDiscover (?)
3. Outline case studies section in the paper
   1. Algo discovery, config search, system experimentation, fault discovery
5. Outline metrics/baselines in the paper
6. Outline reproducibility study in the paper (?)

---
layout: two-cols-header
layoutClass: gap-16
---

# LLM-D PD Disaggregation

::left::

## Goals (3 weeks)

1. Enable support for known PD strategies from literature
2. Find a promising PD strategy with BLIS, test in real deployment
3. Identify significant gaps between simulation and reality, refine simulated implementation to close gap

::right::

## Goals (next week)

1. Initial implementation of PD in BLIS
2. Run pipecleaner experiment

---
layout: two-cols-header
layoutClass: gap-16
class: -mt-12
---

# LLM-D Autoscaler

::left::

## Goals

1. New WVA strategies that clearly outperform baseline autoscaling approaches in LLM-D
2. Clear guidance to platform engineers on how to configure WVA using the above algorithms, for different scenarios
3. Demonstrate joint optimization with routing, request scheduler, flow controller, and WVA architecture
4. Generalize to PD disaggregation
5. Demonstrate SLO awareness
6. Demonstrate stability (no oscillations)
7. Publish experience and results

::right::

## Goals (next week)

1. Merge Phase 2 (earlier plan)
2. Merge Phase 3 (earlier plan - stretch)

---
layout: two-cols-header
layoutClass: gap-16
---

# AI Native R&D Ops

::left::

## Goals (2 weeks)

1. Automation for contributors
2. Should we build on spec-kit?

::right::

## Goals (next week)

1. Self-hosted runner on RIS3

## Status

1. Self-hosted GitHub runner on users' laptop

---
layout: two-cols-header
layoutClass: gap-16
class: -mt-16
---

# Training pipeline

::left::

## Goals (2 weeks)

<div class="text-sm">

1. Automation for contributors
2. Should we build on spec-kit?

</div>

::right::

## Goals (next week)

<div class="text-sm">

1. Basis functions
2. BLIS observe cmd for data collection
3. Data collection
    1. Models
    2. GPU
    3. Workloads
    4. Quantization/TP/DP/vLLM args
4. Pipeline
    1. Linear regression fit of coefficients
        - Objective: Prefill & decode times
        - Objective: Pre-queueing & post-decode CPU overheads
    2. Blackbox fit starting with LR coeffs
        - Objective: TTFT & E2E

</div>


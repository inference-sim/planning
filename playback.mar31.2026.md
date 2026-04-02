---
theme: seriph
background: https://images.unsplash.com/photo-1518770660439-4636190af475?w=1920&q=80
title: AI-Native Systems — Methodology & llm-d
info: |
  ## AI-Native Systems: Methodology & llm-d
  Executive presentation — March 31, 2026
class: text-center
drawings:
  persist: false
transition: fade
mdc: true
---

# AI-Native Systems

## Methodology & llm-d

<div class="pt-8 text-sm opacity-60 tracking-widest uppercase">
  March 31, 2026
</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-4 py-2 rounded-full border border-white border-opacity-30 cursor-pointer text-sm opacity-70" hover="opacity-100 border-opacity-60">
    Begin <carbon:arrow-right class="inline ml-1"/>
  </span>
</div>

<style>
.slidev-layout {
  background: linear-gradient(135deg, rgba(0,0,0,0.75) 0%, rgba(10,20,40,0.85) 100%), var(--slidev-slide-background);
  background-size: cover;
  background-position: center;
}
h1 {
  color: #fff !important;
  font-size: 3.5rem !important;
  font-weight: 700 !important;
  letter-spacing: -0.02em !important;
  text-shadow: 0 4px 24px rgba(0,0,0,0.4);
  -webkit-text-fill-color: #fff;
}
h2 {
  color: rgba(100,180,255,0.9) !important;
  font-size: 1.4rem !important;
  font-weight: 400 !important;
  letter-spacing: 0.05em !important;
  -webkit-text-fill-color: rgba(100,180,255,0.9);
}
</style>

---
layout: default
---

# Objectives

<div class="flex justify-center items-center" style="height: calc(100% - 2rem); margin-top: -0.5rem">
  <img src="./objectivespartial.pdf" class="object-contain" style="height: 100%; width: 100%;" />
</div>

---
layout: default
---

# Objectives

<div class="flex justify-center items-center" style="height: calc(100% - 2rem); margin-top: -0.5rem">
  <img src="./objectivesfull.pdf" class="object-contain" style="height: 100%; width: 100%;" />
</div>

---
layout: default
---

# Methodology

<div class="flex justify-center items-center" style="height: calc(100% - 2rem); margin-top: -0.5rem">
  <img src="./methodologyloops.pdf" class="object-contain" style="height: 100%; width: 100%;" />
</div>


---
layout: default
---

# Progress in Numbers — Since January 2026

<div class="text-xs text-gray-500 uppercase tracking-widest mb-3">inference-sim/inference-sim · inference-sim/training</div>

<div class="grid grid-cols-3 gap-4">

  <div class="bg-blue-50 border border-blue-200 rounded-2xl p-4 flex flex-col items-center justify-center text-center">
    <div class="text-5xl font-black text-blue-600">28K+</div>
    <div class="text-sm font-semibold text-gray-700 mt-1">lines of code added</div>
    <div class="text-xs text-gray-500 mt-1">306 commits across both repos</div>
  </div>

  <div class="bg-emerald-50 border border-emerald-200 rounded-2xl p-4 flex flex-col items-center justify-center text-center">
    <div class="text-5xl font-black text-emerald-600">267</div>
    <div class="text-sm font-semibold text-gray-700 mt-1">pull requests merged</div>
    <div class="text-xs text-gray-500 mt-1">inference-sim (266) · training (1)</div>
  </div>

  <div class="bg-indigo-50 border border-indigo-200 rounded-2xl p-4 flex flex-col items-center justify-center text-center">
    <div class="text-5xl font-black text-indigo-600">65</div>
    <div class="text-sm font-semibold text-gray-700 mt-1">hypothesis experiments</div>
    <div class="text-xs text-gray-500 mt-1">strategy evolution · hypothesis-archive</div>
  </div>

  <div class="bg-rose-50 border border-rose-200 rounded-2xl p-4 flex flex-col items-center justify-center text-center">
    <div class="text-3xl font-black text-rose-600">Ongoing</div>
    <div class="text-sm font-semibold text-gray-700 mt-1">sim2real experiments</div>
    <div class="text-xs text-gray-500 mt-1">admission control & routing · vs real llm-d</div>
  </div>

  <div class="bg-amber-50 border border-amber-200 rounded-2xl p-4 col-span-2 flex flex-col justify-center">
    <div class="text-sm font-semibold text-amber-700 mb-2">BLIS in use across 6 teams</div>
    <div class="grid grid-cols-2 gap-x-4 gap-y-1 text-xs text-gray-700">
      <div><span class="text-amber-600 font-semibold">Our team</span> — AI-Native llm-d research</div>
      <div><span class="text-amber-600 font-semibold">Tal / Udi</span> — AI-Native llm-d research</div>
      <div><span class="text-amber-600 font-semibold">India Research Lab</span> (Arun, Pravein, Pavani) — llm-d agentic routing</div>
      <div><span class="text-amber-600 font-semibold">RedHat NeuralNav</span> — synthetic data source</div>
      <div><span class="text-amber-600 font-semibold">Daniel / Nara</span> — llm-d storage research</div>
      <div><span class="text-amber-600 font-semibold">In proposal</span> — llm-d simulation & capacity planning</div>
    </div>
  </div>

</div>

---
layout: default
---

# Outline

<div class="mt-8 space-y-4">
  <div v-for="(item, i) in [
    'A few simulation experiments & findings',
    'llm-d innovation pipeline',
    'Methodology deep dive',
  ]" class="flex items-center gap-4">
    <span class="text-2xl font-light opacity-30 w-6 text-right">{{ i + 1 }}</span>
    <span class="text-lg">{{ item }}</span>
  </div>
</div>

<br />
<br />

> ### If time permits ...

<div class="mt-8 space-y-4">
  <div v-for="(item, i) in [
    'BLIS demo',
    'Strategy evolution demo',
    'The role of Claude & Research LiteLLM service',
  ]" class="flex items-center gap-4">
    <span class="text-2xl font-light opacity-30 w-6 text-right">{{ i + 4 }}</span>
    <span class="text-lg">{{ item }}</span>
  </div>
</div>


---
layout: default
---

# Finding 1 — Disaggregation: One Fix, Two Wins

<div class="text-xs font-mono text-gray-400 mb-1">qwen/qwen3-14b · shared 8-inst vs disagg P:2/D:6 · input=512 output=256 · rate=400 · migration sweep 0–50ms · seeds 42/123/456</div>

<div class="grid grid-cols-3 gap-3 mt-1">

<div class="col-span-1 flex flex-col gap-2">
  <div class="bg-blue-50 rounded-2xl border-2 border-blue-300 p-2 text-center">
    <div class="text-5xl font-black text-blue-600">341×</div>
    <div class="text-sm text-blue-700 font-medium mt-0.5">TTFT P99</div>
    <div class="text-xs text-gray-500">P:2/D:6 vs shared · rate=400</div>
  </div>
  <div class="bg-blue-50 rounded-xl border border-blue-200 p-2 text-center">
    <div class="text-3xl font-black text-blue-500">5.2×</div>
    <div class="text-xs text-blue-700 font-medium">E2E P99 improvement</div>
    <div class="text-xs text-gray-500">decode pool also benefits</div>
  </div>
  <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="font-semibold">Why:</span> Each decode request takes ~256 steps. Shared instances make every new prefill wait. Disagg prefill handles each in one step — zero queue.
  </div>
</div>

<div class="col-span-2 flex flex-col gap-2">

  <div class="grid grid-cols-2 gap-2">
    <div class="bg-amber-50 border border-amber-300 rounded-lg p-2 text-xs text-gray-700">
      <div class="text-amber-700 font-semibold mb-0.5">Surprise: two failure modes, one fix</div>
      Shared instances fail two ways: <strong>HOL blocking</strong> (prefill queues behind decode steps) and <strong>KV cache pressure</strong> (decode accumulates blocks, starving new requests). Prefill-only instances (output=1) are structurally immune to both.
    </div>
    <div class="bg-green-50 border border-green-300 rounded-lg p-2 text-xs text-gray-700">
      <div class="text-green-700 font-semibold mb-0.5">Tolerant of migration cost</div>
      Simulated with up to 50ms migration penalty: E2E degrades only <strong>+2.1%</strong>. Migration latency is tiny relative to decode time (~1.8s for 256 output tokens). Real network cost would need to be extreme to matter.
    </div>
    <div class="bg-indigo-50 border border-indigo-300 rounded-lg p-2 text-xs text-gray-700">
      <div class="text-indigo-700 font-semibold mb-0.5">Benefit kicks in above moderate load</div>
      Rate sweep (50→400 req/s): at low rates, shared and disagg TTFT are comparable. Between rate=100 and rate=200, disaggregation pulls decisively ahead — HOL blocking amplifies non-linearly as load grows.
    </div>
    <div class="bg-rose-50 border border-rose-300 rounded-lg p-2 text-xs text-gray-700">
      <div class="text-rose-700 font-semibold mb-0.5">Surprise: use round-robin for prefill</div>
      Compound routing <em>hurts</em> the prefill pool. Prefill-only requests are uniform work units — RR achieves perfect balance with zero scoring overhead.
    </div>
  </div>

  <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-600">
    <span class="font-semibold text-gray-700">Optimal split:</span> P:2/D:6 outperforms P:4/D:4 — 2 prefill instances have 50× spare capacity at rate=400; the extra instances are better used on decode.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.5rem !important; padding-bottom: 0.5rem !important; }
</style>

---
layout: default
---

# Finding 2 — Scaling is Super-Linear Near Saturation

<div class="text-xs font-mono text-gray-400 mb-1">meta-llama/llama-3.1-8b-instruct · 2/4/8 instances · least-loaded routing · FCFS · always-admit · 500 requests · rate=500 (sat.) / rate=100 (sub-sat.) · seeds 42/123/456</div>

<div class="grid grid-cols-5 gap-6 mt-1">

<div class="col-span-2">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-2">TTFT P99 at saturation (rate = 500, avg 3 seeds)</div>

  | Instances | TTFT P99 (ms) | vs 8-inst |
  |---|---|---|
  | 2 | ~1,786 | 29.9× worse |
  | 4 | ~441 | 7.4× worse |
  | **8** | **~60** | **baseline** |

  <div class="mt-3 text-xs text-gray-500 uppercase tracking-widest mb-1">Sub-saturation control (rate = 100)</div>

  | Comparison | TTFT P99 ratio |
  |---|---|
  | 4 → 8 instances | 1.06× (≈ flat) |

  <div class="mt-3 text-xs text-gray-500">All 18 runs pass INV-1 conservation check</div>
</div>

<div class="col-span-3 flex flex-col justify-center pl-4 border-l-2 border-gray-200">
  <div class="flex items-baseline gap-3 mb-1">
    <span class="text-7xl font-black text-emerald-600">7.4×</span>
    <span class="text-sm text-gray-500">from 2× instances<br/>(predicted: 2×)</span>
  </div>
  <div class="text-xs text-gray-500 mb-4">4 → 8 instances · TTFT P99 · avg across seeds 42, 123, 456</div>

  <div class="bg-emerald-50 border border-emerald-300 rounded-xl p-4 text-sm text-gray-700">
    <span class="text-emerald-700 font-semibold">Why super-linear?</span><br/>
    Excess arrival rate per instance drops <strong>92.5%</strong> (67.6 → 5.1 req/s) when going 4→8. Queue depth — and therefore TTFT — scales with excess rate, not instance count. Near the saturation boundary, adding capacity is disproportionately powerful.
  </div>

  <div class="mt-3 bg-gray-50 border border-gray-200 rounded-lg p-3 text-xs text-gray-600">
    <span class="font-semibold text-gray-800">Key takeaway:</span> At sub-saturation (rate=100), 4→8 instances yields only 1.06× improvement. The benefit is entirely a saturation-boundary effect — capacity planning must account for this non-linearity.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>

---
layout: default
---

# Finding 3 — KV + Scheduling: Super-Additive

<div class="text-xs font-mono text-gray-400 mb-1">meta-llama/llama-3.1-8b-instruct · H100 TP=2 · 4 instances · 300 req/s · multi-turn · SLO mix 20/40/40% · 48 runs · seeds 42/123/456</div>


<div class="grid grid-cols-3 gap-4 mt-1">

<div class="col-span-1 flex flex-col gap-2">
  <div class="bg-teal-50 rounded-2xl border-2 border-teal-300 p-3 text-center">
    <div class="text-5xl font-black text-teal-600">5.8×</div>
    <div class="text-sm text-teal-700 font-medium mt-1">critical TTFT P99</div>
    <div class="text-xs text-gray-500">joint vs baseline · KV=1,500</div>
  </div>
  <div class="bg-amber-50 border border-amber-300 rounded-xl p-2 text-center">
    <div class="text-2xl font-black text-amber-600">180ms → 4ms</div>
    <div class="text-xs text-gray-600 mt-0.5">latency variance (σ) collapses<br/>more predictable, not just faster</div>
  </div>
  <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-600 text-center">
    Throughput cost: <strong>−0.5%</strong><br/>Essentially free.
  </div>
</div>

<div class="col-span-2 pl-4 border-l-2 border-gray-200 flex flex-col gap-2">
  <div class="grid grid-cols-2 gap-2">
    <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
      <span class="font-semibold text-gray-800">Elastic batching</span><br/>
      Preempts low-priority running requests to make batch slots for critical ones. Protects SLO at the <em>scheduling layer</em>.
    </div>
    <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
      <span class="font-semibold text-gray-800">SLO-aware KV eviction</span><br/>
      Under KV pressure, evicts sheddable requests' memory blocks first — freeing cache space for critical ones. Protects SLO at the <em>storage layer</em>.
    </div>
  </div>

  <div class="text-xs text-gray-500 uppercase tracking-widest">Critical TTFT P99 (ms) · mean 3 seeds · KV = 1,500 blocks</div>

  | Mechanism | Critical TTFT P99 | vs Baseline |
  |---|---|---|
  | Baseline | 464.0 ms | — |
  | KV-aware eviction only | 343.4 ms | 1.35× better |
  | Elastic batching only | 401.0 ms | 1.15× better |
  | **Both together (JOINT)** | **80.0 ms** | **5.8× better** |

  <div class="bg-teal-50 border border-teal-200 rounded-xl p-2 text-xs text-gray-700">
    <span class="text-teal-700 font-semibold">Why super-additive?</span> At moderate KV pressure both layers unblock simultaneously — the joint effect is multiplicative, not additive. At abundant or extreme KV, the mechanisms decouple and interaction drops to 1.0×.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>


---
layout: default
---

# Finding 4 — KV Cache Has a Hard Cliff, Not a Slope

<div class="text-xs font-mono text-gray-400 mb-1">llama-3.1-8b · 4 instances · rate=2000 · 200 requests · Gaussian input μ=512 σ=50, output μ=256 σ=50 · block_size=16 · round-robin · FCFS · seeds 42/123/456</div>

<div class="grid grid-cols-5 gap-6 mt-1">

<div class="col-span-3">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-2">Seed 42 · 4 instances · rate = 2000</div>

  | KV Blocks | Preempt Rate | TTFT P99 (ms) | E2E P99 (ms) |
  |---|---|---|---|
  | 5,000 | 0% | 474 | 3,609 |
  | 3,000 | 0% | 474 | 3,609 |
  | **2,200** | **0%** | **474** | **3,609** |
  | **2,100** | **17.5%** | **2,305** | **6,194** |
  | 2,000 | 59.5% | 2,860 | 7,072 |

  <div class="mt-2 text-xs text-gray-500">Seeds 123 & 456 confirm same cliff location. All 15 configs pass INV-1 conservation. Monotonicity holds across all 3 seeds.</div>

  <div class="mt-3 bg-red-50 border border-red-200 rounded-lg p-3 text-xs text-gray-700">
    <span class="text-red-700 font-semibold">Livelock warning:</span> blocks &lt; 1,000 cause simulation livelock — the cascade prevents forward progress entirely.
  </div>
</div>

<div class="col-span-2 flex flex-col justify-center pl-4 border-l-2 border-gray-200">
  <div class="text-center mb-4">
    <div class="text-6xl font-black text-red-600">4.87×</div>
    <div class="text-sm text-gray-600 mt-1">TTFT P99 degradation<br/>crossing 100-block boundary</div>
    <div class="text-xs text-gray-500 mt-1">474ms → 2,305ms</div>
  </div>

  <div class="bg-red-50 border border-red-300 rounded-xl p-4 text-sm text-gray-700">
    <span class="text-red-700 font-semibold">Why binary?</span><br/>
    <span class="text-xs">Once peak concurrent KV demand exceeds capacity, <code>preempt()</code> evicts running requests and requeues them at <code>ProgressIndex=0</code> — forcing full re-prefill. Each re-prefill consumes blocks again, triggering a cascade. Below the threshold, execution path is identical regardless of extra blocks.</span>
  </div>

  <div class="mt-3 text-xs text-gray-500 text-center">
    Implication: capacity planning requires a safety margin <em>above</em> the cliff — gradual degradation models do not apply here.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>

---
layout: default
---

# Finding 5 — Compound Strategy: Each Lever Has a Job

<div class="text-xs font-mono text-gray-400 mb-1">meta-llama/llama-3.1-8b-instruct · H100 TP=2 · 4 instances · rate=300 (120% capacity) · 1500 requests · SLO mix 20/40/40% · maxRunningReqs=32 · seeds 42/123/456</div>

<div class="grid grid-cols-5 gap-6 mt-1">

<div class="col-span-3">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-3">Critical-class TTFT P99 reduction vs baseline · 120% load · 3 seeds</div>

  <div class="space-y-3 mt-3">
    <div>
      <div class="flex justify-between text-sm mb-1">
        <span class="text-gray-700">T2 — Admission only</span>
        <span class="text-yellow-700 font-bold">10.9%</span>
      </div>
      <div class="bg-gray-200 rounded-full h-4">
        <div class="bg-yellow-400 h-4 rounded-full" style="width: 31%"></div>
      </div>
    </div>
    <div>
      <div class="flex justify-between text-sm mb-1">
        <span class="text-gray-700">T3 — Preemption only</span>
        <span class="text-orange-700 font-bold">29.3%</span>
      </div>
      <div class="bg-gray-200 rounded-full h-4">
        <div class="bg-orange-400 h-4 rounded-full" style="width: 82%"></div>
      </div>
    </div>
    <div>
      <div class="flex justify-between text-sm mb-1">
        <span class="text-gray-800 font-semibold">T4 — Compound (admission + routing + preemption)</span>
        <span class="text-red-700 font-black">35.5%</span>
      </div>
      <div class="bg-gray-200 rounded-full h-4">
        <div class="bg-red-500 h-4 rounded-full" style="width: 100%"></div>
      </div>
    </div>
  </div>

  <div class="mt-4 text-xs text-gray-500">
    Control T4-uniform (uniform SLO, no class differential): &lt;2% vs baseline — confirms mechanisms are inert without class structure
  </div>
</div>

<div class="col-span-2 flex flex-col gap-2 pl-4 border-l-2 border-gray-200">
  <div class="bg-yellow-50 border border-yellow-300 rounded-xl p-3 text-sm">
    <div class="text-yellow-700 font-semibold mb-1">Admission → cluster health</div>
    <div class="text-gray-700 text-xs">SLO-gated rejection sheds low-priority load before it enters the system. Best cluster-wide P99 in 3/3 seeds. Does not directly protect the critical class.</div>
  </div>
  <div class="bg-blue-50 border border-blue-300 rounded-xl p-3 text-sm">
    <div class="text-blue-700 font-semibold mb-1">Routing → cache efficiency</div>
    <div class="text-gray-700 text-xs">Weighted scoring (<code>prefix-affinity:3, queue-depth:2</code>) steers requests toward instances with cached prefixes while avoiding overloaded ones — reducing effective input tokens and queue depth simultaneously.</div>
  </div>
  <div class="bg-orange-50 border border-orange-300 rounded-xl p-3 text-sm">
    <div class="text-orange-700 font-semibold mb-1">Preemption → per-class SLO</div>
    <div class="text-gray-700 text-xs">Directly moves critical requests from queue to batch. Dominant lever for critical P99. Fires 103–118× per run under realistic batch pressure (<code>maxRunningReqs=32</code>).</div>
  </div>
  <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-600">
    Super-additivity is conditional (2/3 seeds). Mechanisms partially substitute when both are strong independently.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>


---
layout: default
---

# Finding 6 — 1% Queue-Depth Weight, 512% Gain

<div class="text-xs font-mono text-gray-400 mb-1">llama-3.1-8b-instruct · 4 instances · prefix-group workload · weighted routing · 200 requests · seeds 42/123/456 · control: no-prefix workload (unique requests)</div>

<div class="grid grid-cols-5 gap-4 mt-1">

<div class="col-span-3">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-1">Config A (100:1 prefix:queue) vs Config B (pure prefix-affinity) · prefix workload</div>

  | Seed | TTFT Mean — B worse by | TTFT P99 — B worse by |
  |---|---|---|
  | 42 | **+512.5%** | +429.9% |
  | 123 | +271.7% | +379.9% |
  | 456 | +481.1% | +485.7% |

  <div class="text-xs text-gray-500 mt-1 mb-2">Config B routes all 200 requests to a single instance (Jain fairness: 0.250). Config A distributes across all 4 (Jain: 0.383).</div>

  <div class="bg-amber-50 border border-amber-200 rounded-lg p-2 text-xs text-gray-700 mb-2">
    <span class="text-amber-700 font-semibold">Binary mechanism (Control A3a):</span> Weights 100:1 and 100:0.001 are byte-identical — the tiebreaker is present-vs-absent, not magnitude-dependent. Any positive queue-depth weight delivers the full benefit.
  </div>
  <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-amber-700 font-semibold">Control A3b:</span> Without prefix sharing, D1 (100:1) achieves near-perfect balance (Jain 0.998) vs D2 all-to-one (Jain 0.250) — queue-depth is the sole signal when prefix scores are zero.
  </div>
</div>

<div class="col-span-2 flex flex-col justify-center pl-4 border-l-2 border-gray-200 gap-2">
  <div class="text-center">
    <div class="text-5xl font-black text-amber-600">512%</div>
    <div class="text-sm text-gray-600 mt-1 font-medium">TTFT improvement from<br/>adding 1% queue-depth weight</div>
    <div class="text-xs text-gray-500">seed 42 · mean latency</div>
  </div>
  <div class="bg-amber-50 border border-amber-300 rounded-xl p-2 text-xs text-gray-700">
    <span class="text-amber-700 font-semibold">Implication:</span> Pure prefix-affinity is a degenerate scorer under load — it collapses all traffic onto a single instance. A tiny orthogonal signal is not a tuning knob; it is a <em>liveness requirement</em>.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>

---
layout: default
---

# llm-d Innovation Pipeline

<div class="flex justify-center items-center" style="height: calc(100% - 2.5rem)">
  <img src="./llmdinnovationpipeline.pdf" class="object-contain" style="max-height: 100%; max-width: 100%;" />
</div>

---
layout: default
---

# Methodology — Strategy Evolution

<div class="grid grid-cols-2 gap-6 mt-2">

<div>
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-2 text-center">5 hypothesis arms</div>
  <div class="flex justify-center items-center">
    <img src="./hypothesisbundle.png" class="object-contain" style="height: 443px; max-width: 100%;" />
  </div>
</div>

<div>
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-2 text-center">5-phase discovery loop</div>
  <div class="flex justify-center items-center">
    <img src="./fivephasediscovery.png" class="object-contain" style="height: 443px; max-width: 100%;" />
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>

---
layout: default
---

# From Optimization to Discovery

<div class="mt-1">
<div class="text-xs text-gray-500 uppercase tracking-widest mb-1">Strategy Evolution vs. fitness-based search (SkyDiscover · OpenEvolve · GEPA)</div>

<table class="w-full text-xs border-collapse">
  <thead>
    <tr class="border-b-2 border-gray-300">
      <th class="text-left py-0.5 pr-4 text-gray-500 font-semibold w-1/4">Dimension</th>
      <th class="text-left py-0.5 pr-4 text-gray-600 font-semibold w-5/12">SkyDiscover / OpenEvolve / GEPA</th>
      <th class="text-left py-0.5 text-indigo-700 font-semibold w-5/12">Strategy Evolution</th>
    </tr>
  </thead>
  <tbody class="divide-y divide-gray-100">
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Primary signal</td>
      <td class="py-0.5 pr-4 text-gray-600">Fitness score — did the metric improve?</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">Prediction error</span> — did the mechanism behave as theorized?</td>
    </tr>
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Hypothesis structure</td>
      <td class="py-0.5 pr-4 text-gray-600">None — search over mutation space</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">5 arms</span> pre-committed before implementation; ablations designed upfront</td>
    </tr>
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Failure value</td>
      <td class="py-0.5 pr-4 text-gray-600">Discarded — variant pruned from population</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">High signal</span> — refutation reveals causal model gaps, directs redesign</td>
    </tr>
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Tool use</td>
      <td class="py-0.5 pr-4 text-gray-600">Mutation + evaluation only</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">Agentic</span> — parallel agents, Bayesian optimizer, LLM judges, principles ledger</td>
    </tr>
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Durable output</td>
      <td class="py-0.5 pr-4 text-gray-600">Best configuration found</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">Principles catalog</span> — evidence-backed design rules valid across regime shifts</td>
    </tr>
    <tr>
      <td class="py-0.5 pr-4 font-medium text-gray-700">Goal</td>
      <td class="py-0.5 pr-4 text-gray-600">Optimization</td>
      <td class="py-0.5 text-gray-800"><span class="text-indigo-700 font-semibold">Scientific discovery</span> — understand <em>why</em> mechanisms work, enabling transfer</td>
    </tr>
  </tbody>
</table>

</div>

<style scoped>
.slidev-layout { padding-top: 0.25rem !important; padding-bottom: 0.25rem !important; }
</style>


---
layout: default
---

# Methodology — Hypotheses & Agentic Toolchain

<div class="grid grid-cols-2 gap-5 mt-2">

<div>
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-2">Each arm requires three elements</div>
  <div class="space-y-2">
    <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
      <span class="font-semibold text-gray-900">Quantitative prediction</span> — specific metric + falsifiable threshold (e.g., "&gt;30% TTFT P99 reduction"). No vague claims.
    </div>
    <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
      <span class="font-semibold text-gray-900">Causal mechanism</span> — explicit explanation of <em>why</em> the prediction holds. Forces reasoning before running.
    </div>
    <div class="bg-gray-50 border border-gray-200 rounded-lg p-2 text-xs text-gray-700">
      <span class="font-semibold text-gray-900">Diagnostic clause</span> — "if this fails, it indicates…" directs investigation when outcomes diverge.
    </div>
  </div>
  <div class="mt-3 text-xs text-gray-500 uppercase tracking-widest mb-1">Outcome classification</div>
  <div class="flex gap-2 mb-1">
    <span class="bg-green-100 text-green-700 border border-green-300 rounded px-2 py-1 text-xs font-semibold">Confirmed</span>
    <span class="bg-yellow-100 text-yellow-700 border border-yellow-300 rounded px-2 py-1 text-xs font-semibold">Partial</span>
    <span class="bg-red-100 text-red-700 border border-red-300 rounded px-2 py-1 text-xs font-semibold">Refuted</span>
  </div>
  <div class="text-xs text-gray-500">Refuted arms diagnose: <strong>direction wrong</strong> → mechanism misunderstood · <strong>magnitude wrong</strong> → strength model off · <strong>regime wrong</strong> → conditional applicability</div>
</div>

<div class="flex flex-col gap-2">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-1">Agentic toolchain </div>
  <div class="bg-indigo-50 border border-indigo-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-indigo-700 font-semibold">Multi-LLM design review</span> — Claude Opus, GPT-4o, and Gemini review candidates independently before a line of code is written.
  </div>
  <div class="bg-indigo-50 border border-indigo-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-indigo-700 font-semibold">Convergence-gated verification</span> — Design (5 perspectives) → Code (5) → Findings (10). Each gate must converge before advancing.
  </div>
  <div class="bg-indigo-50 border border-indigo-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-indigo-700 font-semibold">Parallel arm execution</span> — all 5 arms run across 3+ seeds simultaneously via dispatched agents.
  </div>
  <div class="bg-indigo-50 border border-indigo-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-indigo-700 font-semibold">Bayesian optimization</span> — <code>gp_minimize</code> tunes parameters automatically once H-main is confirmed.
  </div>
  <div class="bg-indigo-50 border border-indigo-200 rounded-lg p-2 text-xs text-gray-700">
    <span class="text-indigo-700 font-semibold">Principles ledger</span> — never-delete log of prediction accuracy. Durable output is the principles catalog, not any single configuration.
  </div>
</div>

</div>

---
layout: default
---

# The Role of Claude & LiteLLM

<div class="grid grid-cols-2 gap-5 mt-3">

<div class="flex flex-col gap-3">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-1">Claude</div>

  <div class="bg-orange-50 border border-orange-200 rounded-lg p-3 text-xs text-gray-700">
    <div class="text-orange-700 font-semibold mb-1">Development environment</div>
    All BLIS engineering — code, tests, PRs, branch management — runs inside Claude Code.
  </div>

  <div class="bg-orange-50 border border-orange-200 rounded-lg p-3 text-xs text-gray-700">
    <div class="text-orange-700 font-semibold mb-1">Agentic discovery loop</div>
    Strategy Evolution runs as Claude Code plugins: parallel arm dispatch, convergence gates, Bayesian optimization, principles ledger.
  </div>

</div>

<div class="flex flex-col gap-3">
  <div class="text-xs text-gray-500 uppercase tracking-widest mb-1">LiteLLM</div>

  <div class="bg-violet-50 border border-violet-200 rounded-lg p-3 text-xs text-gray-700">
    <div class="text-violet-700 font-semibold mb-1">Unified model access</div>
    Single OpenAI-compatible API across Claude Opus, GPT-4o, and Gemini 2.5 Flash — the three judges in every convergence review.
  </div>

  <div class="bg-violet-50 border border-violet-200 rounded-lg p-3 text-xs text-gray-700">
    <div class="text-violet-700 font-semibold mb-1">Enforces judge independence</div>
    Each model sees the same prompt with no visibility into other responses — preventing consensus bias.
  </div>

  <div class="bg-violet-50 border border-violet-200 rounded-lg p-3 text-xs text-gray-700">
    <div class="text-violet-700 font-semibold mb-1">Glue in the agentic loop</div>
    Sits between Claude Code and every non-Claude call — retry, load balancing, cost tracking — so the pipeline scales as the model roster grows.
  </div>
</div>

</div>

<style scoped>
.slidev-layout { padding-top: 0.75rem !important; padding-bottom: 0.75rem !important; }
</style>

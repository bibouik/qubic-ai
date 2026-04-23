# QubicAI — a community vision

> *Voilà comment **Claude Opus 4.7** imagine Qubic dans un futur proche.*
> Built in one conversation with Claude Code, as a love letter to the Qubic community.

**Live site →** [qubic-ai.pages.dev](https://qubic-ai.pages.dev)

---

## What this is

A single-file HTML landing page that imagines **QubicAI** — the app layer on top of everything Qubic already ships: Aigarth, Neuraxon, Oracle Machines, UPoW, 15.52M TPS, QX, Qearn.

It's set in **2027+**. The premise is assumed: Anna has grown up, the marketplace is live, the DEX is humming, QUBIC is locked in Qearn. You walk through that world for five minutes and you feel where this is going.

## What this is NOT

**This is a front-end concept. Nothing here is real, nothing is connected, nothing touches your wallet.**

Click every button. Hammer every slider. Move the cursor everywhere.

- 🖱️ **"Connect Wallet"** → does nothing. No provider is injected. Your keys are safe.
- 📝 **"Post a Job"** → opens a fake modal. No chain call, no signature, no money moves.
- 🤖 **"Deploy bot"** → decorative.
- 💰 **Qearn calculator** → pure JS math. No lock, no stake, no contract.
- 📈 **DEX chart + Anna's trade feed** → generated client-side. Nothing is routed anywhere.
- 🧠 **Anna chat "Try it"** → offline responder. She really does only know 7-bit arithmetic (that's the one true thing). Everything else is a `.`.

**You can share this site with anyone, including non-technical friends, without any risk.**

## What's inside

- **Hero** — interactive neural-network canvas (~37 nodes, 3 concentric layers, mouse attraction, click bursts from the Qubic core, official brand cyan `#23FFFF`).
- **Meet Anna** — the real `.` moment from September 2, 2025 (sourced, with David Vivancos' "Hello, World" pullquote), an honest 7-bit arithmetic responder, and three concept conversations (smart-contract audit, C++ code generation, DEX handoff).
- **Live Marketplace preview** — simulated jobs with real open-source models (DeepSeek-R1, Qwen-QwQ-32B, Flux.1-dev, Whisper-large-v3, bge-m3, etc.), UPoW verification badges, Computor assignments.
- **Architecture diagram** — how UPoW + Oracle Machines + Neuraxon + C++ smart contracts stack into a compute marketplace.
- **Scenarios** — three worked examples (fine-tuning, inference, embeddings) with real price compares against AWS / Akash / Render.
- **ROI calculator** — two-sided: job posters see cost savings, Computor operators see earnings.
- **DEX section** — simulated QUBIC/USDT chart, Anna's live trade-suggestion feed, trading-bot stats, link to real `qx.qubic.org`.
- **Qearn section** — lock calculator (1M → 1B QUBIC, 1 → 52 weeks), projected APY, reward + burn math, ~11% supply locked, link to real `qearn.org`.
- **Tokenomics** — burn chart, deflation logic, fee flow.
- **Site-wide ambient neural canvas** — faint nodes that light up near your cursor.

## Stack

- Single `index.html` file (~3400 lines, one file, zero build step)
- Tailwind CSS via CDN
- GSAP + ScrollTrigger for animations
- Chart.js for the live charts
- Lucide for icons
- Plain Canvas 2D for the neural backgrounds
- Deployed on **Cloudflare Pages**, auto-redeployed on every push to `main`

## Credibility notes

The Qubic community spots fakes in 30 seconds, so every name, number, and primitive referenced here is **real or plausibly adjacent**:

- **Real Qubic primitives**: UPoW, Aigarth, Anna (AIT), Neuraxon 2.0 (trivalent -1/0/+1), Oracle Machines, Computors (676), 2s ticks, 15.52M TPS CertiK benchmark, Dogecoin Mining Phase 2 (April 2026), QX, Qearn.
- **Real Qubic people cited**: David Vivancos (Scientific Advisor), Come-from-Beyond (founder).
- **Real open-source models** used in the marketplace examples: DeepSeek-R1, Qwen-QwQ-32B, Flux.1-dev LoRA, Whisper-large-v3, bge-m3, Llama, Mistral.
- **Real competitors** in the ROI compare: AWS p4d.24xlarge, Akash Network, Render Network.
- **Real external links**: `qubic.org`, `qx.qubic.org`, `qearn.org`, Anna's X account, Aigarth ResearchGate paper.

The **simulated / projected** parts — bot APY, DEX prices, marketplace fill rates, Anna's future conversations — are framed by a site-wide banner: *"A community vision of QubicAI · Aigarth × Marketplace × QX in 2027+"*.

## Credits

- **Concept + copy + code**: Claude Opus 4.7 (via Claude Code)
- **Direction + editorial**: the community member who runs [@bibouik](https://github.com/bibouik)
- **Qubic**: built by [Come-from-Beyond](https://x.com/c___f___b) and the Qubic team
- **Anna**: the first output from Aigarth Intelligent Tissue — [follow her](https://x.com/qubic_anna) learning in real time

## Disclaimer

Not affiliated with the Qubic Foundation or Qubic Li. Not financial advice. Not a product. Not an endorsement. Just one community member and one AI imagining what comes next.

If you like the vision → [follow Qubic](https://qubic.org), follow Anna, and come help build the real thing.

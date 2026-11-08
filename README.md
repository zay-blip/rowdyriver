# Rowdy River — AI Machine Room Console
Interactive training game for a young engineer learning server racks and AI training systems. Live at https://rowdyriver.wtf
## What's inside
- **Steel Rack** — live floor sim: pump RPM and coolant setpoint genuinely drive rack temps, real 83°C throttle point, ~1,000 W per GPU, chilled-water boost, and an emergency stop that cuts cooling too.
- **Training Lab** — real training loop: forward pass, loss, backward pass, optimizer step, live loss curve. Learning rate, batch size, GPU count, and precision controls, with a genuine divergence cliff at high learning rates and NCCL all-reduce overhead.
- **Agent Loop** — the ReAct pattern (Perceive → Reason → Tool dispatch → Reflect → Commit) with failure injection: a tool call fails, the agent reflects, retries, and recovers.
- **Next-Word** — true softmax math: temperature scaling, top-K, top-P sampling.
- **SIREN** — real sin(ω₀x) waveform math with a Web Audio siren.
- **Operator Missions** — 4 scored missions, 400 points, plus a "Real Numbers" reference card.
Single self-contained HTML file — no build step, no server, works offline once loaded.

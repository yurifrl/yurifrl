<div align="center">

# Hey, I'm Yuri 👋

**Staff Platform Engineer** — Kubernetes, AI Agents, Developer Tooling

15 years building the infrastructure that production systems and AI agents run on • Brazil

[![Site](https://img.shields.io/badge/yurifrl.dev-000?style=for-the-badge&logo=jekyll&logoColor=white)](https://yurifrl.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yurifrl)

</div>

---

### 👨‍💻 What I Do

I build platforms: Kubernetes, GitOps, and the gateways and control planes that AI agents run behind. Currently **tech lead of the SRE team @ [Flutter Brazil](https://github.com/NSXBet)**, where I built the internal AI agent platform and the gateway behind every LLM call in the company.

What I enjoy most is developer tooling: CLIs, coding-agent extensions, plugins and skills that make a workflow shorter. Most of what's below started as something I wanted for myself.

### 🏠 The Homelab

My home cluster is run like production, and it's all public in **[home-systems](https://github.com/yurifrl/home-systems)**:

- 7 Talos Linux nodes plus an offsite Raspberry Pi that joins over Tailscale
- 63 ArgoCD applications behind an Istio ambient mesh, with SLOs as code (Pyrra)
- Crossplane provisioning Proxmox VMs and GCP resources; secrets from 1Password via External Secrets, none in git
- **[21 written postmortems](https://github.com/yurifrl/home-systems/tree/HEAD/.agents/postmortems)**, from an apiserver CRD-cache OOM to a Tailscale/Cilium endpoint recursion. Yes, for a homelab.

### 🚀 Projects

- 🏠 **[home-systems](https://github.com/yurifrl/home-systems)** — GitOps repo for the cluster above: Talos, ArgoCD, Istio, Crossplane, VictoriaMetrics, Longhorn.
- ⛵ **[nostos](https://github.com/yurifrl/nostos)** — Go CLI (Charm TUI) that owns the bare-metal-to-cluster flow for Talos home labs: PXE boot, flashable images for zero-touch remote nodes, Talos or Proxmox installs.
- ❄️ **[nixos](https://github.com/yurifrl/nixos)** — One flake for my NixOS machines: a Proxmox workstation VM that rebuilds itself, a FoundryVTT server and a Gatus status page, with Terraform, Tailscale and Cloudflare tunnels.
- ⌨️ **[alt-tab](https://github.com/yurifrl/alt-tab)** — Keyboard-driven macOS window switcher in Swift: search, per-window color tags, multi-display. Signed, notarized and shipped through my own [Homebrew tap](https://github.com/yurifrl/homebrew-casks).
- 🔌 **[Tennon](https://github.com/yurifrl/tennon)** — Kubernetes-native control plane and proxy for MCP servers. Credentials are injected server-side, so agents never hold a secret.
- 🎙️ **[MicSync](https://github.com/yurifrl/MicSync)** — Menu-bar app that keeps one mic state across Google Meet and Slack huddles. Push-to-talk works from a gamepad or a phone.
- 🧰 **[cly](https://github.com/yurifrl/cly)** — Go CLI of day-to-day utilities with Charm TUIs, including a Claude Code statusline.
- 🏙️ **[city-game](https://github.com/yurifrl/city-game)** — Cooperative city simulation delivered as a video stream: one Rust server simulates, renders (wgpu) and encodes; the browser only plays video and sends input.
- 🧩 **[pi-hub](https://github.com/yurifrl/pi-hub)** · **[claude-plugins](https://github.com/yurifrl/claude-plugins)** — Supervision board for running coding agents, and Claude Code plugins written as TypeScript hook modules.

### 🛠️ Stack

```
Platform            │  Kubernetes · Talos · ArgoCD · Crossplane · Helm · Istio · Cilium
Languages           │  Go · TypeScript · Python · Swift · Rust · Nix
AI & Agents         │  MCP · Claude Code · LangGraph · LLM Gateways · AWS Bedrock
Cloud & IaC         │  AWS (EKS) · GCP · Terraform · NixOS · Proxmox
Observability       │  Prometheus · VictoriaMetrics · Grafana · OpenTelemetry · SLOs
```

### 🧠 Interests

LLM Agents • Developer Experience • Homelabs • Distributed Systems • Tabletop RPGs • Board Games

### 📝 Site

Résumé, posts and cheat sheets live at **[yurifrl.dev](https://yurifrl.dev)**

<div align="center">
  <br>
  <img src="https://github-readme-stats.vercel.app/api?username=yurifrl&show_icons=true&theme=dracula&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yurifrl&layout=compact&theme=dracula&hide_border=true&hide=html,css" height="150" />
</div>

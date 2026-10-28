<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0d1117,50:1f6feb,100:00d4aa&text=Guillaume%20Legrain&fontColor=ffffff&fontSize=46&fontAlignY=35&desc=Cybersecurity%20Platform%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" alt="Guillaume Legrain — Cybersecurity Platform Engineer" />

**Securing Kubernetes platforms by default — zero-trust networking, dynamic secrets, observability that wakes the right people.**

[![Numberly](https://img.shields.io/badge/SRE-%40numberly-1f6feb?style=flat-square&logo=github)](https://github.com/numberly)
[![Cloud Native Days France 2026](https://img.shields.io/badge/Speaker-Cloud%20Native%20Days%20France%202026-00d4aa?style=flat-square&logo=cncf&logoColor=white)](https://github.com/SoulKyu/vault-db-injector-cnd)
![Location](https://img.shields.io/badge/Ch%C3%A2teauroux-France-0d1117?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

### 🛡️ What I do

- **Zero-trust networking** — default-deny clusters with Cilium & Hubble, policies generated from real traffic, shipped through GitOps
- **Secrets that expire** — short-lived, per-pod database credentials from Vault / OpenBao, revoked when the pod dies
- **Hardened by default** — least privilege, admission webhooks, sandboxed workloads, auditable by design
- **Observability & incident response** — Prometheus / Alertmanager at scale, alerting the whole team actually uses
- **Secure AI agents for ops** — sandboxed SRE agents with default-deny egress and prompt-injection guardrails

---

### 🚀 Featured projects

<table>
<tr>
<td width="33%" valign="top">

#### 🔐 [vault-db-injector](https://github.com/numberly/vault-db-injector)

[![Stars](https://img.shields.io/github/stars/numberly/vault-db-injector?style=flat-square&color=1f6feb)](https://github.com/numberly/vault-db-injector/stargazers)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)

Kubernetes mutating webhook that injects **dynamic, short-lived database credentials** from Vault into pods — renewal and revocation handled for you. No more static passwords.

[Docs](https://numberly.github.io/vault-db-injector) · [CND France talk](https://github.com/SoulKyu/vault-db-injector-cnd)

</td>
<td width="33%" valign="top">

#### 🕸️ [cpg](https://github.com/SoulKyu/cpg)

[![Stars](https://img.shields.io/github/stars/SoulKyu/cpg?style=flat-square&color=1f6feb)](https://github.com/SoulKyu/cpg/stargazers)
[![Release](https://img.shields.io/github/v/release/SoulKyu/cpg?style=flat-square&color=00d4aa)](https://github.com/SoulKyu/cpg/releases)
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=flat-square&logo=cilium&logoColor=black)

**Cilium Policy Generator** — streams dropped flows from Hubble Relay and writes the `CiliumNetworkPolicy` that allows them. Default-deny without the pain.

`kubectl krew install cilium-policy-gen`

</td>
<td width="33%" valign="top">

#### 🔔 [notificator](https://github.com/SoulKyu/notificator)

[![Stars](https://img.shields.io/github/stars/SoulKyu/notificator?style=flat-square&color=1f6feb)](https://github.com/SoulKyu/notificator/stargazers)
[![Release](https://img.shields.io/github/v/release/SoulKyu/notificator?style=flat-square&color=00d4aa)](https://github.com/SoulKyu/notificator/releases)
![Prometheus](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Karma replacement** — one UI for all your Alertmanagers, with sounds, desktop notifications, acks, comments and OAuth.

[▶ Live playground](https://playground.notificator.org)

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

- 🤖 [**leandro**](https://github.com/SoulKyu/leandro) — AI SRE agent diagnosing Kubernetes incidents, security-first sandbox (NixOS VM, default-deny egress, tool denylist against prompt injection)
- 📚 [**openwiki-cc**](https://github.com/SoulKyu/openwiki-cc) — auto-generated, git-grounded documentation wiki for any repo (Claude Code plugin & Codex skill)
- 🧠 [**pi-agentic-platform**](https://github.com/SoulKyu/pi-agentic-platform) — self-hosted agentic platform on the Pi SDK

</details>

---

### 🧰 Stack

<div align="center">

**Security & secrets**<br/>
<img src="https://img.shields.io/badge/HashiCorp%20Vault-000000?style=for-the-badge&logo=vault&logoColor=FFEC6E" />
<img src="https://img.shields.io/badge/OpenBao-2b2b2b?style=for-the-badge&logo=vault&logoColor=white" />
<img src="https://img.shields.io/badge/Cilium-F8C517?style=for-the-badge&logo=cilium&logoColor=black" />
<img src="https://img.shields.io/badge/eBPF-FF6600?style=for-the-badge" />

**Platform**<br/>
<img src="https://skillicons.dev/icons?i=kubernetes,docker,terraform,ansible,nix,linux&theme=dark" />

**Observability**<br/>
<img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" />

**Code**<br/>
<img src="https://skillicons.dev/icons?i=go,python,ts,bash&theme=dark" />

</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SoulKyu&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SoulKyu&layout=compact&hide_border=true&theme=github_dark&langs_count=6" height="165" alt="Top languages" />

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:00d4aa,50:1f6feb,100:0d1117&section=footer" />

</div>

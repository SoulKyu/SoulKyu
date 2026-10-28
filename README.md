<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0d1117,50:1f6feb,100:00d4aa&text=Guillaume%20Legrain&fontColor=ffffff&fontSize=46&fontAlignY=35&desc=Cybersecurity%20Platform%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" alt="Guillaume Legrain, Cybersecurity Platform Engineer" />

**I build Kubernetes platforms where the network is default-deny, database credentials expire on their own, and alerts from every Alertmanager land in one place.**

[![Numberly](https://img.shields.io/badge/SRE-%40numberly-1f6feb?style=flat-square&logo=github)](https://github.com/numberly)
[![Cloud Native Days France 2026](https://img.shields.io/badge/Speaker-Cloud%20Native%20Days%20France%202026-00d4aa?style=flat-square&logo=cncf&logoColor=white)](https://github.com/SoulKyu/vault-db-injector-cnd)
![Location](https://img.shields.io/badge/Ch%C3%A2teauroux-France-0d1117?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

### What I do

Mostly Go, mostly Kubernetes.

- Default-deny clusters on Cilium, with policies generated from dropped Hubble flows and shipped through GitOps
- Per-pod database credentials from Vault or OpenBao instead of static passwords
- Prometheus and Alertmanager, and the UI on top of them
- Sandboxed AI agents for ops: NixOS VM, no egress by default, tool denylist against prompt injection

---

### Featured projects

<table>
<tr>
<td width="33%" valign="top">

#### [vault-db-injector](https://github.com/numberly/vault-db-injector)

[![Stars](https://img.shields.io/github/stars/numberly/vault-db-injector?style=flat-square&color=1f6feb)](https://github.com/numberly/vault-db-injector/stargazers)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)

Kubernetes mutating webhook: each pod gets its own short-lived database credentials from Vault instead of a static password, renewed while the pod runs and revoked when it dies.

[Docs](https://numberly.github.io/vault-db-injector) · [CND France 2026 demo](https://github.com/SoulKyu/vault-db-injector-cnd)

</td>
<td width="33%" valign="top">

#### [cpg](https://github.com/SoulKyu/cpg)

[![Stars](https://img.shields.io/github/stars/SoulKyu/cpg?style=flat-square&color=1f6feb)](https://github.com/SoulKyu/cpg/stargazers)
[![Release](https://img.shields.io/github/v/release/SoulKyu/cpg?style=flat-square&color=00d4aa)](https://github.com/SoulKyu/cpg/releases)
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=flat-square&logo=cilium&logoColor=black)

Cilium Policy Generator. It streams dropped flows from Hubble Relay and writes the `CiliumNetworkPolicy` that allows them, merged into your existing YAML for you to review and push. Writing policies by hand in a default-deny cluster is nobody's idea of a good Friday night.

`kubectl krew install cilium-policy-gen`

</td>
<td width="33%" valign="top">

#### [notificator](https://github.com/SoulKyu/notificator)

[![Stars](https://img.shields.io/github/stars/SoulKyu/notificator?style=flat-square&color=1f6feb)](https://github.com/SoulKyu/notificator/stargazers)
[![Release](https://img.shields.io/github/v/release/SoulKyu/notificator?style=flat-square&color=00d4aa)](https://github.com/SoulKyu/notificator/releases)
![Prometheus](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white)

A Karma replacement: one web UI for all your Alertmanagers, with sounds, notifications, acks, comments, assignments and OAuth.

[▶ Live playground](https://playground.notificator.org)

</td>
</tr>
</table>

<details>
<summary>More projects</summary>

- [leandro](https://github.com/SoulKyu/leandro): AI SRE agent diagnosing Kubernetes incidents over Google Chat. It runs in a NixOS VM with default-deny egress and a tool denylist against prompt injection.
- [openwiki-cc](https://github.com/SoulKyu/openwiki-cc): auto-generated, git-grounded documentation wiki for any repo (Claude Code plugin and Codex skill)
- [pi-agentic-platform](https://github.com/SoulKyu/pi-agentic-platform): self-hosted agentic platform on the Pi SDK

</details>

---

### Stack

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

<a href="https://github.com/SoulKyu?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/SoulKyu?affiliations=OWNER&style=for-the-badge&logo=github&label=Stars&color=1f6feb" alt="Total stars" /></a>


<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SoulKyu&exclude_repo=pi-agentic-platform&layout=compact&hide_border=true&theme=github_dark&langs_count=6" height="165" alt="Top languages" />

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:00d4aa,50:1f6feb,100:0d1117&section=footer" />

</div>

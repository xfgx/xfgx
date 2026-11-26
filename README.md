### About me

Security researcher and tinkerer. Mostly bug bounties and AI agents, plus networking and the occasional Windows tool.

Right now I'm building [Chameleon](https://github.com/xfgx/Chameleon-CITP-VPN), a VPN that keeps working where VPNs get blocked, and [ElasticMem](https://github.com/xfgx/ElasticMEM), a small RAM tool for Windows. Most recently I took part in the Swarm Alignment Hackathon with [a2a-gateway-audit](https://github.com/xfgx/a2a-gateway-audit).

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/C%23-.NET%208-512BD4?logo=dotnet&logoColor=white" alt="C# / .NET">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Kotlin-Compose-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin">
</p>

## What I've done so far

- **Got full access to the admin panel of a crypto platform** through a flaw in its Telegram login. I can't name the platform; the owners asked me not to.
- **Bug bounties.** I've taken part in plenty of programs. No prize money yet :3
- **Hunting for bugs in different places:**
  - AI agent runtimes and the environments they run in;
  - game engines and networking libraries (ENet);
  - business logic of online platforms.
- **Digging into agent sandboxes:** E2B, KVM, Firecracker, gVisor. I'm interested in how isolated these environments really are and where they leak.
- **Writing my own prompts and jailbreaks** and watching how models behave at the edges of their rules.
- **Hackathons and research.** Most recently, the [Swarm Alignment Hackathon 2026](https://apartresearch.com/sprints/swarm-alignment-2026) by Apart Research.

## How I got into AI agents

I've been following AI agents since OpenAI started beating people at Dota 2. Here's the part of the story that hooked me:

| When | What happened |
|---|---|
| Aug 2017 | At The International 2017, an OpenAI bot beats top pros (including Dendi) in 1v1 |
| Jun 2018 | OpenAI introduces **OpenAI Five**, a team of five neural networks playing full 5v5 |
| Aug 2018 | OpenAI Five wins its Benchmark match against strong players, then loses two show matches against pros at TI 2018 |
| Apr 2019 | OpenAI Five Finals: a **2–0 win over OG**, the reigning TI champions |
| Apr 2019 | OpenAI Five Arena: thousands of public games, **99.4% win rate** |
| Dec 2019 | The paper *"Dota 2 with Large Scale Deep Reinforcement Learning"* comes out |

These days I'm focused on LLM agents: how they delegate work to each other, how permissions get abused, and how to break out of their sandboxes.

## What I'm working on

| Project | What it is | Stack |
|---|---|---|
| [**Chameleon-CITP-VPN**](https://github.com/xfgx/Chameleon-CITP-VPN) | A free, open-source VPN built to work where VPNs get blocked. One button, traffic that doesn't look like a VPN, and your own server in about five minutes. | Go |
| [**ElasticMEM**](https://github.com/xfgx/ElasticMEM) | Frees up RAM using built-in Windows tools and shows how well your memory compresses. No driver, no Hyper-V. | C# / .NET 8 |
| [**a2a-gateway-audit**](https://github.com/xfgx/a2a-gateway-audit) | My Swarm Alignment Hackathon project: how attackers can sneak harmful actions through agent-to-agent networks via approvals and delegation, and a gateway that tracks who actually asked for what. | Python |

These are all my public projects. Everything else I work on is private for now.

## Use my code

Everything public here is free to use, by anyone, for any purpose. Fork it, change it, ship it, use it at work. The only rule: don't use it for anything illegal.

## Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=xfgx&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xfgx&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages">
</p>

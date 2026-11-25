<div align="center">

# Angus

<img src="avatar.jpg" alt="Angus" width="180" />

**15** · Builder · I ship with AI agents every day

![JavaScript](https://img.shields.io/badge/-JavaScript-2b2b2b?style=flat-square&logo=javascript&logoColor=f1e05a)
![TypeScript](https://img.shields.io/badge/-TypeScript-2b2b2b?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/-Python-2b2b2b?style=flat-square&logo=python&logoColor=3776AB)
![Swift](https://img.shields.io/badge/-Swift-2b2b2b?style=flat-square&logo=swift&logoColor=F05138)
![Go](https://img.shields.io/badge/-Go-2b2b2b?style=flat-square&logo=go&logoColor=00ADD8)
![Luau](https://img.shields.io/badge/-Luau-2b2b2b?style=flat-square&logo=lua&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-2b2b2b?style=flat-square&logo=anthropic&logoColor=d4a27f)
![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare_Workers-2b2b2b?style=flat-square&logo=cloudflare&logoColor=F38020)

*Tools that make AI agents work together, and traps that catch them misbehaving.*

![Projects: 458](https://img.shields.io/static/v1?label=Projects&message=458&color=2b2b2b&style=flat-square&logo=github&logoColor=white)
![Public: 3](https://img.shields.io/static/v1?label=Public&message=3&color=2b2b2b&style=flat-square&logo=github&logoColor=white)
![Languages: 14](https://img.shields.io/static/v1?label=Languages&message=14&color=2b2b2b&style=flat-square&logo=github&logoColor=white)

[![Website](https://img.shields.io/badge/angusbuilds.com-2b2b2b?style=flat-square&logo=google-chrome&logoColor=white)](https://angusbuilds.com)
[![X](https://img.shields.io/badge/@angusbuilds-2b2b2b?style=flat-square&logo=x&logoColor=white)](https://x.com/angusbuilds)

`Multi-Agent Coding` · `AI Red-Teaming` · `Claude Code Skills` · `Mac Apps` · `Security Tools`

</div>

<p align="center">
<a href="#agent-tools">Agent Tools</a> · <a href="#security">Security</a> · <a href="#odd-and-fun">Odd and Fun</a> · <a href="#how-i-work">How I Work</a> · <a href="#connect">Connect</a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="stats-light.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="stats.svg" />
    <img src="stats.svg" width="49%" alt="458 repos, 3 public, 14 languages, age 15" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="languages-light.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="languages.svg" />
    <img src="languages.svg" width="49%" alt="Repos by main language" />
  </picture>
</p>

> [!NOTE]
> **458 repos, 3 public.** Most are still private. I open one up when it has tests, proof and a README worth reading. The ones without a link below are next.

---

## Agent Tools

Things I built because one AI agent on its own is not enough.

| Project | What it does | Proof |
|---|---|---|
| **gambit-lines** | Plans one job five ways, runs real checks, ranks what survives | 219 tests, no dependencies. Checked on 10 real jobs |
| **claudecodex** | Claude and Codex debate who codes, then the other one reviews the diff | 2,171 tests |
| **huddle** | Stops parallel Claude Code terminals editing the same file | A daemon plus hooks that join every terminal and gate each edit |
| **task-split** | One task splits into an animated tree of Claude terminals | One HTML file, demo and live modes |
| **claude-token-forensics** | A local proxy that measures what Claude Code sends and caches | Dated findings, including the ones that came back negative |
| [**dyslexic-mode**](https://github.com/hangryclaude/dyslexic-mode) | A terminal AI that thinks and answers the way a dyslexic reader needs | Runs with `npx`. 44 tests |

## Security

I want to be a world-class AI red-teamer. These are the reps.

| Project | What it does | Proof |
|---|---|---|
| **agent-mirror** | A honeypot that gets a hacking AI agent to report on itself | A recorded run where Claude Code carried the canary into its own report |
| [**api-key-crawler**](https://github.com/hangryclaude/api-key-crawler) | Stops API keys reaching GitHub, even with `--no-verify` | Go. 170 test files. 35.5 ms per commit |
| **redteam-course** | Hands-on labs that attack local models and score every hit | 27 units of runnable labs with canary scoring |

## Odd and Fun

| Project | What it does | Proof |
|---|---|---|
| [**flyby**](https://github.com/hangryclaude/flyby) | Finds where a video was filmed from the planes you can hear in it | Placed the reference clip 26 m from the true spot |
| **stark** | Control your Mac with hand gestures through the webcam | Native Swift and Apple Vision. 25 self-test fixtures |
| **sourcescan** | Tells you the most to pay for a thrift find, from eBay survival curves | Kaplan-Meier with Greenwood intervals. 269 tests |

## How I Work

- I build every day and push every night.
- Every project needs a check that can fail. No check, no claim.
- If a number is in a README, the repo can reproduce it.
- I say what does not work yet.

## Connect

[X @angusbuilds](https://x.com/angusbuilds) · [angusbuilds.com](https://angusbuilds.com)

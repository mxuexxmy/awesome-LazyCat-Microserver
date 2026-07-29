# awesome-LazyCat-Microserver

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/mxuexxmy/awesome-LazyCat-Microserver?style=social)](https://github.com/mxuexxmy/awesome-LazyCat-Microserver)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

[English](./README-EN.md) | [中文](./README.md)

A curated (unofficial) resource map for the LazyCat Microserver ecosystem. [Star](https://github.com/mxuexxmy/awesome-LazyCat-Microserver) and [PR](./CONTRIBUTING.md) welcome.

[LazyCat Microserver](https://lazycat.cloud/) is a next-generation home private cloud and AI data center, combining NAS, an app store, intranet penetration, and AI compute.

* [LazyCat Microserver LC-03](https://lazycat.cloud/lcmd): 7-bay all-SSD, high-performance standard-voltage CPU, up to 96TB storage

* [LazyCat AI Pod](https://lazycat.cloud/ai-pod): Current flagship LC-X5 (2070T compute, 128GB unified memory, ~284B models); LC-X3 and other SKUs — see AI Pod docs

* [LazyCat Camera](https://lazycat.cloud/camera): Distinctive design with private storage

* [LazyCat Microserver OS](https://lazycat.cloud/): Debian-based three-layer architecture, stable and secure

* [LazyCat App Store](https://appstore.lazycat.cloud/#/shop): 3000+ apps with one-click installation

* [LazyCat AI Browser](https://lazycat.cloud/): Chromium-based, supports AI plugins and Chrome extensions on mobile

* Built-in intranet penetration, accessible from anywhere, hassle-free

## Contents

* [Official Resources & Community](#official-resources--community)
* [Community Tutorials](#community-tutorials)
* [LazyCat AI Pod](#lazycat-ai-pod)
* [Skill / MCP / AI Agent](#skill--mcp--ai-agent)
* [LightOS](#lightos)
* [Development](#development)
* [Community Developers](#community-developers)
* [Quick Migration Tools](#quick-migration-tools)
* [Other Development Tools](#other-development-tools)
* [Application Repositories](#application-repositories)
* [Developer Modes](#developer-modes)
* [Recommended Applications](#recommended-applications)
* [Self-hosted Resources](#self-hosted-resources)
* [User Experiences](#user-experiences)
* [Others](#others)
* [Contributing](#contributing)

# Official Resources & Community

1. [LazyCat Microserver Official Site](https://lazycat.cloud/)

2. [LazyCat Microserver Product Page](https://lazycat.cloud/lcmd)

3. [App Store](https://appstore.lazycat.cloud/#/shop)

4. [Guides / Playground](https://playground.lazycat.cloud/#/home?dynamic=latest)

5. [LazyCat Microserver Developer Manual](https://developer.lazycat.cloud/en/)

6. [Developer Center](https://developer.lazycat.cloud/manage/)

7. [AI Pod Manual](https://developer.lazycat.cloud/aipod/)

8. [Client Downloads](https://lazycat.cloud/download)

9. [AI Assistant](https://lazycat.cloud/chat)

10. [LazyCat Camera](https://lazycat.cloud/camera)

11. [About LazyCat](https://lazycat.cloud/about)

12. [Community Forum](https://bbs.lazycat.cloud/)

13. [Changelog](https://developer.lazycat.cloud/changelog.html)

14. [Community Incentive Rules](https://developer.lazycat.cloud/en/store-rule.html)

15. [Developer Hardware Discount](https://developer.lazycat.cloud/en/developer-cyber-discount.html)

16. [Getting Started Path](https://developer.lazycat.cloud/en/getting-started/)

17. [Developer Docs Repository](https://gitee.com/lazycatcloud/lzc-developer-doc)

18. [Developer Manual (Chinese)](https://developer.lazycat.cloud/)

19. [Founder's Blog](https://manateelazycat.github.io/)

# Community Tutorials

1. [LazyCat Microserver Column](https://lazycat-docs.netlify.app/) — 80+ practical articles covering getting started, advanced topics, development, and containers

2. [Jinghu / Wangji Shanren](https://blog.no-claw.com/) — advanced notes (registry, Docker engine, and more)

3. [LazyCat Microserver — A Unique NAS Experience (sspai)](https://sspai.com/post/103942)

4. [Porting Docker Compose Apps to LazyCat](https://lazycat.cloud/playground/guideline/662)

5. [How Store Apps Take Over the Docker Engine](https://blog.no-claw.com/e8e61ce7/)

6. [Every Indie Developer / Startup Should Own a LazyCat](https://liaobinbin.com/posts/everyone-needs-lazycat-microserver/)

# LazyCat AI Pod

1. [AI Pod Product Page](https://lazycat.cloud/ai-pod) — Current flagship LC-X5 (2070T / 128GB / ~284B)

2. [AI Pod Developer Manual](https://developer.lazycat.cloud/aipod/)

3. [LC-X5 Config (lzc-thor)](https://developer.lazycat.cloud/aipod/lc-x5/config.html)

4. [Ollama API](https://developer.lazycat.cloud/aipod/ollama/app-use-ollama-api.html)

5. [vLLM](https://developer.lazycat.cloud/aipod/vllm/)

6. [ComfyUI FAQ](https://developer.lazycat.cloud/aipod/comfyui/)

7. [The World's First Personal AI Supercomputer Is Here!](https://manateelazycat.github.io/2025/09/20/microserver-and-ai-pod/)

# Skill / MCP / AI Agent

1. [Skill / MCP Spec | Developer Manual](https://developer.lazycat.cloud/resource-skill-mcp.html)

2. [Drive Context Menu, MCP & SKILL Guide](https://lazycat.cloud/playground/guideline/1628)

3. [llama-dash Guide](https://lazycat.cloud/playground/guideline/1580) — Local LLM gateway and ops console

4. [lazycat-mcp](https://github.com/lazycat-contrib/lazycat-mcp) — MCP service bridging LazyCat hardware and LLMs

5. [lazycat-skills](https://github.com/whoamihappyhacking/lazycat-skills) — Agent Skills for Cursor / Claude (`npx skills add whoamihappyhacking/lazycat-skills`)

# LightOS

LightOS is a lightweight systematic runtime on LazyCat Microserver, complementary to LPK packaging: LPK fits standalone apps (frontend, backend, routing, app-level data); LightOS fits long-term management of full runtime environments.

1. [LightOS Scenarios | Developer Manual](https://developer.lazycat.cloud/en/advanced-lightos.html)

2. [LightOS Entry | App Store](https://appstore.lazycat.cloud/#/shop/detail/cloud.lazycat.lightos.entry)

3. [LightOS Guide | Playground](https://playground.lazycat.cloud/#/guideline/1537)

# Development

1. [LazyCat Microserver Developer Manual (English)](https://developer.lazycat.cloud/en/)

2. [Getting Started Path](https://developer.lazycat.cloud/en/getting-started/)

3. [Hello World in 5 Minutes](https://developer.lazycat.cloud/getting-started/hello-world-fast.html)

4. [LazyCat Development Quick Guide](https://czyt.tech/post/simple-guide-for-developing-for-lazycat-nas/)

5. [@lazycatcloud/lzc-cli](https://www.npmjs.com/package/@lazycatcloud/lzc-cli) — Official CLI for creating, building, deploying, and publishing LPK apps

6. [Developer Environment Setup](https://developer.lazycat.cloud/en/getting-started/env-setup.html)

7. [Hello World](https://developer.lazycat.cloud/en/hello-world.html)

8. [Publish Your First App](https://developer.lazycat.cloud/publish-app.html)

9. [lzc-build.yml Specification](https://developer.lazycat.cloud/en/spec/build.html)

10. [How LPK Works](https://developer.lazycat.cloud/en/getting-started/lpk-how-it-works.html)

11. [AI Pod Manual](https://developer.lazycat.cloud/aipod/)

12. [@lazycatcloud/sdk](https://www.npmjs.com/package/@lazycatcloud/sdk) — Official SDK for interacting with microserver system state

13. [App Store Submission Guide](https://developer.lazycat.cloud/en/store-submission-guide.html)

14. [AI App Packaging Spec](https://developer.lazycat.cloud/aipod/package/spec.html)

15. [LightOS Scenarios](https://developer.lazycat.cloud/en/advanced-lightos.html) — Systematic runtime, complementary to LPK

16. [Skill / MCP Spec](https://developer.lazycat.cloud/resource-skill-mcp.html)

# Community Developers

1. Glzjin [GitHub](https://github.com/glzjin) [Blog](https://www.zhaoj.in/)

2. czyt [GitHub](https://github.com/czyt) [Blog](https://czyt.tech/)

3. mxuexxmy [GitHub](https://github.com/mxuexxmy) [Blog](https://www.infoq.cn/u/mxuexxmy/publish)

4. Wangji Shanren [Jinghu Blog](https://blog.no-claw.com/)

# Quick Migration Tools

1. [lzc-dtl](https://github.com/glzjin/lzc-dtl)

# Other Development Tools

1. [LazyCat UID Impersonator](https://github.com/glzjin/lzc-uid-impersonation)

2. [lazycat-mcp](https://github.com/lazycat-contrib/lazycat-mcp) — MCP service for connecting large language models

3. [apps-scheduler](https://github.com/lazycat-contrib/apps-scheduler) — Application scheduling tool

4. [lazycat-skills](https://github.com/whoamihappyhacking/lazycat-skills) — AI coding assistant skills pack

# Application Repositories

1. [Official Ported Applications Repository](https://gitee.com/lazycatcloud/appdb)

2. [Community App Contributions (Unofficial)](https://github.com/lazycat-contrib)

# Developer Modes

1. [KVM Mode | Developer Manual](https://developer.lazycat.cloud/kvm.html)

2. [Dockerd Development Mode | Developer Manual](https://developer.lazycat.cloud/dockerd-support.html)

3. [PVE](https://appstore.lazycat.cloud/#/shop/detail/in.zhaoj.webvirtcloud)

4. [lzcapp](https://developer.lazycat.cloud/develop-mode.html)

5. [LightOS | Developer Manual](https://developer.lazycat.cloud/en/advanced-lightos.html)

# Recommended Applications

## Official Applications

1. [Contacts](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.contacts)

Contacts can backup, restore, and sync phone contacts, with batch import/export.

2. [LazyCat Application Generator](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.create)

3. [Downloader](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.downloader)

Downloader fetches files by URL or keywords, with multi-threaded download and task management.

4. [LAN Port Forwarding Tool](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forward)

Maps container/app ports in the microserver to LAN ports.

5. [LazyCat Experimental Ollama](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzcollama)

6. [LazyCat Smart Screen](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzctvcontroller)

Smart Screen integrates music, video, games, and control with LazyCat ecosystem apps.

7. [Text Recognition](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ocr)

OCR converts text in images or scans into editable, searchable text.

8. [LazyCat Photo Album](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.photo)

Photo management with upload, share, edit, categorize, and album permissions.

9. [Movie Watching Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.re)

Browser-style viewing with bookmarks, history, downloads, and casting.

10. [Beta Testing Tool](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.testflight)

Grayscale testing.

11. [LazyCat Todo List](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.todolist)

Simple and effective to-do / task management.

12. [Video Player](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.video)

Video player supporting many audio/video formats.

13. [LazyCat Developer Tools](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.developer.tools)

14. [LazyCat Cloud Drive](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.shell.files)

File management for backup, sharing, and anytime access.

## AI Applications

1. [LazyCat Experimental Ollama](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzcollama) — Local LLM inference

2. [llama-dash Guide](https://lazycat.cloud/playground/guideline/1580) — Local LLM gateway, API keys, and Playground

3. [Ollama API (AI Pod)](https://developer.lazycat.cloud/aipod/ollama/app-use-ollama-api.html) — Call Ollama / OpenAI-compatible APIs via AI Pod

4. [vLLM (AI Pod)](https://developer.lazycat.cloud/aipod/vllm/) — High-performance and distributed inference

5. [ComfyUI (AI Pod)](https://developer.lazycat.cloud/aipod/comfyui/) — Image generation workflows

6. [Skill / MCP Spec](https://developer.lazycat.cloud/resource-skill-mcp.html) — Connect agents to LazyCat skills and tools

## Entertainment

1. [Jellyfin](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyfin)

Open-source home media center with transcoding, multi-device streaming, and 4K playback.

2. [Emby](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.emby)

Feature-rich media server for a home theater library.

3. [Navidrome](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.navidrome)

Lightweight music server with Subsonic API and multi-platform clients.

4. [MoviePilot](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.moviepilot)

Media automation for subscriptions, search, and library organization.

5. [qBittorrent Enhanced](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.qbittorrentee)

Enhanced BT/PT client for media collection.

6. [Stremio](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.stremio)

Cross-platform streaming aggregator with plugins.

## Productivity Tools

1. [Vaultwarden](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.vaultwarden)

Self-hosted password manager compatible with Bitwarden clients.

2. [Syncthing](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.syncthing)

Decentralized real-time multi-device file sync.

3. [Tailscale](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.tailscale)

WireGuard-based virtual networking.

4. [Memos](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.memos)

Lightweight memos with tags and sharing.

5. [EZ Bookkeeping](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ezbookkeeping)

Simple personal bookkeeping.

## Lifestyle

1. [Home Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.homeassistant)

Open-source smart home platform with thousands of integrations.

2. [Immich](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.immich)

High-performance photo backup with AI face recognition.

3. [Lucky](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lucky)

Router / public-network tool with port forwarding, DDNS, and penetration.

## Graphic Design

1. [Draw.io](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.drawio)

Online flowcharts and architecture diagrams.

2. [Excalidraw](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.excalidraw)

Hand-drawn style whiteboard for sketches and collaboration.

## Reading and Learning

1. [Calibre](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.calibre)

E-book management with format conversion and library tools.

2. [SiYuan Note](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.siyuan-note)

Local-first block notes with bidirectional links.

## Games

1. [Minecraft Server](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.minecraftserver)

One-click Minecraft server for multiplayer.

## Development Tools

1. [Coder](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.coder)

Browser-based remote IDE with code stored on the microserver.

2. [Forgejo](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forgejo)

Lightweight Git hosting, community fork of Gitea.

3. [GitLab](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.gitlab)

Full DevOps platform with CI/CD and code review.

## Others

1. [AList](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.alist)

Multi-cloud drive aggregation and mounting.

2. [Jellyseerr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyseerr)

Media request management for Jellyfin/Plex.

3. [Sonarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.sonarr)

TV series auto-download and library management.

4. [Radarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.radarr)

Movie auto-download and library management.

# Self-hosted Resources

1. [Laosu's Blog](https://laosu.tech/)

2. [Awesome-Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)

3. [LazyCat Microserver Column](https://lazycat-docs.netlify.app/)

4. [Jinghu / Wangji Shanren](https://blog.no-claw.com/)

# User Experiences

1. [LazyCat Microserver: Small Size, Big Satisfaction](https://www.zhaoj.in/read-8958.html)

2. [LazyCat Microserver Experience — Free Collaboration](https://blog.kevinzhow.com/posts/lazycat/zh)

3. [Atypical Uses of LazyCat Microserver](https://ironfeet.me/unconventional-usage-of-lazycat-microserver/)

4. [Unlimited Tinkering, Unlimited Joy](https://mp.weixin.qq.com/s/Sp6Xme0ulNFgPtXstLnANg)

5. [Unboxing AI Server: LazyCat Microserver LC-02](https://mp.weixin.qq.com/s/_s2zz1axhUfBeXXc0UqlxQ)

6. [This LazyCat is a Bit Toxic 1](https://lorddoomed.notion.site/1-16000d63a5ed809db153dcec0abfff7f)

7. [This LazyCat is a Bit Toxic 2](https://lorddoomed.notion.site/2-16000d63a5ed80eab00fceccb165ba3d)

8. [This LazyCat is a Bit Toxic 3](https://lorddoomed.notion.site/3-16000d63a5ed8013998fde1f1499cf2c)

9. [Family Black Tech! Beyond NAS](https://www.xiaohongshu.com/explore/679841ec000000002900d24e?note_flow_source=wechat&xsec_token=CBbXKvDur-yvMCWTsfO2JPm6PUm2S-qT7DhEwfhnVyq5g=)

10. [My First Home Server — Experience Report](https://be1yu.notion.site/150c78753c2f80469051dc02dc4ffcd9)

11. [Something New for Self-Entertainment — LazyCat](https://mp.weixin.qq.com/s/AsmRqfZEUrUOP0DrzXq7Gg)

12. [The World's First Personal AI Supercomputer Is Here!](https://manateelazycat.github.io/2025/09/20/microserver-and-ai-pod/)

13. [What Does LazyCat Offer Technical Users?](https://manateelazycat.github.io/2025/05/03/microserver-for-developer/)

14. [LCMD Microserver & AI Pod (English review)](https://the-diy-life.com/lcmd-microserver-ai-pod-a-compact-homelab-powerhouse/)

15. [Sharing My New Device — LazyCat (V2EX)](https://www.v2ex.com/t/1111706)

16. [LazyCat + LightOS Vibe Coding (V2EX)](https://www.v2ex.com/t/1204968)

# Others

[The Past and Present of LazyCat Microserver](https://manateelazycat.github.io/2024/08/20/why-microserver/)

> The founder explains the origin of LazyCat Microserver

# Contributing

PRs that add links, fix broken URLs, or keep EN/ZH in sync are welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md).

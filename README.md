# Awesome LazyCat Microserver [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="media/lazycat-microserver.webp" width="420" alt="LazyCat Microserver">](https://lazycat.cloud/)

> A home private-cloud appliance with NAS features, an application marketplace, remote-access tooling, and local AI compute.

[English](./README.md) | [中文](./README-ZH.md)

Contributions welcome via [PR](./CONTRIBUTING.md) or [Issues](https://github.com/mxuexxmy/awesome-lazycat-microserver/issues/new/choose).

## Contents

- [Official Resources](#official-resources)
- [Community Tutorials](#community-tutorials)
- [AI Pod](#ai-pod)
- [Skill / MCP / AI Agent](#skill--mcp--ai-agent)
- [LightOS](#lightos)
- [Development](#development)
- [Tools](#tools)
- [Application Repositories](#application-repositories)
- [Developer Modes](#developer-modes)
- [Recommended Applications](#recommended-applications)
- [User Experiences](#user-experiences)
- [Others](#others)

## Official Resources

- [LazyCat Microserver Official Site](https://lazycat.cloud/) - Product home for Microserver, AI Pod, camera, OS, and browser.
- [LazyCat Microserver Product Page](https://lazycat.cloud/lcmd) - LC-03 family private cloud hardware.
- [App Store](https://appstore.lazycat.cloud/#/shop) - 3000+ one-click apps.
- [Guides / Playground](https://playground.lazycat.cloud/#/home?dynamic=latest) - Official how-tos for Microserver and AI Pod.
- [Developer Manual](https://developer.lazycat.cloud/en/) - English application development docs.
- [Developer Center](https://developer.lazycat.cloud/manage/) - Developer console.
- [AI Pod Manual](https://developer.lazycat.cloud/aipod/) - AI Pod OS, services, and packaging.
- [Client Downloads](https://lazycat.cloud/download) - Desktop and mobile clients.
- [AI Assistant](https://lazycat.cloud/chat) - Official AI assistant entry.
- [LazyCat Camera](https://lazycat.cloud/camera) - Private camera hardware.
- [About LazyCat](https://lazycat.cloud/about) - Company and product background.
- [Community Forum](https://bbs.lazycat.cloud/) - Official discussion board.
- [Changelog](https://developer.lazycat.cloud/changelog.html) - System and platform changes.
- [Community Incentive Rules](https://developer.lazycat.cloud/en/store-rule.html) - Rewards for porting apps and writing guides.
- [Developer Hardware Discount](https://developer.lazycat.cloud/en/developer-cyber-discount.html) - Open-source contributor purchase discount.
- [Getting Started Path](https://developer.lazycat.cloud/en/getting-started/) - First-app learning path.
- [Developer Docs Repository](https://gitee.com/lazycatcloud/lzc-developer-doc) - Docs source on Gitee.
- [Developer Manual (Chinese)](https://developer.lazycat.cloud/) - Chinese documentation site.
- [Founder's Blog](https://manateelazycat.github.io/) - Product philosophy and release notes.

## Community Tutorials

- [LazyCat Microserver Column](https://lazycat-docs.netlify.app/) - 80+ practical articles on getting started, advanced topics, development, and containers.
- [Jinghu / Wangji Shanren](https://blog.no-claw.com/) - Advanced notes on registry, Docker engine, and more.
- [LazyCat Microserver — A Unique NAS Experience (sspai)](https://sspai.com/post/103942) - Hands-on NAS-style review.
- [Porting Docker Compose Apps to LazyCat](https://lazycat.cloud/playground/guideline/662) - Manifest, routing, and image sync walkthrough.
- [How Store Apps Take Over the Docker Engine](https://blog.no-claw.com/e8e61ce7/) - Mounting docker.sock from store apps.
- [Every Indie Developer / Startup Should Own a LazyCat](https://liaobinbin.com/posts/everyone-needs-lazycat-microserver/) - Independent developer perspective.

## AI Pod

- [AI Pod Product Page](https://lazycat.cloud/ai-pod) - Current flagship LC-X5 (2070T / 128GB / ~284B).
- [LC-X5 Config (lzc-thor)](https://developer.lazycat.cloud/aipod/lc-x5/config.html) - System init and network tooling.
- [Ollama API](https://developer.lazycat.cloud/aipod/ollama/app-use-ollama-api.html) - Call Ollama / OpenAI-compatible APIs via AI Pod.
- [vLLM](https://developer.lazycat.cloud/aipod/vllm/) - High-performance and distributed inference.
- [ComfyUI FAQ](https://developer.lazycat.cloud/aipod/comfyui/) - Image generation workflows.
- [The World's First Personal AI Supercomputer Is Here!](https://manateelazycat.github.io/2025/09/20/microserver-and-ai-pod/) - Founder announcement post.

## Skill / MCP / AI Agent

- [Skill / MCP Spec](https://developer.lazycat.cloud/resource-skill-mcp.html) - How agents discover and use skills / MCP providers.
- [Drive Context Menu, MCP and SKILL Guide](https://lazycat.cloud/playground/guideline/1628) - Integrate file actions and agent tools.
- [llama-dash Guide](https://lazycat.cloud/playground/guideline/1580) - Local LLM gateway and ops console.
- [lazycat-mcp](https://github.com/lazycat-contrib/lazycat-mcp) - MCP bridge for LazyCat hardware and LLMs.
- [lazycat-skills](https://github.com/whoamihappyhacking/lazycat-skills) - Agent Skills for Cursor / Claude (`npx skills add whoamihappyhacking/lazycat-skills`).

## LightOS

LightOS is a systematic runtime complementary to LPK packaging: LPK fits standalone apps; LightOS fits long-lived full environments.

- [LightOS Scenarios](https://developer.lazycat.cloud/en/advanced-lightos.html) - When to choose LightOS vs LPK.
- [LightOS Entry (App Store)](https://appstore.lazycat.cloud/#/shop/detail/cloud.lazycat.lightos.entry) - Install LightOS entry app.
- [LightOS Guide (Playground)](https://playground.lazycat.cloud/#/guideline/1537) - Usage guide.

## Development

- [Hello World in 5 Minutes](https://developer.lazycat.cloud/getting-started/hello-world-fast.html) - Fast multi-client deploy path.
- [Development Quick Guide](https://czyt.tech/post/simple-guide-for-developing-for-lazycat-nas/) - Community concise tutorial.
- [@lazycatcloud/lzc-cli](https://www.npmjs.com/package/@lazycatcloud/lzc-cli) - Official CLI for create / build / deploy / publish.
- [Environment Setup](https://developer.lazycat.cloud/en/getting-started/env-setup.html) - Local tooling and box connection.
- [Hello World](https://developer.lazycat.cloud/en/hello-world.html) - First project walkthrough.
- [Publish Your First App](https://developer.lazycat.cloud/publish-app.html) - Store publish flow.
- [lzc-build.yml Spec](https://developer.lazycat.cloud/en/spec/build.html) - Build configuration reference.
- [How LPK Works](https://developer.lazycat.cloud/en/getting-started/lpk-how-it-works.html) - Package format and install model.
- [@lazycatcloud/sdk](https://www.npmjs.com/package/@lazycatcloud/sdk) - SDK for system state and platform APIs.
- [App Store Submission Guide](https://developer.lazycat.cloud/en/store-submission-guide.html) - Listing requirements.
- [AI App Packaging Spec](https://developer.lazycat.cloud/aipod/package/spec.html) - AI services and browser extensions in LPK.
- [Dev Workflow Overview](https://developer.lazycat.cloud/getting-started/dev-workflow.html) - Dev vs release build configs.

## Tools

- [lzc-dtl](https://github.com/jn7163/lzc-dtl) - Convert Docker Compose apps to LazyCat format (`npm i -g lzc-dtl`).
- [LazyCat UID Impersonator](https://github.com/glzjin/lzc-uid-impersonation) - UID simulation helper for development.
- [apps-scheduler](https://github.com/lazycat-contrib/apps-scheduler) - Application scheduling helper.

## Application Repositories

- [Official Ported Applications (appdb)](https://gitee.com/lazycatcloud/appdb) - Official ported app references.
- [lazycat-contrib](https://github.com/lazycat-contrib) - Unofficial community app organization.

## Developer Modes

- [KVM Mode](https://developer.lazycat.cloud/kvm.html) - Virtualization mode docs.
- [Dockerd Development Mode](https://developer.lazycat.cloud/dockerd-support.html) - Docker daemon development support.
- [PVE (WebVirtCloud)](https://appstore.lazycat.cloud/#/shop/detail/in.zhaoj.webvirtcloud) - Proxmox-style management app.
- [Enable SSH](https://developer.lazycat.cloud/ssh.html) - SSH access setup.

## Recommended Applications

### Official Applications

- [Contacts](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.contacts) - Backup, restore, and sync phone contacts.
- [Application Generator](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.create) - Create LazyCat apps.
- [Downloader](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.downloader) - Multi-threaded downloads by URL or keyword.
- [LAN Port Forwarding](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forward) - Map container ports to the LAN.
- [Experimental Ollama](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzcollama) - Local LLM inference.
- [Smart Screen](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzctvcontroller) - TV / big-screen LazyCat experience.
- [OCR](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ocr) - Image and scan text recognition.
- [Photo Album](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.photo) - Private photo management and sharing.
- [Movie Watching Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.re) - Browser-style viewing and casting.
- [Beta Testing Tool](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.testflight) - Grayscale testing.
- [Todo List](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.todolist) - Simple task management.
- [Video Player](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.video) - Multi-format media player.
- [Developer Tools](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.developer.tools) - Official developer tooling app.
- [Cloud Drive](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.shell.files) - File backup and sharing.

### Entertainment

- [Jellyfin](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyfin) - Open-source media center with transcoding.
- [Emby](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.emby) - Feature-rich home theater server.
- [Navidrome](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.navidrome) - Lightweight music server with Subsonic API.
- [MoviePilot](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.moviepilot) - Media automation and library organization.
- [qBittorrent Enhanced](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.qbittorrentee) - Enhanced BT/PT client.
- [Stremio](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.stremio) - Streaming aggregator with plugins.

### Productivity

- [Vaultwarden](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.vaultwarden) - Self-hosted Bitwarden-compatible passwords.
- [Syncthing](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.syncthing) - Decentralized file sync.
- [Tailscale](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.tailscale) - WireGuard mesh networking.
- [Memos](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.memos) - Lightweight notes with tags.
- [EZ Bookkeeping](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ezbookkeeping) - Personal bookkeeping.

### Lifestyle

- [Home Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.homeassistant) - Smart home automation.
- [Immich](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.immich) - Photo backup with AI face recognition.
- [Lucky](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lucky) - Port forwarding, DDNS, and penetration helpers.

### Design and Learning

- [Draw.io](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.drawio) - Diagrams and architecture charts.
- [Excalidraw](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.excalidraw) - Hand-drawn whiteboard.
- [Calibre](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.calibre) - E-book library management.
- [SiYuan Note](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.siyuan-note) - Local-first block notes.

### Games and Dev Tools

- [Minecraft Server](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.minecraftserver) - One-click multiplayer server.
- [Coder](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.coder) - Browser-based remote IDE.
- [Forgejo](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forgejo) - Lightweight Git hosting.
- [GitLab](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.gitlab) - Full DevOps platform.

### More Apps

- [AList](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.alist) - Multi-cloud drive mounting.
- [Jellyseerr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyseerr) - Media request management.
- [Sonarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.sonarr) - TV library automation.
- [Radarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.radarr) - Movie library automation.

## User Experiences

- [Small Size, Big Satisfaction](https://www.zhaoj.in/read-8958.html) - Full experience from aesthetics to features.
- [A Tool for Free Collaboration](https://blog.kevinzhow.com/posts/lazycat/zh) - Collaboration-focused review.
- [Atypical Uses](https://ironfeet.me/unconventional-usage-of-lazycat-microserver/) - Unconventional setups.
- [Unlimited Tinkering](https://mp.weixin.qq.com/s/Sp6Xme0ulNFgPtXstLnANg) - WeChat long-form journey.
- [Unboxing LC-02 AI Server](https://mp.weixin.qq.com/s/_s2zz1axhUfBeXXc0UqlxQ) - Hardware unboxing.
- [This LazyCat is a Bit Toxic 1](https://lorddoomed.notion.site/1-16000d63a5ed809db153dcec0abfff7f) - Series part 1.
- [This LazyCat is a Bit Toxic 2](https://lorddoomed.notion.site/2-16000d63a5ed80eab00fceccb165ba3d) - Series part 2.
- [This LazyCat is a Bit Toxic 3](https://lorddoomed.notion.site/3-16000d63a5ed8013998fde1f1499cf2c) - Series part 3.
- [Family Black Tech Beyond NAS](https://www.xiaohongshu.com/explore/679841ec000000002900d24e) - Xiaohongshu note.
- [My First Home Server Report](https://be1yu.notion.site/150c78753c2f80469051dc02dc4ffcd9) - First-server write-up.
- [Something New for Self-Entertainment](https://mp.weixin.qq.com/s/AsmRqfZEUrUOP0DrzXq7Gg) - Casual usage story.
- [What LazyCat Offers Technical Users](https://manateelazycat.github.io/2025/05/03/microserver-for-developer/) - Founder view for developers.
- [LCMD Microserver and AI Pod (English)](https://the-diy-life.com/lcmd-microserver-ai-pod-a-compact-homelab-powerhouse/) - The DIY Life hardware review.
- [Sharing My New Device (V2EX)](https://www.v2ex.com/t/1111706) - Community discussion.
- [LightOS Vibe Coding (V2EX)](https://www.v2ex.com/t/1204968) - LightOS remote coding discussion.

## Others

- [The Past and Present of LazyCat Microserver](https://manateelazycat.github.io/2024/08/20/why-microserver/) - Origin story by the founder.

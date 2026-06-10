# awesome-LazyCat-Microserver

[English](./README-EN.md) | [中文](./README.md)

[LazyCat Microserver](https://lazycat.cloud/) is a next-generation home private cloud and AI data center, combining NAS, an app store, intranet penetration, and AI compute in one platform, positioned as a high-end private cloud solution.

* New Microserver: 7-bay all-SSD, high-performance standard-voltage CPU, up to 96TB storage

* [LazyCat AI Pod X3](https://lazycat.cloud/ai-pod): 275T compute, 64GB VRAM, supports 70B ~ 671B large models, compatible with the NVIDIA CUDA ecosystem

* [LazyCat Microserver OS](https://lazycat.cloud/): Debian-based three-layer architecture, stable and secure

* [LazyCat App Store](https://lazycat.cloud/appstore/): 3000+ apps with one-click installation

* [LazyCat AI Browser](https://lazycat.cloud/): Chromium-based, supports AI plugins, Chrome extensions on mobile

* Built-in intranet penetration, accessible from anywhere, hassle-free

# Official Resources & Community

1. [LazyCat Microserver Official Site](https://lazycat.cloud/)

2. [LazyCat App Store](https://lazycat.cloud/appstore/)

3. [LazyCat Microserver Developer Manual (English)](https://developer.lazycat.cloud/en/)

4. [LazyCat Microserver Community Forum](https://bbs.lazycat.cloud/)

5. [LazyCat Microserver Developer Docs Repository](https://gitee.com/lazycatcloud/lzc-developer-doc)

6. [LazyCat Microserver Developer Manual (Chinese)](https://developer.lazycat.cloud/)

7. [Founder's Blog](https://manateelazycat.github.io/)

# Community Tutorials

1. [LazyCat Microserver Column](https://lazycat-docs.netlify.app/) — 80+ practical articles covering getting started, advanced topics, development, and containers

2. [LazyCat Microserver — A Unique NAS Experience (sspai)](https://sspai.com/post/103942)

# LazyCat AI Pod

1. [LazyCat AI Pod Product Page](https://lazycat.cloud/ai-pod)

2. [AI Pod Developer Manual](https://developer.lazycat.cloud/aipod/)

3. [The World's First Personal AI Supercomputer Is Here!](https://manateelazycat.github.io/2025/09/20/microserver-and-ai-pod/)

# LightOS

LightOS is a lightweight systematic runtime environment on LazyCat Microserver, complementary to LPK app packaging: LPK is for standalone apps (frontend, backend, routing, app-level data), while LightOS is better for long-term management of complete runtime environments.

1. [LightOS Scenarios | Developer Manual](https://developer.lazycat.cloud/en/advanced-lightos.html)

2. [LightOS Entry | App Store](https://appstore.lazycat.cloud/#/shop/detail/cloud.lazycat.lightos.entry)

3. [LightOS Guide | Playground](https://playground.lazycat.cloud/#/guideline/1537)

# Development

1. [LazyCat Microserver Developer Manual (English)](https://developer.lazycat.cloud/en/)

2. [LazyCat Microserver Development Quick Guide](https://czyt.tech/post/simple-guide-for-developing-for-lazycat-nas/)

3. [@lazycatcloud/lzc-cli](https://www.npmjs.com/package/@lazycatcloud/lzc-cli) — Official CLI for creating, building, deploying, and publishing LPK apps

4. [Developer Environment Setup](https://developer.lazycat.cloud/en/getting-started/env-setup.html)

5. [Hello World](https://developer.lazycat.cloud/en/hello-world.html)

6. [lzc-build.yml Specification](https://developer.lazycat.cloud/en/spec/build.html)

7. [How LPK Works](https://developer.lazycat.cloud/en/getting-started/lpk-how-it-works.html)

8. [AI Pod Developer Manual](https://developer.lazycat.cloud/aipod/)

9. [@lazycatcloud/sdk](https://www.npmjs.com/package/@lazycatcloud/sdk) — Official SDK for interacting with microserver system state

10. [App Store Submission Guide](https://developer.lazycat.cloud/en/store-submission-guide.html)

11. [AI App Packaging Specification](https://developer.lazycat.cloud/aipod/package/spec.html)

12. [LightOS Scenarios](https://developer.lazycat.cloud/en/advanced-lightos.html) — Systematic runtime environment, complementary to LPK

# Community Developers

1. Glzjin [GitHub](https://github.com/glzjin) [Blog](https://www.zhaoj.in/)

2. czyt [GitHub](https://github.com/czyt) [Blog](https://czyt.tech/)

3. mxuexxmy [GitHub](https://github.com/mxuexxmy) [Blog](https://www.infoq.cn/u/mxuexxmy/publish)

# Quick Migration Tools

1. [lzc-dtl](https://github.com/glzjin/lzc-dtl)

# Other Development Tools

1. [LazyCat Microserver UID Impersonator](https://github.com/glzjin/lzc-uid-impersonation)

2. [lazycat-mcp](https://github.com/lazycat-contrib/lazycat-mcp) — MCP service for connecting large language models

3. [apps-scheduler](https://github.com/lazycat-contrib/apps-scheduler) — Application scheduling tool

# Application Repositories

1. [LazyCat Microserver Official Ported Applications Repository](https://gitee.com/lazycatcloud/appdb)

2. [LazyCat Microserver Related App Contributions (Unofficial)](https://github.com/lazycat-contrib)

# Developer Modes

1. [KVM Mode | LazyCat Microserver Developer Manual](https://developer.lazycat.cloud/kvm.html)

2. [Dockerd Development Mode | LazyCat Microserver Developer Manual](https://developer.lazycat.cloud/dockerd-support.html)

3. [PVE](https://appstore.lazycat.cloud/#/shop/detail/in.zhaoj.webvirtcloud)

4. [lzcapp](https://developer.lazycat.cloud/develop-mode.html)

5. [LightOS | LCMD Developer Manual](https://developer.lazycat.cloud/en/advanced-lightos.html)

# Recommended Applications

## Official Applications

1. [Contacts](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.contacts)

Contacts is an application that can backup, restore, and synchronize mobile phone contacts. It supports batch import and export of contacts, protects information security, and improves office efficiency.

2. [LazyCat Application Generator](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.create)

3. [Downloader](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.downloader)

Downloader is a download tool provided by the LazyCat Cloud platform. It can download target files through URL addresses or specific keywords and download them to local computers or mobile devices. The downloader can download various types of files, including audio, video, documents, images, etc. Meanwhile, the downloader also supports multi-threaded downloading to improve download speed, and can pause, resume, delete, and manage download tasks.

4. [LAN Port Forwarding Tool](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forward)

Used to map ports from other containers and applications in the microserver to LAN ports.

5. [LazyCat Experimental Ollama](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzcollama)

6. [LazyCat Smart Screen](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lzctvcontroller)

LazyCat Smart Screen is a smart software that integrates music, video, games, intelligent control, and other multi-functions. It combines smart TV multi-functional display and supports numerous applications in the LazyCat Microserver ecosystem, providing users with a more intelligent and interactive home life experience.

7. [Text Recognition](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ocr)

Text Recognition is a text recognition tool provided by the LazyCat Cloud platform. It can convert text in images or scanned documents into editable and searchable text, quickly convert paper documents to electronic documents, and improve document utilization value and management efficiency.

8. [LazyCat Photo Album](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.photo)

LazyCat Photo Album is an image management tool provided by the LazyCat Cloud platform. Users can upload personal or family photos to the cloud and access and share them through the network. Users can manage photos through the album, including editing, deleting, categorizing, searching, and other functions, and can also create albums, set album permissions, invite friends to share, etc.

9. [Movie Watching Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.re)

Browser is a browser provided by the LazyCat Cloud platform. It offers faster browsing experience, more secure browsing protection, and supports features like address bar, bookmarks, history, download manager, etc. It can also be cast to a player for use.

10. [Beta Testing Tool](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.testflight)

Grayscale testing.

11. [LazyCat Todo List](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.todolist)

LazyCat Todo List is a simple and effective to-do and task management application.

12. [Video Player](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.video)

Player is a video playback tool provided by the LazyCat Cloud platform. It supports various formats of media files including audio and video, creating a powerful video player for users.

13. [LazyCat Developer Tools](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.developer.tools)

14. [LazyCat Cloud Drive](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.shell.files)

LazyCat Cloud Drive is a file management tool provided by the LazyCat Cloud platform. Users can upload their files to the cloud drive for backup and sharing, free up local space, and access their files anytime, anywhere through the internet.

## Entertainment

1. [Jellyfin](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyfin)

Open-source home media center with transcoding, multi-device remote streaming, and 4K playback.

2. [Emby](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.emby)

Feature-rich media server for building a home theater library.

3. [Navidrome](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.navidrome)

Lightweight music server with Subsonic API support and multi-platform client streaming.

4. [MoviePilot](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.moviepilot)

Media automation tool for subscriptions, search, and library organization.

5. [qBittorrent Enhanced](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.qbittorrentee)

Enhanced BT/PT download client for media collection.

6. [Stremio](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.stremio)

Cross-platform streaming aggregator with plugin support.

## Productivity Tools

1. [Vaultwarden](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.vaultwarden)

Self-hosted password manager compatible with Bitwarden clients, fully private data.

2. [Syncthing](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.syncthing)

Decentralized file sync tool for real-time multi-device synchronization.

3. [Tailscale](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.tailscale)

WireGuard-based virtual networking tool for easy device connectivity.

4. [Memos](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.memos)

Lightweight memo and knowledge recording tool with tags and sharing.

5. [EZ Bookkeeping](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.ezbookkeeping)

Simple personal bookkeeping app for daily income and expense tracking.

## Lifestyle

1. [Home Assistant](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.homeassistant)

Open-source smart home platform supporting thousands of devices and automation.

2. [Immich](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.immich)

High-performance photo backup and management with AI face recognition and mobile auto-backup.

3. [Lucky](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.lucky)

Router and public network tool supporting port forwarding, DDNS, and intranet penetration.

## Graphic Design

1. [Draw.io](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.drawio)

Online flowchart and architecture diagram tool supporting multiple chart types.

2. [Excalidraw](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.excalidraw)

Hand-drawn style whiteboard tool for quick sketches and collaborative drawing.

## Reading and Learning

1. [Calibre](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.calibre)

Powerful e-book management and reading tool with format conversion and library organization.

2. [SiYuan Note](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.siyuan-note)

Local-first block-based note app with bidirectional links and multi-device sync.

## Games

1. [Minecraft Server](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.minecraftserver)

One-click Minecraft game server deployment for multiplayer with friends.

## Development Tools

1. [Coder](https://lazycat.cloud/appstore/#/shop/detail/community.lazycat.app.coder)

Browser-based remote development environment with code stored directly on the microserver.

2. [Forgejo](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.forgejo)

Lightweight Git code hosting platform, a community fork of Gitea.

3. [GitLab](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.gitlab)

Full-featured DevOps platform with CI/CD, code review, and project management.

## Others

1. [AList](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.alist)

Multi-cloud drive aggregation and mounting tool for Aliyun Drive, Baidu Netdisk, and more.

2. [Jellyseerr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.jellyseerr)

Media request management tool for use with Jellyfin/Plex.

3. [Sonarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.sonarr)

TV series auto-download and media library management tool.

4. [Radarr](https://lazycat.cloud/appstore/#/shop/detail/cloud.lazycat.app.radarr)

Movie auto-download and media library management tool.

# Self-hosted Resources

1. [Laosu's Blog](https://laosu.tech/)

2. [Awesome-Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)

3. [LazyCat Microserver Column](https://lazycat-docs.netlify.app/)

# User Experiences

1. [LazyCat Microserver: Small Size, Big Satisfaction - A Comprehensive Experience from Aesthetics to Functionality](https://www.zhaoj.in/read-8958.html)

2. [LazyCat Microserver Experience - A Tool for Free Collaboration](https://blog.kevinzhow.com/posts/lazycat/zh)

3. [Atypical Uses of LazyCat Microserver](https://ironfeet.me/unconventional-usage-of-lazycat-microserver/)

4. [Unlimited Tinkering, Unlimited Joy - My LazyCat Microserver Journey](https://mp.weixin.qq.com/s/Sp6Xme0ulNFgPtXstLnANg)

5. [Unboxing and Review of AI Server: LazyCat Microserver LC - 02](https://mp.weixin.qq.com/s/_s2zz1axhUfBeXXc0UqlxQ)

6. [This LazyCat is a Bit Toxic 1](https://lorddoomed.notion.site/1-16000d63a5ed809db153dcec0abfff7f)

7. [This LazyCat is a Bit Toxic 2](https://lorddoomed.notion.site/2-16000d63a5ed80eab00fceccb165ba3d)

8. [This LazyCat is a Bit Toxic 3](https://lorddoomed.notion.site/3-16000d63a5ed8013998fde1f1499cf2c)

9. [Family Black Tech! Beyond NAS - LazyCat Microserver](https://www.xiaohongshu.com/explore/679841ec000000002900d24e?note_flow_source=wechat&xsec_token=CBbXKvDur-yvMCWTsfO2JPm6PUm2S-qT7DhEwfhnVyq5g=)

10. [My First Home Server - LazyCat Microserver Experience Report](https://be1yu.notion.site/150c78753c2f80469051dc02dc4ffcd9)

11. [I Found Something New for Self-Entertainment -- LazyCat Microserver](https://mp.weixin.qq.com/s/AsmRqfZEUrUOP0DrzXq7Gg)

12. [The World's First Personal AI Supercomputer Is Here!](https://manateelazycat.github.io/2025/09/20/microserver-and-ai-pod/)

13. [What Does LazyCat Microserver Offer Technical Users?](https://manateelazycat.github.io/2025/05/03/microserver-for-developer/)

# Others

[The Past and Present of LazyCat Microserver](https://manateelazycat.github.io/2024/08/20/why-microserver/)

> The founder explains the origin of LazyCat Microserver

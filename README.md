# Samir Kattel

**Backend Engineer · Trading Infrastructure · Low-Latency Systems**

Backend engineer focused on market data pipelines, order execution, and exchange connectivity for quantitative trading systems. Primary stack is Node.js/TypeScript and Python, with Go for control planes and developer tooling, including [Drawa](https://drawa.cc). Experienced across the stack, from schema design to production deployment.

Currently building real-time market data infrastructure at **QubitGlobal**, and studying probability and stochastic processes for quantitative roles.

---

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Shell](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Backend & Messaging**

![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)

**Hardware / HDL** (exploratory)

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-%23F1C40F.svg?style=for-the-badge)

Icarus Verilog, Verilator, GTKWave

---

## Experience

**QubitGlobal, Backend Engineer** (Oct 2024 – Present)
Quantitative trading and analytics firm. Build and maintain market data and execution infrastructure across 13+ venues and 30+ trading pairs, processing roughly 1,000 quote updates per second. Replaced fixed-spread quoting with an async GLFT grid market maker whose spreads retune themselves online, and built a Go control plane on the Kubernetes API and NATS for bot rollout. Reduced venue onboarding time from 3 days to 1, boot reconciliation to approximately 20 seconds, and bot rollout time from 15-30 minutes to 30 seconds. Support 50+ live trading bots across 3 client accounts within a single process, with 100+ restarts and zero drift.

**TokenPilot, Backend Developer** (Jan – Sep 2024)
Market making firm. Integrated 10+ centralized exchanges, including Binance, Bybit, MEXC, Gate.io, KuCoin, and XT, through a custom connector layer that standardized order, balance, and market data formats. Processed 100,000+ orders per day with daily reporting across 20 client accounts.

---

## Projects

**[Drawa](https://github.com/HimalayanNomads/drawa)** · [drawa.cc](https://drawa.cc) ![Release](https://img.shields.io/github/v/release/HimalayanNomads/drawa) ![Stars](https://img.shields.io/github/stars/HimalayanNomads/drawa)
Creator and lead maintainer of an open-source canvas for running coding agents side by side. Designed its Go core as a protocol translation layer: one backend interface and wire format over Claude Code's stream-json, Codex's JSON-RPC app-server and OpenCode's HTTP event stream, with indexed per-session buffers so a reloaded page re-attaches mid-response, process-group isolation for agents and their tools, and git hardening for cloning untrusted repos.

**[GharBhada](https://ghar-bhada.com)**
Nationwide rental platform on Django, Next.js and PostGIS. 19-source scraping pipeline, H3 hex-indexed geospatial search, PostgreSQL full-text search, and a saved-search alert engine on Celery.

**[itch-fpga](https://github.com/probablysamir/itch-fpga)**
Byte-serial SystemVerilog decoder and order book for NASDAQ TotalView-ITCH 5.0, covering 9 message types and 98% of session traffic. Verified against Python reference models on real session captures: 264M+ messages byte-identical, zero frame errors.

**[chunk-store](https://github.com/probablysamir/chunk-store)**
Go CLI that splits large files into AES-256-GCM encrypted chunks and distributes them across multiple cloud providers and accounts. Includes round-robin load balancing, SHA-256 integrity verification, and manifest-based reassembly.

**[go-container](https://github.com/probablysamir/go-container)**
Container runtime built from scratch in Go using Linux namespaces, built to understand process isolation at the kernel level.

---

## Writing

**[Parsing NASDAQ ITCH on an FPGA](https://medium.com/@probablysamir/parsing-nasdaq-itch-on-an-fpga-421dac8787ed)**
How the itch-fpga decoder frames and parses ITCH messages in hardware, one byte per clock.

**[How I Used Zero-Copy to Achieve Blazingly Fast File Transfers](https://medium.com/@probablysamir/how-i-used-zero-copy-to-achieve-blazingly-fast-file-transfers-d93eb093a8fb)**
An overview of zero-copy I/O and how it reduces CPU overhead in data transfer pipelines.

**[Vertical vs Horizontal Scaling](https://medium.com/@probablysamir/vertical-vs-horizontal-scaling-d8cdd8db4caa)**
A comparison of the two core strategies for scaling systems under load, and when to apply each.

---

## Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=probablysamir&theme=dark&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=probablysamir&theme=dark&hide_border=true&layout=compact)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/probablysamir/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@probablysamir)

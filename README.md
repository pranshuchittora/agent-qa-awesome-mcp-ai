# Awesome MCP AI

A curated list of Model Context Protocol (MCP) repositories for AI agents.

**Inclusion criteria**

- ★ 100+ stars
- Latest push within the last 3 months (pushed on/after 2026-07-31)
- Actively related to MCP (server, client, SDK, gateway, or MCP-native tool)
- Exceptions (young or niche fields, lower star bar, same 3-month push rule):
  - [ArtCraft Ecosystem](#artcraft-ecosystem-exception-below-100): any star count
  - [CAE & Engineering Simulation](#cae--engineering-simulation): ★ 10+
  - [Measurement & Instruments](#measurement--instruments): ★ 1+
  - [Compliance, GRC & ISMS](#compliance-grc--isms): ★ 10+
  - [Entra ID, Identity & Endpoint](#entra-id-identity--endpoint): ★ 10+

Snapshot date: 2026-10-31 (data via GitHub search API; stars are rounded).
Note: "pushed" means the most recent push to any branch, which is a close proxy for the latest commit.

## Contents

- [SDKs, Frameworks & Learning](#sdks-frameworks--learning)
- [Awesome Lists & Directories](#awesome-lists--directories)
- [Coding & Developer Tools](#coding--developer-tools)
- [Browser, Web & Scraping](#browser-web--scraping)
- [Images, Video & Audio Operation](#images-video--audio-operation)
  - [Image & Design](#image--design)
  - [Video](#video)
  - [Audio & Sound](#audio--sound)
  - [All-in-one Creative Studios](#all-in-one-creative-studios)
  - [ArtCraft Ecosystem (exception: below ★100)](#artcraft-ecosystem-exception-below-100)
- [3D, CAD, Game Engines & Simulation](#3d-cad-game-engines--simulation)
  - [3D & Blender](#3d--blender)
  - [CAD & 3D Printing](#cad--3d-printing)
  - [Game Engines](#game-engines)
- [CAE & Engineering Simulation](#cae--engineering-simulation)
- [Measurement & Instruments](#measurement--instruments)
  - [Instrument Control & Test Equipment](#instrument-control--test-equipment)
  - [Logic Analyzers & Embedded Debugging](#logic-analyzers--embedded-debugging)
  - [LabVIEW](#labview)
  - [Data Acquisition, Sensors & Industrial Protocols](#data-acquisition-sensors--industrial-protocols)
- [Note Taking & Knowledge Bases](#note-taking--knowledge-bases)
- [Microsoft 365](#microsoft-365)
  - [Graph & Admin](#graph--admin)
  - [Teams, Outlook & Calendar](#teams-outlook--calendar)
  - [Excel & Office Documents](#excel--office-documents)
  - [OneDrive, SharePoint & Dataverse](#onedrive-sharepoint--dataverse)
- [Security](#security)
  - [SOC, SIEM & Threat Intelligence](#soc-siem--threat-intelligence)
  - [OSINT](#osint)
  - [Offensive Security & Vulnerability Scanning](#offensive-security--vulnerability-scanning)
  - [Reverse Engineering & Malware Analysis](#reverse-engineering--malware-analysis)
  - [MCP & Agent Security](#mcp--agent-security)
  - [Compliance, GRC & ISMS](#compliance-grc--isms)
  - [Entra ID, Identity & Endpoint](#entra-id-identity--endpoint)
- [No-code Databases & Database Management](#no-code-databases--database-management)
  - [No-code Databases (NocoDB-style)](#no-code-databases-nocodb-style)
  - [SQL Clients, Schema & API Generators](#sql-clients-schema--api-generators)
  - [Per-database MCP Servers](#per-database-mcp-servers)
  - [Monitoring, DBA & Governance](#monitoring-dba--governance)
- [Database, Search & RAG](#database-search--rag)
- [Memory & Context](#memory--context)
- [Agent Platforms, Gateways & Clients](#agent-platforms-gateways--clients)
- [Cloud & DevOps](#cloud--devops)
- [Productivity & Knowledge](#productivity--knowledge)
- [Domain Apps](#domain-apps)

## SDKs, Frameworks & Learning

- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) ★24.7k - Official Python SDK for MCP servers and clients.
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) ★13.7k - Official TypeScript SDK for MCP servers and clients.
- [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) ★17.6k - Open-source MCP curriculum with .NET, Java, TypeScript, Rust and Python examples.
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) ★10.8k - Fullstack MCP framework for MCP Apps and MCP servers.
- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) ★29.2k - TypeScript framework for AI agents with MCP support.

## Awesome Lists & Directories

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ★97.1k - The largest collection of MCP servers.
- [yzfly/Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) ★7.8k - Chinese-language MCP resources, servers and clients.
- [punkpeye/awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers) ★2.3k - Remote MCP servers.
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) ★1.2k - Another remote MCP server list.
- [YuzeHao2023/Awesome-MCP-Servers](https://github.com/YuzeHao2023/Awesome-MCP-Servers) ★1.1k - Curated MCP server list.
- [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) ★1.0k - Comprehensive MCP server collection.
- [MobinX/awesome-mcp-list](https://github.com/MobinX/awesome-mcp-list) ★904 - Concise MCP server list.
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ★535 - OSINT MCP servers.
- [punkpeye/awesome-mcp-devtools](https://github.com/punkpeye/awesome-mcp-devtools) ★487 - Dev tools, SDKs and testing utilities for MCP server development.
- [BlockRunAI/awesome-finance-mcp](https://github.com/BlockRunAI/awesome-finance-mcp) ★249 - MCP servers for finance agents.
- [e2b-dev/awesome-mcp-gateways](https://github.com/e2b-dev/awesome-mcp-gateways) ★193 - MCP gateways.
- [mcpHQ/awesome-mcp-servers](https://github.com/mcpHQ/awesome-mcp-servers) ★189 - Catalog of MCP servers by category.
- [SciSharp/Awesome-DotNET-MCP](https://github.com/SciSharp/Awesome-DotNET-MCP) ★156 - .NET MCP resources.
- [AlexMili/Awesome-MCP](https://github.com/AlexMili/Awesome-MCP) ★155 - General MCP resources.
- [ever-works/awesome-mcp-servers](https://github.com/ever-works/awesome-mcp-servers) ★128 - Curated MCP servers and tools.

## Coding & Developer Tools

- [upstash/context7](https://github.com/upstash/context7) ★64.0k - Up-to-date docs for AI agents.
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) ★54.5k - Chrome DevTools for coding agents.
- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) ★47.9k - Local code intelligence graph for agents.
- [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) ★36.5k - Create and edit draw.io diagrams via AI, with MCP server.
- [github/github-mcp-server](https://github.com/github/github-mcp-server) ★34.1k - GitHub's official MCP server.
- [mksglu/context-mode](https://github.com/mksglu/context-mode) ★33.0k - Context window optimization for coding agents.
- [oraios/serena](https://github.com/oraios/serena) ★30.9k - Semantic retrieval and editing toolkit for coding agents.
- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) ★23.2k - MCP to build n8n workflows.
- [MinishLab/semble](https://github.com/MinishLab/semble) ★6.3k - Fast code search for agents.
- [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) ★5.3k - Graph RAG for monorepos.
- [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) ★2.6k - MCP plugin for the x64dbg debugger.
- [aoci-spec/aoci-code](https://github.com/aoci-spec/aoci-code) ★1.8k - Git-versioned codebase and schema map for agents.

## Browser, Web & Scraping

- [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) ★90.6k - Web scraping framework with MCP server.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ★38.9k - Official Playwright MCP server.
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) ★14.0k - Thousands of ready-made scrapers via MCP.
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) ★7.7k - Official Firecrawl MCP server.
- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) ★7.3k - Control your browser from AI apps.
- [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) ★5.5k - Local-first web search, fetch and crawl over MCP.
- [vibheksoni/stealth-browser-mcp](https://github.com/vibheksoni/stealth-browser-mcp) ★3.3k - Stealth browser automation over CDP.
- [zhizhuodemao/js-reverse-mcp](https://github.com/zhizhuodemao/js-reverse-mcp) ★3.0k - JS reverse-engineering MCP server.
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) ★2.7k - Public web access MCP server.
- [A9T9/RPA](https://github.com/A9T9/RPA) ★2.1k - Browser and desktop automation with MCP server.
- [vmoranv/jshookmcp](https://github.com/vmoranv/jshookmcp) ★2.1k - Reverse-engineering workspace with 735 tools.
- [opentabs-dev/opentabs](https://github.com/opentabs-dev/opentabs) ★1.0k - Call web app APIs instead of clicking buttons.
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) ★886 - Undetected Playwright MCP server.

## Images, Video & Audio Operation

MCP servers and tools that let agents generate, edit, analyze, or process images, video and sound.

### Image & Design

- [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract) ★4.4k - Extract a website's design system (tokens, Figma variables, Tailwind) with an MCP server.
- [glincker/thesvg](https://github.com/glincker/thesvg) ★2.9k - Open SVG brand and cloud icon library, searchable via MCP.
- [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) ★1.8k - Find inspiration and create images and videos with the latest AI models.
- [marvkr/better-design](https://github.com/marvkr/better-design) ★545 - Design-system MCP server and shadcn/ui registry.

### Video

- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) ★4.1k - 42 local FFmpeg tools for cutting, captions, reframing and exports, with an MCP server.
- [jordanrendric/claude-video-vision](https://github.com/jordanrendric/claude-video-vision) ★1.4k - Lets Claude watch and understand videos (frame extraction and audio analysis).
- [xixihhhh/clipforge](https://github.com/xixihhhh/clipforge) ★1.2k - Open-source AI short-video generator for e-commerce, with MCP.

### Audio & Sound

- [MiniMax-AI/MiniMax-MCP](https://github.com/MiniMax-AI/MiniMax-MCP) ★1.6k - Official MiniMax MCP: text-to-speech, voice cloning, image and video generation.
- [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) ★548 - Local AI BGM and sound effects (Stable Audio 3), no cloud or API key.

### All-in-one Creative Studios

- [artokun/comfyui-mcp](https://github.com/artokun/comfyui-mcp) ★879 - MCP server and agent for ComfyUI: images, video and audio, 178 tools.
- [guaardvark/guaardvark](https://github.com/guaardvark/guaardvark) ★294 - Self-hosted AI studio with MCP server and local video, image, music and voice generation.

### ArtCraft Ecosystem (exception: below ★100)

[ArtCraft](https://github.com/storytold/artcraft) (★37.9k) is an open-source "IDE for artists" for AI image and video creation. A family of Rust "Craft" apps surrounds it; third-party projects below expose them to agents through MCP, CLI or skills. All of these were created in 2026 and pushed recently, but most have fewer than 100 stars, so treat them as early-stage.

Host apps (MCP surface is documented by the third-party projects below, not verified in each README):
[PhotoCraft](https://github.com/storytold/photocraft) ★75.4k (photo editor) · [LightCraft](https://github.com/storytold/lightcraft) ★15.1k (RAW editor) · [VectorCraft](https://github.com/storytold/vectorcraft) ★11.1k (vector art) · [FilmCraft](https://github.com/storytold/filmcraft) ★17.0k (video editor) · [EffectCraft](https://github.com/storytold/effectcraft) ★8.2k (motion graphics)

MCP servers, gateways and skills:

- [herdodp/snapgent-connector](https://github.com/herdodp/snapgent-connector) ★67 - Chatbot connector that links many apps via MCP.
- [midasmatterhorn/artcraft-skills](https://github.com/midasmatterhorn/artcraft-skills) ★51 - Evidence-verified agent skills for the ArtCraft suite (MCP and CLI).
- [theCosmicCrafter/artcraft-mcp](https://github.com/theCosmicCrafter/artcraft-mcp) ★33 - Rust MCP server for ArtCraft.
- [devsolux/storytold](https://github.com/devsolux/storytold) ★10 - Claude Code and Codex plugin driving 13 headless Craft MCP apps (photo, vector, video, RAW, audio, motion and more).
- [smoermeow/artcraft-mcp](https://github.com/smoermeow/artcraft-mcp) ★6 - ArtCraft subscription MCP server for Hermes Agent (image and video generation).
- [kjranyone/artcraft-agent-skills](https://github.com/kjranyone/artcraft-agent-skills) ★0 - Skills for FilmCraft (video editing) and EffectCraft (motion graphics/VFX) via CLI, MCP and GUI bridge.
- [xiewg1987/artcraft-command-bridge](https://github.com/xiewg1987/artcraft-command-bridge) ★0 - One MCP server for all 13 Craft apps (5 tools instead of 799).
- [jw2122-kiwi/artcraft-mcp](https://github.com/jw2122-kiwi/artcraft-mcp) ★0 - MCP gateway for 13 Craft apps behind one HTTP endpoint.
- [GadatheGod/artcraft-mcp-unified-router](https://github.com/GadatheGod/artcraft-mcp-unified-router) ★0 - Unified MCP router with dynamic tool discovery.
- [Shin-seong-su/artcraft-mcp](https://github.com/Shin-seong-su/artcraft-mcp) ★0 - Control local ArtCraft apps from ChatGPT (macOS installer beta).
- [sandraschi/democraft-mcp](https://github.com/sandraschi/democraft-mcp) ★1 - Live demos of the 13 Craft apps producing real files (MP4, WAV, DOCX and more), MCP server and web app.
- [kosecom/art-cli](https://github.com/kosecom/art-cli) ★1 - ArtCraft integration for Hermes via CLI and stdio MCP (Windows and macOS).
- [dnviti/artcraft-skills](https://github.com/dnviti/artcraft-skills) ★1 - Community skills for ArtCraft apps, installable with skills.sh.
- [lznnnnn1998/dsh-artcraft](https://github.com/lznnnnn1998/dsh-artcraft) ★1 - 12 DSH plugins driving Craft apps (CADCraft, GridCraft, SoundCraft and more).
- [verdulife/pi-artcraft](https://github.com/verdulife/pi-artcraft) ★0 - Pi package toggling FigCraft and VectorCraft per session with MCP attached.
- [joaoalvesmarrucho/patio-artcraft](https://github.com/joaoalvesmarrucho/patio-artcraft) ★0 - Skill driving VectorCraft through its official MCP route.
- [anton-belkin/aitocraft](https://github.com/anton-belkin/aitocraft) ★0 - One MCP connector to open documents in GridCraft, WordCraft and DeckCraft.
- [MGBuilds9/craft-agent-kit](https://github.com/MGBuilds9/craft-agent-kit) ★0 - CLI wrappers, MCP configs and skills for all 13 apps.
- [esanchma/mcp-trigger](https://github.com/esanchma/mcp-trigger) ★0 - Stdio MCP server that opens the ArtCraft desktop app only when a tool is called.
- [MGrunwald42/safecraft-mcp](https://github.com/MGrunwald42/safecraft-mcp) ★0 - Run ArtCraft tools through MCP inside a sandbox.
- [xouel/artcraft-ai-bridge](https://github.com/xouel/artcraft-ai-bridge) ★0 - C#/WPF MCP bridge for FigCraft, PhotoCraft and GridCraft on Windows.
- [kleinhansda/artcraft-mcp-ha](https://github.com/kleinhansda/artcraft-mcp-ha) ★0 - Home Assistant add-on exposing VectorCraft, PhotoCraft and PdfCraft as remote MCP servers.

## 3D, CAD, Game Engines & Simulation

MCP servers that let agents drive 3D tools, CAD, 3D printers and game engines. For engineering simulation see [CAE & Engineering Simulation](#cae--engineering-simulation).

### 3D & Blender

- [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) ★32.9k - Community plugin to control Blender 3D with any LLM (Blender MCP).
- [pascalorg/editor](https://github.com/pascalorg/editor) ★25.2k - Open-source 3D architectural editor with a local CLI and MCP tools.
- [scenario-labs/skills](https://github.com/scenario-labs/skills) ★1.3k - Skills for images, video, audio and 3D via the Scenario MCP, plus teams driving Blender, Maya, ZBrush, Unreal and Unity.
- [scenario-labs/blender-plugin](https://github.com/scenario-labs/blender-plugin) ★918 - Blender extension with AI images, video, 3D and PBR materials, plus a local MCP server.
- [EL4CTEO/blender-skills](https://github.com/EL4CTEO/blender-skills) ★615 - Professional Blender workflows (modeling, UVs, PBR, rigging, export) as agent skills.
- [reality-opened/openreality](https://github.com/reality-opened/openreality) ★552 - Phone video to AI-queryable 3D scenes, with MCP tools.
- [squall01337/mixamo-llm-mocap](https://github.com/squall01337/mixamo-llm-mocap) ★420 - Turn any video into a Mixamo-rig animation, applied in Blender via MCP.
- [instruktlabs/kiln](https://github.com/instruktlabs/kiln) ★307 - Procedural 3D asset builder with local MCP server and GLB export.
- [nirholas/three.ws](https://github.com/nirholas/three.ws) ★262 - Platform for 3D AI agents and rigged GLB avatars with a remote MCP server.
- [HoldMyBeer-gg/blenderwright](https://github.com/HoldMyBeer-gg/blenderwright) ★183 - Blender MCP server with hundreds of tools for modeling, materials and rendering.

### CAD & 3D Printing

- [spkane/freecad-addon-robust-mcp-server](https://github.com/spkane/freecad-addon-robust-mcp-server) ★263 - FreeCAD robust MCP server and bridge workbench.
- [DMontgomery40/mcp-3D-printer-server](https://github.com/DMontgomery40/mcp-3D-printer-server) ★257 - MCP for 3D printer APIs (OctoPrint, Klipper, Bambu and more) and STL operations.
- [DMontgomery40/bambu-printer-mcp](https://github.com/DMontgomery40/bambu-printer-mcp) ★256 - MCP for Bambu Lab printers: STL tools, slicing and printer control.
- [codeofaxel/Kiln](https://github.com/codeofaxel/Kiln) ★231 - MCP server for 3D printing with git-style design version control.
- [U-C4N/Autocad-MCP](https://github.com/U-C4N/Autocad-MCP) ★206 - AutoCAD MCP server with 240+ tools to draw, edit and read DWG/DXF files.

### Game Engines

- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) ★4.6k - AI skills, MCP tools and CLI for the Unity Engine.
- [ChiR24/Unreal_mcp](https://github.com/ChiR24/Unreal_mcp) ★998 - MCP server controlling Unreal Engine via a C++ Automation Bridge plugin.
- [kevinpbuckley/VibeUE](https://github.com/kevinpbuckley/VibeUE) ★800 - Unreal Engine vibe-coding tool with MCP server.
- [AnkleBreaker-Studio/unity-mcp-server](https://github.com/AnkleBreaker-Studio/unity-mcp-server) ★531 - Unity MCP server with 268 tools for Editor and Unity Hub.
- [tugcantopaloglu/godot-mcp](https://github.com/tugcantopaloglu/godot-mcp) ★506 - Godot 4.x MCP server with 157 tools.
- [db-lyon/ue-mcp](https://github.com/db-lyon/ue-mcp) ★462 - Unreal Engine development toolkit exposed as MCP tools.
- [IvanMurzak/Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) ★317 - MCP integration for the Godot Editor in C#.
- [FunplayAI/funplay-unity-mcp](https://github.com/FunplayAI/funplay-unity-mcp) ★276 - Unity Editor MCP server with code execution and play-mode automation.

## CAE & Engineering Simulation

Structural (FEA), fluid (CFD), multiphysics and numerical computing. Star bar for this section is ★10+ because the field is young.

- [matlab/matlab-mcp-server](https://github.com/matlab/matlab-mcp-server) ★1.7k - Official MathWorks MATLAB MCP server.
- [tangency-labs/fieldcraft](https://github.com/tangency-labs/fieldcraft) ★253 - Rust modeler for structures, heat and fluids: meshing, nonlinear FEA and lattice Boltzmann CFD, built for engineers and agents.
- [yusong652/itasca-mcp](https://github.com/yusong652/itasca-mcp) ★225 - MCP server for ITASCA engines (PFC, FLAC, 3DEC): geotechnical and geomechanics simulation.
- [Whfkl/Abaqus-Control-MCP](https://github.com/Whfkl/Abaqus-Control-MCP) ★215 - Local MCP bridge for real-time control of Abaqus/CAE.
- [gokeshenzhen/TraceWeave](https://github.com/gokeshenzhen/TraceWeave) ★125 - MCP server for RTL simulation debugging (VCS/Xcelium logs, waveforms, UVM).
- [hongwenwang36-eng/ANSYS-Workbench-mcp](https://github.com/hongwenwang36-eng/ANSYS-Workbench-mcp) ★97 - Local MCP bridge for Ansys Workbench and MAPDL batch automation.
- [cavoiie/fluent-cfd-skill](https://github.com/cavoiie/fluent-cfd-skill) ★86 - Skill for Ansys Fluent and PyFluent CFD workflows.
- [armpro24-blip/cad-cae-copilot](https://github.com/armpro24-blip/cad-cae-copilot) ★83 - Text-to-CAD and text-to-CAE workbench (build123d/OpenCASCADE, CalculiX) with MCP tools.
- [ansys/pyfluent-mcp](https://github.com/ansys/pyfluent-mcp) ★67 - Official PyFluent MCP server.
- [kimimgo/awesome-ai-cae](https://github.com/kimimgo/awesome-ai-cae) ★64 - Curated list of 100+ AI-ready CAE tools (CFD, FEA, SPH, DEM, MCP servers).
- [ansys/pymechanical-mcp](https://github.com/ansys/pymechanical-mcp) ★34 - Official PyMechanical MCP server.
- [sandraschi/freecad-mcp](https://github.com/sandraschi/freecad-mcp) ★33 - FreeCAD automation with FluidX3D and OpenFOAM CFD extensions.
- [ansys/pyaedt-mcp](https://github.com/ansys/pyaedt-mcp) ★30 - Official PyAEDT MCP server (electromagnetics).
- [open-PASO/openPASO](https://github.com/open-PASO/openPASO) ★29 - MCP server that runs nine finite-element and multiphysics codes with cross-code coupling.
- [Tomsabay/abaqus_agent](https://github.com/Tomsabay/abaqus_agent) ★29 - AI-driven Abaqus workbench with verification gates.
- [ansys/pyansys-common-mcp](https://github.com/ansys/pyansys-common-mcp) ★23 - Official PyAnsys common MCP.
- [kimimgo/viznoir](https://github.com/kimimgo/viznoir) ★19 - AI-ready VTK visualization for CFD and OpenFOAM results.
- [isabecurtis023-lang/HarnessFOAM](https://github.com/isabecurtis023-lang/HarnessFOAM) ★17 - Multi-agent framework automating OpenFOAM CFD simulation (LangGraph, MCP).

## Measurement & Instruments

MCP servers for physical measurement, test equipment, embedded debugging and industrial protocols. Star bar for this section is ★1+ because the field is very young (almost everything here appeared in 2026). Expect rough edges.

### Instrument Control & Test Equipment

- [lagerdata/lager](https://github.com/lagerdata/lager) ★9 - Hardware test automation: drive real instruments and embedded targets from a laptop or CI.
- [Anai-Guo/LabAgent](https://github.com/Anai-Guo/LabAgent) ★8 - AI lab assistant with 46 measurement templates for GPIB/PyVISA instruments (Keithley, Lakeshore).
- [mrn2se/AgenticWebInstrumentControl](https://github.com/mrn2se/AgenticWebInstrumentControl) ★6 - Web, AI-agent and SCPI control for cheap USB oscilloscopes and logic analyzers.
- [techmanual-ai/lablink-mcp](https://github.com/techmanual-ai/lablink-mcp) ★5 - Unified MCP server for lab equipment over VISA/SCPI, SSH, REST and serial.
- [sandraschi/oscilloscope-mcp](https://github.com/sandraschi/oscilloscope-mcp) ★5 - FastMCP server for USB PC oscilloscopes.
- [reinhardjvv/labrat](https://github.com/reinhardjvv/labrat) ★3 - Universal interface for lab automation (instrument control, SCPI).
- [mabl/pyMSO5000](https://github.com/mabl/pyMSO5000) ★3 - Python client and MCP server for Rigol MSO5000 oscilloscopes.
- [KenosInc/dwf-mcp-server](https://github.com/KenosInc/dwf-mcp-server) ★3 - MCP server for the Digilent Analog Discovery 3 (scope, signal generator, logic analysis).
- [fengbihe/ScopeBridge](https://github.com/fengbihe/ScopeBridge) ★3 - Local oscilloscope workbench with web UI, offline voice and MCP tools.
- [colingimenez/SCPI_MCP](https://github.com/colingimenez/SCPI_MCP) ★1 - Benchtop waveform generator, multimeter, oscilloscope and power supply over SCPI.
- [mp911de/siglent-scpi-mcp](https://github.com/mp911de/siglent-scpi-mcp) ★1 - MCP server for Siglent oscilloscopes (SCPI over TCP).
- [RainfallMax/instr-core](https://github.com/RainfallMax/instr-core) ★1 - Type system and safety firewall between AI assistants and physical instruments.
- [sandraschi/spectrum-analyzer-mcp](https://github.com/sandraschi/spectrum-analyzer-mcp) ★1 - Spectrum analyzer MCP for RTL-SDR and TinySA.
- [BonBear/open-ps3005d](https://github.com/BonBear/open-ps3005d) ★1 - Control for the Velleman PS3005D lab power supply with an MCP server.
- [f-steff/KUAIQU-NICE-PSU](https://github.com/f-steff/KUAIQU-NICE-PSU) ★1 - Controller for KUAIQU-NICE-POWER programmable DC supplies with an MCP stdio server.

### Logic Analyzers & Embedded Debugging

- [Clifford-Swartz/peripheral-pretender](https://github.com/Clifford-Swartz/peripheral-pretender) ★49 - QEMU digital twin of Microchip boards with logic-analyzer timeline, fault injection and MCP.
- [YaoIsAI/SerialRUN](https://github.com/YaoIsAI/SerialRUN) ★38 - Serial port debugging assistant with Modbus, PLC, CAN, I2C/SPI support and an MCP server.
- [keyuraghao/chipwhisperer-studio](https://github.com/keyuraghao/chipwhisperer-studio) ★24 - ChipWhisperer side-channel and fault-injection studio with scope, logic analyzer and MCP server.
- [Kyin-code/KDock](https://github.com/Kyin-code/KDock) ★16 - Embedded-focused AI agent platform: serial/network I/O, flashing, scope and logic analyzer tools.
- [KenosInc/sigrok-mcp-server](https://github.com/KenosInc/sigrok-mcp-server) ★14 - AI logic analyzer control via sigrok-cli for signal capture and protocol decoding.
- [hugelzhang/atk-logic-mcp](https://github.com/hugelzhang/atk-logic-mcp) ★3 - MCP server for the ALIENTEK ATK-Logic analyzer with 208 sigrok decoders.
- [sandraschi/logic-analyzer-mcp](https://github.com/sandraschi/logic-analyzer-mcp) ★2 - USB logic analyzer MCP with a sigrok backend.
- [ling99LL/ag32-logic-analyzer](https://github.com/ling99LL/ag32-logic-analyzer) ★1 - Four-channel logic analyzer on AG32VF303 with signal generator and MCP server.
- [controlpaths/tramuntana](https://github.com/controlpaths/tramuntana) ★1 - Open hardware tool for debugging embedded systems (SPI/I2C/UART, scope, logic analyzer) with an MCP server.

### LabVIEW

- [Zuehlke/labview-mcp](https://github.com/Zuehlke/labview-mcp) ★93 - Connect AI to LabVIEW.
- [JanGoebel/LabVIEW-MCP-Server-Toolkit](https://github.com/JanGoebel/LabVIEW-MCP-Server-Toolkit) ★67 - Toolkit to host MCP servers from LabVIEW.
- [chinayuren2022-2025/labview-native-mcp](https://github.com/chinayuren2022-2025/labview-native-mcp) ★11 - Native LabVIEW 2021 VI Scripting MCP for Windows (create, wire, run VIs via COM).
- [abcdefghkang/labview-vi-mcp](https://github.com/abcdefghkang/labview-vi-mcp) ★2 - LabVIEW VI development and HMI restoration skill via the LabVIEW Native MCP server.
- [kostandrey/labview-mcp](https://github.com/kostandrey/labview-mcp) ★1 - Early proof of concept for self-driving LabVIEW code generation.
- [JorgenSteen/labview-mcp-skills](https://github.com/JorgenSteen/labview-mcp-skills) ★1 - Skills for using the LabVIEW MCP effectively.
- [LYXLCF/-LabVIEW-CSM-MCP-Server](https://github.com/LYXLCF/-LabVIEW-CSM-MCP-Server) ★1 - MCP server for LabVIEW CSM (Communicable State Machine) block diagrams.

### Data Acquisition, Sensors & Industrial Protocols

- [stixez/droid-mcp](https://github.com/stixez/droid-mcp) ★40 - Android SDK and MCP server exposing 157 device tools including sensors and camera.
- [nobrega8/modbench](https://github.com/nobrega8/modbench) ★12 - Cross-platform Modbus TCP/RTU client for device testing and register debugging (MCP server topic).
- [daqifi/daqifi-core](https://github.com/daqifi/daqifi-core) ★5 - Official .NET SDK for DAQiFi wireless data acquisition devices, with an MCP server.
- [Sgh1107/FieldLink-Modbus-DataAcquisition](https://github.com/Sgh1107/FieldLink-Modbus-DataAcquisition) ★3 - Qt6 industrial Modbus data acquisition platform (TCP/RTU, MQTT, alarms) with MCP support.

## Note Taking & Knowledge Bases

### Obsidian & Markdown Vaults

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) ★4.5k - MCP server for Obsidian via the Local REST API plugin.
- [coddingtonbear/obsidian-local-rest-api](https://github.com/coddingtonbear/obsidian-local-rest-api) ★3.1k - Secure REST API and MCP server for your Obsidian vault.
- [tianma-if/edgeever](https://github.com/tianma-if/edgeever) ★3.1k - AI-native knowledge base (Evernote/Obsidian alternative) with native MCP.
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) ★1.7k - Lightweight MCP server for safe Obsidian vault access.
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) ★749 - Simple MCP server for Obsidian.
- [cyanheads/obsidian-mcp-server](https://github.com/cyanheads/obsidian-mcp-server) ★698 - Read, write, search and edit Obsidian notes, tags and frontmatter via MCP.
- [docsagent/docsagent](https://github.com/docsagent/docsagent) ★579 - Private knowledge base search across Zotero, Obsidian and Apple Notes.
- [rotbit/xedit](https://github.com/rotbit/xedit) ★184 - Local-first markdown editor (Obsidian/Notion style) with MCP for AI.
- [andylow92/file-system-brain-mcp](https://github.com/andylow92/file-system-brain-mcp) ★162 - Markdown vault with 24-tool MCP server, semantic search and RAG.

### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) ★4.7k - Official Notion MCP server.
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) ★924 - MCP server connecting Notion to MCP clients.
- [awkoy/notion-mcp-server](https://github.com/awkoy/notion-mcp-server) ★179 - Notion MCP server with token auth and a small tool surface.
- [makenotion/lore](https://github.com/makenotion/lore) ★179 - Persistent shared AI memory backed by Notion.

### Zotero, Logseq, Joplin & Apple Notes

- [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp) ★5.7k - Connect your Zotero library to AI assistants.
- [papersgpt/papersgpt-for-zotero](https://github.com/papersgpt/papersgpt-for-zotero) ★2.7k - AI research tool for Zotero with built-in MCP server.
- [cookjohn/zotero-mcp](https://github.com/cookjohn/zotero-mcp) ★1.3k - Zotero plugin enabling AI assistant integration through MCP.
- [ergut/mcp-logseq](https://github.com/ergut/mcp-logseq) ★349 - MCP server for LogSeq via its local HTTP API.
- [introfini/ZotSeek](https://github.com/introfini/ZotSeek) ★238 - Local AI semantic search for Zotero with a built-in MCP server.
- [alondmnt/joplin-mcp](https://github.com/alondmnt/joplin-mcp) ★174 - MCP server for the Joplin note taking app.
- [sweetrb/apple-notes-mcp](https://github.com/sweetrb/apple-notes-mcp) ★173 - Read, search, create and edit Apple Notes on macOS.
- [kujenga/zotero-mcp](https://github.com/kujenga/zotero-mcp) ★162 - Lightweight MCP server for the Zotero API.

## Microsoft 365

### Graph & Admin

- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) ★1.1k - MCP server for Microsoft 365 and Office services through the Graph API.
- [merill/lokka](https://github.com/merill/lokka) ★310 - MCP for Microsoft 365 including Microsoft Graph.
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) ★135 - Manage Microsoft 365 with an MCP server (CLI for Microsoft 365).

### Teams, Outlook & Calendar

- [Vexa-ai/vexa](https://github.com/Vexa-ai/vexa) ★2.9k - Meeting transcription API for Google Meet, Microsoft Teams and Zoom, with MCP server.
- [ridafkih/keeper.sh](https://github.com/ridafkih/keeper.sh) ★1.4k - Calendar sync and universal calendar MCP server (Google, Outlook, Office 365, iCloud, CalDAV).
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) ★463 - Read, create and reply to Microsoft Teams messages.
- [floriscornel/teams-mcp](https://github.com/floriscornel/teams-mcp) ★148 - Microsoft Teams and Graph API access: messaging, search and user management.
- [tecnologicachile/mail-mcp](https://github.com/tecnologicachile/mail-mcp) ★112 - Secure IMAP/SMTP/EWS/Graph mail MCP server in Rust (Microsoft 365, Gmail and more).

### Excel & Office Documents

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) ★4.3k - Create and edit Excel files with charts, PivotTables and formulas (no Excel required).
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) ★836 - Automate real Microsoft Excel: Power Query, DAX, VBA, PivotTables.
- [harumiWeb/exstruct](https://github.com/harumiWeb/exstruct) ★203 - Excel to structured JSON for LLM pipelines, plus agent read/write via CLI and MCP.
- [Aimino-Tech/opendocswork-mcp](https://github.com/Aimino-Tech/opendocswork-mcp) ★162 - Rust MCP server for Excel, Word and PowerPoint processing.

### OneDrive, SharePoint & Dataverse

- [microsoft/Dataverse-skills](https://github.com/microsoft/Dataverse-skills) ★250 - Dataverse skills for AI agents, wrapping the Dataverse MCP server, CLI and Python SDK.
- [lionello/onedrive-cli](https://github.com/lionello/onedrive-cli) ★178 - Command line interface and MCP for OneDrive.
- [microsoft/SharePoint-Embedded-Samples](https://github.com/microsoft/SharePoint-Embedded-Samples) ★108 - SharePoint Embedded samples, including an MCP server for AI coding agents.

## Security

MCP servers for defensive and offensive security work. Use offensive tools only on systems you are authorized to test. For reverse-engineering tools listed elsewhere see [x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server), [js-reverse-mcp](https://github.com/zhizhuodemao/js-reverse-mcp) and [jshookmcp](https://github.com/vmoranv/jshookmcp).

### SOC, SIEM & Threat Intelligence

- [7onez/cti-expert](https://github.com/7onez/cti-expert) ★619 - Cyber threat intelligence and OSINT analysis skill with 79 typed MCP tools and ICD-203 reports.
- [google/mcp-security](https://github.com/google/mcp-security) ★536 - Google Security Operations (Chronicle SIEM/SOAR), Threat Intelligence and Security Command Center MCP servers.
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) ★274 - Official CrowdStrike Falcon MCP for security analysis and threat hunting.
- [gensecaihq/Wazuh-MCP-Server](https://github.com/gensecaihq/Wazuh-MCP-Server) ★262 - Wazuh SIEM MCP server with 55 tools: alert triage, threat hunting, vulnerability management and compliance mapping (PCI DSS, GDPR, HIPAA, NIST CSF, ISO 27001).
- [Sentinel-One/purple-mcp](https://github.com/Sentinel-One/purple-mcp) ★101 - SentinelOne Purple AI and security services via MCP: alerts, vulnerabilities, misconfigurations and inventory.

### OSINT

- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) ★1.8k - Passive OSINT engine with 21 tools as CLI, MCP server and web UI.
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) ★268 - Username search across thousands of sites with maigret.
- [OSINT-Experts-Society/Consensus-OSINT](https://github.com/OSINT-Experts-Society/Consensus-OSINT) ★194 - Username, email and phone OSINT with 9,700+ lookup checks and an MCP server.
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) ★183 - Shodan MCP: devices, IP reconnaissance, DNS and CVE/CPE intelligence.
- [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) ★154 - VirusTotal MCP for URLs, files, IPs and domains.
- More: [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ★535 (curated list).

### Offensive Security & Vulnerability Scanning

- [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) ★13.2k - MCP server letting agents run 150+ security tools for pentesting and bug bounty work.
- [ZeroDayEvil/ai-security-tool](https://github.com/ZeroDayEvil/ai-security-tool) ★1.3k - AI security terminal and vulnerability scanner (CVE, SBOM) with MCP.
- [Aletheore/Aletheore](https://github.com/Aletheore/Aletheore) ★661 - Evidence-grounded repository audit CLI with MCP server, secrets detection and dependency vulnerability checks.
- [ARCANGEL0/Mitsu](https://github.com/ARCANGEL0/Mitsu) ★537 - Agentic pentest operator with 165+ MCP-connected tools.
- [shinthink/blitzstrike](https://github.com/shinthink/blitzstrike) ★515 - MCP security-audit toolbelt: reconnaissance, analysis and validation.
- [hahwul/gori](https://github.com/hahwul/gori) ★131 - Keyboard-driven HTTP intercepting proxy and pentesting toolkit for humans and agents.
- [sinewaveai/agent-security-scanner-mcp](https://github.com/sinewaveai/agent-security-scanner-mcp) ★123 - Security scanner for coding agents: prompt-injection firewall, package hallucination detection, SAST.
- [RamKansal/pentestMCP](https://github.com/RamKansal/pentestMCP) ★113 - MCP designed for penetration testers.

### Reverse Engineering & Malware Analysis

- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) ★13.2k - Bridge IDA Pro with language models through MCP.
- [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) ★6.0k - Ghidra MCP server with 200+ tools (GUI plugin and headless server).
- [CYB3RMX/Qu1cksc0pe](https://github.com/CYB3RMX/Qu1cksc0pe) ★2.1k - All-in-one malware analysis tool with MCP server.
- [miscusi-peek/cheatengine-mcp-bridge](https://github.com/miscusi-peek/cheatengine-mcp-bridge) ★1.7k - Connect agents to Cheat Engine for memory analysis and reverse engineering.
- [qybaihe/bla](https://github.com/qybaihe/bla) ★1.6k - Adversarial defense shield protecting binaries and bundles against AI reverse-engineering agents.
- [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) ★1.3k - AI reverse-engineering platform and MCP server for Ghidra, Frida, x64dbg and Rizin.
- [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered) ★963 - 17,000+ open-source tools built by reverse engineering, with search site and MCP server.
- [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) ★886 - MCP server for reverse engineering in Ghidra.
- [sjkim1127/Reversecore_MCP](https://github.com/sjkim1127/Reversecore_MCP) ★215 - Security-first MCP for reverse engineering, malware analysis and forensics (Radare2, YARA, LIEF).

### MCP & Agent Security

Gateways, guardrails, secrets, identity and audit trails for agents and MCP servers.

- [casdoor/casdoor](https://github.com/casdoor/casdoor) ★14.7k - Agent-first IAM and MCP/LLM gateway with OAuth, OIDC, SAML, SCIM, WebAuthn, TOTP and MFA.
- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) ★4.4k - Enterprise AI platform with guardrails, MCP registry and gateway.
- [octelium/octelium](https://github.com/octelium/octelium) ★4.1k - Self-hosted zero-trust access platform that also works as an API/AI/MCP gateway (SSO, MFA, policy-as-code).
- [mnemox-ai/tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) ★1.4k - Decision audit trail for AI trading agents with a tamper-evident hash chain.
- [agentic-community/mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) ★1.0k - Enterprise MCP gateway and registry with OAuth, Keycloak and Entra ID integration, audit-friendly tool access.
- [VibeTensor/attestix](https://github.com/VibeTensor/attestix) ★841 - Agent identity, signed credentials, delegated authority and governance evidence.
- [HelpCode-ai/anythingmcp](https://github.com/HelpCode-ai/anythingmcp) ★765 - MCP gateway turning REST, GraphQL, SOAP or SQL APIs into tools, with RBAC, SSO and audit logs.
- [notinferred/keypaste](https://github.com/notinferred/keypaste) ★663 - KeePass-compatible password and secrets manager for people working with AI agents.
- [sandbaseai/sandbase-harness](https://github.com/sandbaseai/sandbase-harness) ★639 - Local-first agent runtime and MCP bridge with sandboxed sessions, credentials and audit/replay.
- [awslabs/iam-policy-autopilot](https://github.com/awslabs/iam-policy-autopilot) ★502 - Generate baseline AWS IAM policies from code, as CLI and MCP server.
- [btsouth/toolport](https://github.com/btsouth/toolport) ★232 - Local-first MCP gateway with OS-keychain secrets, tool integrity checks and quarantine.
- [MCP-Manager/MCP-Security-Checklists](https://github.com/MCP-Manager/MCP-Security-Checklists) ★199 - Security checklists for MCP servers, clients and hosts.
- [Bevel-Software/Hexis](https://github.com/Bevel-Software/Hexis) ★122 - Centrally manage agent skills, tools, permissions and identity across an org.

### Compliance, GRC & ISMS

Star bar for this subsection is ★10+. ISO 27001 coverage is still thin: only one dedicated ISO 27001 MCP server exists at the snapshot date.

- [intuitem/ciso-assistant-community](https://github.com/intuitem/ciso-assistant-community) ★4.6k - GRC platform for risk, compliance and audit with 200+ frameworks (ISO 27001, NIST CSF, SOC 2, NIS2, DORA, GDPR) and MCP support.
- [arthurpanhku/DocSentinel](https://github.com/arthurpanhku/DocSentinel) ★89 - MCP server for assessing security documents and questionnaires: risks, compliance gaps and remediation.
- [Farenhytee/database-sentinel](https://github.com/Farenhytee/database-sentinel) ★51 - Read-only security audit MCP server for Supabase (RLS, exposed keys), with scored reports.
- [Sushegaad/MCP-Server-for-ISO27001](https://github.com/Sushegaad/MCP-Server-for-ISO27001) ★35 - Stateful ISO 27001:2022 ISMS server: gap assessments, risk management, policy generation, evidence tracking and audits (encrypted local SQLite).
- [NISD2/open-isms](https://github.com/NISD2/open-isms) ★20 - Free, self-hostable ISMS for the EU NIS 2 Directive (GDPR, EU AI Act, CRA) with MCP support.
- [writer/cerebro](https://github.com/writer/cerebro) ★15 - Turns security, identity, cloud and compliance data into evidence-backed context for agents.
- [ComplianceCow/cow-mcp](https://github.com/ComplianceCow/cow-mcp) ★13 - MCP servers (Rules, Insights, Workflow, Assistant) automating GRC tasks.
- [Threat-Vector-Security/guardian-agent](https://github.com/Threat-Vector-Security/guardian-agent) ★13 - Local workstation and network security with threat modeling and GRC via scoped MCP; optional Entra ID integration.
- [AmanSK5/shadow-ai-guard](https://github.com/AmanSK5/shadow-ai-guard) ★13 - Shows which AI tools (including MCP) your organisation actually uses, with a governance portal (ISO 27001 / ISO 42001 oriented).

### Entra ID, Identity & Endpoint

Star bar for this subsection is ★10+. Microsoft Entra ID, Intune and identity-aware MCP access. See also [Microsoft 365](#microsoft-365).

- [okieselbach/AutopilotMonitor](https://github.com/okieselbach/AutopilotMonitor) ★90 - Windows Autopilot and Intune enrollment monitoring with an MCP server for AI-assisted troubleshooting.
- [Jinssi/AuthFlowMap](https://github.com/Jinssi/AuthFlowMap) ★66 - Interactive map of OAuth, Conditional Access, Entra Agent ID and MCP authentication flows (learning resource).
- [OpenAdminOS/greybeard](https://github.com/OpenAdminOS/greybeard) ★34 - Microsoft 365, Intune and Entra admin skills plus MCP servers, with a human approval gate on every tenant write.
- [babs/mcp-auth-proxy](https://github.com/babs/mcp-auth-proxy) ★18 - OAuth 2.1 and OIDC bridge for private MCP servers (works with Keycloak to Entra).
- [aixolotl/microsoft-planner-mcp](https://github.com/aixolotl/microsoft-planner-mcp) ★15 - Unofficial Microsoft Planner MCP server using Graph and Entra ID delegated auth.
- [microsoft/entrabot](https://github.com/microsoft/entrabot) ★12 - Reference implementation giving a device-local AI agent its own Microsoft Entra identity (Agent 365, Entra Agent ID).
- [nelladath/Intune-mcp-server](https://github.com/nelladath/Intune-mcp-server) ★12 - MCP server for Microsoft Intune management via Graph.

## No-code Databases & Database Management

Tools for managing SQL data without hand-writing SQL, plus per-database MCP servers and DBA tooling.

### No-code Databases (NocoDB-style)

Self-hostable Airtable alternatives that sit on top of SQL databases. For the five platforms marked "built-in MCP", MCP code was confirmed by searching each repository's source (not by reading documentation), so check the project docs for setup.

- [nocodb/nocodb](https://github.com/nocodb/nocodb) ★65.4k - Self-hostable Airtable alternative over PostgreSQL/SQLite; built-in MCP (MCP service and tokens in source).
- [directus/directus](https://github.com/directus/directus) ★38.8k - Turn a SQL database (Postgres, MySQL, SQLite, MSSQL) into a headless CMS and admin app; built-in MCP (OAuth service in source).
- [teableio/teable](https://github.com/teableio/teable) ★21.9k - AI spreadsheet on PostgreSQL; MCP-related OAuth components in source.
- [gristlabs/grist-core](https://github.com/gristlabs/grist-core) ★12.0k - Relational spreadsheet-database; MCP connect banner in the client.
- [baserow/baserow](https://github.com/baserow/baserow) ★6.2k - No-code database and app builder on PostgreSQL; built-in MCP (MCP backend modules in source; official config repo [baserow/baserow-mcp](https://github.com/baserow/baserow-mcp) ★2).
- [supabase/mcp](https://github.com/supabase/mcp) ★3.0k - Official Supabase MCP server (Postgres, auth, storage).
- [julien040/anyquery](https://github.com/julien040/anyquery) ★1.8k - One SQL interface for 60+ tools (Notion, Airtable, GitHub) exposed through MCP.
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) ★456 - Airtable MCP server.
- [saltmd/salt.md](https://github.com/saltmd/salt.md) ★176 - Docs, databases and realtime collaboration with an MCP server in one Go binary and one SQLite file.

### SQL Clients, Schema & API Generators

- [TabularisDB/tabularis](https://github.com/TabularisDB/tabularis) ★5.3k - Desktop SQL workspace with built-in MCP server, SQL notebooks and visual EXPLAIN.
- [bytebase/dbhub](https://github.com/bytebase/dbhub) ★3.8k - Token-conscious database MCP server for Postgres, MySQL, SQL Server, Oracle, MariaDB and SQLite.
- [dineug/erd-editor](https://github.com/dineug/erd-editor) ★1.7k - ERD editor that agents can edit live over MCP.
- [pgplex/pgconsole](https://github.com/pgplex/pgconsole) ★157 - Minimal Postgres editor for speed, collaboration and AI (MCP server).
- [faucetdb/faucet](https://github.com/faucetdb/faucet) ★167 - Turn any SQL database into a governed REST API with RBAC and MCP support.

### Per-database MCP Servers

- [timescale/pg-aiguide](https://github.com/timescale/pg-aiguide) ★1.9k - MCP server and Claude plugin for Postgres skills and documentation.
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) ★1.4k - Secure MCP server for MySQL.
- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) ★1.2k - Official MCP server for MongoDB and MongoDB Atlas.
- [redis/mcp-redis](https://github.com/redis/mcp-redis) ★641 - Official Redis MCP server.
- [timescale/tiger-cli](https://github.com/timescale/tiger-cli) ★127 - Tiger Cloud CLI with an MCP server for production-level Postgres code.

### Monitoring, DBA & Governance

- [BetterDB-inc/monitor](https://github.com/BetterDB-inc/monitor) ★1.3k - Real-time monitoring, slowlog analysis and audit trails for Valkey and Redis.
- [erikdarlingdata/PerformanceMonitor](https://github.com/erikdarlingdata/PerformanceMonitor) ★526 - SQL Server and Postgres performance monitoring with an MCP server for AI analysis.
- [ashishsinha1602/schemagate](https://github.com/ashishsinha1602/schemagate) ★179 - Text-to-SQL access control: gives the LLM only the tables the caller may read (row-level-security aware).
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) ★164 - 30+ PostgreSQL DBA tools: performance, bloat, locks, autovacuum.
- [postgres-ai/postgresai](https://github.com/postgres-ai/postgresai) ★140 - Postgres observability for humans and AI agents.
- [benseverndev-oss/goldenmatch](https://github.com/benseverndev-oss/goldenmatch) ★135 - Entity resolution and master data management with 97 MCP tools (Postgres, DuckDB).

## Database, Search & RAG

For database clients and DBA tooling see [No-code Databases & Database Management](#no-code-databases--database-management).

- [xerj-org/xerj](https://github.com/xerj-org/xerj) ★17.8k - Rust search engine and MCP server (BM25, vector, hybrid).
- [pipeshub-ai/pipeshub-ai](https://github.com/pipeshub-ai/pipeshub-ai) ★3.9k - Permission-aware context layer over company knowledge (Slack, Drive, Microsoft 365 and more).

## Memory & Context

- [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) ★2.1k - Persistent memory with knowledge graph for agents.
- [mex-memory/mex](https://github.com/mex-memory/mex) ★1.8k - Team memory shared through Git.
- [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) ★78.4k - Compress tool outputs and RAG chunks (library, proxy, MCP server).

## Agent Platforms, Gateways & Clients

- [n8n-io/n8n](https://github.com/n8n-io/n8n) ★209.2k - Workflow automation with MCP client and server.
- [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) ★108.6k - Gemini agent in your terminal.
- [cheaper-inference/OmniRoute](https://github.com/cheaper-inference/OmniRoute) ★83.1k - AI gateway with MCP/A2A support.
- [ruvnet/ruflo](https://github.com/ruvnet/ruflo) ★80.4k - Multi-agent swarm harness.
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ★53.1k - AI workspace with MCP client.
- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) ★45.2k - Agent assistant framework with MCP.
- [Kong/kong](https://github.com/Kong/kong) ★44.3k - API and AI gateway with MCP gateway features.
- [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) ★39.5k - Multimodal AI agent stack.
- [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) ★30.4k - Autonomous deep-research agent.
- [deepset-ai/haystack](https://github.com/deepset-ai/haystack) ★26.9k - AI orchestration framework.
- [activepieces/activepieces](https://github.com/activepieces/activepieces) ★25.3k - Automation with ~400 MCP servers.
- [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) ★16.7k - Durable AI agents and workflows.
- [pacifio/atlas](https://github.com/pacifio/atlas) ★9.6k - Source control for coding agents.
- [osaurus-ai/osaurus](https://github.com/osaurus-ai/osaurus) ★8.1k - Native macOS harness for AI agents.
- [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) ★6.4k - AI assistant client with MCP.
- [lemma-work/lemma-platform](https://github.com/lemma-work/lemma-platform) ★636 - Multiplayer agent harness for teams.

## Cloud & DevOps

- [awslabs/mcp](https://github.com/awslabs/mcp) ★9.9k - Open-source MCP servers for AWS.
- [txn2/kubefwd](https://github.com/txn2/kubefwd) ★4.2k - Kubernetes port forwarding with MCP server.
- [skyhook-io/radar](https://github.com/skyhook-io/radar) ★4.0k - Kubernetes UI with built-in MCP server.
- [patrickchugh/terravision](https://github.com/patrickchugh/terravision) ★1.7k - Cloud architecture diagrams to/from Terraform via MCP.

## Productivity & Knowledge

- [rusq/slackdump](https://github.com/rusq/slackdump) ★2.8k - Export Slack data locally (with MCP server).

## Domain Apps

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) ★89.8k - Real-time global intelligence dashboard.
- [sansan0/TrendRadar](https://github.com/sansan0/TrendRadar) ★63.3k - AI-driven trend and opinion monitor.
- [xpzouying/xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) ★16.7k - MCP for xiaohongshu.com.
- [liketrek/TREK](https://github.com/liketrek/TREK) ★15.3k - Travel planner with MCP server.
- [budtmo/docker-android](https://github.com/budtmo/docker-android) ★16.1k - Android in Docker with MCP server.
- [irinabuht12-oss/google-ads-meta-ads-mcp](https://github.com/irinabuht12-oss/google-ads-meta-ads-mcp) ★6.6k - Google Ads, Meta Ads and GA4 hosted MCP.
- [crbnos/carbon](https://github.com/crbnos/carbon) ★2.8k - Manufacturing ERP/MES/QMS with MCP server.
- [relaticle/relaticle](https://github.com/relaticle/relaticle) ★1.8k - CRM your AI agents can read and update.

## Contributing

Add a repository only if it meets the inclusion criteria above and include its star count.

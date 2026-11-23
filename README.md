# Hi, I'm Napat (Tan) Phasundhiae

### Geospatial & Environmental Analyst | Creator & Maintainer, [ISCV | Isocurve Research Lab (@iscvlab)](https://github.com/iscvlab)

**GeoAI | Climate Risk | Environmental Simulation**

Bridging geospatial data, spatial simulation, and verifiable analytical frameworks to support resilience across the built and natural environment.

[![ISCV Lab](https://img.shields.io/badge/ISCV%20%7C%20Isocurve%20Research%20Lab-%40iscvlab-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/iscvlab)
[![CanopyGIS](https://img.shields.io/badge/CanopyGIS-v1.8.1%20GeoAI-2E7D32?style=flat-square&logo=leaflet&logoColor=white)](https://github.com/napattan/CanopyGIS/releases/tag/v1.8.1)
[![CanopyGIS Live Demo](https://img.shields.io/badge/Live%20Demo-napattan.github.io%2FCanopyGIS-00796B?style=flat-square&logo=googleearth&logoColor=white)](https://napattan.github.io/CanopyGIS/)
[![SSE Space Syntax](https://img.shields.io/badge/SSE%20Space%20Syntax-v1.1.1%20Rust%20%2B%20QGIS-4F46E5?style=flat-square&logo=rust&logoColor=white)](https://github.com/napattan/sse-space-syntax)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-napatphas-0A66C2?style=flat-square)](https://www.linkedin.com/in/napatphas/)
[![Email](https://img.shields.io/badge/Email-tanfasantia%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tanfasantia@gmail.com)
[![Location](https://img.shields.io/badge/Location-Bangkok%2C%20Thailand-475569?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Bangkok,+Thailand)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Opportunities-16A34A?style=flat-square)](https://www.linkedin.com/in/napatphas/)

`Python` | `Rust` | `GeoAI (SAM 3 / DeepForest)` | `Space Syntax (SSE)` | `Rhino / Grasshopper` | `RhinoCommon (C# / C++)` | `QGIS` | `Spatial SQLite` | `MCP`

---

## What I build

<table>
<tr>
<td width="33%" valign="top">

**Automated workflows & GeoAI**

Status: **LIVE**

AI coding agents and hybrid computer-vision pipelines connected to GIS, CAD, and documentation tools so complex spatial workflows run repeatably.

- **[napattan/CanopyGIS](https://github.com/napattan/CanopyGIS)** ([Live Demo](https://napattan.github.io/CanopyGIS/))
- **[napattan/sse-space-syntax](https://github.com/napattan/sse-space-syntax)** ([QGIS Portal](https://plugins.qgis.org/plugins/sse/))
- **[iscvlab/xlaya](https://github.com/iscvlab/xlaya)**
- **[iscvlab/xboost](https://github.com/iscvlab/xboost)**
- [iscvlab/xocr](https://github.com/iscvlab/xocr)
- [iscvlab/mcp-bridges](https://github.com/iscvlab/mcp-bridges) (Supporting Utility)

</td>
<td width="33%" valign="top">

**City-scale data & network topology**

Status: **LIVE**

Urban analytics, Space Syntax street-network & visibility engines, VHR canopy intelligence, and GIS for Bangkok-scale questions: mobility, urban forestry, environment, demographics, and land use.

- **[CanopyGIS v1.8.1](https://github.com/napattan/CanopyGIS/releases/tag/v1.8.1)** (Zero-Shot Planar SAM 3 + Watershed + 3-Pass RAG; optional DeepForest 2.1 in web portal)
- **[SSE - Space Syntax Engine v1.1.1](https://github.com/napattan/sse-space-syntax)** (Rust CSR + PyQGIS + 9-Tool MCP)
- [QGIS Axonometric Transformer](https://plugins.qgis.org/plugins/axonometric_transformer/) (Supporting Utility)
- [Bangkok Spatial Intelligence Suite](https://bangkok.iscvlab.com) (Working Prototype - Secondary / In Polish)

</td>
<td width="33%" valign="top">

**Environmental simulation**

Status: **IN PIPELINE** (flagship next)

Multi-threaded Grasshopper / C# & C++ solvers for urban environmental analysis (`Isocurve` microclimate, wind, and solar engine).

Hardware ground-truthing (`Timberpin`: MeeGoo ER307UWB BLE smart measuring tape tree-girth & GPS mapper + ESP32/BME688 environmental sensing) sits with this track.

</td>
</tr>
</table>

---

## Public receipts

| Repo | Status | What it is |
|:---|:---|:---|
| **[napattan/CanopyGIS](https://github.com/napattan/CanopyGIS)** | **LIVE ([v1.8.1](https://github.com/napattan/CanopyGIS/releases/tag/v1.8.1) \| [Live Demo](https://napattan.github.io/CanopyGIS/))** | **GeoAI Individual Tree Crown (ITC) Delimitation & Zero-Shot Planar Baseline** combining pure zero-shot **Meta SAM 3**, **Compact Geodesic Watershed**, and **3-Pass Region-Adjacency-Graph (RAG) Coalescing** evaluated on **`MillionTrees v0.25`** ([`weecology/MillionTrees#184`](https://github.com/weecology/MillionTrees/pull/184) `OPEN`: **OOD `F1 = 0.744`**, `MaskAwareP = 0.936` `1st`, `AP40 = 0.439`, `AP60 = 0.350`; **WD `F1 = 0.604`**, `MaskAwareP = 0.882`; **TLS `Complete-59` `F1 = 0.627`**; `5,815` tile evaluations / `458,851` crowns with `0` overlap px & `Euler = 1`, `4.27 GiB` peak GPU VRAM), alongside optional **Weecology DeepForest 2.1** nadir seeding in the interactive web portal with `< 30 ms` 6-slider client filtering & GIS/CAD export. Org mirror: [iscvlab/CanopyGIS](https://github.com/iscvlab/CanopyGIS) |
| **[napattan/sse-space-syntax](https://github.com/napattan/sse-space-syntax)** | **LIVE (v1.1.1 \| [QGIS Portal #6905](https://plugins.qgis.org/plugins/sse/) \| 108 downloads in 14d)** | **Dual-Engine Native Rust (`sse-desktop`, `sse-cli`, 9-Tool `sse-mcp`) & Qt6-Ready PyQGIS Space Syntax Engine** with `100%` `UCL depthmapX v0.8.0` Tulip-1024 directed-segment parity (`R² = 1.0000`, `54.4×-57.8×` faster Angular Segment Analysis; `16.69 s` on Bangkok `166,514` segments in `< 16 MB` CSR RAM; `34.9×-144.3×` faster Axial; `35.8×` faster VGA & Analytical Isovists; `495.5×` faster Gibson Visual Agents). Org mirror: [iscvlab/sse-space-syntax](https://github.com/iscvlab/sse-space-syntax) |
| **[iscvlab/xlaya](https://github.com/iscvlab/xlaya)** | **LIVE (v2.4.0 local \| [v2.3.0 LIVE](https://github.com/iscvlab/xlaya/releases/tag/v2.3.0))** | Standalone 5-profile System 1 → System 1.5 semantic decision, regime-invariant 8D AST/code-graph sieve, Wallacei `v2.7` K-Fold OOF `NSGA-II` MOO, & `vega-U` conformal triage engine (`laya 0.4.31+` & `vegaml 0.16.1+`), pairing zero-torch `--profile nano` (`8.50 MB` clean RSS, `79.07%` Blind `Kaggle 129 R1` `31B R@8`, `78.72%` `SWE-bench_Verified` `R@8`, `71.69%` `nvidia/When2Call` MCQ) with `~30 ms` warm 6-tool JSON-RPC 2.0 `stdio` MCP server, `859.1 q/s` (`8.9×` mixed EN/HI) GPU batch routing, `0.45/0.55` ensemble jury, `--thorough` 4-facet rubric + `file_summaries`, `--vega-views 1..3` debiasing, `xlaya_fit` persistent `TTTHead` conformal policy (`90.0%` fitted accuracy), local multimodal (`image`/`audio`/`video`), 3-Question Joint NLI Contradiction Triad (`100%`), and `0.00%` XERJ `#1108` wrong-and-confident fires |
| **[iscvlab/xboost](https://github.com/iscvlab/xboost)** | **LIVE (v3.6.0 local \| [v3.5.0 LIVE](https://github.com/iscvlab/xboost/releases/tag/v3.5.0))** | **Deterministic Verification, Sharded Compound Learning Playbooks & Reproducible Research Workflows** - composable 15-skill `/x*` AI agent ecosystem & 10 deterministic Python CLI & MCP verification engines (`22,237` LOC) for **any AI coding agent - cloud, IDE, CLI, or local LLM** (`Claude`, `Grok`, `Gemini`, `Cursor`, `Codex`, `Ollama`, `OpenHands`, `Cline`, etc.), featuring the **[4-Tier Sharded Compound Learning Playbooks (`L1` Hub + `4 L2` Shards)](https://github.com/iscvlab/xboost/blob/main/docs/COMPOUND_LEARNING_PLAYBOOK.md)** (`/xlearn`, `24 PAT-*/OPT-*` across `21` families incl. `OPT-MOO-01`, `14 FALS-01..14`, `7 GOV-01..07`), `/xmouse` Background Ghost Mouse, `100%` red-team defect recall across `25` seeded defects in `8.14 ms`, `-97.06%` briefing context noise reduction, and 5-profile `/xlaya v2.4.0` (`8.50 MB` clean `--profile nano`, `0.00%` XERJ `#1108` wrong-and-confident fires) |
| **[Upstream PR Contributions](https://github.com/iscvlab/xboost/blob/main/docs/COMPOUND_LEARNING_PLAYBOOK.md)** | LIVE (26 PRs + 1 Hold \| 11 MERGED \| 6 OPEN \| 13 Orgs) | Empirical open-source bottlenecks & bugfixes powered by XBoost & CanopyGIS R&D ([Full Benchmark Playbook](https://github.com/iscvlab/xboost/blob/main/docs/COMPOUND_LEARNING_PLAYBOOK.md)):<br>- **Geospatial, Forest Ecology & Vision**: **[Weecology/DeepForest #1449](https://github.com/weecology/DeepForest/pull/1449) & [#1464](https://github.com/weecology/DeepForest/pull/1464) (MERGED, closed #1447 & #1440)** (`74×-421×` Shapely 2.0 vectorization & `os.PathLike` discovered while building [CanopyGIS](https://github.com/napattan/CanopyGIS)) \| **[weecology/MillionTrees #184](https://github.com/weecology/MillionTrees/pull/184) (`OPEN`)** (`CanopyGIS v1.8.1` zero-shot planar baseline: `OOD F1 = 0.744`, `MaskAwareP = 0.936` `1st`, `WD F1 = 0.604`, `TLS-59 F1 = 0.627`) \| **[opengeos/geoai #960 (MERGED)](https://github.com/opengeos/geoai/pull/960)** \| **[gboeing/osmnx #1412 (MERGED, closed #1410)](https://github.com/gboeing/osmnx/pull/1412)** & #1405 (`40.2×` speedup) \| [martibosch/pylandstats #77](https://github.com/martibosch/pylandstats/pull/77) (`OPEN`, `4.0×` centroids) \| [opengeos/segment-geospatial #569](https://github.com/opengeos/segment-geospatial/pull/569) (`Closed` to rescope)<br>- **Climate, ESG & Urban Physics**: **[CLIMADA #1350](https://github.com/CLIMADA-project/climada_python/pull/1350) (MERGED; reverted → re-applied via [#1358](https://github.com/CLIMADA-project/climada_python/pull/1358) `OPEN`, Fixes `#1357`)** & [#1349](https://github.com/CLIMADA-project/climada_python/pull/1349) (`OPEN`; `69.9×` `apply_box` / `11.7×` CSR `impact_at_reg` & `#1331` World Bank ISO fallback) \| [Deltares/hydromt #1566](https://github.com/Deltares/hydromt/pull/1566) (`OPEN`, `27.5×` speedup & `#1563` non-EPSG:4326 basin CRS) \| [os-climate/physrisk #651](https://github.com/os-climate/physrisk/pull/651) (`OPEN`, `17.5×` Chronic Heat) \| [ladybug-tools/uwg #292](https://github.com/ladybug-tools/uwg/pull/292) (`Closed` - dormant repo; `1,735.6×` speedup & `#291`) \| [natcap/invest #2813, #2829](https://github.com/natcap/invest/issues/2829) (`Hold`; `23.1×` UCM & `18.1×` UFRM)<br>- **Rust & Agent Infrastructure**: **[xerj-org/xerj #2922-#2927 (6/6 MERGED)](https://github.com/xerj-org/xerj/pulls?q=is%3Apr+author%3Anapattan)** (`6` PRs: skill root auto-indexing, Thai PDF PUA, MSVC fixes, `0.00%` false-confident gate on [#1108](https://github.com/xerj-org/xerj/issues/1108)) \| [scb-10x/typhoon-ocr #16](https://github.com/scb-10x/typhoon-ocr/pull/16) (`Closed` - dormant repo, `-35.9%` vision tokens) \| [mufeedvh/code2prompt #348](https://github.com/mufeedvh/code2prompt/pull/348) (`Closed`) |
| [iscvlab/xocr](https://github.com/iscvlab/xocr) | LIVE (v2.4.0 local \| [v2.1.0 LIVE](https://github.com/iscvlab/xocr/releases/tag/v2.1.0)) | High-speed C++ PyMuPDF vector/table extractor (`19-97 ms/page`, `15.0×-3,326×` faster hybrid routing), Two-Stage LaTeX `booktabs` & scanned HTML `<table>` → RFC-4180 CSV surgery, Thai PUA/Sara-Am glyph normalizer, and 5-profile local `SCB 10X Typhoon-OCR v1.5` (`Qwen3-VL`) & `baidu/Unlimited-OCR-2` hybrid engine |
| [iscvlab/mcp-bridges](https://github.com/iscvlab/mcp-bridges) | Supporting Utility (8 Bridges incl. `/cad` AutoCAD \| Unpinned \| Selected for [XERJ Corpus Hub](https://hub.xerj.org)) | Supporting Model Context Protocol bridges connecting any cloud, IDE, CLI, or local AI agent to **AutoCAD (`/cad`), QGIS, Rhino 3D, Grasshopper, Adobe Illustrator, and Figma** (`8` bridges incl. `/cad` AutoCAD) with 1-prompt universal agent install and Parallel-Brains Single-Mouse `/xultra` swarm serialization (Selected for the [XERJ Corpus Hub](https://hub.xerj.org), `144` resolved graph edges) |
| [iscvlab/qgis-axonometric-transformer](https://plugins.qgis.org/plugins/axonometric_transformer/) | Supporting Utility (#6219 \| v1.2.2 LIVE \| 584 downloads \| Unpinned) | Supporting Qt6-verified QGIS plugin (Plugin ID: `6219`, `QGIS 4 Ready`) for 1-click 3D isometric & axonometric diagram generation (`30×` faster than manual CAD) with multi-format transparent clipboard export ([GitHub Repo](https://github.com/iscvlab/qgis-axonometric-transformer)) |
| [Bangkok Spatial Intelligence Suite (`bangkok.iscvlab.com`)](https://bangkok.iscvlab.com) | **WORKING PROTOTYPE** (Secondary / In Polish \| Demoted from Front-Door Hero) | Interactive 3D MapLibre GL JS & Deck.gl urban analytics prototype for Bangkok (`8` Dashboards `A-H`, `50` BMA districts, `31` spatial layers backed by `tiles.iscvlab.com` Cloudflare R2 PMTiles covering multi-modal transit accessibility, environmental comfort, land use, and urban ecology; staged for polish rather than front-door hero) |

---

## Next

| Item | Status |
|:---|:---|
| Isocurve simulation plugin (Grasshopper / Food4Rhino - [@iscvlab](https://github.com/iscvlab)) | IN PIPELINE |
| Timberpin field sensing (MeeGoo ER307UWB BLE smart measuring tape tree-girth & GPS mapper + ESP32/BME688 environmental sensing) | PREPARED |
| Unified portfolio site (`iscvlab.com`) | IN PIPELINE |

---

## Experience & Leadership

- **Creator & Open-Source Maintainer, [ISCV | Isocurve Research Lab (@iscvlab)](https://github.com/iscvlab):** Independent geospatial data, GIS mapping, climate risk, and environmental simulation research lab.
- **Research & Intelligence Intern - SHMALAB (Shma, Apr 2026 - Sep 2026)** (cross-appointed across two units):
  - *Research:* Environmental data research, urban microclimate comfort, and evidence-based sustainability frameworks (supporting LEED/WELL principles).
  - *Intelligence:* Custom QGIS/Rhino automated workflows, parametric modeling, and multi-threaded simulation tools.
- **Student Union President,** Faculty of Architecture, Kasetsart University (2024-2025). Led faculty-scale student operations.
- **TEDxKasetsartU** core team, Head of Media. Ran media for a large public event.

---

## Connect

Open to roles and collaborations in geospatial analytics, climate risk, environmental simulation, and spatial tooling.

- **Research Lab:** [ISCV | Isocurve Research Lab (@iscvlab)](https://github.com/iscvlab)
- **CanopyGIS (Thesis GeoAI Platform):** [github.com/napattan/CanopyGIS](https://github.com/napattan/CanopyGIS) | [Live Demo](https://napattan.github.io/CanopyGIS/)
- **SSE (Space Syntax Engine):** [github.com/napattan/sse-space-syntax](https://github.com/napattan/sse-space-syntax) | [QGIS Plugin Portal](https://plugins.qgis.org/plugins/sse/)
- **Bangkok Spatial Suite (Working Prototype):** [bangkok.iscvlab.com](https://bangkok.iscvlab.com)
- **LinkedIn:** [linkedin.com/in/napatphas](https://www.linkedin.com/in/napatphas/)
- **Email:** [tanfasantia@gmail.com](mailto:tanfasantia@gmail.com)
- **GitHub:** [@napattan](https://github.com/napattan)

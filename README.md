# Urban Metabolism ABM: Multi-Agent Simulation Marketplace & Lifecycle Assessment Engine

An advanced, peer-review-grade Python framework engineered to simulate urban metabolism, material circularity, and lifecycle environmental impacts within the built environment. This engine addresses critical peer-review constraints by replacing deterministic recycling assumptions with a dynamic, spatial-temporal multi-agent interaction marketplace.

---

## Key Scientific Innovations

### Decentralized Agent Marketplace
Simulates deconstruction and construction projects as spatial-temporal nodes $(x, y, t)$. Material allocation is dynamically bounded by:

- Spatial friction (hauling radius thresholds)
- Coordination delays (lag metrics)
- Marketplace availability constraints
- Agent-to-agent transaction logic

### Elimination of Classification Bias
Replaces arbitrary data handling routines with a dedicated `RESIDUAL` data pipeline, isolating unmapped industrial materials to ensure unbiased:

- Global Warming Potential (GWP)
- Net Present Value (NPV)
- Circularity efficiency metrics

### Empirically Grounded 3D Analytics
Features analytical plotting routines that capture true operational runtime coordinates rather than synthetic functions, improving interpretability and publication validity.

---

# Repository Structure

```text
├── urban_metabolism.py          # Core Simulation Engine & Data Extraction Pipeline
├── README.md                    # Academic Technical Documentation
└── publication_figures/         # Exported High-Resolution (300 DPI) Graphics
    ├── Fig1_CarbonTrajectory.png
    ├── Fig2_DistrictNPV.png
    ├── Fig3_MaterialFlows.png
    ├── Fig4_ProbabilitySurface.png
    ├── Fig5_ZeroWaste.png
    ├── Fig6_LCASensitivity.png
    └── Fig7_Elasticity.png
```

---

# Comprehensive File Descriptions

## 1. `urban_metabolism.py`

The primary execution module containing:

### `ZenloliMasterPipeline`
A robust, layout-agnostic data extraction class featuring fuzzy-matching keyword trees to automatically digest unaligned material flow matrices.

### `UrbanMetabolismEngine`
The core simulation hub managing:

- Agent initialization
- Geographic coordinate mappings
- Marketplace matching logic
- Lifecycle stage accounting matrices
- Circularity flow balancing
- Spatial-temporal synchronization

### `plot_publication_figures`
Automated graphics suite leveraging:

- Serif typographic stack
- Compact high-legibility axis footprints
- Journal-grade styling
- 300 DPI export rendering

---

## 2. `publication_figures/` (Generated Artifacts)

### `Fig1_CarbonTrajectory.png`
Plots cumulative district embodied carbon volume $(ktCO_2e)$ across a 10-year simulation timeline, demonstrating system boundary variance $(\pm 4\%)$ across:

- Baseline (BAU)
- Partial circularity
- Full digital circularity scenarios

### `Fig2_DistrictNPV.png`
Comparative bar chart demonstrating the Net Present Value (NPV @ 5%) of the system, quantifying:

- Capital expenditure penalties
- Recycled resource savings
- Marketplace optimization impacts

### `Fig3_MaterialFlows.png`
Horizontal volumetric distribution diagram tracking:

- Terminal waste leakage
- Matched recirculated flows
- Residual industrial materials

### `Fig4_ProbabilitySurface.png`
A 3D spatial-temporal allocation surface mapping empirical matching density against:

- Coordination lag (months)
- Hauling radius boundaries $(km)$
- Agent transaction probability

### `Fig5_ZeroWaste.png`
Three-panel donut chart matrix validating structural compliance against strict 90% zero-waste diversion targets.

### `Fig6_LCASensitivity.png`
Clustered bar chart profiling carbon footprint sensitivities distributed across ISO lifecycle stages:

| Lifecycle Stage | Description |
|---|---|
| A1–A3 | Production |
| A4 | Distribution |
| C2 | End-of-Life Logistics |
| C3–C4 | Terminal Processing |
| D | Circular System Offsets |

### `Fig7_Elasticity.png`
Dual-axis scatter plot tracing:

- Recirculated structural mass elasticity
- Avoided operational liabilities
- Data synchronization refresh impacts

---

# System Architecture Overview

The framework integrates three core analytical layers:

1. **Material Flow Intelligence**
2. **Spatial-Temporal Agent Marketplace**
3. **Lifecycle Environmental Accounting**

Each project node operates as an autonomous agent capable of:

- Generating reusable material inventories
- Requesting secondary construction resources
- Negotiating allocation under geographic constraints
- Participating in circularity optimization dynamics

---

# Core Methodological Features

## Spatial-Temporal Constraints

The engine incorporates realistic operational boundaries:

- Transportation radius thresholds
- Material decay windows
- Coordination lag penalties
- Marketplace saturation effects

---

## Lifecycle Assessment (LCA)

Environmental impacts are calculated using stage-based accounting aligned with ISO lifecycle frameworks:

\[
\text{Total Impact} = A1\text{-}A3 + A4 + C2 + C3\text{-}C4 - D
\]

Where:

- $A1$–$A3$: Production impacts
- $A4$: Distribution logistics
- $C2$: End-of-life transport
- $C3$–$C4$: Waste processing
- $D$: Circularity offset credits

---

# Quick Start

## Requirements

Install dependencies:

```bash
pip install numpy pandas matplotlib
```

---

# Local / Cloud Execution

This framework runs entirely out-of-the-box in environments such as:

- Google Colab
- Kaggle
- JupyterLab
- Local Python environments

Example execution:

```python
from urban_metabolism import UrbanMetabolismEngine, plot_publication_figures

# Initialize simulation space with 60 spatial infrastructure nodes
engine = UrbanMetabolismEngine(
    data_dir="/path/to/input/data",
    num_projects=60
)

# Execute scenario simulations
bau = engine.execute_scenario("BAU")
partial = engine.execute_scenario("PARTIAL")
full = engine.execute_scenario("FULL")

# Render and export all publication-grade figures
plot_publication_figures(bau, partial, full)
```

---

# Simulation Scenarios

| Scenario | Description |
|---|---|
| BAU | Conventional linear construction economy |
| PARTIAL | Moderate circularity adoption |
| FULL | Fully digitized circular construction marketplace |

---

# Research Applications

This framework is suitable for:

- Urban metabolism modeling
- Circular economy optimization
- Construction material recirculation studies
- Smart city sustainability analysis
- Embodied carbon accounting
- Lifecycle assessment research
- Multi-agent infrastructure simulations

---

# Publication Readiness

The framework was designed for academic and industrial research workflows, featuring:

- High-resolution publication exports
- Deterministic reproducibility
- Modular simulation architecture
- Transparent lifecycle accounting
- Peer-review-oriented methodological design

---

# Citation

If you use this framework in academic research, please cite:

```bibtex
@software{urban_metabolism_abm,
  title={From Waste to Wealth: Digital Material Tracking and Circular Metabolism in Climate-Positive Districts},
  year={2026},
  url={https://github.com/your-repository}
}
```

---

# License

This project is released under the MIT License.

---

# Future Extensions

Planned future capabilities include:

- GIS-integrated transportation routing
- Reinforcement learning marketplace optimization
- BIM interoperability pipelines
- Real-time IoT material tracking
- Dynamic carbon pricing integration
- GPU-accelerated simulation scaling

---

# Contact

**Fatemeh Amini**  
Researcher in AI, Urban Sustainability, and Multi-Agent Systems

- Email: fatmehe.amini@aut.ac.ir
- GitHub: `fateme-amini`

---

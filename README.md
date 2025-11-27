# Process Model for Carbon Nanomaterials Production from Plastic Waste Using Agro/Animal Waste

##  Overview

This project presents a comprehensive **waste-to-value** process model that converts plastic waste and biomass into high-value **carbon nanomaterials (CNMs)** using Aspen Plus V14. The integrated approach addresses two critical waste management challenges while producing valuable outputs: hydrogen-rich syngas, high-quality bio-oil, and carbon nanomaterials.

### The Problem We're Solving
-  **360 million tonnes** of plastic produced annually (only 20% recycled)
-  **500+ million tonnes** of agricultural waste generated in India alone
-  Global CNM market projected to reach **$9.8 billion by 2028**
-  Traditional CNM production relies on expensive catalysts and fossil fuels

### Our Solution
**Waste → Resource → High-Value CNMs**

A scalable, sustainable pathway that simultaneously:
- ✅ Mitigates plastic and biomass waste
- ✅ Produces carbon nanotubes (CNTs) and carbon nanospheres (CNSs)
- ✅ Generates hydrogen-rich syngas
- ✅ Captures carbon in stable forms
- ✅ Reduces greenhouse gas emissions

##  Key Features

### Technical Highlights
- **Dual-Feed System**: Integrates plastic pyrolysis (bio-oil) and biomass pyrolysis (biochar catalyst)
- **Cost-Effective Catalyst**: Uses biochar from agro/animal waste instead of expensive metal catalysts
- **High Performance**: 40-70% methane conversion, 9.4-15.6 mg·h⁻¹·g⁻¹ carbon deposition rate
- **Energy Efficient**: Partial oxidation provides autothermal operation
- **Circular Economy**: Closes the loop from waste to valuable nanomaterials

### Simulation Capabilities
- Steady-state equilibrium modeling
- Thermodynamic property analysis (Peng-Robinson, NRTL)
- Parametric sensitivity studies
- Mass and energy balance calculations
- Product yield optimization

##  Process Description

The process consists of three integrated flowsheets:

### Flowsheet 1: Plastic Waste to Bio-Oil
```
PLASTIC → DRYER → PYROLYSIS → SEPARATOR → CONDENSER → FLASH
                                    ↓           ↓          ↓
                                  CHAR      GASES     BIO-OIL
```

**Key Operations:**
- Pre-treatment (moisture removal)
- Thermal pyrolysis at 400-800°C
- Multi-stage separation (gas/liquid/solid)
- Product recovery and purification

### Flowsheet 2: Biomass to Biochar
```
BIOMASS → DRYER → PYROLYSIS (N₂) → SEPARATOR
                                        ↓
                                   BIOCHAR (Catalyst)
```

**Key Operations:**
- Drying at 100-150°C
- Slow pyrolysis at 500-700°C
- Solid-gas separation
- Biochar collection

### Flowsheet 3: Carbon Nanomaterial Formation
```
BIO-OIL + BIOCHAR + AIR → MIXER → HEATER → CVD REACTOR → SEPARATOR
                                                              ↓
                                                    CNMs + H₂-rich gas
```

**Key Operations:**
- Feed homogenization and preheating
- Catalytic CVD at 650-800°C
- Carbon deposition on biochar surface
- Product separation and purification

##  Technical Details

### Feedstock Specifications
<img width="913" height="377" alt="image" src="https://github.com/user-attachments/assets/e295f1b7-a52d-496f-bb16-9af7bf2df9d8" />


### Thermodynamic Methods
- **Peng-Robinson (PR-BM)**: Hydrocarbon-rich phases
- **NRTL**: Oxygenated biomass products
- **HCOALGEN/DCOALIGT + IDEAL**: Solid biochar modeling

### Key Reactions
```
CH₄ → C(s) + 2H₂
C₂H₄ → 2C(s) + 2H₂
C₂H₂ → 2C(s) + H₂
```

## 📊 Simulation Results

### Performance Metrics
- ✅ **Methane Conversion**: 40-70%
- ✅ **Carbon Deposition Rate**: 9.4-15.6 mg·h⁻¹·g⁻¹ catalyst
- ✅ **CNM Yield**: 20-25% of reactor output
- ✅ **H₂ Volume %**: Increases with temperature
- ✅ **Product Purity**: >90% carbon content

### Product Distribution (Typical Run)

**Plastic Pyrolysis:**
- Bio-oil: 20-30 wt%
- Gases: 60-75 wt%
- Char: 5-10 wt%

**Biomass Pyrolysis:**
- Biochar: 20-35 wt%
- Volatiles: 65-80 wt%

**CNM Reactor:**
- Solid CNMs: 20-25%
- H₂-rich gas: 75-80%

### Parametric Analysis
The simulation includes sensitivity studies showing:
- ↗️ Temperature increases → Higher CH₄ conversion
- ↗️ Temperature increases → Higher carbon deposition rate
- ↗️ Temperature increases → Greater CNM yield
- ↗️ Temperature increases → Higher H₂ concentration in off-gas

##  Installation & Usage

### Prerequisites
- Aspen Plus V14 or later
- Windows OS (recommended)
- Basic knowledge of process simulation
- Familiarity with pyrolysis and CVD processes

### Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/CNM-from-waste.git
cd CNM-from-waste
```

2. **Open Aspen Plus files**
- Navigate to `/simulations/` directory
- Open `.bkp` or `.apw` files in Aspen Plus V14

3. **Run simulations**
- Flowsheet 1: `Plastic_to_Biooil.bkp`
- Flowsheet 2: `Biomass_to_Biochar.bkp`
- Flowsheet 3: `CNM_Formation.bkp`

4. **Modify parameters**
- Feed composition: Update in `PLASTIC` and `BIOMASS` streams
- Operating conditions: Modify in reactor blocks (PYROL, PYRO, R-PLUG)
- Property methods: Configure in `Setup → Properties`

### Running Parametric Studies
1. Navigate to `Model Analysis Tools → Sensitivity`
2. Select variable to vary (e.g., CNM Reactor Temperature)
3. Define range and number of points
4. Select output variables to track
5. Run analysis and export results

##  Project Structure

```
CNM-from-waste/
│
├── simulations/
│   ├── Flowsheet1_Plastic_Pyrolysis.bkp
│   ├── Flowsheet2_Biomass_Pyrolysis.bkp
│   └── Flowsheet3_CNM_Formation.bkp
│
├── docs/
│   ├── Project_Report.pdf
│   ├── Process_Diagrams.pdf
│   └── Results_Analysis.xlsx
│
├── data/
│   ├── feedstock_properties.csv
│   ├── experimental_validation.csv
│   └── parametric_study_results.csv
│
├── images/
│   ├── flowsheet1.png
│   ├── flowsheet2.png
│   ├── flowsheet3.png
│   └── results_plots/
│
├── README.md
├── LICENSE
└── CITATION.cff
```

##  Future Work

### Experimental Validation
- [ ] Bench-scale reactor construction (50-200 g/h)
- [ ] CNM morphology characterization (TEM, SEM, Raman)
- [ ] Product yield verification
- [ ] Long-term catalyst stability testing

### Model Enhancement
- [ ] Detailed kinetic rate expressions
- [ ] Dynamic modeling capabilities
- [ ] Catalyst deactivation/regeneration cycles
- [ ] Scale-up design considerations

### Optimization Studies
- [ ] Biochar activation/impregnation (Fe, Ni loading)
- [ ] Heat integration network design
- [ ] Multi-objective optimization (yield, purity, energy)
- [ ] Sensitivity to feedstock variability

### Economic & Environmental Analysis
- [ ] Life Cycle Assessment (LCA)
- [ ] Techno-economic analysis (TEA)
- [ ] Carbon footprint quantification
- [ ] Market analysis for CNM applications

## 📚 References

1. Production of hydrogen by catalytic methane decomposition using biochar - [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0360319920330317)

2. Conversion of pyrolytic gases into bamboo-type carbon nanotubes - [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0301479721018533)

3. Computer-Aided Design of Large-Scale Nanomaterials Synthesis - [Wiley](https://onlinelibrary.wiley.com/doi/full/10.1002/cben.202300075)

4. Wong et al. (2015). Plastic waste as fuel source. *Renewable and Sustainable Energy Reviews*, 50, 1167-1180.

5. Kumar & Ando (2010). CVD of carbon nanotubes: A review. *Journal of Nanoscience and Nanotechnology*, 10(6), 3739-3758.

## 👨‍🔬 Author

**Ayushi Singh**  
B.Tech. Chemical Engineering  
Indian Institute of Technology Jodhpur  
Roll No: B22CH005

**Supervisor:** Prof. Manoj Kumar Jena

## 🙏 Acknowledgments

- IIT Jodhpur Chemical Engineering Department
- Prof. Manoj Kumar Jena for supervision and guidance
- Aspen Technology for simulation software support



---

**⭐ If you find this project useful, please consider starring the repository!**

---

*Last Updated: November 2025*

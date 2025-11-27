Process Model for Carbon Nanomaterials Production from Plastic Waste Using Agro/Animal Waste

Transforming Waste into Wealth: A Circular Economy Approach to Advanced Materials

 Project Overview
This B.Tech project presents a groundbreaking circular economy solution that simultaneously addresses two critical environmental challenges: plastic waste pollution and biomass waste management. By intelligently integrating thermochemical conversion processes, we transform these waste streams into high-value carbon nanomaterials (CNMs) while generating clean hydrogen energy.
Key Achievement: A comprehensive Aspen Plus V14 simulation model demonstrating 40-70% methane conversion and carbon deposition rates of 9.4-15.6 mg·h⁻¹·g⁻¹ catalyst.

 The Innovation
The Problem

🌍 360 million tons of plastic produced annually
♻ Only 20% recycled effectively
🔥 500+ million tons of agricultural waste generated in India
💰 CNM market projected to reach $9.8 billion by 2028
⚡ Traditional CNM production relies on expensive catalysts and fossil fuels

Our Solution
A three-stage integrated process that converts waste into value:
Plastic Waste → Bio-Oil → 
                          ↓
                    [CVD Reactor] → Carbon Nanomaterials + H₂-rich Gas
                          ↑
Biomass Waste → Biochar Catalyst →

 Key Features
 Technical Highlights

Dual-feed system utilizing both plastic and biomass waste
Biochar catalyst from agro/animal waste (cost-effective alternative to metal catalysts)
Three integrated flowsheets modeled in Aspen Plus V14
Equilibrium-based modeling using RGibbs and kinetic reactors
Multi-product output: CNMs, hydrogen-rich syngas, upgraded bio-oil

 Environmental Benefits

✅ Zero landfill waste from feedstocks
✅ Carbon capture in stable solid forms
✅ Reduced greenhouse gas emissions
✅ Lower PAH content in bio-oil
✅ Sustainable alternative to fossil-based CNM production

 Product Quality

CNM Purity: >90%
Hydrogen-rich gas for energy integration
Enhanced bio-oil with reduced pollutants
Stable catalyst performance over extended reaction times


 Process Architecture
Flowsheet 1: Plastic Waste to Bio-Oil
PLASTIC → DRYER → PYROLYSIS (500-600°C) → PHASE SEPARATOR → 
    ├─ CHAR (5-10%)
    ├─ GASES (60-75%)
    └─ BIO-OIL (20-30%)
Flowsheet 2: Biomass to Biochar
BIOMASS → DRYER → PYROLYSIS (500-700°C) → SEPARATOR → 
    ├─ BIOCHAR (20-35%)
    └─ VOLATILES (65-80%)
Flowsheet 3: CNM Formation (CVD Process)
BIO-OIL + BIOCHAR + AIR → MIXER → HEATER → R-PLUG REACTOR (650-800°C) → 
    ├─ CNMs (20-25%)
    └─ H₂-RICH GAS (75-80%)

 Simulation Results
Performance Metrics
ParameterValueUnitMethane Conversion40-70%Carbon Deposition Rate9.4-15.6mg·h⁻¹·g⁻¹ catCNM Purity>90%Biochar Yield20-35wt%Bio-oil Yield20-30wt%Reactor Temperature650-800°C
Key Graphs Generated

CH₄ Conversion vs. Temperature - Shows optimal operating windows
Carbon Deposition Rate vs. Temperature - CNM formation kinetics
CNM Yield vs. Temperature - Production optimization
H₂ Volume % in Gas - Co-product value assessment


 Technology Stack
Software & Tools

Aspen Plus V14 - Process simulation and modeling
Property Methods:

Peng-Robinson (PR-BM) for hydrocarbon systems
NRTL for oxygenated compounds
HCOALGEN/DCOALIGT for solid biochar



Reactor Models Used

RYield - Feed preparation and drying
RGibbs - Equilibrium-based pyrolysis
R-PLUG - Catalytic CVD reactor
SEP/SSPLIT - Phase separation
FLASH - Product fractionation


📋 Project Structure
├── Flowsheets/
│   ├── Flowsheet_1_Plastic_to_BioOil.apw
│   ├── Flowsheet_2_Biomass_to_Biochar.apw
│   └── Flowsheet_3_CNM_Formation.apw
├── Results/
│   ├── simulation_outputs/
│   ├── performance_graphs/
│   └── sensitivity_analysis/
├── Documentation/
│   ├── Project_Report.pdf
│   ├── Literature_Review.pdf
│   └── Design_Calculations.xlsx
└── README.md

 Academic Context
Institution: Indian Institute of Technology Jodhpur
Department: Chemical Engineering
Student: Ayushi Singh (B22CH005)
Supervisor: Prof. Manoj Kumar Jena
Submission Date: November 2025
Degree: Bachelor of Technology

 Methodology
1. Feedstock Selection & Characterization

Plastic waste (PE, PP, PS) from municipal solid waste
Agricultural residues and animal waste (rice husk, bagasse, manure)
Compositional analysis using ultimate and proximate analysis

2. Process Design Strategy

Thermodynamic foundation with validated property methods
Steady-state modeling for process feasibility
Parametric analysis for optimization
Equipment design considerations

3. Simulation Approach

Feed characterization as nonconventional materials
Sequential unit operations modeling
Energy and mass balance closure
Sensitivity studies on key parameters


 Key Reactions Modeled
Pyrolysis Stage
Plastic/Biomass → Char + Bio-oil + Gases
CNM Formation (CVD)
CH₄ → C(s) + 2H₂
C₂H₄ → 2C(s) + 2H₂
C₂H₂ → 2C(s) + H₂

🌟 Advantages Over Conventional Methods
AspectConventional CNM ProductionOur ProcessCatalystExpensive metals (Ni, Co, Fe)Low-cost biocharCarbon SourceFossil fuels (methane, acetylene)Waste plasticsCostHigh CAPEX/OPEXSignificantly reducedSustainabilityHigh CO₂ emissionsCarbon-negative potentialWaste ManagementNot addressedDual waste valorizationEnergyExternal heating requiredPartial autothermal operation

🔮 Future Work
Experimental Validation

 Bench-scale reactor construction (50-200 g/h capacity)
 Parametric experimental runs
 CNM characterization (TEM, SEM, Raman, XRD)
 Product quality assessment

Model Enhancement

 Detailed kinetic rate expressions
 RStoic implementation for CNM growth
 Catalyst deactivation modeling
 Dynamic simulation capabilities

Scale-up & Commercialization

 Pilot plant design (1-10 ton/day)
 Techno-economic analysis (TEA)
 Life cycle assessment (LCA)
 Heat integration optimization
 Market application studies

Catalyst Optimization

 Biochar activation methods
 Metal impregnation studies (Fe, Ni)
 Selectivity tuning (CNTs vs. CNSs)
 Regeneration protocols


 Applications of Carbon Nanomaterials
The CNMs produced through this process can be utilized in:

⚡ Energy Storage: Supercapacitors, lithium-ion batteries
🔬 Electronics: Conductive composites, sensors, transistors
🏗 Structural Materials: High-strength composites
🌊 Environmental: Water treatment, gas adsorption
⚕ Biomedical: Drug delivery, biosensors, tissue engineering
⚗ Catalysis: Catalyst supports, electrocatalysts


 Key References

Production of hydrogen by catalytic methane decomposition using biochar - ScienceDirect
Conversion of pyrolytic gases into bamboo-type CNTs using biochar catalyst - ScienceDirect
Wong et al. (2015) - Plastic waste as fuel source review
Wang & Wang (2019) - Biochar preparation and environmental applications
Kumar & Ando (2010) - CVD carbon nanotube growth mechanisms

(Full reference list available in project report)

 Acknowledgments
Special thanks to:

Prof. Manoj Kumar Jena for invaluable guidance and supervision
IIT Jodhpur Chemical Engineering Department for facilities and support
Aspen Technology for simulation software access


 Contact
Ayushi Singh
B.Tech Chemical Engineering
Indian Institute of Technology Jodhpur
Roll No: B22CH005



 Project Highlights

"This project demonstrates that waste is not waste—it's a resource. By intelligently integrating plastic and biomass waste streams through thermochemical conversion, we can simultaneously solve environmental problems while producing high-value nanomaterials and clean hydrogen energy, creating a truly circular and sustainable economy."

Waste → Resource → High-Value CNMs
A scalable, green pathway that closes the loop on circular materials

## A. Fabrication of modified BioMe microplate

Microplate components were fabricated using materials detailed in Table 1. The body segments were produced via a multi-step casting process. First, master parts were 3D printed to create a high-fidelity negative mold from PlatSil Gel-25 Silicone Rubber. This mold was cured under 25 psi of positive pressure to eliminate voids. The cured mold was then filled with EasyFlo 60 Liquid Plastic again under 25 psi of positive pressure and allowed to solidify for 48 hours. The resulting solid plastic segments were drilled using a drill press, manually sanded (400-Grit) to create smooth sealing surfaces, and cleaned of residual manufacturing chemicals by agitation in deionized water on an orbital shaker for 48 hours.

The polycarbonate base plate was CNC-milled from polycarbonate sheets, while gaskets (both bottom layer and in between segments, discussed in assembly section) were laser-cut from food grade silicone rubber sheets using a CAMFive CFL-CMA2416k 80-watt $CO_2$ laser cutter. The co-culture interface was prepared from 0.2 µm Nucleopore track-etched polycarbonate hydrophilic membranes. These membranes were cut into 8 mm circles with a leather punch, washed in 70% ethanol and air-dried before assembly.

Table 1: Materials used in modified BioMe microplate
| Material | Vendor/Catalogue# |
| --- | --- |
| Plastil Gel-25 | Polytek/GEL25U2 |
| EasyFlo 60 Liquid Plastic | Polytek/EZFLOU3.8 |
| 18-8 Stainless Steel Threaded Rod, 6" Long, 6-32 Tread Size | McMaster-Carr/95412A373 |
| 18-8 Stainless Steel Flange Nut, 6-32 Tread Size | McMaster-Carr/94758A102 |
| 18-8 Stainless Steel Narrow Hex Nut, 4-40 Thread Size | McMaster-Carr/90730A005 |
| 316 Stainless Steel Hex Drive Flat Head Screw, 82 Degree Countersink Angle, 4-40 Thread Size, 3/4" Long | McMaster-Carr/990585A206 |
| 1/32" Food-Grade High Temp Silicone Rubber Sheet (40A Medium Soft) | McMaster-Carr/86945K58 |
| Scratch- and UV-Resistant Polycarbonate 1/16” | McMaster-Carr/8707K161 |
| Nuclepore Hydrophilic Membrane, 0.2 µm pore size, 47 mm circle | Cytiva/10417012 |

## B. Assembly and Quality Control

The microplate was assembled according to the protocol established by Jo et al. [1], placing a silicone gasket between the polycarbonate base and the first body segment, as well as between each subsequent segment, to form a liquid-tight seal. A procedural modification was implemented to ensure sterility and seal integrity: all screws and joints were kept intentionally loose before the entire apparatus was autoclaved using a gravity cycle (20-minute exposure, 20-minute dry time). Following sterilization, the plate was transferred to a disinfected biosafety cabinet where all joints were fully tightened to create the final, sterile seal. A final quality control check was performed on the assembled plate by adding 250 µL of sterile growth media to each well. The plate was incubated for 1 hour at room temperature and then a micropipette was used to measure any loss of volume.

<p align="center"><img src="https://github.com/pavia27/co-culture-device/blob/main/fig1.png" width=80% height=80%></p>
Modified BioMe microplate. The modified BioMe microplate from Jo et al. [1], is depicted in
the top image and represents a fully assembled unit. Each well is partitioned from its
counterpart by a 0.2µm pore-sized filter, that is securely positioned by a precision-cut
silicone sheet. The semi-permeable barrier, as indicated by the red arrow, is designed to
permit the passage of metabolites while preventing the translocation of microbes.

## C. Calibration and Validation

The fully assembled microplate was validated for both its optical properties and its biological application. First, the optical sensitivity and minimal detectable optical density ($OD_{600}$) were determined by generating a standard curve using McFarland standards ranging from 0.1 to 4 (Figure 1). Next, to ensure the polycarbonate material did not interfere with measurements, a comparative analysis of $OD_{600}$ readings was performed against a standard polystyrene 96-well plate. While no statistically significant difference was found overall (paired two-sample t-test, *p*=0.6656), it was noted that McFarland standards 1, 1.5, and 2 consistently produced marginally higher readings in the polycarbonate plate.

Figure 1. Distribution of $OD_{600}$ across varying McFarland standards measured through polycarbonate and polystyrene material. Each point represents the $OD_{600}$ measurement for a given McFarland standard, color-coded, and shaped according to the standards.

The biological efficacy of the device was confirmed through a co-culture of *Lactobacillus plantarum* and *Acetobacter pasteurianus* in a chemically defined medium [2]. The resulting growth curves demonstrated the plate's ability to support microbial growth and detect known metabolic interactions, as evidenced by the enhanced growth of *A. pasteurianus* in co-culture (Figure 2).

## D. Bibliography 
1.     Jo, C., et al., Construction and Modeling of a Coculture Microplate for Real-Time Measurement of Microbial Interactions. mSystems 8, (2023).
2.     Aumiller, K. et al., A chemically-defined growth medium to support Lactobacillus-Acetobacter sp. community analysis. PLoS One 18, 1–12 (2023).

# Introduction to Pediatric Ontogeny Qualification (PEQ)

## Translation of Adult PBPK to Children

Using a developed and validated (adult) PBPK model for an *in vivo* probe substance, a pediatric PBPK model can be established for children by scaling physiology, clearance processes (as parameterized in the adult model) and age-dependent protein binding including the process specific variabilities. 

For qualification purpose, during the translation of Adult PBPK to children the following assumptions and considerations were made: 

- when scaling and adult model to children, it was assumed that the metabolism and excretion
  pathways are qualitatively the same in children as in adults.
- For qualification purpose, no further changes to any other input parameters (eg, lipophilicity, intestinal permeability, solubility) were allowed during the simulations in children. 

### Anthropometric and Physiological Information 

Regarding the age-dependencies of the relevant anthropometric (height, weight) and physiological parameters (blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in children was gathered from the literature and has been previously published [[1](#reference)]. The information was incorporated into PK-Sim® and was used as default values for the simulations in children.

The  applied ontogeny and variability of active processes that are built-in into PK-Sim® for translation to children, are described in the publically available ‘PK-Sim® Ontogeny Database Version 7.3 [[2](#reference)] or otherwise referenced for the specific process.

### Qualifications of Ontogenies

**Distribution and GFR ontogeny**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Amikacin [[3](#reference)]
- Vancomycin [[4](#reference)]
- Pregabalin [[5](#reference)]

**CYP3A4 enzyme ontogeny**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Alfentanil [[6](#reference)]
- Sufentanil [[7](#reference)]
- Itraconazole [[8](#reference)]

**CYP2C8 enzyme ontogeny qualification**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Montelukast [[9](#reference)]
- Paclitaxel [[10](#reference)]

## References

[1] [Edginton AN, Schmitt W, Willmann S. Development and evaluation of a generic physiologically based pharmacokinetic model for children. Clin Pharmacokinet. 2006;45(10):1013-34.](https://www.ncbi.nlm.nih.gov/pubmed/16984214)

[2]  [OSPSuite.Documentation/PK-Sim Ontogeny Database Version 7.3.pdf ](https://github.com/Open-Systems-Pharmacology/OSPSuite.Documentation/blob/38cf71b384cfc25cfa0ce4d2f3addfd32757e13b/PK-Sim%20Ontogeny%20Database%20Version%207.3.pdf)

[3] [Amikacin-Model, Whole-body PBPK model of Amikacin. https://github.com/Open-Systems-Pharmacology/Amikacin-Model](https://github.com/Open-Systems-Pharmacology/Amikacin-Model)

[4] [Vancomycin-Model, Whole-body PBPK model of Vancomycin. https://github.com/Open-Systems-Pharmacology/Amikacin-Model](https://github.com/Open-Systems-Pharmacology/Vancomycin-Model)

[5] [Pregabalin-Model, Whole-body PBPK model of Pregabalin. https://github.com/Open-Systems-Pharmacology/Pregabalin-Model](https://github.com/Open-Systems-Pharmacology/Pregabalin-Model)

[6] [Alfentanil-Model, Whole-body PBPK model of Alfentanil. https://github.com/Open-Systems-Pharmacology/Alfentanil-Model](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model)

[7] [Sufenatnil-Model, Whole-body PBPK model of Sufenatnil. https://github.com/Open-Systems-Pharmacology/Sufenatnil-Model](https://github.com/Open-Systems-Pharmacology/Sufenatnil-Model)

[8] [Itraconazole-Model, Whole-body PBPK model of Itraconazole. https://github.com/Open-Systems-Pharmacology/Itraconazole-Model](https://github.com/Open-Systems-Pharmacology/Itraconazole-Model)

[9] [Montelukast-Model, Whole-body PBPK model of Montelukast. https://github.com/Open-Systems-Pharmacology/Montelukast-Model](https://github.com/Open-Systems-Pharmacology/Montelukast-Model)

[10] [Paclitaxel-Model, Whole-body PBPK model of Paclitaxel. https://github.com/Open-Systems-Pharmacology/Paclitaxel-Model](https://github.com/Open-Systems-Pharmacology/Paclitaxel-Model)


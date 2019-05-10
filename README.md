# Pediatric Ontogeny Qualification (PEQ)

## Translation of Adult PBPK  Model to Children

Using a developed and validated (adult) PBPK model for an *in vivo* probe substance, a pediatric PBPK model can be established for children by scaling physiology, clearance processes (as parameterized in the adult model) and age-dependent protein binding including the process specific variabilities. 

For qualification purpose, the following assumptions and considerations were made, 

- when scaling and adult model to children, it was assumed that the metabolism and excretion
  pathways are qualitatively the same in children as in adults.
- For qualification purpose, no further changes to any other input parameters (eg, lipophilicity, intestinal permeability, solubility) were allowed during the simulations in children. 

### Anthropometric and Physiological Information 

Regarding the age-dependencies of the relevant anthropometric (height, weight) and physiological parameters (blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in children was gathered from the literature and has been previously published [[1](#reference)]. The information was incorporated into PK-Sim® and was used as default values for the simulations in children.

The  applied ontogeny and variability of active processes that are built-in into PK-Sim® for translation to children, are described in the publically available ‘PK-Sim® Ontogeny Database Version 7.3 [[2](#reference)] or otherwise referenced for the specific process.

### Qualifications 

**Distribution and GFR ontogeny**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Amikacin
- Vamcomycin
- Pregabalin


**CYP3A4 enzyme ontogeny**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Containing
  - Alfentanil
  - Sufentanil
  - Itraconazole
  

**CYP2C8 enzyme ontogeny qualification**

For the Qualification of the distribution and GFR elimination of compounds, the following probe substances were included:

- Containing
  - Montelukast
  - Paclitaxel

  

## Reference

[1]  [OSPSuite.Documentation/PK-Sim Ontogeny Database Version 7.3.pdf ](https://github.com/Open-Systems-Pharmacology/OSPSuite.Documentation/blob/38cf71b384cfc25cfa0ce4d2f3addfd32757e13b/PK-Sim%20Ontogeny%20Database%20Version%207.3.pdf)

[2] [Edginton AN, Schmitt W, Willmann S. Development and evaluation of a generic physiologically based pharmacokinetic model for children. Clin Pharmacokinet. 2006;45(10):1013-34.](https://www.ncbi.nlm.nih.gov/pubmed/16984214)

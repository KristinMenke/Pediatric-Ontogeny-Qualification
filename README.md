# Pediatric Ontogeny Qualification (PEQ)

## Translation of Adult PBPK  Model to Children

Using a developed and validated (adult) PBPK model for an *in vivo* probe substance, a pediatric PBPK model can be established for children by scaling physiology, clearance processes (as parameterized in the adult model) and age-dependent protein binding including the process specific variabilities. 

The available information on ontogeny and variability of processes governing PK in children is considered, which are described in the publically available ‘PK-Sim® Ontogeny Database Version 7.3 [[1](#reference)].

For qualification purpose, the following assumptions and considerations were made, 

- when scaling and adult model to children, it was assumed that the metabolism and excretion
  pathways are qualitatively the same in children as in adults.

- For qualification purpose, no further changes to any other input parameters (eg, lipophilicity, intestinal permeability, solubility) should be allowed during the simulations in children. 


### Anthropometric and Physiological Information 

Regarding the age-dependencies of the relevant anthropometric (height, weight) and physiological parameters (blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in children was gathered from the literature and has been
previously published [[2](#reference)]. The information was incorporated into PK-Sim® and was used as default values for the simulations in children.

A detailed description of the literature information relevant for the translation ADME processes from adults to children incorporated into the pediatric PBPK model used for the scaling procedure can be found in Section xxx. The Workflow for extrapolation from adults to the pediatric population is described in Best Practices Population Simulation (ref) and Pediatric scaling (ref) and depicted in Figure 4‑2. 

**Distribution and GFR ontogeny qualification**

- Containing
  - Amikacin
  - Vamcomycin
  - Pregabalin

**CYP3A4 ontogeny qualification**

- Containing
  - Alfentanil
  - Sufentanil
  - Itraconazole

**CYP2C8 ontogeny qualification**

- Containing
  - Montelukast
  - Paclitaxel
  
  
  

## Reference

[1]  [OSPSuite.Documentation/PK-Sim Ontogeny Database Version 7.3.pdf ](https://github.com/Open-Systems-Pharmacology/OSPSuite.Documentation/blob/38cf71b384cfc25cfa0ce4d2f3addfd32757e13b/PK-Sim%20Ontogeny%20Database%20Version%207.3.pdf)

[2] [Edginton AN, Schmitt W, Willmann S. Development and evaluation of a generic physiologically based pharmacokinetic model for children. Clin Pharmacokinet. 2006;45(10):1013-34.](https://www.ncbi.nlm.nih.gov/pubmed/16984214)


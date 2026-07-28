# Fraxinus-angustifolia-responses-to-mammalian-herbivory

This repository contains data and scripts for data analyses performed for the publication: 'The architectural response of a mediterranean tree to mammalian browsing overwhelms the leaf's chemical and structural responses' by Barral, Bochu, Caries, Gaudry, Lecoq, Lo Bue _et al._, [year] (doi)

## Summary

This study characterises the responses of Fraxinus angustifolia to browsing by large mammals, here investigated through cattle browsing. We compared unbrowsed and browsed individuals to characterise plastic responses at three levels of organisation: leaf secondary compounds, leaf structure, and whole-plant structure. We conducted this study in a Mediterranean open woodland located in southern France, where cattle pasture occurred for 29 years.

Chemical and structural leaf-level traits suggested a tolerance strategy. We found no differences between treatments in leaf concentrations of common chemical defences (total phenols and condensed tannins) and browsed trees exhibited less expensive leaves with reduced leaf area and leaf dry matter content. In contrast, architectural traits highlighted a defensive strategy: 1) multiple trunks from the base of the plant 2) a highly branched cage-like architecture, associated with a lower herbivore bite size index showing the limitation of biomass consumption by large mammalian herbivores. In addition, while browsed individuals invested in structural defences, they did not produce any reproductive organ over the study period, suggesting a lower investment in reproduction.

## Data

1. chemical_traits.csv contains data for phenols and tannins concentration in leaves

2. structural_leaf_traits.csv contains data for leaf area, leaf mass per area and leaf dry matter content

3. architectural_traits.csv contains data for branch density, the number of trunk reiterates, bite size index, presence of C3 axes and sexual organs
   Description of columns:
   - 'Treatment' is coded as C for control, unbrowsed individuals; and H for 'herbivory', browsed individuals
   - 'mass_bite' is the preleved biomass (in g) by the experimenter bite that is further used to compute the bite size index. See Wigley _et al._ (2020) for the detailed protocol (doi.org/10.1071/BT20048_CO)
   - 'height' and 'circ' are tree height at the highest point of the canopy, and trunk circumference at the base of the trunk. Both are expressed in cm
   - 'reit_bas_tot' and 'reit_bas_part' are the number of total and partial reiterates, respectively, from the base of the trunk. See Barthélémy & Caraglio (2007, doi.org/10.1093/aob/mcl260) for a definition of reiterates and axis categories
   - 'nb_c2_c1' is the number of branches (C2) borne on a trunk (C1)
   - 'c3' is the presence, coded as '1', or absence, coded as '0', of short shoots (C3 axis)
   - 'sex' is the presence, coded as '1', or absence, coded as '0', of sexual organs

## Data analysis

describe briefly scripts

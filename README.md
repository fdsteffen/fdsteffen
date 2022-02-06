<img src=header.png/>

<p align="center">
<a href="https://ch.linkedin.com/in/fabio-steffen" target="blank"><p align="center"><img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://orcid.org/0000-0001-8795-2212" target="blank"><img src="https://img.shields.io/badge/orcid%20-%23A6CE39.svg?&style=for-the-badge&logo=orcid&logoColor=white"/></a>
</p>

Working at the intersections of chemistry, physics and biology, I integrate multimodal data from **single-molecule microscopy** and **molecular modeling** to explore the folding landscapes of large RNAs. 

To this end, I have been developing frameworks to simulate fluorescence spectroscopy experiments *in silico*. Some recent projects are featured below. For an extended list visit [RNA-FRETools](https://github.com/RNA-FRETools).

## Featured Projects

|  Package  | brief description | language & deployment |
|---|---|---|
| <a href="https://github.com/RNA-FRETools/lifefit"> <img src=https://github.com/RNA-FRETools/lifefit/blob/master/docs/source/_static/lifefit_logo.png width=50px/></a> | Analyze fluorescence lifetime and anisotropy decays interactively | <img src="https://img.shields.io/badge/python%20-%2300599C.svg?&style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter%20-%23F37626.svg?&style=flat-square&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/heroku%20-%23430098.svg?&style=flat-square&logo=heroku&logoColor=white"/>|
| <a href="https://github.com/RNA-FRETools/fretlabel"> <img src=https://github.com/RNA-FRETools/fretlabel/blob/master/docs/images/fretlabel_logo.png width=50px/></a> | Label nucleic acids with fluorophores for molecular dynamics simulations | <img src="https://img.shields.io/badge/python%20-%2300599C.svg?&style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyMOL%20-%238a8a8a.svg?&style=flat-square&logo=moleculer&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-5093c7.svg?&style=flat-square&logo=docker&logoColor=white"/> |
| <a href="https://github.com/RNA-FRETools/fretraj"> <img src=https://github.com/RNA-FRETools/fretraj/blob/master/docs/images/fretraj_logo.png width=50px/></a> | Calculate dye accessible-contact volumes (ACV) and predict FRET efficiencies | <img src="https://img.shields.io/badge/python%20-%2300599C.svg?&style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/c++%20-%2349B16C.svg?&style=flat-square&logo=c%2B%2B&ogoColor=white"/> <img src="https://img.shields.io/badge/PyMOL%20-%238a8a8a.svg?&style=flat-square&logo=moleculer&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-5093c7.svg?&style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter%20-%23F37626.svg?&style=flat-square&logo=Jupyter&logoColor=white"/> |

## Selected Publications
&rarr; click to expand

<details>
<summary>F. D. Steffen, R. K. O. Sigel, R. Börner, <i>Bioinformatics</i> (2021) <a href="https://doi.org/10.1093/bioinformatics/btab615"><img src="https://img.shields.io/badge/DOI-10.1093/bioinformatics/btab615-blue.svg?&style=flat-square"/></a></summary>
<br><p align="center"><img src=graphical_abstracts/Steffen_Bioinformatics_2021.jpg width=500px></p>
<h3>FRETraj: integrating single-molecule spectroscopy with molecular dynamics</h3>
Quantitative interpretation of single-molecule FRET experiments requires a model of the dye dynamics to link experimental energy transfer efficiencies to distances between atom positions. We have developed FRETraj, a Python module to predict FRET distributions based on accessible-contact volumes (ACV) and simulated photon statistics.
FRETraj helps to identify optimal fluorophore positions on a biomolecule of interest by rapidly evaluating donor-acceptor distances. FRETraj is scalable and fully integrated into PyMOL and the Jupyter ecosystem. Here, we describe the conformational dynamics of a DNA hairpin by computing multiple ACVs along a molecular dynamics trajectory and compare the predicted FRET distribution with single-molecule experiments. FRET-assisted modeling will accelerate the analysis of structural ensembles in particular dynamic, non-coding RNAs and transient proteinnucleic acid complexes.
</details>

<details>
<summary>F. D. Steffen, M. Khier, D. Kowerko, R. A. Cunha, R. Börner, R. K. O. Sigel, <i>Nat. Commun.</i> (2020) <a href="https://doi.org/10.1038/s41467-019-13683-4"><img src="https://img.shields.io/badge/DOI-10.1038/s41467--019--13683--4-blue.svg?&style=flat-square"/></a></summary>
<br><p align="center"><img src=graphical_abstracts/Steffen_NatCommun_2020.jpg width=500px></p>
<h3>Metal ions and sugar puckering balance single-molecule kinetic heterogeneity in RNA and DNA tertiary contacts</h3>
The fidelity of group II intron self-splicing and retrohoming relies on long-range tertiary interactions between the intron and its flanking exons. By single-molecule FRET, we explore the binding kinetics of the most important, structurally conserved contact, the exon and intron binding site 1 (EBS1/IBS1). A comparison of RNA-RNA and RNA-DNA hybrid contacts identifies transient metal ion binding as a major source of kinetic heterogeneity which typically appears in the form of degenerate FRET states. Molecular dynamics simulations suggest a structural link between heterogeneity and the sugar conformation at the exon-intron binding interface. While Mg<sup>2+</sup> ions lock the exon in place and give rise to long dwell times in the exon bound FRET state, sugar puckering alleviates this structural rigidity and likely promotes exon release. The interplay of sugar puckering and metal ion coordination may be an important mechanism to balance binding affinities of RNA and DNA interactions in general.
</details>

<details>
<summary>F. D. Steffen, R. Börner, E. Freisinger, R. K. O. Sigel, <i>Chimia</i> (2019) <a href="https://doi.org/10.2533/chimia.2019.257"><img src="https://img.shields.io/badge/DOI-10.2533/chimia.2019.257-blue.svg?&style=flat-square"/></a></summary>
<br><p align="center"><img src=graphical_abstracts/Steffen_Chimia_2019.jpg width=500px></p>
<h3>Stick, Flick, Click: DNA-guided Fluorescent Labeling of Long RNA for Single-molecule</h3>
Exploring the spatiotemporal dynamics of biomolecules on a single-molecule level requires innovative ways to make them spectroscopically visible. Fluorescence resonance energy transfer (FRET) uses a pair of organic dyes as reporters to measure distances along a predefined biomolecular reaction coordinate. For this nanoscopic ruler to work, the fluorescent labels need to be coupled onto the molecule of interest in a bioorthogonal and site-selective manner. Tagging large non-coding RNAs with single-nucleotide precision is an open challenge. Here we summarize current strategies in labeling riboswitches and ribozymes for fluorescence spectroscopy and FRET in particular. A special focus lies on our recently developed, DNA-guided approach that inserts two fluorophores through a stepwise process of templated functionality transfer and click chemistry.
</details>

<details>
<summary>M. Zhao, F. D. Steffen, R. Börner, M. F. Schaffer, R. K. O. Sigel, <i>Nucleic Acids Res.</i> (2018) <a href="https://doi.org/10.1093/nar/gkx1100"><img src="https://img.shields.io/badge/DOI-10.1093/nar/gkx1100-blue.svg?&style=flat-square"/></a></summary>
<br><p align="center"><img src=graphical_abstracts/Zhao_NAR_2018.jpg width=500px></p>
<h3>Site-specific dual-color labeling of long RNAs for single-molecule spectroscopy</h3>
Labeling of long RNA molecules in a site-specific yet generally applicable manner is integral to many spectroscopic applications. Here we present a novel covalent labeling approach that is site-specific and scalable to long intricately folded RNAs. In this approach, a custom-designed DNA strand that hybridizes to the RNA guides a reactive group to target a preselected adenine residue. The functionalized nucleotide along with the concomitantly oxidized 3'-terminus can subsequently be conjugated to two different fluorophores via bio-orthogonal chemistry. We validate this modular labeling platform using a regulatory RNA of 275 nucleotides, the btuB riboswitch of Escherichia coli, demonstrate its general applicability by modifying a base within a duplex, and show its site-selectivity in targeting a pair of adjacent adenines. Native folding and function of the RNA is confirmed on the single-molecule level by using FRET as a sensor to visualize and characterize the conformational equilibrium of the riboswitch upon binding of its cofactor adenosylcobalamin. The presented labeling strategy overcomes size and site constraints that have hampered routine production of labeled RNA that are beyond 200 nt in length.
</details>

<details>
<summary>F. D. Steffen, R. K. O. Sigel, R. Börner, <i>Phys. Chem. Chem. Phys.</i> (2016) <a href="https://doi.org/10.1039/c6cp04277e "><img src="https://img.shields.io/badge/DOI-10.1039/c6cp04277e -blue.svg?&style=flat-square"/></a></summary>
<br><p align="center"><img src=graphical_abstracts/Steffen_PCCP_2016.jpg width=500px></p>
<h3>An atomistic view on carbocyanine photophysics in the realm of RNA</h3>
Carbocyanine dyes have a long-standing tradition in fluorescence imaging and spectroscopy, due to their photostability and large spectral separation between individual dye species. Herein, we explore the versatility of cyanine dyes to probe the dynamics of nucleic acids and we report on the interrelation of fluorophores, RNA, and metal ions, namely K(+) and Mg(2+). Photophysical parameters including the fluorescence lifetime, quantum yield and dynamic anisotropy are monitored as a function of the nucleic acid composition, conformation, and metal ion abundance. Occasional excursions to a non-fluorescent cis-state hint at the remarkable sensitivity of carbocyanines to their local environment. Comparison of time-correlated single photon experiments with all-atom molecular dynamics simulations demonstrate that the propensity of photoisomerization is dictated by sterical constraints imposed on the fluorophore. Structural features in the vicinity of the dye play a crucial role in RNA recognition and have far-reaching implications on the mobility of the fluorescent probe. An atomic level description of the mutual interactions will ultimately benefit the quantitative interpretation of single-molecule FRET measurements on large RNA systems.
</details>

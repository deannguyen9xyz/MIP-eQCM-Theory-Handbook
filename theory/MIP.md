# Molecularly imprinted polymers

The concept of molecular imprinting started early in the 20th century and gained significant recognition in the 1980s. Wulff and colleagues demonstrated that polymers could be tailored to incorporate specific binding sites for target molecules through template molecules during polymerization [125]. This discovery laid the groundwork for the development of molecularly imprinted polymers (MIPs) that are functional materials mimic biological receptors in discriminating between molecules but surpassing them in lower preparation cost and environmental stability [126]. Since then, there have been substantial advancements in MIP technology, including improvements in synthesis methods, characterization techniques, and their applications across diverse fields. These innovations have enabled MIPs to be produced in various shapes, such as membranes, thin layers, nanoparticles, regular spherical particles, irregularly ground particles, and composites [127]. MIPs have become highly versatile materials and are employed in numerous fields such as determine selected target in analytical chemistry [128], monitoring contaminants in environmental/ milk/ food samples [129–131] and enhance the efficiency of therapeutic compounds in drug delivery [132].

## 1. Principles of MIPs
The fundamental concept of MIPs is based on the formation of a polymer network containing specific binding sites that are complementary toward a target template molecule. This is achieved by polymerizing suitable functional monomers in the presence of target analyte, or similar molecules, acting as template molecules. The template molecule is chosen depending on application purpose with a wide variety of them are available, covering from large molecules (e.g., protein) to smaller organic compounds (e.g., antibiotic) [133,134]. The suitable functional monomers interact initially with template to form a pre-polymerization complex. During the subsequent polymerization, the template is embedded within the polymer matrix. By removing the template, cavities that are chemical complementary to the original target molecules are revealed, enabling highly selective recognition of the target molecules (Figure 1). Based on how templates interact with functional monomers, molecular imprinting approaches are categorized as covalent, non-covalent, semi-covalent, and meta-ion interaction.

<div align="center">
<img width="709" height="234" alt="image" src="https://github.com/user-attachments/assets/71a5ee3e-5b37-4a1f-80ce-272dfb8e28c7" />

Figure 1. Schematic representation of molecular imprinting
</div>

The covalent approach involves the formation of reversible covalent bonds between the template and functional monomers during the polymerization process. The complexes are highly stable under a broad range of conditions for polymerization are the main advantages of this approach. However, this approach has limited numbers of suitable monomers (e.g., alcohols, aldehydes, ketones, amines or carboxylic acids) and challenging to remove the template during template removal [135]. Furthermore, due to the difficulty in the rebinding/removal of the template, this approach is unsuitable for applications requiring fast kinetics [136].

On the other hand, non-covalent approach is favoured for its simplicity with the variety of possible functional groups and fast template removal [137]. It relies on weak interactions such as hydrogen bonding, van der Waals forces, and electrostatic interactions to form the pre-polymerization complex [138]. This makes it widely used in various investigation and practical application. However, the specificity of the binding sites is compromised due to the heterogeneity resulting from the formation of various pre-polymerization complexes, as well as the direct competition from the solvent and the cross-linker [135].

The third approach, semi-covalent, is the combination of both covalent and non-covalent binding. The template is covalently bound to the functional monomer during polymerization, but noncovalent interactions are exploited during the rebinding [139]. Imprinting semi-covalent owns the advantages of both approaches while counterbalancing their disadvantages, offering a balance between stability and flexibility.

Lastly, the metal-ion interaction approach utilizes coordination bonds to form highly specific recognition sites, making it ideal for imprinting metal ions or molecules with strong metal affinity. However, it is limited to strategies involving complex-forming groups with metals [140,141].


## 2. Computational approach for the selection of suitable functional monomer

The effectiveness of MIPs primarily depends on the strength of the interaction between the template molecule and the functional monomer [142]. This interaction facilitates the formation of molecular memory within the MIP by considering both the shape and arrangement of functional groups in the template molecule. Therefore, the choice of functional monomer is a critical factor in achieving the optimal performance of a MIP. It can be accomplished by conducting a preliminary study of molecular complexes between a monomer and template molecule to design MIP with optimal performance. Traditionally, this selection process has been largely involving experimental screening. However, computational approaches have emerged as powerful tools to rationalize and optimize the selection of functional monomers in MIP research nowadays.

By simulation and estimation of interactions between template and monomer molecules, the trial-and-error steps are carried out via computational software reduce reagents consumptions and amount of time for experimental work [143]. Different computational approaches, including quantum mechanics (QM), molecular mechanics, and molecular dynamics were reported to provide insights into the molecular interactions, lead to the selection of suitable functional monomers, purpose optimizing the overall efficiency [134]. Within this work, QM approach was chosen for its ability to estimate the chemical binding energies with high accuracy for modelling weak non-covalent interactions which suitable to apply for small systems. QM focus on the approximation of electron density to offer insight into the non-covalent interactions that govern the binding affinity between the template and monomer [144]. The use of binding energies calculations on complexes between the template and monomers was adopted by Luliński at PM3 level of theory for the design of a dopamine-imprinted polymer system [145]. Dong et al. calculated the binding energy of theophylline molecule and monomer in MIP using DFT at B3LYP/6–31+G**//B3LYP/3–21 G level in Gaussian 09 for the screening of functional monomers for the fabrication of highly selective MIP [146].

## 3. Synthesis method

Most often MIPs are prepared by free radical polymerization using a variety of methods, such as bulk, suspension, precipitation, emulsion, swelling and surface imprinting polymerizations. Even though these methods are well-established, they may not precisely control the thickness of polymer and can be challenging for template removal [132]. Meanwhile, electropolymerization allows for direct deposition of the polymer onto an electrode surface, enabling precise control over the thickness, which are critical for sensor applications [147]. Moreover, this synthesis method has superior properties with respect to adherence to the transducer surface (e.g., gold, carbon, platinum), along with simplicity and possibility of operation in aqueous solutions at room temperature [148,149].

The film thickness is governed by the amount of charge transferred during electropolymerization under galvanostatic, potentiostatic, or potentiodynamic conditions [147]. It involves the anodic oxidation of an electropolymerizable monomer employing different modes of potential stimulus to form radical cation [150]. These unstable radicals quickly react with other monomers thereby forming oligomers and subsequently the final polymer chain [151]. Such polymerization requires an electrolyte in the form of a solvent containing a doping salt or an ionically conducting medium [152].
To achieve optimal imprinting efficiency, it is crucial to preserve the structural integrity of the template molecules during electrosynthesis by preventing template oxidation during electropolymerization [153–155]. A wide range of electropolymerizable monomers is available, among which commonly used examples are pyrrole [156], aniline [157], thiophene [158], phenol [159], phenylenediamine [160], 3,4-ethylenedioxythiophene (EDOT) [161], and aminophenylboronic acid [162].

## 3. Class-selective MIPs

Even though[VS15.1] MIPs are designed to selectively bind a single target molecule; recently group-selective or class-selective MIPs were developed, offering the capability to recognize many structurally similar molecules [163,164]. During the synthesis process, the use of a single template as a substitute for a whole class takes full advantage of similar molecular structures among compounds. This method optimizes the preparation stage by reducing the required template amount, particularly advantageous in applications where imprint for each individual member of a class is unnecessary. This phenomenon is useful in environmental monitoring, pharmaceuticals, or food safety, where detecting entire classes of contaminants, drugs, or toxins can be more practical and efficient. For example, class-selective MIPs will result in their enrichment and detection simultaneously for polychlorinated aromatic compounds that occur as congeners or homologs [165]. However, designing class-selective MIPs requires a profound comprehension of the complex molecular features that define the target class. Additionally, the potential of cross-reactivity toward unwanted molecules is also another challenge. Thus, the further development and optimization of template design and functional monomers composition is required to improve the class-selective MIPs’ performance for real-world applications.

## References

[125]	G. Wulff, W. Vesper, R. Grobe‐Einsler, A. Sarhan, Enzyme‐analogue built polymers, 4. On the synthesis of polymers containing chiral cavities and their use for the resolution of racemates, Makromol. Chem. 178 (1977) 2799–2816. https://doi.org/10.1002/macp.1977.021781004.

[126]	K. Haupt, P.X. Medina Rangel, B.T.S. Bui, Molecularly Imprinted Polymers: Antibody Mimics for Bioimaging and Therapy, Chem. Rev. 120 (2020) 9554–9582. https://doi.org/10.1021/acs.chemrev.0c00428.

[127]	B. Fresco-Cala, A.D. Batista, S. Cárdenas, Molecularly Imprinted Polymer Micro- and Nano-Particles: A Review, Molecules 25 (2020) 4740. https://doi.org/10.3390/molecules25204740.

[128]	J.W. Lowdon, H. Diliën, P. Singla, M. Peeters, T.J. Cleij, B. Van Grinsven, K. Eersels, MIPs for commercial application in low-cost sensors and assays – An overview of the current status quo, Sensors and Actuators B: Chemical 325 (2020) 128973. https://doi.org/10.1016/j.snb.2020.128973.

[129]	V. Ayerdurai, M. Cieplak, W. Kutner, Molecularly imprinted polymer-based electrochemical sensors for food contaminants determination, TrAC Trends in Analytical Chemistry 158 (2023) 116830. https://doi.org/10.1016/j.trac.2022.116830.

[130]	Y. Pan, X. Liu, J. Liu, J. Wang, J. Liu, Y. Gao, N. Ma, Chemiluminescence sensors based on molecularly imprinted polymers for the determination of organophosphorus in milk, Journal of Dairy Science 105 (2022) 3019–3031. https://doi.org/10.3168/jds.2021-21213.

[131]	A.G. Ayankojo, J. Reut, V.B.C. Nguyen, R. Boroznjak, V. Syritski, Advances in Detection of Antibiotic Pollutants in Aqueous Media Using Molecular Imprinting Technique—A Review, Biosensors 12 (2022) 441. https://doi.org/10.3390/bios12070441.

[132]	S. He, L. Zhang, S. Bai, H. Yang, Z. Cui, X. Zhang, Y. Li, Advances of molecularly imprinted polymers (MIP) and the application in drug delivery, European Polymer Journal 143 (2021) 110179. https://doi.org/10.1016/j.eurpolymj.2020.110179.

[133]	A.G. Ayankojo, R. Boroznjak, J. Reut, A. Öpik, V. Syritski, Molecularly imprinted polymer based electrochemical sensor for quantitative detection of SARS-CoV-2 spike protein, Sensors and Actuators B: Chemical 353 (2022) 131160. https://doi.org/10.1016/j.snb.2021.131160.

[134]	A.G. Ayankojo, A. Tretjakov, J. Reut, R. Boroznjak, A. Öpik, J. Rappich, A. Furchner, K. Hinrichs, V. Syritski, Molecularly Imprinted Polymer Integrated with a Surface Acoustic Wave Technique for Detection of Sulfamethizole, Anal. Chem. 88 (2016) 1476–1484. https://doi.org/10.1021/acs.analchem.5b04735.

[135]	A. Herrera-Chacón, X. Cetó, M. Del Valle, Molecularly imprinted polymers - towards electrochemical sensors and electronic tongues, Anal Bioanal Chem 413 (2021) 6117–6140. https://doi.org/10.1007/s00216-021-03313-8.

[136]	X. Wu, Synthetic Strategies for the Generation of Molecularly Imprinted Polymers, in: Z. Liu, Y. Huang, Y. Yang (Eds.), Molecularly Imprinted Polymers as Advanced Drug Delivery Systems, Springer Singapore, Singapore, 2021: pp. 27–59. https://doi.org/10.1007/978-981-16-0227-6_2.

[137]	E. Yılmaz, B. Garipcan, H. Patra, L. Uzun, Molecular Imprinting Applications in Forensic Science, Sensors 17 (2017) 691. https://doi.org/10.3390/s17040691.

[138]	A. Martín-Esteban, Molecularly-imprinted polymers as a versatile, highly selective tool in sample preparation, TrAC Trends in Analytical Chemistry 45 (2013) 169–181. https://doi.org/10.1016/j.trac.2012.09.023.

[139]	M. Gao, Y. Gao, G. Chen, X. Huang, X. Xu, J. Lv, J. Wang, D. Xu, G. Liu, Recent Advances and Future Trends in the Detection of Contaminants by Molecularly Imprinted Polymers in Food Samples, Front. Chem. 8 (2020) 616326. https://doi.org/10.3389/fchem.2020.616326.

[140]	B.-C. Iacob, A.E. Bodoki, L. Oprean, E. Bodoki, Metal–Ligand Interactions in Molecular Imprinting, in: C. Saravanan, B. Biswas (Eds.), Ligand, InTech, 2018. https://doi.org/10.5772/intechopen.73407.

[141]	L. Wu, Y. Li, Metal ion-mediated molecular-imprinting polymer for indirect recognition of formate, acetate and propionate, Analytica Chimica Acta 517 (2004) 145–151. https://doi.org/10.1016/j.aca.2004.05.015.

[142]	A.G. Ayankojo, J. Reut, A. Öpik, A. Tretjakov, V. Syritski, Enhancing binding properties of imprinted polymers for the detection of small molecules, Proc. Estonian Acad. Sci. 67 (2018) 138. https://doi.org/10.3176/proc.2018.2.04.

[143]	T. Sajini, B. Mathew, A brief overview of molecularly imprinted polymers: Highlighting computational design, nano and photo-responsive imprinting, Talanta Open 4 (2021) 100072. https://doi.org/10.1016/j.talo.2021.100072.

[144]	N. Kumar, S. Saha, G.N. Sastry, Towards developing a criterion to characterize non-covalent bonds: a quantum mechanical study, Phys. Chem. Chem. Phys. 23 (2021) 8478–8488. https://doi.org/10.1039/D0CP05689H.

[145]	P. Luliński, D. Maciejewska, M. Bamburowicz-Klimkowska, M. Szutowski, Dopamine-Imprinted Polymers: Template-Monomer Interactions, Analysis of Template Removal and Application to Solid Phase Extraction, Molecules 12 (2007) 2434–2449. https://doi.org/10.3390/12112434.

[146]	W. Dong, M. Yan, M. Zhang, Z. Liu, Y. Li, A computational and experimental investigation of the interaction between the template molecule and the functional monomer used in the molecularly imprinted polymer, Analytica Chimica Acta 542 (2005) 186–192. https://doi.org/10.1016/j.aca.2005.03.032.

[147]	P.S. Sharma, A. Pietrzyk-Le, F. D’Souza, W. Kutner, Electrochemically synthesized polymers in molecular imprinting for chemical sensing, Anal Bioanal Chem 402 (2012) 3177–3204. https://doi.org/10.1007/s00216-011-5696-6.

[148]	M.C. Blanco-L�pez, S. Guti�rrez-Fern�ndez, M.J. Lobo-Casta��n, A.J. Miranda-Ordieres, P. Tu��n-Blanco, Electrochemical sensing with electrodes modified with molecularly imprinted polymer films, Analytical and Bioanalytical Chemistry 378 (2004) 1922–1928. https://doi.org/10.1007/s00216-003-2330-2.

[149]	D. Zane, A. Raffaele, A. Curulli, G.B. Appetecchi, S. Passerini, Electrosynthesis of poly(o-phenylenediamine) in a room temperature ionic liquid, Electrochemistry Communications 9 (2007) 2037–2040. https://doi.org/10.1016/j.elecom.2007.06.002.

[150]	G. Fomo, T. Waryo, U. Feleni, P. Baker, E. Iwuoha, Electrochemical Polymerization, in: M.A. Jafar Mazumder, H. Sheardown, A. Al-Ahmed (Eds.), Functional Polymers, Springer International Publishing, Cham, 2019: pp. 105–131. https://doi.org/10.1007/978-3-319-95987-0_3.

[151]	G. Appel, D. Schmeißer, J. Bauer, M. Bauer, H.J. Egelhaaf, D. Oelkrug, The formation of oligomers in the electrolyte upon polymerization of pyrrole, Synthetic Metals 99 (1999) 69–77. https://doi.org/10.1016/S0379-6779(98)00200-8.

[152]	R.D. Crapnell, A. Hudson, C.W. Foster, K. Eersels, B.V. Grinsven, T.J. Cleij, C.E. Banks, M. Peeters, Recent Advances in Electrosynthesized Molecularly Imprinted Polymer Sensing Platforms for Bioanalyte Detection, Sensors 19 (2019) 1204. https://doi.org/10.3390/s19051204.

[153]	A. Pietrzyk, S. Suriyanarayanan, W. Kutner, R. Chitta, F. D’Souza, Selective Histamine Piezoelectric Chemosensor Using a Recognition Film of the Molecularly Imprinted Polymer of Bis(bithiophene) Derivatives, Anal. Chem. 81 (2009) 2633–2643. https://doi.org/10.1021/ac8025652.

[154]	A. Pietrzyk, S. Suriyanarayanan, W. Kutner, R. Chitta, M.E. Zandler, F. D’Souza, Molecularly imprinted polymer (MIP) based piezoelectric microgravimetry chemosensor for selective determination of adenine, Biosensors and Bioelectronics 25 (2010) 2522–2529. https://doi.org/10.1016/j.bios.2010.04.015.

[155]	P. Zahedi, M. Ziaee, M. Abdouss, A. Farazin, B. Mizaikoff, Biomacromolecule template-based molecularly imprinted polymers with an emphasis on their synthesis strategies: a review: Biomacromolecule Template-Based MIP, Polym. Adv. Technol. 27 (2016) 1124–1142. https://doi.org/10.1002/pat.3754.

[156]	M.D.L. Gonçalves, L.A.N. Truta, M.G.F. Sales, F.T.C. Moreira, Electrochemical Point-of Care (PoC) Determination of Interleukin-6 (IL-6) Using a Pyrrole (Py) Molecularly Imprinted Polymer (MIP) on a Carbon-Screen Printed Electrode (C-SPE), Analytical Letters 54 (2021) 2611–2623. https://doi.org/10.1080/00032719.2021.1879108.

[157]	T.-X. Chu, V.-P. Vu, H.-T. Tran, T.-L. Tran, Q.-T. Tran, T. Le Manh, Molecularly Imprinted Polyaniline Nanowire-Based Electrochemical Biosensor for Chloramphenicol Detection: A Kinetic Study of Aniline Electropolymerization, J. Electrochem. Soc. 167 (2020) 027527. https://doi.org/10.1149/1945-7111/ab6a7e.

[158]	Y. Pan, D. Shan, L. Ding, X. Yang, K. Xu, H. Huang, J. Wang, H. Ren, Developing a generally applicable electrochemical sensor for detecting macrolides in water with thiophene-based molecularly imprinted polymers, Water Research 205 (2021) 117670. https://doi.org/10.1016/j.watres.2021.117670.

[159]	B. Qader, M. Baron, I. Hussain, J.M. Sevilla, R.P. Johnson, J. Gonzalez-Rodriguez, Electrochemical determination of disulfoton using a molecularly imprinted poly-phenol polymer, Electrochimica Acta 295 (2019) 333–339. https://doi.org/10.1016/j.electacta.2018.10.127.

[160]	A. Radi, M. Ragaa Abd‐Ellatief, Molecularly Imprinted Poly‐o‐phenylenediamine Electrochemical Sensor for Entacapone, Electroanalysis 33 (2021) 1578–1584. https://doi.org/10.1002/elan.202100022.

[161]	G. Kaniraja, M. Karthikeyan, M.D. Kumar, P. Ananthappan, A. Anil, V.S. Vasantha, K.A. Kumar, C. Karunakaran, Molecularly imprinted (3, 4-ethylenedioxythiophene) polymer based electrochemical non-enzymatic glucose sensor, Organic Electronics 138 (2025) 107181. https://doi.org/10.1016/j.orgel.2024.107181.

[162]	M. Karthikeyan, M. Dhinesh Kumar, G. Kaniraja, P. Ananthappan, V. Sivasamy Vasantha, C. Karunakaran, Gold nanoparticles enhanced molecularly imprinted poly(3-aminophenylboronic acid) sensor for myo-inositol detection, Microchemical Journal 189 (2023) 108536. https://doi.org/10.1016/j.microc.2023.108536.

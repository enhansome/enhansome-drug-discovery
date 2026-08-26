# Awesome Drug Discovery with stars

Computational methods for identifying and developing new drug candidates.

> Drug discovery is the process by which new candidate medications are identified, designed, and developed using experimental, computational, and informational techniques to address complex challenges in biology, chemistry, and medicine. — [Wikipedia](https://en.wikipedia.org/wiki/Drug_discovery)

## Contents

* [Databases and Chemical Libraries](#databases-and-chemical-libraries)
  * [General Compound Libraries](#general-compound-libraries)
  * [Natural Product Libraries](#natural-product-libraries)
  * [Bioactivity Databases](#bioactivity-databases)
* [Target and Protein Data](#target-and-protein-data)
  * [Protein Structures](#protein-structures)
  * [Binding Site and Pocket Detection](#binding-site-and-pocket-detection)
  * [Protein Engineering and Modeling](#protein-engineering-and-modeling)
* [Network Pharmacology](#network-pharmacology)
* [Ligand Design and Optimization](#ligand-design-and-optimization)
  * [Pharmacophore Modeling](#pharmacophore-modeling)
  * [QSAR and Descriptor Tools](#qsar-and-descriptor-tools)
  * [Descriptor and Featurization Tools](#descriptor-and-featurization-tools)
  * [Molecular Property Prediction](#molecular-property-prediction)
  * [Fragment-Based Drug Design](#fragment-based-drug-design)
* [Virtual Screening and Docking](#virtual-screening-and-docking)
* [Interaction Analysis and Visualization](#interaction-analysis-and-visualization)
* [Molecular Dynamics and Simulation](#molecular-dynamics-and-simulation)
  * [Engines](#engines)
  * [Topology and Force Field Tools](#topology-and-force-field-tools)
  * [Analysis Tools](#analysis-tools)
* [Synthesis and Retrosynthesis Planning](#synthesis-and-retrosynthesis-planning)
* [Specialized Modalities](#specialized-modalities)
  * [PROTACs and Ternary Complexes](#protacs-and-ternary-complexes)
  * [Peptide Design](#peptide-design)
* [Machine Learning and AI](#machine-learning-and-ai)
  * [Chemistry-focused ML Frameworks](#chemistry-focused-ml-frameworks)
  * [Pretrained Models](#pretrained-models)
  * [Molecule Standardization](#molecule-standardization)
* [Utility and Workflow Tools](#utility-and-workflow-tools)
* [Learning Resources](#learning-resources)
  * [Free Courses](#free-courses)
  * [Blogs](#blogs)
  * [Instructional Notebooks](#instructional-notebooks)
* [Labs and Research Groups](#labs-and-research-groups)

## Databases and Chemical Libraries

### General Compound Libraries

* [DrugBank](https://go.drugbank.com/) - Comprehensive data on approved and investigational drugs.
* [ZINC](https://zinc.docking.org/) - Free compounds for screening.
* [ChemSpider](http://www.chemspider.com/) - Chemical structures and data.
* [DrugSpaceX](https://drugspacex.simm.ac.cn/) - Chemical and biological spaces.
* [Mcule](https://mcule.com/) - Virtual screening platform with purchasable compounds.
* [Otava Chemicals](https://www.otavachemicals.com/) - Screening compounds and building blocks.
* [Vitas-M Laboratory](https://vitasmlab.biz/) - Chemical libraries for HTS and lead discovery.
* [Eximed](https://eximedlab.com/Screening-Compounds.html) - 60k+ compounds for virtual screening.
* [OTAVA NP-like Library](https://otavachemicals.com/sdf) - Screening compounds for prompt delivery.
* [Ambinter](https://www.ambinter.com/) - 40M+ compounds for HTS, building blocks, and a wide selection of fragments and natural products.
* [VAST Chemical Space](https://www.aifchem.com/vast) - 4.6 billion synthetically accessible compounds for virtual screening and hit expansion.

### Natural Product Libraries

* [ZINC15 Natural Products](https://zinc15.docking.org/substances/subsets/natural-products/) - 200k+ natural compounds.
* [COCONUT](https://coconut.naturalproducts.net/) - 400k+ natural products.
* [LOTUS](https://lotus.naturalproducts.net/) - Annotated molecular data with sourcing organisms.
* [NPASS](http://bidd.group/NPASS/index.php) - 94k activity-species links.
* [ANPDB](https://phabidb.vm.uni-freiburg.de/anpdb/) - 27k+ African medicinal plant compounds.
* [SANCDB](https://sancdb.rubi.ru.ac.za/) - Natural compounds from the plant and marine life in and around South Africa.
* [CMNPD](https://www.cmnpd.org/) - 31k+ marine natural products.
* [The Natural Products Atlas](https://www.npatlas.org/) - An open-access database for microbial natural products structures and metadata.
* [BIAdb](https://webs.iiitd.edu.in/raghava/biadb/type.php?tp=natural) - A database for benzylisoquinoline alkaloids.
* [IMPPAT](https://cb.imsc.res.in/imppat/home) - Phytochemicals from Indian medicinal plants.
* [NP-MRD](https://np-mrd.org/natural_products) - 280k+ NMR-based NP studies.
* [IBS Natural Compounds](https://www.ibscreen.com/natural-compounds) - 60k+ compounds.
* [PhytoHub](https://phytohub.eu/) - Dietary phytochemicals and metabolites.
* [Dr. Duke's Phytochemical DB](https://phytochem.nal.usda.gov/) - Plant compounds and uses.
* [CyanoMetDB](https://zenodo.org/records/13854577) - Over 3,000 cyanobacterial metabolites.
* [Seaweed Metabolite DB](https://www.swmd.co.in/) - Marine algae compounds.
* [FooDB](https://foodb.ca/) - A comprehensive resource on food constituents.

### Bioactivity Databases

* [ChEMBL](https://www.ebi.ac.uk/chembl/) - Bioactivity and ADMET data.
* [SureChEMBL](https://www.surechembl.org/) - Patent chemistry search.
* [BindingDB](https://www.bindingdb.org/) - Binding affinities for biomolecules.
* [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - Structures, properties, and bioassays.
* [PDBbind](http://www.pdbbind.org.cn/index.php) - Protein-ligand affinity data.
* [BRENDA](https://www.brenda-enzymes.org/) - Enzyme properties and functions.
* [ExCAPE-DB](https://solr.ideaconsult.net/search/excape/) - A large-scale chemogenomics database.
* [Therapeutics Data Commons](https://tdcommons.ai/) - AI/ML-ready datasets and learning tasks for therapeutics.
* [Therapeutic Target Database (TTD)](https://idrblab.net/ttd/) - Drug targets with linked diseases and compounds.
* [Aircheck Datasets](https://aircheck.ai/datasets) - Curated DEL datasets for AI‑driven drug discovery, enabling benchmarking and model development.
* [canSAR](https://cansar.ai/) - Integrative cancer knowledgebase aggregating molecular, genetic, and structural data for drug target identification.
* [CDD Vault](https://www.collaborativedrug.com/public-access-cdd-vault) - Hosted informatics platform providing public access to aggregated drug discovery data.
* [ClinicalTrials.gov](https://clinicaltrials.gov/) - Comprehensive registry and results database for clinical studies involving human participants.
* [CovalentInDB (CIDB)](https://cadd.zju.edu.cn/cidb/) - A comprehensive database dedicated to covalent inhibitors, targets, and experimental data.
* [HSADab](https://github.com/proszxppp/HSADab) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-03-27 - Database of binding thermodynamics, structures, and docking data for human serum albumin.

## Target and Protein Data

### Protein Structures

* [RCSB PDB](https://www.rcsb.org/) - Repository for macromolecular structures.
* [PDBe](https://www.ebi.ac.uk/pdbe/) - European counterpart to RCSB PDB.
* [OPM](https://opm.phar.umich.edu/) - Orientation of proteins in membranes.
* [UniProt](https://www.uniprot.org/) - Protein sequences, structures, and functions.
* [InterPro](https://www.ebi.ac.uk/interpro/) - Protein classification and domain prediction.
* [AlphaFold DB](https://alphafold.ebi.ac.uk/) - Predicted structures from AlphaFold.
* [Proteopedia](https://proteopedia.org/wiki/index.php/Main_Page) - Interactive protein visualizations.
* [Pfam](https://www.ebi.ac.uk/interpro/entry/pfam/) - Collection of protein families represented by multiple sequence alignments and hidden Markov models.
* [Human Protein Atlas](https://www.proteinatlas.org/) - Spatial mapping of all human proteins across tissues and cells.

### Binding Site and Pocket Detection

* [Pocket Binding Site Prediction](https://github.com/MariaPau03/Pocket_Binding_Site_Prediction) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2026-04-05 - ML-based tool for predicting binding pockets and active sites on protein structures.
* [PrankWeb](https://prankweb.cz/) - Pocket prediction and analysis.
* [CASTp](http://sts.bioe.uic.edu/castp/index.html?2r7g) - Pocket geometry and volume analysis.
* [CavityPlus](http://www.pkumdl.cn:8000/cavityplus/index.php#/) - Pocket detection and druggability.
* [CaverWeb](https://loschmidt.chemi.muni.cz/caverweb/) - Tunnel and channel detection.
* [PASSer](https://passer.smu.edu/) - Allosteric site prediction.
* [Protplex](https://protplex.com/) - Semantic search engine for the PDB enabling multidimensional queries on structures and binding pockets.

### Protein Engineering and Modeling

* [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion) ⭐ 3,025 | 🐛 244 | 🌐 Python | 📅 2026-07-15 - Open-source method for de novo protein design using structure-guided diffusion models.
* [PDBFixer](https://github.com/openmm/pdbfixer) ⭐ 671 | 🐛 60 | 🌐 Python | 📅 2026-03-10 - Repairs PDB files by adding missing atoms, residues, and hydrogens for MD simulations.
* [Melodia](https://github.com/rwmontalvao/Melodia_py) ⭐ 86 | 🐛 1 | 🌐 Python | 📅 2026-04-29 - Python library for analyzing and comparing protein structure shapes via differential geometry.
* [DynaMut](https://biosig.lab.uq.edu.au/dynamut/) - Predicts mutation-induced stability changes.
* [SWISS-MODEL](https://swissmodel.expasy.org/) - A fully automated protein structure homology-modeling server.
* [MODELLER](https://salilab.org/modeller/) - A software for homology or comparative modeling of protein structures.
* [OpenFold Portal](https://portal.openfold.omsf.io/) - Cloud portal for predicting 3D protein structures using the open-source OpenFold model.

## Network Pharmacology

* [GeneCards](https://www.genecards.org/) - Human gene database with genomic, proteomic, and clinical data.
* [SwissTargetPrediction](http://www.swisstargetprediction.ch/) - Predicts targets of small molecules via similarity-based screening.
* [STITCH](https://stitch.embl.de/) - Integrates chemical–protein interactions across organisms.
* [STRING](https://string-db.org/) - A database of known and predicted protein–protein interactions.
* [Cytoscape](https://cytoscape.org/) - Visualizes and analyzes molecular interaction networks.
* [Open Targets](https://platform.opentargets.org/) - Integrative platform for therapeutic target identification.
* [OmicsNet](https://www.omicsnet.ca/) - Builds multi-omics networks for systems biology.
* [DisGeNET](https://disgenet.com/) - Curated gene–disease associations for network analysis.
* [PharmMapper](https://www.lilab-ecust.cn/pharmmapper/) - Identifies potential targets via reverse pharmacophore mapping.
* [ChEA3](https://maayanlab.cloud/chea3/) - Transcription factor enrichment tool integrating ChIP-seq, co-expression, and perturbation datasets.
* [miRDB](https://mirdb.org/) - Predicts functional microRNA targets using machine learning and high-throughput data.
* [Venny 2.1](https://bioinfogp.cnb.csic.es/tools/venny/) - A web tool for comparing lists using Venn diagrams.
* [OMIM](https://www.omim.org/) - Authoritative compendium of human genes and their relationship to genetic variation and phenotypic expression.
* [PharmGKB](https://pgx-db.org/target_lookup/) - Pharmacogenomics resource exploring genetic variation impacts on drug response and molecular targets.
* [Polypharmacology Browser PPB3](https://ppb3.gdb.tools/) - Deep learning tool predicting off-target effects and polypharmacology for bioactive molecules.
* [Drug-Target Interaction Explorer](https://github.com/yashhhhhhhhh504/Drug-Target-Interaction-Explorer) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-10 - Dashboard for exploring and visualizing drug-target interaction networks.

## Ligand Design and Optimization

### Pharmacophore Modeling

* [Pharmit](https://pharmit.csb.pitt.edu/) - Interactive pharmacophore modeling.

### QSAR and Descriptor Tools

* [QSPRpred](https://github.com/CDDLeiden/QSPRpred) ⭐ 94 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-06-26 - Open-source Python toolkit for building, reproducing, and deploying QSAR/QSPR models.
* [pyADA](https://github.com/jeffrichardchemistry/pyADA) ⭐ 28 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-02-08 - Assesses the applicability domain of molecular fingerprints via similarity-based thresholds for QSAR validation.
* [QSAR Toolbox](https://qsartoolbox.org/) - Hazard assessment and QSAR.
* [OCHEM](https://ochem.eu/home/show.do) - QSAR model building and prediction.
* [ChemMaster](https://crescent-silico.com/chemmaster/) - QSAR and cheminformatics suite.
* [3D-QSAR](https://www.3d-qsar.com/) - Web resources for 3D QSAR modeling.
* [QSAR-Co](https://sites.google.com/view/qsar-co/) - Robust multitarget QSAR modeling.
* [DataWarrior](https://openmolecules.org/datawarrior/) - Free software for chemical analysis, QSAR, and visualization.
* [KNIME](https://www.knime.com/) - Workflow platform for cheminformatics and ML integration.

### Descriptor and Featurization Tools

* [Mordred](https://github.com/mordred-descriptor/mordred) ⭐ 479 | 🐛 55 | 🌐 Python | 📅 2024-02-07 - Python library with 1800+ molecular descriptors.
* [ChemDescriptor](https://github.com/darkreactions/chemdescriptor) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2021-11-19 - Open-source tool for generating chemical descriptors and fingerprints, supporting cheminformatics workflows.
* [RDKit](https://www.rdkit.org/) - Open-source cheminformatics toolkit with descriptor, fingerprint, and molecular manipulation support.
* [PaDEL-Descriptor](http://www.yapcwsoft.com/dd/padeldescriptor/) - Java tool for calculating molecular descriptors and fingerprints.
* [CDK](https://cdk.github.io/) - Java cheminformatics library with descriptor calculators.
* [alvaDesc](https://www.alvascience.com/alvadesc/) - Commercial software for molecular descriptors and fingerprints.
* [MolFeat](https://molfeat.datamol.io/) - Python package for molecular featurization and embeddings.
* [Dragon](https://www.talete.mi.it/products/dragon_description.htm) - Commercial molecular descriptor calculator (widely cited).

### Molecular Property Prediction

* [SwissADME](http://www.swissadme.ch/) - Drug-likeness and PK.
* [pkCSM](https://biosig.lab.uq.edu.au/pkcsm/) - ADMET property prediction.
* [DeepPK](https://biosig.lab.uq.edu.au/deeppk/) - DL-based pharmacokinetics.
* [admetSAR 2.0](https://lmmd.ecust.edu.cn/admetsar2/) - Comprehensive ADMET.
* [ADMETlab 2.0](https://admetmesh.scbdd.com/) - PK, toxicity and drug-likeness.
* [ProTox-II](https://tox-new.charite.de/protox_II/) - Toxicity predictions.
* [PreADMET](https://preadmet.webservice.bmdrc.org/) - PK property predictions.
* [FAF-Drugs](https://bioserv.rpbs.univ-paris-diderot.fr/services.html) - ADMET filtering.
* [Admetboost](https://ai-druglab.smu.edu/admet) - ML-based ADMET prediction.
* [MetaPredict](http://metapredict.icoa.fr/) - Predict molecular properties from structure.
* [ADMET-AI](https://admet.ai.greenstonebio.com/) - A web-based tool for predicting ADMET properties based on Chemprop-RDKit models trained on datasets from the TDC.

### Fragment-Based Drug Design

* [FragmentFinder](https://github.com/1JELC1/FragmentFinder) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - Computational tool for identifying and matching structural fragments in drug discovery workflows.
* [FragBuilder](https://github.com/andersx/fragbuilder) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2014-10-31 - Python API for building peptide-like and small molecule fragments.
* [SwissSidechain](https://www.swisssidechain.ch/) - Fragment and linker library for small molecule design.
* [BoBER](http://bober.insilab.org/) - Bioisosteric replacements for lead optimization.
* [SeeSAR](https://www.biosolveit.de/SeeSAR/) - Fragment growing and linking software (free academic version).
* [Enamine Fragment Libraries](https://enamine.net/compound-libraries/fragment-libraries) - Large curated collection of diverse fragments for FBDD.

## Virtual Screening and Docking

* [DiffDock](https://github.com/gcorso/DiffDock) ⭐ 1,569 | 🐛 132 | 🌐 Python | 📅 2025-05-02 - Deep learning-based docking tool that predicts ligand poses directly from protein structures using diffusion models.
* [Gnina](https://github.com/gnina/gnina) ⭐ 964 | 🐛 24 | 🌐 C++ | 📅 2026-06-29 - CNN-scoring docking.
* [AutoDock-GPU](https://github.com/ccsb-scripps/AutoDock-GPU) ⭐ 608 | 🐛 87 | 🌐 C++ | 📅 2026-08-11 - GPU-accelerated version of AutoDock for faster ligand-receptor docking.
* [Meeko](https://github.com/forlilab/Meeko) ⭐ 386 | 🐛 48 | 🌐 Python | 📅 2026-08-25 - Prepares ligands/receptors for AutoDock by assigning partial charges and atom types.
* [Smina](https://github.com/mwojcikowski/smina) ⭐ 148 | 🐛 0 | 🌐 C++ | 📅 2018-11-18 - Vina fork with extra features.
* [PandaDock](https://github.com/pritampanda15/PandaDock) ⭐ 100 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - Python docking tool.
* [EasyDock](https://github.com/ci-lab-cz/easydock) ⭐ 83 | 🐛 13 | 🌐 Python | 📅 2026-08-21 - Vina/Smina pipeline.
* [MolScrub](https://github.com/forlilab/molscrub) ⭐ 58 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Enumerates tautomers, pH states, and conformers for docking and structure-based modeling.
* [MzDOCK](https://github.com/Muzatheking12/MzDOCK) ⭐ 28 | 🐛 11 | 🌐 Python | 📅 2026-08-25 - GUI docking pipeline.
* [Chopdock](https://github.com/JanoschMenke/chopdock) ⭐ 18 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-05-01 - Molecular docking and cheminformatics tool for structural interaction analysis and fragment-based design.
* [EasyDockVina2](https://github.com/S3cr3t-SDN/EasyDockVina2) ⭐ 0 | 🐛 0 | 📅 2020-03-28 - Vina automation.
* [OpenBabel](https://openbabel.org/index.html) - Format conversion and ligand prep.
* [MGLTools](https://ccsb.scripps.edu/mgltools/) - Structure preparation.
* [AutoDockTools](https://autodocksuite.scripps.edu/adt/) - AutoDock GUI.
* [AutoDock Vina](https://vina.scripps.edu/) - Popular docking software.
* [Webina](https://durrantlab.pitt.edu/webina/) - Web-based Vina.
* [HADDOCK](https://wenmr.science.uu.nl/haddock2.4/) - Flexible docking suite.
* [ZDOCK](https://zdock.wenglab.org/) - Protein-protein docking.
* [ClusPro](https://cluspro.org/) - Protein-protein docking server.
* [pyDockWEB](https://life.bsc.es/pid/pydockweb/) - Electrostatics-based docking.
* [SwissDock](https://www.swissdock.ch/) - Web docking for beginners.
* [Uni-Mol Docking V2](https://www.bohrium.com/apps/unimoldockingv2/job?type=app) - AI-assisted docking.
* [Vina on Colab](https://autodock-vina.readthedocs.io/en/latest/colab_examples.html) - Run Vina in Google Colab.
* [MetalDock](https://metaldock.readthedocs.io/en/latest/) - A Python-based tool designed for the docking of metal-organic compounds to proteins, DNA, or other biomolecules.
* [Boltzmann Maps](https://boltzmannmaps.com/) - Web application for structure-guided drug design using pre-computed water and chemical fragment maps.

## Interaction Analysis and Visualization

* [xyzrender](https://github.com/aligfellow/xyzrender) ⭐ 590 | 🐛 12 | 🌐 Python | 📅 2026-08-13 - CLI for producing publication-quality molecular graphics, GIFs, and SVGs from coordinate files.
* [pymol-sifts](https://github.com/connyyu/pymol_sifts/) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-05-18 - PyMOL plugin for integrating and visually mapping SIFTS structural and sequence data.
* [posecheck-fast](https://github.com/LigandPro/posecheck-fast) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-02-19 - High-throughput docking pose validation with symmetry-corrected RMSD and lightweight distance and clash filters.
* [PLIP](https://plip-tool.biotec.tu-dresden.de/plip-web/plip/index) - Protein-ligand interaction profiling.
* [GetContacts](https://getcontacts.github.io/index.html) - Compute and visualize noncovalent interactions from structures and MD trajectories.
* [LigPlot+](https://www.ebi.ac.uk/thornton-srv/software/LigPlus/) - 2D interaction diagrams.
* [Discovery Studio Visualizer](https://discover.3ds.com/discovery-studio-visualizer-download) - Advanced visualization.
* [PyMOL](https://www.pymol.org/) - Python-based molecular visualization software.
* [UCSF ChimeraX](https://www.rbvi.ucsf.edu/chimerax/) - A molecular visualization program with emphasis on structural biology.
* [Avogadro](https://avogadro.cc/) - Cross-platform molecular editor and visualizer featuring an extensible plugin system.

## Molecular Dynamics and Simulation

### Engines

* [GROMACS](https://www.gromacs.org/) - Fast, scalable MD engine optimized for biomolecular simulations and energy minimization.
* [OpenMM](https://openmm.org/) - Flexible MD toolkit with GPU acceleration and Python bindings.
* [LAMMPS](https://www.lammps.org/) - Classical MD simulator for materials science and soft matter.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - Highly parallel MD engine tailored for large biomolecular systems.
* [AMBER](https://ambermd.org/) - Suite for biomolecular simulations and free energy calculations.
* [Desmond](https://www.deshawresearch.com/resources.html) - GPU-accelerated MD engine for high-performance simulations.

### Topology and Force Field Tools

* [CGenFF](https://cgenff.silcsbio.com/) - CHARMM force field parametrization of drug-like molecules.
* [SwissParam](https://www.swissparam.ch/) - Rapid generation of CHARMM-compatible parameters for small organic molecules.
* [ATB](https://atb.uq.edu.au/) - Automated topology builder and repository for classical force field parameters.
* [CHARMM-GUI](https://www.charmm-gui.org/) - Web-based interface for building complex biomolecular systems and generating MD input files.
* [LigParGen](https://traken.chem.yale.edu/ligpargen/) - Automated OPLS-AA parameter generator for organic ligands.

### Analysis Tools

* [cmd-viewer](https://github.com/Kopec-Lab/cmd-viewer) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-07-08 - Tool for visualizing and analyzing MD simulation trajectories and structural data.
* [Pharmacon](https://github.com/k-georgiou/pharmacon) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - Open-source toolkit for molecular dynamics simulation analysis in medicinal chemistry.
* [MD DaVis](https://md-davis.readthedocs.io/en/latest/index.html) - Interactive visualization and analysis of MD trajectories.
* [iMODS](https://imods.chaconlab.org/) - Normal Mode Analysis toolkit using internal coordinates.
* [MolAiCal](https://molaical.github.io/) - Web-based platform for binding free energy calculations using MM/PBSA and MM/GBSA methods.
* [gmx\_MMPBSA](https://valdes-tresanco-ms.github.io/gmx_MMPBSA/dev/) - Port of AMBER MMPBSA.py for GROMACS.
* [VMD](https://www.ks.uiuc.edu/Research/vmd/) - Large biomolecular systems visualization and analysis using 3D graphics and scripting.
* [Grace](https://plasma-gate.weizmann.ac.il/Grace/) - 2D plotting tool for Unix-like systems with advanced graphing, fitting, and analysis features.
* [CPPTRAJ](https://amberhub.chpc.utah.edu/cpptraj/) - Fast, parallelizable trajectory analysis from AMBER.
* [MDAnalysis](https://www.mdanalysis.org/) - Open-source Python library for analyzing MD simulations.
* [CABS-flex 3.0](https://lcbio.pl/cabsflex3/) - Web server for rapid simulation of protein and peptide structural flexibility using coarse-grained models.

## Synthesis and Retrosynthesis Planning

* [Spaya](https://spaya.ai/app/search) - AI-driven retrosynthesis engine with route ranking and synthetic feasibility scoring.
* [AiZynthFinder](https://github.com/MolecularAI/aizynthfinder) ⭐ 882 | 🐛 9 | 🌐 Python | 📅 2026-04-13 - Monte Carlo tree search-based retrosynthesis using trained neural networks.
* [ASKCOS](https://askcos.mit.edu/) - Synthesis route prediction with ML, developed by MIT.
* [IBM RoboRXN](https://rxn.res.ibm.com/rxn/robo-rxn/welcome) - Automated reaction prediction using transformer models.
* [MANIFOLD](https://postera.ai/) - Search engine for synthetically accessible molecules and building blocks.
* [onepot.ai](https://www.onepot.ai/) - AI-enabled molecular editor and synthesis planning platform with an encrypted structure environment.

## Specialized Modalities

### PROTACs and Ternary Complexes

* [PROTAC-db](http://cadd.zju.edu.cn/protacdb/) - Curated database of PROTAC molecules, targets, and linkers for degrader design.
* [PROsettaC](https://prosettac.weizmann.ac.il/) - Structure-based modeling of ternary complexes for targeted protein degradation.

### Peptide Design

* [PepDraw](https://pepdraw.com/) - Peptide visualization with annotated physicochemical properties.
* [PEP-SiteFinder](https://bioserv.rpbs.univ-paris-diderot.fr/services/PEP-SiteFinder/) - Predicts peptide-binding sites on protein structures using drug-like ligand mapping.
* [PEP-FOLD3](https://bioserv.rpbs.univ-paris-diderot.fr/services/PEP-FOLD3/) - De novo peptide structure prediction framework.

## Machine Learning and AI

### Chemistry-focused ML Frameworks

* [DeepChem](https://github.com/deepchem/deepchem) ⭐ 6,960 | 🐛 1,165 | 🌐 Python | 📅 2026-08-20 - Open-source deep learning framework for chemistry and biology.
* [Chemprop](https://github.com/chemprop/chemprop) ⭐ 2,438 | 🐛 13 | 🌐 Python | 📅 2026-08-21 - Directed message passing neural networks for molecular property prediction.
* [DGL-LifeSci](https://github.com/awslabs/dgl-lifesci) ⭐ 809 | 🐛 32 | 🌐 Python | 📅 2023-11-01 - Graph deep learning toolkit for life sciences using the Deep Graph Library.
* [scikit-mol](https://github.com/EBjerrum/scikit-mol) ⭐ 204 | 🐛 7 | 🌐 Python | 📅 2025-11-02 - Open-source toolkit bridging RDKit and scikit-learn for molecular ML workflows.
* [ChemML](https://github.com/hachmannlab/chemml) ⭐ 180 | 🐛 3 | 🌐 Python | 📅 2026-08-19 - Machine learning and informatics suite for analyzing, mining, and modeling chemical and materials data.
* [LigandForge](https://github.com/HTS-Oracle/LigandForge) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2026-05-08 - ML-based structure-guided de novo ligand generation and optimization for hit identification.
* [iChem](https://github.com/mqcomplab/iChem) ⭐ 22 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-06-20 - Python cheminformatics package for molecular comparisons, fingerprints, and chemical data analysis.
* [Oloren ChemEngine](https://pypi.org/project/olorenchemengine/) - Unified API for molecular property prediction with uncertainty quantification, interpretability, and model tuning.
* [TorchDrug](https://torchdrug.ai/) - A machine learning library for drug discovery with support for GNNs and molecular datasets.

### Pretrained Models

* [Boltz-2](https://github.com/jwohlwend/boltz) ⭐ 4,176 | 🐛 152 | 🌐 Python | 📅 2026-05-29 - A foundation model that jointly predicts structure and binding affinity, rivaling physics-based FEP methods in accuracy.
* [ESM3](https://github.com/evolutionaryscale/esm) ⭐ 2,925 | 🐛 73 | 🌐 Jupyter Notebook | 📅 2026-08-25 - Generative biology foundation model for designing novel proteins across sequence, structure, and function.
* [Chai-1](https://github.com/chaidiscovery/chai-lab) ⭐ 1,986 | 🐛 93 | 🌐 Python | 📅 2026-06-30 - Multi-modal foundation model for biomolecular structure prediction of proteins, nucleic acids, and ligands.
* [Uni-Mol](https://github.com/dptech-corp/Uni-Mol) ⭐ 1,155 | 🐛 112 | 🌐 Python | 📅 2025-05-29 - 3D molecular representation learning framework.
* [MolBERT](https://github.com/BenevolentAI/MolBERT) ⭐ 150 | 🐛 9 | 🌐 Python | 📅 2021-06-06 - Transformer-based molecular representation learning.
* [Zatom](https://github.com/Zatom-AI/zatom) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2026-07-25 - AI-driven generative chemistry platform for discovering and analyzing molecular structures.
* [ChemBERTa](https://huggingface.co/seyonec/ChemBERTa-zinc-base-v1) - Pretrained BERT-like models for molecules from SMILES.
* [ESMc](https://biohub.ai/models/esmc) - A family of open protein language foundation models for sequence generation and design.

### Molecule Standardization

* [MolVS](https://github.com/mcs07/MolVS) ⭐ 188 | 🐛 23 | 🌐 Python | 📅 2020-04-16 - Molecule validation and standardization library based on RDKit.
* [cleanmol](https://github.com/nurtilekgalimov/cleanmol) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-04-15 - Python library for cleaning, standardizing, and preparing molecular structures for cheminformatics workflows.

## Utility and Workflow Tools

* [chembl\_webresource\_client](https://github.com/chembl/chembl_webresource_client) ⭐ 449 | 🐛 29 | 🌐 Python | 📅 2026-03-24 - Official Python client library for programmatic access to the ChEMBL database API.
* [PyChem-Pro](https://github.com/vijaymasand/PyChem-Pro) ⭐ 348 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - Pure-Python desktop application for molecular visualization, geometry optimization, and cheminformatics.
* [spyrmsd](https://github.com/RMeli/spyrmsd) ⭐ 119 | 🐛 6 | 🌐 Python | 📅 2026-08-03 - Python tool for symmetry-corrected RMSD calculations using graph isomorphism.
* [biopipelines](https://github.com/locbp-uzh/biopipelines) ⭐ 104 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-28 - Modular Python framework for automated computational protein and ligand engineering workflows on SLURM clusters.
* [NAMI](https://github.com/mqcomplab/NAMI) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2026-08-11 - Computational tool for clustering and evaluating differences across molecular datasets.
* [ComProScanner](https://github.com/slimeslab/ComProScanner) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2026-08-11 - Pipeline for automated large-scale profiling and screening of chemical compounds against protein targets.
* [HEDGEHOG](https://github.com/LigandPro/hedgehog) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2026-06-22 - Stage-based evaluation pipeline for generative molecular design with filters, retrosynthesis checks, docking, pose validation, and reports.
* [AssayCurveFit (GitHub)](https://github.com/yapici/assaycurvefit) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-09 - Source repository for IC50/EC50 calculation from biochemical assays.
* [rdkit-agent](https://github.com/scottmreed/rdkit-agent) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-19 - Agent-first cheminformatics CLI powered by RDKit WASM for structure validation and format conversion.
* [ProteinsPlus](https://proteins.plus/) - A web-based platform designed to assist life scientists in analyzing and working with protein structures.
* [OPSIN](https://opsin.ch.cam.ac.uk) - Convert IUPAC names to chemical structures.
* [OSRA](https://cactus.nci.nih.gov/cgi-bin/osra/index.cgi) - Extract chemical structures from images.
* [ChemPlot](https://chemplot.streamlit.app/) - Chemical space visualization.
* [ChemDB](https://chemdb.igb.uci.edu/) - Chemoinformatics portal with compound data and tools.
* [Screening Explorer](http://stats.drugdesign.fr/) - Analyze screening datasets and hit distributions.
* [NERDD](https://nerdd.univie.ac.at/) - Curated drug discovery resources.
* [LigBuilder3](http://www.pkumdl.cn:8080/ligbuilder3/) - De novo ligand design.
* [ChemMine Tools](https://chemminetools.ucr.edu/) - Web-based cheminformatics toolkit for compound analysis.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - Perl/Python scripts for cheminformatics.
* [Click2Drug](https://www.click2drug.org/) - CADD software and databases directory.
* [Galaxy Europe](https://usegalaxy-eu.github.io/index-cheminformatics.html) - Galaxy instance for cheminformatics.
* [CADD Vault](https://drugbud-suite.github.io/CADD_Vault/) - CADD resources repository.
* [BioMoDes](https://abeebyekeen.com/biomodes-biomolecular-structure-prediction/) - Biomolecular structure prediction and modeling tools.
* [PlayMolecule](https://open.playmolecule.org/landing) - Interactive molecular modeling and simulation platform.
* [Ertl Molecular](https://ertlmolecular.com/) - Cheminformatics tools for medicinal chemists, including scaffold analysis, ring replacement, and property calculators.
* [Datagrok](https://datagrok.ai/) - Environment for working with chemical data, covering full-range of tasks from data access to de novo design.
* [AssayCurveFit](https://assaycurvefit.com/) - Web application for processing dose-response data and generating IC50/EC50 curve fits.
* [CHEESE](https://cheese.deepmedchem.com/) - AI-driven interactive tool for analyzing chemical spaces and optimizing hit compounds.
* [ChemIllusion MCP](https://chemillusion.com/mcp-server) - Model Context Protocol server providing language models with tools for generating and analyzing molecular data.
* [Neurosnap](https://neurosnap.ai/) - Web platform providing no-code interfaces to bioinformatics and ML tools including AlphaFold.

## Learning Resources

### Free Courses

* [AI for Chemistry Course](https://github.com/schwallergroup/ai4chem_course) ⭐ 290 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-04-03 - Lecture slides, Jupyter notebooks, and exercises for machine learning in chemistry.
* [TMP Chem Lectures](https://youtube.com/playlist?list=PLm8ZSArAXicIWTHEWgHG5mDr8YbrdcN1K) - Recorded lectures from a leading cheminformatics summer school.
* [Strasbourg Summer School in Chemoinformatics](https://youtube.com/playlist?list=PLhgURFExPmJsDuHevu5n8y0R41WsXfbnC) - Summer school lectures.
* [BIGCHEM](https://bigchem.eu/node/63) - Online course on big data applications in chemistry.
* [Drug Discovery Course](https://www.stereoelectronics.org/webDD/DD_home.html) - Foundations of drug discovery and development.
* [drugdesign.org](https://www.drugdesign.org/) - Free courses on drug design and cheminformatics.
* [Learn CADD](https://learn-cadd.vercel.app/) - An interactive, visual, first-principles guide to computer-aided drug design.
* [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics) - Intercollegiate course on cheminformatics theory and coding.
* [Python For Cheminformatics Docking](https://pdb101.rcsb.org/train/training-events/python4) - Python tutorials for molecular docking via RCSB.
* [DDA CDD Workshop](https://wcair.dundee.ac.uk/training/training-resources/computational-drug-design/) - Workshop on generative and computational drug design.
* [MDTutorials](http://www.mdtutorials.com/gmx/) - Step-by-step tutorials for MD simulations using GROMACS.
* [Resources for Learning Bioinformatics](https://learnbioinformatics.org/) - Curated collection of tutorials and materials for bioinformatics and computational biology.
* [Synthesis Workshop](https://synthesis-workshop.com/) - Open-access video podcast on advanced organic synthesis and medicinal chemistry.
* [AI for Chemistry (ai4chem Book)](https://zzhenglab.github.io/ai4chem/intro.html) - An open-access book and interactive guide to machine learning and AI in chemistry.
* [CCAS Training Materials](https://ccas.nd.edu/research/training-materials/) - Training resources for computer-assisted synthesis tools, reaction modeling, and machine learning.
* [ML in Chemistry (CHEM 542)](https://sites.rutgers.edu/sun-lab/teach-chem542/) - Rutgers University course materials covering machine learning applications in chemical sciences.

### Blogs

* [Awesome Learning Digital Chemistry](https://github.com/mlederbauer/awesome-learning-digital-chemistry) ⭐ 50 | 🐛 5 | 📅 2026-01-25 - Curated compilation of resources for learning digital chemistry, including courses, tutorials, and books.
* [Practical Fragments](http://practicalfragments.blogspot.com/) - Insights into fragment-based drug discovery.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Tools and tips for cheminformatics workflows.
* [Neovarsity](https://neovarsity.org/blogs?categories=CHEMINFORMATICS) - Deep-tech blog on cheminformatics and drug discovery applications.
* [Cheminformania](https://www.cheminformania.com/) - Cheminformatics meets deep learning and molecular modeling.
* [Daily Dose of Data Science](https://www.blog.dailydoseofds.com/) - Digestible data science tutorials and concepts.
* [Machine Learning Mastery](https://machinelearningmastery.com/) - Practical ML guides for developers and scientists.
* [Chem-Workflows](https://chem-workflows.com/index.html) - Jupyter-based chemistry workflows and tutorials.
* [Structural Bioinformatics](https://proteinstructures.com/) - Guide to structure-based drug design and protein modeling.
* [McConnellsMedChem](https://mcconnellsmedchem.com/) - Medicinal chemistry insights and commentary.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) - AI-powered approaches to drug discovery.
* [MacinChem](https://macinchem.org/) - Computational chemistry tools for macOS users.
* [Jeremy Monat](https://bertiewooster.github.io/) - Cheminformatics research and academic resources.
* [RDKit blog](https://greglandrum.github.io/rdkit-blog/) - A rich collection of tutorials, technical tips, and experimental insights from Greg Landrum.
* [DeepMedChem](https://www.deepmedchem.com/) - AI-powered insights, tool reviews, and workflows for modern drug discovery.
* [The Data Chemist's Handbook](https://data-chemist-handbook.github.io/) - A curated handbook with guidelines, code snippets, and tools for data-driven chemistry.
* [CCAS Data sets, Tools, and Workflows](https://ccas.nd.edu/research/data-sets-tools-and-workflows/) - A repository of datasets and computational workflows for computer-assisted organic synthesis.

### Instructional Notebooks

* [DeepChem Tutorials](https://github.com/deepchem/deepchem/tree/master/examples/tutorials) ⭐ 6,960 | 🐛 1,165 | 🌐 Python | 📅 2026-08-20 - Comprehensive set of tutorials covering deep learning for chemistry, biology, and materials science.
* [Practical Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials) ⭐ 1,300 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-22 - Hands-on Jupyter tutorials for RDKit, SAR, clustering, generative models, and ML pipelines.
* [intro\_pharma\_ai](https://github.com/kochgroup/intro_pharma_ai) ⭐ 167 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-09-09 - Notebook-based introduction to AI applications in pharma.
* [how-to-train-your-chemeleon](https://github.com/JacksonBurns/how-to-train-your-chemeleon) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2026-07-06 - Tutorial and framework for training chemical machine learning models.
* [rdkit-tips-and-tricks](https://github.com/mohamedzaghloul-lab638/rdkit-tips-and-tricks-/tree/main) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-04-05 - Practical snippets and examples for the RDKit cheminformatics toolkit.
* [TeachOpenCADD](https://projects.volkamerlab.org/teachopencadd/all_talktorials.html) - Modular Jupyter tutorials for CADD workflows and concepts.
* [AI/DL for Life Sciences](https://onlinelibrary.wiley.com/doi/10.1002/ardp.202200628) - Interactive notebooks showcasing AI/DL use cases in life sciences.
* [Fingerprint Generator Tutorial](https://greglandrum.github.io/rdkit-blog/posts/2023-01-18-fingerprint-generator-tutorial.html) - RDKit blog tutorial on generating and manipulating molecular fingerprints.

## Labs and Research Groups

* [Carlsson Lab](https://www.carlssonlab.org/) - GPCR modeling, receptor-ligand interactions, MD, docking, and AI for drug discovery. (Uppsala University, Sweden)
* [InSiliChem](https://insilichem.com/) - Computational chemobiology and metalloenzyme design. (Universitat Autònoma de Barcelona, Spain)
* [LCBC](https://sites.google.com/view/lcbc) - Molecular dynamics, free energy calculations, retrosynthesis using machine learning. (Seoul National University, Korea)
* [Angelo Raymond Rossi](https://angeloraymondrossi.github.io/) - High-performance computing for computational chemistry and cheminformatics. (University of Connecticut, USA)
* [Laboratory of Chemoinformatics](https://complex-matter.unistra.fr/en/research-teams/laboratory-of-chemoinformatics/team/) - QSAR/QSPR, chemical similarity, and virtual screening. (Université de Strasbourg / CNRS, France)
* [Erastova Lab](https://www.erastova.xyz/) - Molecular modeling of soft matter and biomolecular simulations. (University of Edinburgh, UK)
* [The Ballester Group](https://ballestergroup.github.io/) - Developing ML/AI methods for structure-based scoring and virtual screening. (Imperial College London, UK)
* [Meiler Lab](https://meilerlab.org/) - Rosetta software, protein design, and ML-based protein engineering. (Vanderbilt / Leipzig University, USA / Germany)
* [COMP3D](https://comp3d.univie.ac.at/) - Develops and applies AI methods to design safe, effective pharmaceuticals and agrochemicals. (University of Vienna, Austria)
* [Dral Group](http://dr-dral.com/) - AI-enhanced computational chemistry, quantum chemical methods, and development of MLatom. (Xiamen University, China)
* [Bonvin Lab](https://www.bonvinlab.org/) - Computational structural biology, HADDOCK, and integrative modeling. (Utrecht University, Netherlands)
* [Volkamer Lab](https://volkamerlab.org/) - Binding site analysis and AI-powered virtual screening. (Saarland University, Germany)
* [AI Laboratory for Molecular Engineering](https://ailab.bio/) - PROTACs, molecular glues, and ML for chemistry and life sciences. (Chalmers University, Sweden)
* [Loschmidt Labs - PEG](https://loschmidt.chemi.muni.cz/peg/) - Protein and enzyme engineering, AI-assisted enzyme design. (Masaryk University, Czechia)
* [QSAR4U](https://qsar4u.com/index.php) - Cheminformatics tools, QSAR modeling, CReM, and EasyDock. (Palacky University, Czechia)
* [LBMD](https://www.chem.kuleuven.be/lbmd/index.html) - Computational strategies to understand and engineer biomolecular systems. (KU Leuven, Belgium)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._

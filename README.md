# coevo_dimer
CBMFW4761 at Columbia University, SP22
Group project title: investigating the Implications of coevolution in heterodimeric protein complexes

- [Dylan Marshall](dmm2269@cumc.columbia.edu), Columbia Systems Biology PhD student
- [Julia Urban](jau2112@cumc.columbia.edu), Columbia Systems Biology PhD student
- [Peiwen Cai](pc2976@cumc.columbia.edu), Columbia Systems Biology PhD student

4 heterodimers from [Ovchinnikov et al 2014, eLife](https://elifesciences.org/articles/2030) are included. Under each `__dimer_name__` folder, the followings are included:
  - `AF2.ipynb`: modified based on [ColabFold] (https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/beta/AlphaFold2_advanced.ipynb) for structural prediction of the heterodimer
  - `msa.pickle`: paired MSA from AF2 above
  - `rank_1_model_1_ptm_seed_0_relaxed.pdb`: PDB file
  - `MRF_analysis.ipynb`: MRF model 
  - `*_coevo.pickle`: coevolutionary coefficient matrcies from MRF_analysis.ipynb
  
  `results_merged.ipynb` provides code for data analysis (e.g. MSA bootstrapping) and visualizations.
  all jupyter notebooks are run on Google-Colab GPU; all package dependency requirements are addressed in corresponding notebooks.

# ML for Drug Discovery | Dr Jean-Paul Ebejer

These slides and practicals will cover Day 4 (Thu Sep 14th 2023, 09:00-13:00) of the MALTAomics Summer School 2023. The material provided here is for educational purposes only.

## Agenda

|Time         |Session                                             |Link                                                                            |
|-------------|----------------------------------------------------|--------------------------------------------------------------------------------|
|09:00 – 10:30|Introduction to Computer-Aided Drug Design          |[Slides (PDF)](slides/Day4_IntroductionToComputerAidedDrugDesign_DrJPEbejer.pdf)|
|10:30 – 10:40|Break                                               |                                                                                |
|10:40 – 11:30|Introduction to Molecular Representation            |[Slides (PDF)](slides/Day4_IntroductionToMolecularRepresentation_DrJPEbejer.pdf)|
|11:30 – 11:40|Break                                               |                                                                                |
|11:40 – 13:00|Introduction to Random Forests for Virtual Screening|[Slides (PDF)](slides/Day4_IntroductionToRandomForests_DrJPEbejer.pdf)          |


## Practicals

All code supplied for these sessions are provided as Jupyter Notebooks.  These may be run either locally (on your laptop or desktop) or, experimentally, on Google Colab.

### Data

All data used in these tutorials are provided in the [data](code/data/) directory. If running via Google Colab, you will have to upload these when prompted from the notebook.

### Google Colab

The following notebooks should open in Google Colab by using the below link provided. Note that each of these notebooks sets up its own environment (this takes a while, please have patience).

+ Practical 1 ‒ Molecular Representation (<a target="_blank" href="https://colab.research.google.com/github/BioGeMT/MALTAomics-Summer-School/blob/main/Day4_WorkshopVI_MachineLearningForDrugDiscovery/code/colab/practical1-cadd_molecular_representation_colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>)
+ Practical 2 ‒ Using a Random Forest for Virtual Screening (<a target="_blank" href="https://colab.research.google.com/github/BioGeMT/MALTAomics-Summer-School/blob/main/Day4_WorkshopVI_MachineLearningForDrugDiscovery/code/colab/practical2-cadd_ml_rf_model_colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>)
+ Practical 3 ‒ Running a Ligand Based Virtual Screening Experiment using Fingerprints (<a target="_blank" href="https://colab.research.google.com/github/BioGeMT/MALTAomics-Summer-School/blob/main/Day4_WorkshopVI_MachineLearningForDrugDiscovery/code/colab/practical3-cadd_lbvs_fingerprints_colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>)
+ Practical 4 ‒ Seperating actives and decoys using a PCA (<a target="_blank" href="https://colab.research.google.com/github/BioGeMT/MALTAomics-Summer-School/blob/main/Day4_WorkshopVI_MachineLearningForDrugDiscovery/code/colab/practical4-cadd_pca_colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>)

### Running the Jupyter Notebooks Locally

You may want to run the notebooks locally on your laptop. This is probably the way to go if you want to dig deeper and have a play around with the code. The way to install and run these notebooks locally is via the conda environment manager.

Follow these instructions:

1. Using the conda environment file [maltaomics_env.yml](code/data/maltaomics_env.yml) install this environment as described [here](https://www.bitsilla.com/wiki/doku.php?id=howto:create_python_environment_for_study_unit_xxx).
2. Clone this git repository (so you have all notebooks found in [code](code/) available locally).
3. Make sure to activate the conda environment, i.e. `conda activate maltaomics`
4. Run `jupyter notebook` in the directory where the notebooks are located and you should be able to run these locally.




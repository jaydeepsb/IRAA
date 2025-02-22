# IRAA: A statistical tool for investigating a protein-protein interaction interface from multiple structures

## Jaydeep Belapure, Marija Sorokina, Panagiotis L. Kastritis

![See the full article in Protein Science:](https://doi.org/10.1002/pro.4523) (https://doi.org/10.1002/pro.4523)

*A GUI within ipynb*

It is a tool to assess protein interface of a any complex [AB] with components [A] and [B].
Multiple 3D structures of complex [AB] in the bound state, as well as multiple 3D structrues of the components [A] and [B] are combined together to identify and understand the properties of the interface residues.

A Jupyter Notebook based GUI:
![A GUI within ipynb](https://github.com/kastritislab/IRAA/blob/main/Screenshot_IRAA_GUI_within_notebook.png)

You can easily build the GUI within a jupyter notebook as shown below -

![A GUI within ipynb](https://github.com/kastritislab/IRAA/blob/main/screen_shot_v2.gif)


Github repos is structure as below:

Notebook -> Main file: jupyter notebook 
For a quick sneak peek the notebook file is converted to .html and .pdf format only for viewing purposes. To actually interact and run the analysis please open the Run_IRAA.ipynb and go through it cell-by-cell. At the beginning there is a simple GUI panel created within the notebook for easy interaction.

* iraa_utils -> contains scripts to offer some functionality ot the notebook
* figures -> all output figure will be saved here.
* data -> Contains downloaded mmCIF files data as well as processed SASA data. 
* jpnb_overview_files -> Here are four .txt files, each containing lists of PDB IDs of structures of A, B, AB, and allow skipping any files a file \_drop.txt. 

Dependencies:
- numpy
- scipy
- pandas
- biopython
- tqdm
- pylab
- seaborn
- freesasa

You need to install freesasa and make sure it is added to the path, and available in your python run session.

# Citation:
Please cite accordingly using (https://doi.org/10.1002/pro.4523) -
```
@article{belapure2023iraa,
  title={IRAA: A statistical tool for investigating a protein--protein interaction interface from multiple structures},
  author={Belapure, Jaydeep and Sorokina, Marija and Kastritis, Panagiotis L},
  journal={Protein Science},
  volume={32},
  number={1},
  pages={e4523},
  year={2023},
  publisher={Wiley Online Library}
}
```

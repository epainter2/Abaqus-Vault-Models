# Abaqus-Vault-Models

## Welcome

For this project, I created four half vault models in Abaqus to explore the effect of different element types for vault webs and ribs. I have included the .inp and .odb files for each model (the difference between the pairs of files for each model is the material properties) and they are as follows:

**Shell-Beam model**: shell elements for vault webs, beam elements for vault ribs

Analysis-ShellBeam-origprop.inp

Analysis-ShellBeam-origprop.odb

Analysis-ShellBeam-upprop.inp

Analysis-ShellBeam-upprop.odb

**Shell-Shell model**: shell elements for both vault webs and ribs

Analysis-ShellShell-origprop.inp

Analysis-ShellShell-origprop.odb

Analysis-ShellShell-upprop.inp

Analysis-ShellShell-upprop.odb

**Shell-Solid model**: shell elements for vault webs, solid elements for vault ribs

Analysis-ShellSolid-origprop.inp

Analysis-ShellSolid-origprop.odb

Analysis-ShellSolid-upprop.inp

Analysis-ShellSolid-upprop.odb

**Solid-Solid model**: solid elements for both vault webs and ribs

Analysis-SolidSolid-origprop.inp

Analysis-SolidSolid-origprop.odb

Analysis-SolidSolid-upprop.inp

Analysis-SolidSolid-upprop.odb


I also created a series of models with a preliminary parametric analysis of solid element properties for the solid-solid model with the following files:

Analysis-SolidSolid-It1.inp

Analysis-SolidSolid-It2.inp

Analysis-SolidSolid-It3.inp

Analysis-SolidSolid-It4.inp

Analysis-SolidSolid-It5.inp

Analysis-SolidSolid-It6.inp

Analysis-SolidSolid-It7.inp

Analysis-SolidSolid-It1.odb

Analysis-SolidSolid-It2.odb

Analysis-SolidSolid-It3.odb

Analysis-SolidSolid-It4.odb

Analysis-SolidSolid-It5.odb

Analysis-SolidSolid-It6.odb

Analysis-SolidSolid-It7.odb


If you are using any of these files for further research or as reference materials, please include a citation for my thesis (found in citation file). 


---

## To open these models

These models were created in Abaqus/CAE 2019. 

The .inp files are the complete models, but need to be run for results to be viewed.

The .odb files are just the results and won't show any of the model construction.

To open a .inp file:

1. Save the **.inp** file from this repository to a location on your computer.
2. Open Abaqus/CAE 2019 and create a new database.
3. Go to File > Import > Model and select the **.inp** file.
4. Go to the Job module and create a new job (make sure your new job refers to the correct model).
5. Submit the job and view the results once complete. 

To open a .odb file: 

1. Save the **.odb** file from this repository to a location on your computer.
2. Open Abaqus/CAE 2019 and select **Open database**.
3. Filter files by **Output Database (*.odb)**.
4. Select the **.odb** file and click **OK**.

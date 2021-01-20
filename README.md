# Ab_isotype_correction
---
> This is a repository for doing antibody isotype corrections for mass cytometry
---
## Steps
1. Step up Jupyter notebook by downlading
[Anaconda individual version](https://www.anaconda.com/products/individual)

2. Start **Jupyter notebook** inside anaconda

3. Open **Correction.ipynb** and execute

---
### Requirement for the excel file:
#### **Channel** 
> this is supposed to be the name you assigned when you run the mass cytometry, if you did not assigned a name to it, it is supposed to be *'Pr141Di'* form
#### **Protein** 
> only the *'Rabbit_ISO'* and *'Mouse_ISO'* really matter, please don't change them
#### **Host** 
> source of the antibody, use *'Mouse'* or *'Rabbit'* only
#### **Ratio**
> the mean value calculated from solution mode (all the antibodies are supposed to be of the same concentration, so that when doing the corrections, (readings from FCS)/(mean value) corresponds to the antibody number)

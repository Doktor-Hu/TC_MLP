# Improving surface melt estimation over the Antarctic Ice Sheet using deep learning



Welcome to the repository for **post-processing RACMO2 surface melt using deep learning and MODIS albedo**

Current version: 1.0 (7 December 2021)



## 1. Repository Overview

This repository includes the code for building the MLP model, as well as its implementation.

- The provided Jupyter Notebook can be used for training the MLP model.

- We provide an example at AWS 14, demonstrating the MLP implementation 

  (1) with albedo from AWS/MODIS
  
  (2) with meterorogical parameters provided by AWS/RACMO2



## 2. Model Structure



![image-20211207120720707](https://github.com/Doktor-Hu/TC_MLP/blob/main/IMG/image-20211207120720707.png)


## 3. Data Availability

MODIS/Terra Surface Reflectance Daily L2G Global 1 km and 500 m SIN Grid product is available via the Land Processes Distributed Active Archive Center (LP DAAC) (https://doi.org/10.5067/MODIS/MOD09GA.006, last access: 3 December 2021). MODIS/Terra+Aqua Albedo Daily L3 Global 500 m SIN Grid product is also available via LP DAAC (https://doi.org/10.5067/MODIS/MCD43A3.006, last access: 3 December 2021). Sentinel-1 images are provided by the European Space Agency (ESA) (https://sentinel.esa.int/web/sentinel/sentinel-data-access, last access: 3 December 2021). Automatic weather station observations from AWS 14, 17, and 18 are available via https://doi.pangaea.de/10.1594/PANGAEA.910473. RACMO2 simulations (https://www.projects.science.uu.nl/iceclimate/models/antarctica.php#2-1, last access: 3 December 2021) are provided by van Wessem et al. (2018) which are available on request to the original authors. Some RACMO2 data are also available via Zenodo: https://zenodo.org/record/3677642.



## 4. Model Execution
```python
a

```



## Related Publication:

Hu, Z., Kuipers Munneke, P., Lhermitte, S., Izeboud, M., and van den Broeke, M.: Improving Surface Melt Estimation over Antarctica Using Deep Learning: A Proof-of-Concept over the Larsen Ice Shelf, The Cryosphere Discuss. [preprint], https://doi.org/10.5194/tc-2021-102, in review, 2021.

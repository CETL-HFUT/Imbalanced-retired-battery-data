# Imbalanced retired battery data

This is a sample dataset for our published article [Retired battery capacity screening based on deep learning with embedded feature smoothing under massive imbalanced data](https://www.sciencedirect.com/science/article/pii/S0360544225004037) at Energy.

**ATTENTION: THE DATA IS ONLY FOR ACADEMIC STUDY. NO COMMERCIAL USE PLEASE!**

---
### Data description

CETL-data.mat is the sample data of **4000** commercial retired batteries. These batteries have been tested at the room temperature of about 25&deg;C and recorded with a sampling interval of 3s.

|Symbol	|Meaning|
| --------   | ------   |
|Vp|Voltage data of retired batteries during charging|
|Ip	|Current data of retired batteries during charging|
|Ep	|Energy data of retired batteries during charging|
|Qp	|Capacity data of retired batteries during charging|
|Capacity_labels	|Corresponding available capacity of each battery|


---
### Specification of the battery

|Specification	|Value|
| --------   | ------   |
|Model|IFR32135|
|Size	|33.4 mm (D) 140.0 mm (H)|
|Anode material	|LiFePO<sub>4</sub>|
|Nominal capacity	|15.5 Ah|
|Nominal voltage	|3.1 V|
|Maximum allowable charging voltage	|3.9 V|
|Maximum continuous discharge current	|1 C|

---
### Declaration 

Citing as **CETL-data** if you feel the dataset is helpful.

```
@article{WU2025134761,
title = {Retired battery capacity screening based on deep learning with embedded feature smoothing under massive imbalanced data},
journal = {Energy},
volume = {318},
pages = {134761},
year = {2025},
issn = {0360-5442},
doi = {https://doi.org/10.1016/j.energy.2025.134761},
url = {https://www.sciencedirect.com/science/article/pii/S0360544225004037},
author = {Ji Wu and Jieming Wang and Mingqiang Lin and Jinhao Meng}
}
```

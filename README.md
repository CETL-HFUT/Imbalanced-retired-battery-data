# Imbalanced retired battery data

This is a sample dataset for our published article [Retired battery capacity screening based on deep learning with embedded feature smoothing under massive imbalanced data](https://www.sciencedirect.com/science/article/pii/S0360544225004037) at Energy.

**ATTENTION: THE DATA IS ONLY FOR ACADEMIC STUDY. NO COMMERCIAL USE PLEASE!**

---
### Data description

`CETL-data.zip` is the sample data of **4000** commercial retired lithium-ion batteries. 
- Charging is started from a random terminal voltage since the tested retired battery is usually not empty in practical applications.
- After charge and rest, each battery will have a full discharge process to get the capacity label.
- Ambient temperature is about 25&deg;C.
- Data is recorded with a sampling interval of 3s.
- More details can be found in the published paper.

|Battery specification	|Value|
| --------   | ------   |
|Model|IFR32135|
|Size	|33.4 mm (D) 140.0 mm (H)|
|Anode material	|LiFePO<sub>4</sub>|
|Nominal capacity	|15.5 Ah|
|Nominal voltage	|3.1 V|
|Maximum allowable charging voltage	|3.9 V|
|Maximum continuous discharge current	|1 C|

---
### CETL-data.mat

|Symbol	|Meaning| Unit|
| --------   | ------   |  ------ |
|Vp |Voltage data during charging |mV |
|Ip	|Current data during charging |mA |
|Ep	|Energy data during charging |mWh |
|Qp	|Capacity data during charging |mAh |
|Capacity_labels	|Obtained through fully discharging |mAh |

---
### Declaration 

Citing our paper as **CETL-data** if you find this dataset is helpful.

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

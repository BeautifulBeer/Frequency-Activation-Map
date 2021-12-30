# Frequency-Activation-Map
This is implementation for a research paper, "An Explainable Neural Network for Fault Diagnosis With a Frequency Activation Map". It is developed and tested on Google Colab platform, but also compatible with local running environment. **The uploaded dataset, "bearing_dataset.csv", is from Case Western Reserve University[1], and it follows its copyright law.** Additionally, you had better to check [3] to fully understand this paper.



## Bearing dataset

"Normal Baseline Data" and "12k Drive End Bearing Fault Data" are used. The dataset is preprocessed as experiment configurations of the paper: the length of window = 2048, overlap ratio = 25%.



- Normal Baseline Data
  - HP0, HP1, HP2, HP3
- 12k Drive End Bearing Fault Data
  - Fault Diameter 0.007
    - Inner Race, Ball, Outer Race(Centered) - HP0 ~ HP4
  - Fault Diameter 0.014
    - Inner Race, Ball, Outer Race(Centered) - HP0 ~ HP4
  - Fault Diameter 0.021
    - Inner Race, Ball, Outer Race(Centered) - HP0 ~ HP4
  - Fault Diameter 0.028
    - Inner Race, Ball - HP0 ~ HP4



You can download preprocessed dataset through the below link:

https://drive.google.com/drive/folders/1N2CuXQV7xqffN0s602nnFOL5v5mPWZgp?usp=sharing



## References

[1]  https://engineering.case.edu/bearingdatacenter

[2] Kim, Min Su, Jong Pil Yun, and Poogyeon Park. "An Explainable Neural Network for Fault Diagnosis With a Frequency Activation Map." *IEEE Access* 9 (2021): 98962-98972.

[3] Kim, Min Su, Jong Pil Yun, and PooGyeon Park. "An Explainable Convolutional Neural Network for Fault Diagnosis in Linear Motion Guide." *IEEE Transactions on Industrial Informatics* 17.6 (2020): 4036-4045.

---
layout: home
title: "Home"
---

LAGENDA dataset has been created by [LayerTeam](https://developers.sber.ru/portal/products/layer) for age and gender recognition tasks. 

The key features of this dataset are as follows:

- Includes a total of **67 159** images from [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html) featuring **84 192** individuals with ages from **0** to **95**.
- Near perfect balance for all ages up to **~65** years, achieved by balancing ages and genders within each age group with a step of 5. See our paper for the details.
- Each image contains a minimum of **1** face with an associated person. We also provide all the faces and persons that can be detected in every image using our detector. Please refer to the paper for more details.
The images do not have any ground truth labels, and the answers have been manually created by **human annotators**. To the best of our knowledge, this is the first dataset of its kind.
- The aggregation method used in this dataset achieved a mean absolute error (**MAE**) of **3.47** for human annotators, as per statistics from control tasks.
- The dataset contains minimal celebrity data, thus reflecting real-world, in-the-wild scenarios.
- The license for this dataset is [CC 2.0](https://creativecommons.org/licenses/by/2.0/). Do whatever you want, just remember to cite us.
- We have additionally provided modifications of the IMDB-clean, UTK, FairFace and Adience datasets, which have been annotated in the same manner for all persons (except Adience) and faces.
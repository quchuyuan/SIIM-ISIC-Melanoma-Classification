# SIIM-ISIC-Melanoma-Classification
![](https://img.shields.io/badge/Creator-KQ-ff69b4)
![](https://img.shields.io/pypi/pyversions/torch)
![](https://img.shields.io/github/license/quchuyuan/SIIM-ISIC-Melanoma-Classification)

  General Discription:
---

Skin cancer is the most prevalent type of cancer. Melanoma, specifically, is responsible for 75% of skin cancer deaths, despite being the least common skin cancer. The American Cancer Society estimates over 100,000 new melanoma cases will be diagnosed in 2020. It's also expected that almost 7,000 people will die from the disease. As with other cancers, early and accurate detection—potentially aided by data science—can make treatment more effective.

Currently, dermatologists evaluate every one of a patient's moles to identify outlier lesions or “ugly ducklings” that are most likely to be melanoma. Existing AI approaches have not adequately considered this clinical frame of reference. Dermatologists could enhance their diagnostic accuracy if detection algorithms take into account “contextual” images within the same patient to determine which images represent a melanoma. If successful, classifiers would be more accurate and could better support dermatological clinic work.

As the leading healthcare organization for informatics in medical imaging, the Society for Imaging Informatics in Medicine (SIIM)'s mission is to advance medical imaging informatics through education, research, and innovation in a multi-disciplinary community. SIIM is joined by the International Skin Imaging Collaboration (ISIC), an international effort to improve melanoma diagnosis. The ISIC Archive contains the largest publicly available collection of quality-controlled dermoscopic images of skin lesions.

In this project, we identify melanoma in images of skin lesions. In particular, we used images within the same patient and determine which are likely to represent a melanoma. Using patient-level contextual information may help the development of image analysis tools, which could better support clinical dermatologists.

Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Image analysis tools that automate the diagnosis of melanoma will improve dermatologists' diagnostic accuracy. Better detection of melanoma has the opportunity to positively impact millions of people.

  Tech Space:
---
Tested on Ubuntu 14.04 with NVIDIA TESLA V100  

To replicate the experiment results, a number of dependencies need to be installed, namely:  
- Python 3.5
- Torch 1.5.1
- Pandas
- Numpy 
- matplotlib
- sklearn

I did not use TPUs but you can take a try if you have access to a TPU.

Run 
---
```#Bash
$ nohup python3 main.py
```
According to the main code, in the end(After a long training time), you will have a file `nohup.out`, a png image `submission.csv`.  




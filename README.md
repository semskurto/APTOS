# APTOS
https://www.kaggle.com/c/aptos2019-blindness-detection

STEP-1:
Used kernels(APTOS-01a,01b,01c,01d) 
+The data set was prepared and determined.
+ML algorithm was trained (eefnet)
https://ai.googleblog.com/2019/05/efficientnet-improving-accuracy-and.html
https://arxiv.org/pdf/1905.11946.pdf

STEP-2:
TARGET:::Images have five possible ratings, 0,1,2,3,4.

Estimation was performed with the trained algorithm.

Result:
Stability was increased by replacing batch normalization with group normalization previously in "eefnet".
https://arxiv.org/pdf/1803.08494.pdf

Training results are not stable at the desired level.
A new methodology is currently being studied to reduce the error rate.

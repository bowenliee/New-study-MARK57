# New-study-MARK57 `Coming soon`
An EEG decoding method for RSVP-BCI and **All you need is attention** <br>
The codes will be uploaded after submitting the paper.
# Experiment Log
## EXP 2023-03-04 
`First`**`big`**`experiment`
The structure has been fixed. And models have been trained for all subjects.<br> Performance will determine whether to continue the experiment or optimize the model further. Fortunately, the performance of this new model has improved compared with the previous mulitiple-XGB-DIM. <br>
Here is a case for example.<br>
<details><summary><b>New model</b></summary>
![sub5.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/sub5.png)<br>
<b>multi-XGB-DIM</b><br>
![sub5_comparison.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/sub5_comparison.png)<br>
All results will be shown later.

## EXP 2023-03-04 
All results are shown below. It is indicated that I can continue the experiments.<br>
![comparison.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/comparison.png)<br>

## EXP 2023-03-04
This new model had good performance on CROSS-SUBJRCT classification. I used 22 subjects' data to train a cross-subject model, and the other 41 subjects' data were used as testing data. Here is a case.
<details><summary><b>New model</b></summary>
Subject 5 N_G 1 BA 0.817454 ACC 0.838063 TPR 0.796154 FPR 0.161245 AUC 0.876462<br>
Subject 5 N_G 5 BA 0.844047 ACC 0.875500 TPR 0.811538 FPR 0.123443 AUC 0.914418<br>
Subject 5 N_G 10 BA 0.850357 ACC 0.876750 TPR 0.823077 FPR 0.122363 AUC 0.921953<br>
Subject 5 N_G 15 BA 0.857683 ACC 0.880000 TPR 0.834615 FPR 0.119250 AUC 0.925092<br>
Subject 5 N_G 20 BA 0.863769 ACC 0.880813 TPR 0.846154 FPR 0.118615 AUC 0.927052<br>
Subject 5 N_G 25 BA 0.863706 ACC 0.880688 TPR 0.846154 FPR 0.118742 AUC 0.928445<br>
Subject 5 N_G 30 BA 0.858223 ACC 0.881063 TPR 0.834615 FPR 0.118170 AUC 0.927787<br>
Subject 5 N_G 35 BA 0.861719 ACC 0.880500 TPR 0.842308 FPR 0.118869 AUC 0.927867<br>
Subject 5 N_G 40 BA 0.859733 ACC 0.880313 TPR 0.838462 FPR 0.118996 AUC 0.927082
</details>

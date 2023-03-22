# New-study-MARK57 `Coming soon`
An EEG decoding method for RSVP-BCI and **All you need is attention** <br>
The codes will be uploaded after submitting the paper.
# Experiment Log
## EXP 2023-03-04 
`First`**`big`**`experiment`
The structure has been fixed. And models have been trained for all subjects.<br> Performance will determine whether to continue the experiment or optimize the model further. Fortunately, the performance of this new model has improved compared with the previous mulitiple-XGB-DIM. <br>
Here is a case for example.<br>
<details><summary><b>New model</b></summary>
  <b>New model subject-dependent:</b><br>
![sub5.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/sub5.png)<br>
 </details>
<details><summary><b>multi-XGB-DIM</b></summary>
  <b>multi-XGB-DIM subject-dependent:</b><br>
![sub5_comparison.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/sub5_comparison.png)<br>
</details>
All results will be shown later.

## EXP 2023-03-05 
All results are shown below. It is indicated that I can continue the experiments.<br>
<details><summary><b>multi-XGB-DIM vs New model</b></summary>
 <b>subject-dependent:</b><br>
![comparison.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/comparison.png)<br>
 </details>
 
## EXP 2023-03-06
This new model had good performance on CROSS-SUBJRCT classification. I used 22 subjects' data to train a cross-subject model, and the other 41 subjects' data were used as testing data. Here are two cases.
<details><summary><b>New model subject-independent</b></summary>
Subject 5 N_G 1 BA 0.817454 ACC 0.838063 TPR 0.796154 FPR 0.161245 AUC 0.876462<br>
Subject 5 N_G 5 BA 0.844047 ACC 0.875500 TPR 0.811538 FPR 0.123443 AUC 0.914418<br>
Subject 5 N_G 10 BA 0.850357 ACC 0.876750 TPR 0.823077 FPR 0.122363 AUC 0.921953<br>
Subject 5 N_G 15 BA 0.857683 ACC 0.880000 TPR 0.834615 FPR 0.119250 AUC 0.925092<br>
Subject 5 N_G 20 BA 0.863769 ACC 0.880813 TPR 0.846154 FPR 0.118615 AUC 0.927052<br>
Subject 5 N_G 25 BA 0.863706 ACC 0.880688 TPR 0.846154 FPR 0.118742 AUC 0.928445<br>
Subject 5 N_G 30 BA 0.858223 ACC 0.881063 TPR 0.834615 FPR 0.118170 AUC 0.927787<br>
Subject 5 N_G 35 BA 0.861719 ACC 0.880500 TPR 0.842308 FPR 0.118869 AUC 0.927867<br>
Subject 5 N_G 40 BA 0.859733 ACC 0.880313 TPR 0.838462 FPR 0.118996 AUC 0.927082<br>
Subject 5 N_G 50 BA 0.860368 ACC 0.881563 TPR 0.838462 FPR 0.117726 AUC 0.927814<br>
Subject 6 N_G 1 BA 0.801718 ACC 0.908500 TPR 0.691406 FPR 0.087970 AUC 0.904073<br>
Subject 6 N_G 5 BA 0.859470 ACC 0.942750 TPR 0.773438 FPR 0.054497 AUC 0.936398<br>
Subject 6 N_G 10 BA 0.858978 ACC 0.945563 TPR 0.769531 FPR 0.051575 AUC 0.943214<br>
Subject 6 N_G 15 BA 0.863392 ACC 0.946688 TPR 0.777344 FPR 0.050559 AUC 0.942406<br>
Subject 6 N_G 20 BA 0.862074 ACC 0.947875 TPR 0.773438 FPR 0.049289 AUC 0.941006<br>
Subject 6 N_G 25 BA 0.865219 ACC 0.946500 TPR 0.781250 FPR 0.050813 AUC 0.940643<br>
Subject 6 N_G 30 BA 0.864250 ACC 0.948375 TPR 0.777344 FPR 0.048844 AUC 0.940831<br>
 ...<br>
</details>
The performance of cross-subject model is even better than that of subject-dependent model. Please see <b>EXP 2023-03-04</b>

## EXP 2023-03-07
The cross-subject performance is very exciting.
<details><summary><b>New model subject-independent</b></summary>
![comparison.png](https://raw.githubusercontent.com/bowenliee/New-study-MARK57/master/example/cross-subject-auc.png)<br>
</details>
For the next period of time, I will be working on some tasks related to online systems and will temporarily pause updating the experimental results.

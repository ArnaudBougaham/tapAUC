# tapAUC : Towards a Trustworthy  Anomaly Detection for Critical Applications through Approximated Partial AUC Loss
Arnaud Bougaham, Benoît Frénay

**Abstract:**
Anomaly Detection is a crucial step for critical applications such in the industrial, medical or cybersecurity domains. These sectors share the same requirement of handling differently the different types of classification errors. Indeed, even if false positives are undesirable but acceptable, false negatives are not, because it would reflect a missed detection of a quality issue, a disease or a cyber threat. To fulfill this requirement, we propose a method that dynamically applies a trustworthy approximated partial AUC ROC loss (tapAUC ). A binary classifier is trained to optimize the specific range of the AUC ROC curve that prevents the True Positive Rate (TPR) to reach 100% while minimizing the False Positive Rate (FPR). The optimal threshold that does not trigger any false negative is then kept and used at the test step. The results show a TPR of 92.52% at a 20.43% FPR for an average across 6 datasets, representing a TPR improvement of 4.3% for a FPR cost of 12.2% against other state-of-the-art methods. The code is available at https://github.com/ArnaudBougaham/tapAUC.

**Keywords:** Anomaly Detection, Industry 4.0, Industrial images, Medical images, High Sensitivity, pAUC

**Code:** See ![tapAUC.ipynb](https://github.com/ArnaudBougaham/tapAUC/blob/main/tapAUC.ipynb)

**Graphical Abstract:**
![GraphicalAbstract_tapAUC](https://github.com/user-attachments/assets/f4a95de2-310b-43f3-a461-46ec13394249)

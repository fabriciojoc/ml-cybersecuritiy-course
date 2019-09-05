# Machine Learning applied to Cyber Security Course <img src="imgs/ml-sec.png" width="75" align="right">

This course is an introduction to machine learning applied to cyber security.

## Abstract

The massive amount of data produced by security solutions have been creating a strong dependency on automated methods for knowledge discovery. Attacks against computer systems make use of several transmission channels and formats (e.g., network traffic, binary files, text, chained system calls etc.), which difficult their observation among unsuspicious data. Machine learning techniques are a great aid for separating data into classes, but they need to be correctly deployed. In this course, we will show how to adequately apply machine learning algorithms to the security data science process. To do so, we will discuss key concepts about the subject and present practical examples with free, open source tools.

## Requirements

* **Python Version**: make sure you are using **Python 3.5 or higher**.
* **Libraries:** all the python libraries used can be found in the file "requirements.txt". To install them, just run the following command (using pip): 
> *pip install -r requirements.txt*
* **Datasets:** the datasets located at folder "./datasets/" are going to be used in our entire course. They are all in .zip extension. When extracting, make sure the .csv are located in this same folder. To extract, use the following command from a terminal: 
> *unzip \<filename\>.zip*.

## Summary 

### **1. [Introduction](01_introduction.ipynb)**
### **2. [Datasets](02_datasets.ipynb)**
### **3. [Attributes](03_attributes.ipynb)**
### **4. [Feature Extraction](04_features.ipynb)**
### **5. [Models](05_models.ipynb)**
### **6. [Evaluation](06_evaluation.ipynb)**
### **7. [Conclusion](07_conclusion.ipynb)**

## Cite our Work

If you want to cite this course in your work, please cite our paper [F. Ceschin, F. Pinage, M. Castilho, D. Menotti, L. S. Oliveira and A. Gregio, "The Need for Speed: An Analysis of Brazilian Malware Classifiers," in IEEE Security & Privacy, vol. 16, no. 6, pp. 31-41, Nov.-Dec. 2018. doi: 10.1109/MSEC.2018.2875369](https://ieeexplore.ieee.org/document/8636415/), which motivated us to create this content. Here is the bibtex of our work, if you want to cite us:

>@ARTICLE{8636415, 
>
>author={F. {Ceschin} and F. {Pinage} and M. {Castilho} and D. {Menotti} and L. S. {Oliveira} and A. {Gregio}}, 
>
>journal={IEEE Security Privacy}, 
>
>title={The Need for Speed: An Analysis of Brazilian Malware Classifiers}, 
>
>year={2018}, 
>
>volume={16}, 
>
>number={6}, 
>
>pages={31-41}, 
>
>keywords={invasive software;learning (artificial intelligence);pattern classification;Brazilian malware classifers;machine-learning systems;malware classification;Malware;Feature extraction;Support vector machines;Machine learning;Security;Security of data}, 
>
>doi={10.1109/MSEC.2018.2875369}, 
>
>ISSN={1540-7993}, 
>
>month={Nov},}

## References

[Abadi et al. 2015] Abadi, M., Agarwal, A., Barham, P., Brevdo, E., Chen, Z., Citro, C.,
Corrado, G. S., Davis, A., Dean, J., Devin, M., Ghemawat, S., Goodfellow, I., Harp,
A., Irving, G., Isard, M., Jia, Y., Jozefowicz, R., Kaiser, L., Kudlur, M., Levenberg,
J., Mané, D., Monga, R., Moore, S., Murray, D., Olah, C., Schuster, M., Shlens, J.,
Steiner, B., Sutskever, I., Talwar, K., Tucker, P., Vanhoucke, V., Vasudevan, V., Viégas,
F., Vinyals, O., Warden, P., Wattenberg, M., Wicke, M., Yu, Y., and Zheng, X. (2015).
TensorFlow: Large-scale machine learning on heterogeneous systems. Software available
from tensorflow.org.

[Albert Bifet 2018] Albert Bifet, Ricard Gavalda, G. H. B. P. (2018). Machine Learning
for Data Streams with Practical Examples in MOA. MIT Press. https://moa.cms.waikato.ac.nz/book/.

[Almeida et al. 2015] Almeida, P., Oliveira, L., Britto, A., and Sabourin, R. (2015). Dealing
with concept drifts using dynamic ensembles of classifiers. Tesis presented as
partial requirement for the degree of Doctor. Graduate Program in Informatics, Sector
of Exact Sciences, Universidade Federal do Paraná.

[Arp et al. 2014] Arp, D., Spreitzenbarth, M., Hubner, M., Gascon, H., and Rieck, K.
(2014). Drebin: Effective and explainable detection of android malware in your pocket.
In NDSS.

[Baena-Garcıa et al. 2006] ´ Baena-Garcıa, M., del Campo-Ávila, J., Fidalgo, R., Bifet, ´
A., Gavaldà, R., and Morales-Bueno, R. (2006). Early drift detection method.

[Bifet and Gavaldà 2007] Bifet, A. and Gavaldà, R. (2007). Learning from timechanging
data with adaptive windowing. volume 7.

[Bishop 2006] Bishop, C. M. (2006). Pattern Recognition and Machine Learning (Information
Science and Statistics). Springer-Verlag, Berlin, Heidelberg.

[Botacin et al. 2018] Botacin, M., de Geus, P. L., and Grégio, A. (2018). The other guys:
automated analysis of marginalized malware. Journal of Computer Virology and Hacking
Techniques, 14(1):87–98.

[Breiman 2001] Breiman, L. (2001). Random forests. Mach. Learn., 45(1):5–32.

[Ceschin et al. 2018] Ceschin, F., Pinage, F., Castilho, M., Menotti, D., Oliveira, L. S.,
and Gregio, A. (2018). The need for speed: An analysis of brazilian malware classifers.
IEEE Security Privacy, 16(6):31–41.

[Chollet et al. 2015] Chollet, F. et al. (2015). Keras. https://github.com/
fchollet/keras.

[Cortes and Vapnik 1995] Cortes, C. and Vapnik, V. (1995). Support-vector networks.
Machine Learning, 20(3):273–297.

[Dwork and Roth 2014] Dwork, C. and Roth, A. (2014). The algorithmic foundations of
differential privacy. Found. Trends Theor. Comput. Sci., 9(3&#8211;4):211–407.

[Ester et al. 1996] Ester, M., Kriegel, H.-P., Sander, J., and Xu, X. (1996). A densitybased
algorithm for discovering clusters in large spatial databases with noise. In KDD.

[Filho et al. 2011] Filho, D. S. F., Afonso, V. M., Martins, V. F., Grégio, A. R. A.,
de Geus, P. L., Jino, M., and dos Santos, R. D. C. (2011). Técnicas para análise dinâmica
de malware. Minicurso do SBSEG. https://sbseg2011.redes.unb.
br/resources/downloads/minicursos/91936.pdf.

[Fradkin and Muchnik 2006] Fradkin, D. and Muchnik, I. (2006). Support vector machines
for classification. ”Discrete Methods in Epidemiology”, DIMACS Series in
Discrete Mathematics and Theoretical Computer Science, 70:13–20.

[Gama et al. 2004] Gama, J., Medas, P., Castillo, G., and Rodrigues, P. (2004). Learning
with drift detection. In Bazzan, A. L. C. and Labidi, S., editors, Advances in Arti-
ficial Intelligence – SBIA 2004, pages 286–295, Berlin, Heidelberg. Springer Berlin
Heidelberg.

[Gama et al. 2014] Gama, J. a., Žliobaite, I., Bifet, A., Pechenizkiy, M., and Bouchachia, ˙
A. (2014). A survey on concept drift adaptation. ACM Comput. Surv., 46(4):44:1–
44:37.

[Gandotra et al. 2014] Gandotra, E., Bansal, D., and Sofat, S. (2014). Malware analysis
and classification: A survey. Journal of Information Security, 5(2):56–64.

[Gron 2017] Gron, A. (2017). Hands-On Machine Learning with Scikit-Learn and TensorFlow:
Concepts, Tools, and Techniques to Build Intelligent Systems. O’Reilly Media,
Inc., 1st edition.

[Haykin 2009] Haykin, S. (2009). Neural Networks and Learning Machines. Number v.
10 in Neural networks and learning machines. Prentice Hall.

[Hoffmann et al. 2016] Hoffmann, J., Rytilahti, T., Maiorca, D., Winandy, M., Giacinto,
G., and Holz, T. (2016). Evaluating analysis tools for android apps: Status quo and
robustness against obfuscation. pages 139–141.

[Jordan 2017] Jordan, M. I. (2017). The kernel trick, advanced topics in learning
& decision making. https://people.eecs.berkeley.edu/~jordan/
courses/281B-spring04/lectures/lec3.pdf, accessed in July 2017.

[Manning et al. 2008a] Manning, C. D., Raghavan, P., and Schütze, H. (2008a). Introduction
to Information Retrieval. Cambridge University Press, New York, NY, USA.

[Manning et al. 2008b] Manning, C. D., Raghavan, P., and Schütze, H. (2008b). Introduction
to Information Retrieval. Cambridge University Press, Cambridge, UK.

[Mellish 2017] Mellish, C. (2017). Machine learning, lecture notes. http://www.
inf.ufpr.br/lesoliveira/aprendizado/machine_learning.pdf,
accessed in July 2017.

[Michie et al. 1994] Michie, D., Spiegelhalter, D. J., Taylor, C. C., and Campbell, J., editors
(1994). Machine Learning, Neural and Statistical Classification. Ellis Horwood,
Upper Saddle River, NJ, USA.

[Mikolov et al. 2013a] Mikolov, T., Chen, K., Corrado, G., and Dean, J. (2013a). Efficient
estimation of word representations in vector space. CoRR, abs/1301.3781.

[Mikolov et al. 2013b] Mikolov, T., Sutskever, I., Chen, K., Corrado, G., and Dean, J.
(2013b). Distributed representations of words and phrases and their compositionality.
CoRR, abs/1310.4546.

[Milgram et al. 2006] Milgram, J., Cheriet, M., and Sabourin, R. (2006). “One Against
One” or “One Against All”: Which One is Better for Handwriting Recognition
with SVMs? In Lorette, G., editor, Tenth International Workshop on Frontiers
in Handwriting Recognition, La Baule (France). Université de Rennes 1, Suvisoft.
http://www.suvisoft.com.

[Mitchell 1997] Mitchell, T. M. (1997). Machine Learning. McGraw-Hill, Inc., New
York, NY, USA, 1 edition.

[Montiel et al. 2018] Montiel, J., Read, J., Bifet, A., and Abdessalem, T. (2018). Scikitmultiflow:
A multi-output streaming framework. Journal of Machine Learning Research,
19(72):1–5.

[Oktavianto and Muhardianto 2013] Oktavianto, D. and Muhardianto, I. (2013). Cuckoo
Malware Analysis. Packt Publishing.

[Pedregosa et al. 2011] Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion,
B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J.,
Passos, A., Cournapeau, D., Brucher, M., Perrot, M., and Duchesnay, E. (2011). Scikitlearn:
Machine learning in Python. Journal of Machine Learning Research, 12:2825–
2830.

[Rehurek and Sojka 2010] Reh ˚u ˇ ˇrek, R. and Sojka, P. (2010). Software Framework for
Topic Modelling with Large Corpora. In Proceedings of the LREC 2010 Workshop on
New Challenges for NLP Frameworks, pages 45–50, Valletta, Malta. ELRA. http://is.muni.cz/publication/884893/en.

[Rogers and Girolami 2011] Rogers, S. and Girolami, M. A. (2011). A First Course in
Machine Learning. Chapman and Hall / CRC machine learning and pattern recognition
series. CRC Press.

[Rong 2014] Rong, X. (2014). word2vec parameter learning explained. CoRR,
abs/1411.2738.

[Saxe and Sanders 2018] Saxe, J. and Sanders, H. (2018). Malware Data Science: Attack
Detection and Attribution. No Starch Press, San Francisco, CA, USA.

[Schubert et al. 2017] Schubert, E., Sander, J., Ester, M., Kriegel, H. P., and Xu, X.
(2017). Dbscan revisited, revisited: Why and how you should (still) use dbscan. ACM
Trans. Database Syst., 42(3):19:1–19:21.

[Sebastián et al. 2016] Sebastián, M., Rivera, R., Kotzias, P., and Caballero, J. (2016).
Avclass: A tool for massive malware labeling. In Monrose, F., Dacier, M., Blanc, G.,
and Garcia-Alfaro, J., editors, Research in Attacks, Intrusions, and Defenses, pages
230–253, Cham. Springer International Publishing.

[Seide and Agarwal 2016] Seide, F. and Agarwal, A. (2016). Cntk: Microsoft’s opensource
deep-learning toolkit. pages 2135–2135.

[Shulman 2016] Shulman, B. (2016). A tour of sentiment analysis techniques:
Getting a baseline for sunny side up. https://gab41.lab41.org/
a-tour-of-sentiment-analysis-techniques-getting-a-baseline-for-sunny-side-up-45730ec03330.

[Symantec 2019] Symantec (2019). 2019 internet security threat report. https://
www.symantec.com/security-center/threat-report.

[Tam et al. 2017] Tam, K., Feizollah, A., Anuar, N. B., Salleh, R., and Cavallaro, L.
(2017). The evolution of android malware and android analysis techniques. ACM
Comput. Surv., 49(4):76:1–76:41.

[Theano Development Team 2016] Theano Development Team (2016). Theano: A
Python framework for fast computation of mathematical expressions. arXiv e-prints,
abs/1605.02688.

[Wang et al. 2011] Wang, S., Schlobach, S., and Klein, M. (2011). Concept drift and how
to identify it. Web Semantics: Science, Services and Agents on the World Wide Web,
9(3):247 – 265. Semantic Web Dynamics Semantic Web Challenge, 2010.

[Yonts 2010] Yonts, J. (2010). Building a Malware Zoo. The SANS Institute.

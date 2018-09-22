## Explainable AI for Healthcare
KDD 2018 London, UK (August 19, 2018)
Room 14: 1:00 PM - 5:00 PM

* Muhammad Aurangzeb Ahmad
* Dr. Carly Eckert M.D
* Ankur Teredesai
* Vikas Kumar

KenSci Inc. and University of Washington
      
**Abstract:** This tutorial extensively covers the definitions, nuances, challenges, and requirements for the design
		of interpretable and explainable machine learning models and systems in healthcare. We discuss many uses in which interpretable machine learning models are needed in healthcare and how they should be deployed. Additionally, we explore the landscape of recent advances to address the challenges model interpretability in healthcare and also describe how one would go about choosing the right interpretable machine learnig algorithm for a given problem in healthcare.
    
## Extended Abstract:
Interpretable Machine Learning refers to machine learning models that can provide explanations regarding why certain predictionsare made. In many domains where user trust in the predictions of machine learning systems is needed, merely providing traditional machine learning metrics like AUC, precision, and recall may not be sufficient. While machine learning techniques have been employed for decades, the expansion of these techniques into fields like healthcare have led to an increased emphasis for explanations of machine learning systems. Clinical providers and other decision makers in healthcare note interpretability of model predictions as a priority for implementation and utilization.  As machine learning applications are increasingly being integrated into various parts of the continuum of patient care, the need for prediction explanation is imperative.  Machine learning solutions are being used to assist providers across clinical care domains as well as clinical operations, and costs.  Decisions based on machine learning predictions could inform diagnoses, clinical care pathways, and patient risk stratification, among many others.  It follows, that for decisions of such import, clinicians and others desire to know the "reason" behind the prediction.  In this tutorial, we will give an extensive overview of the various nuances of what constitutes explanation in machine learning, explore multiple definitions of explanation.
	
The contexts within healthcare systems where it may be prudent to ask machine learning systems for explanations vs. explanation agnostic contexts will also be explorred. Thus a physician may be greatly interested in knowing why a machine learning system is suggesting a cancer diagnosis vs. a hospital ED planner would rarely be interested in knowing why a machine learning system is making predictions about hourly arrivals in ED.  We also discuss how these definitions map to various machine learning systems and algorithms that are available today - all within a healthcare context. We use results from our research on performance comparison of interpretable models on real world problems like risk of readmission prediction, ED utilization prediction and hospital length of stay prediction to explore the constraints and drivers around going about using explainable machine learning algorithms in various healthcare contexts.
	
Different aspects of explainability in machine learning will be explored in this tutorial e.g., explainability is not limited to machine learning models but also to other aspects of machine learning like input data, model parameters, and the algorithms used. Additionally, the type of explanation provided to the is highly dependent upon the user of the system e.g., competence (cognitive capacity), novice vs. expert (domain knowledge), depth of explanation (explanation granularity) etc. Thus, in some cases, a simple linear model using highly engineered and complex features may be less interpretable than a deep learning model using simple intuitive features. Based on a comprehensive survey of literature on interpretable machine learning models we describe a framework which can be used to evaluate interpretable machine learning systems. We then map this framework and various machine learning algorithms to multiple problem domains within healthcare. We also describe in detail the constraints and pitfalls for interpretable machine learning within healthcare from the perspective of a healthcare domain expert.
	
In the later half of the tutorial, we focus on real world use cases and studies on machine learning systems in healthcare e.g., A landmark study on a machine learning model predicting pneumonia revealed that the machine learning system was giving a lower risk score to patients who also have asthema. In reality the patients in the asthma cohort were already being given extra care so that the data was biased. Nuances like these get lost in Black Box machine learning systems. In medical image diagnosis where deep learning algorithms have shown to have excellent predictive power, it has been demonstrated that it is possible to fool the system into making mistakes which a human expert would never make. We explore use cases accross the patient care continuum to address the various nuances needed to balance between algorithmic optimization and explanability in problems like disease progression, risk of readmission, emergency department admission and utilization, disease diagnosis etc. Lastly we give our perspective on the future of machine learning and healthcare by extrapolating on some of the current trends, exploring some emerging areas in this field and describing areas where the healthcare domain can benefit the most from application of machine learning.

## Slides ##
- [Power Point](http://mlhealthcare.github.io/ExplainableAIinHealthcareKDD2018.pptx.zip)
- [PDF](http://mlhealthcare.github.io/ExplainableAIinHealthcareKDD2018.pdf)

## References ##
- Addis, T. R. "Towards an" expert" diagnostic system." ICL Technical Journal 1 (1956): 79-105. 
 - Ahmad, Muhammad Aurangzeb, Eckert, Carly, McKelvey, Greg, Zolfagar, Kiyana, Zahid, Anam and Teredesai Ankur “Death vs. Data Science: Predicting End of Life” IAAI February 2-6, 2018
 - Ahmad, Muhammad Aurangzeb, Eckert, Carly, Teredesai Ankur and McKelvey, Greg “Interpretable Machine Learning in Healthcare” IEEE Intelligent Informatics Bulletin August 2018
 - Al-Shedivat, Maruan, Avinava Dubey, and Eric P. Xing. ”Contextual Explanation Networks.” arXiv preprint arXiv:1705.10301 (2017).
 - Al-Shedivat, Maruan, Avinava Dubey, and Eric P. Xing. "The Intriguing Properties of Model Explanations."
 - Bach, Sebastian, et al. "On pixel-wise explanations for non-linear classifier decisions by layer-wise relevance propagation." PloS one 10.7 (2015): e0130140
 - Bayes, Thomas, Richard Price, and John Canton. "An essay towards solving a problem in the doctrine of chances." (1763): 370-418.
 - Biran, Or, and Kathleen McKeown. "Justification narratives for individual classifications." In Proceedings of the AutoML workshop at ICML, vol. 2014. 2014.
 - Biran, Or, and Kathleen R. McKeown. "Human-Centric Justification of Machine Learning Predictions." In IJCAI, pp. 1461-1467. 2017.
 - Biran, Or, and Courtenay Cotton. "Explanation and justification in machine learning: A survey." In IJCAI-17 Workshop on Explainable AI (XAI), p. 8. 2017.
 - Buciluǎ, Cristian, Rich Caruana, and Alexandru Niculescu-Mizil. "Model compression." In Proceedings of the 12th ACM SIGKDD international conference on Knowledge discovery and data mining, pp. 535-541. ACM, 2006.
 - Burrell, Jenna. "How the machine ‘thinks’: Understanding opacity in machine learning algorithms." Big Data & Society 3, no. 1 (2016): 2053951715622512.
 - Caruana, Rich, Yin Lou, Johannes Gehrke, Paul Koch, Marc Sturm, and Noemie Elhadad. "Intelligible models for healthcare: Predicting pneumonia risk and hospital 30-day readmission." In Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, pp. 1721-1730. ACM, 2015.
 - Caruana, Rich, Sarah Tan, Yin Lou, Johannes Gehrke, Paul Koch, Marc Sturm, Noemie Elhadad et al. "Interactive Machine Learning via Transparent Modeling: Putting Human Experts in the Driver’s Seat.” IDEA 2017
 - Chakraborty, Supriyo, Richard Tomsett, Ramya Raghavendra, Daniel Harborne, Moustafa Alzantot, Federico Cerutti, Mani Srivastava et al. "Interpretability of deep learning models: a survey of results." In IEEE Smart World Congress 2017 Workshop: DAIS. 2017.
 - Chang, Jonathan, et al. “Reading tea leaves: How humans interpret topic models.” Advances in Neural Information Processing Systems. 2009
 - Chen, Xi, Yan Duan, Rein Houthooft, John Schulman, Ilya Sutskever, and Pieter Abbeel. "Infogan: Interpretable representation learning by information maximizing generative adversarial nets." In Advances in neural information processing systems, pp. 2172-2180. 2016.
 - Cook, James AI doctor app Babylon fails to diagnose heart attack, complaint alleges July 1, 2018 The Telegraph
 - Craik, Kenneth James Williams. The nature of explanation. Vol. 445. CUP Archive, 1967.
 - Mark W. Craven and Jude W. Shavlik. Extracting tree-structured representations of trained networks. Advances in Neural Information Processing Systems, 1996.
 - Datta, Anupam, Shayak Sen, and Yair Zick. "Algorithmic transparency via quantitative input influence: Theory and experiments with learning systems." Security and Privacy (SP), 2016 IEEE Symposium on. IEEE, 2016
 - Domingos, Pedro. "The role of Occam's razor in knowledge discovery." Data mining and knowledge discovery 3, no. 4 (1999): 409-425.
 - Doshi-Velez, Finale, and Been Kim. "Towards a rigorous science of interpretable machine learning." arXiv preprint arXiv:1702.08608 (2017).
 - Doshi-Velez, Finale, Mason Kortz, Ryan Budish, Chris Bavitz, Sam Gershman, David O'Brien, Stuart Schieber, James Waldo, David Weinberger, and Alexandra Wood. "Accountability of AI under the law: The role of explanation." arXiv preprint arXiv:1711.01134 (2017).
 - Druzdzel, Marek J. "Qualitiative verbal explanations in bayesian belief networks." AISB QUARTERLY (1996): 43-54.
 - Farah, M.J. Brain images, babies, and bathwater: Critiquing critiques of functional neuroimaging. Interpreting Neuroimages: An Introduction to the Technology and Its Limits 45, S19-S30 (2014)
 - Freitas, Alex A. "Comprehensible classification models: a position paper." ACM SIGKDD explorations newsletter 15, no. 1 (2014): 1-10.
 - Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. The elements of statistical learning. Vol. 1. New York: Springer series in statistics, 2001.
 - Friedman, Jerome H., and Bogdan E. Popescu. "Predictive learning via rule ensembles." The Annals of Applied Statistics2, no. 3 (2008): 916-954.
 - Gilpin, Leilani H., David Bau, Ben Z. Yuan, Ayesha Bajwa, Michael Specter, and Lalana Kagal. "Explaining Explanations: An Approach to Evaluating Interpretability of Machine Learning." arXiv preprint arXiv:1806.00069 (2018).
 - Goldstein, Alex, Adam Kapelner, Justin Bleich, and Emil Pitkin. "Peeking inside the black box: Visualizing statistical learning with plots of individual conditional expectation." Journal of Computational and Graphical Statistics 24, no. 1 (2015): 44-65.
 - Guidotti, Riccardo, Anna Monreale, Franco Turini, Dino Pedreschi, and Fosca Giannotti. "A survey of methods for explaining black box models." arXiv preprint arXiv:1802.01933(2018).
 - Gulshan, Varun, Lily Peng, Marc Coram, Martin C. Stumpe, Derek Wu, Arunachalam Narayanaswamy, Subhashini Venugopalan et al. "Development and validation of a deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs." Jama 316, no. 22 (2016): 2402-2410.
 - David Gunning Explainable Artificial Intelligence (XAI) DARPA/I2O 2016
 - Gupta, Puneet. "Machine Learning: The Future of Healthcare." Harvard Sci. Rev. (2017).
 - Gorbunov, K. Yu, and Vassily A. Lyubetsky. "The tree nearest on average to a given set of trees." Problems of Information Transmission 47, no. 3 (2011): 274.
 - Habibi, Shafi, Maryam Ahmadi, and Somayeh Alizadeh. "Type 2 diabetes mellitus screening and risk factors using decision tree: results of data mining." Global journal of health science7, no. 5 (2015): 304.
 - Hajian, Sara, Francesco Bonchi, and Carlos Castillo. "Algorithmic bias: From discrimination discovery to fairness-aware data mining." In Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining, pp. 2125-2126. ACM, 2016.
 - Hall, P., Gill, N., Kurka, M., Phan, W. (May 2018). Machine Learning Interpretability with H2O Driverless AI. http://docs.h2o.ai.
 - Hardt, Moritz, Eric Price, and Nati Srebro. "Equality of opportunity in supervised learning." In Advances in neural information processing systems, pp. 3315-3323. 2016.
 - T. Hastie and R. Tibshirani. Generalized additive models . Chapman and Hall/CRC, 1990.
 - Herlocker, Jonathan L., Joseph A. Konstan, and John Riedl. "Explaining collaborative filtering recommendations." In Proceedings of the 2000 ACM conference on Computer supported cooperative work, pp. 241-250. ACM, 2000.
 - Daniela Hernandez , Ted Greenwald IBM Has a Watson Dilemma Wall Street Journal Augist 11, 2018
 - Hoffman, Robert R., Shane T. Mueller, and Gary Klein. "Explaining Explanation, Part 2: Empirical Foundations." IEEE Intelligent Systems 32, no. 4 (2017): 78-86.
 - Hohman, Fred Matthew, Minsuk Kahng, Robert Pienta, and Duen Horng Chau. "Visual Analytics in Deep Learning: An Interrogative Survey for the Next Frontiers." IEEE Transactions on Visualization and Computer Graphics (2018).
 - Holzinger, Andreas, Chris Biemann, Constantinos S. Pattichis, and Douglas B. Kell. "What do we need to build explainable AI systems for the medical domain?." arXiv preprint arXiv:1712.09923 (2017).
 - Hutson, Matthew. "Has artificial intelligence become alchemy?." (2018): 478-478.
 - Jeffery, Alvin D., Laurie L. Novak, Betsy Kennedy, Mary S. Dietrich, and Lorraine C. Mion. "Participatory design of probability-based decision support tools for in-hospital nurses." Journal of the American Medical Informatics Association 24, no. 6 (2017): 1102-1110.
 - Kaufman, Shachar, Saharon Rosset, Claudia Perlich, and Ori Stitelman. "Leakage in data mining: Formulation, detection, and avoidance." ACM Transactions on Knowledge Discovery from Data (TKDD) 6, no. 4 (2012): 15.
 - Kendall, M. (1938). "A New Measure of Rank Correlation". Biometrika. 30 (1–2): 81–89.
 - Kendall, M. G.; Babington Smith, B. (Sep 1939). "The Problem of m Rankings". The Annals of Mathematical Statistics. 10 (3): 275–287. doi:10.1214/aoms/1177732186. JSTOR 2235668.
 - Kim, Been, Martin Wattenberg, Justin Gilmer, Carrie Cai, James Wexler, and Fernanda Viegas. "Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)." In International Conference on Machine Learning, pp. 2673-2682. 2018.
 - Koh, Pang Wei, and Percy Liang. "Understanding black-box predictions via influence functions." arXiv preprint arXiv:1703.04730 (2017).Harvard
 - Krening, Samantha, Brent Harrison, Karen M. Feigh, Charles Lee Isbell, Mark Riedl, and Andrea Thomaz. "Learning from explanations using sentiment and advice in RL." IEEE Transactions on Cognitive and Developmental Systems 9, no. 1 (2017): 44-55.
 - Kulesza, Todd. "Personalizing machine learning systems with explanatory debugging." PhD Dissertation, Oregon State University, (2014).
 - Himabindu Lakkaraju, Stephen H. Bach, and Jure Leskovec. “Interpretable decision sets: A joint framework for description and prediction.” Proc. 22nd ACM SIGKDD Intl. Conf. on Knowledge Discovery and Data Mining. ACM, 2016.
 - Jing Lei, Max G’Sell, Alessandro Rinaldo, Ryan J. Tibshirani, and Larry Wasserman. Distribution-free predictive inference for regression. Journal of the American Statistical Association, 2017
 - Lipovetsky, Stan, and Michael Conklin. "Analysis of regression in game theory approach." Applied Stochastic Models in Business and Industry 17.4 (2001): 319-330
 - Lipton, Zachary C. ”The mythos of model interpretability.” arXiv preprint arXiv:1606.03490 (2016).
 - Lipton, Zachary C. "The Doctor Just Won't Accept That!." arXiv preprint arXiv:1711.08037 (2017).
 - Lou, Yin, Rich Caruana, Johannes Gehrke, and Giles Hooker. ”Accurate intelligible models with pairwise interactions.” In Proceedings of the 19th ACM SIGKDD international conference on Knowledge discovery and data mining, pp. 623-631. ACM, 2013.
 - Lundberg, Scott M., and Su-In Lee. "A unified approach to interpreting model predictions." In Advances in Neural Information Processing Systems, pp. 4765-4774. 2017.
 - Manogaran, Gunasekaran, and Daphne Lopez. "A survey of big data architectures and machine learning algorithms in healthcare." International Journal of Biomedical Engineering and Technology 25, no. 2-4 (2017): 182-211.
 - Miller, Tim. ”Explanation in artificial intelligence: Insights from the social sciences.” arXiv preprint arXiv:1706.07269 (2017).
 - Miller, Tim, Piers Howe, and Liz Sonenberg. "Explainable AI: Beware of inmates running the asylum." In IJCAI-17 Workshop on Explainable AI (XAI), vol. 36. 2017.
 - Miotto, Riccardo, Fei Wang, Shuang Wang, Xiaoqian Jiang, and Joel T. Dudley. "Deep learning for healthcare: review, opportunities and challenges." Briefings in bioinformatics(2017).
 - Montavon, Grégoire, Sebastian Lapuschkin, Alexander Binder, Wojciech Samek, and Klaus-Robert Müller. "Explaining nonlinear classification decisions with deep taylor decomposition." Pattern Recognition 65 (2017): 211-222.
 - Moosavi-Dezfooli, Seyed-Mohsen, Alhussein Fawzi, and Pascal Frossard. "Deepfool: a simple and accurate method to fool deep neural networks." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 2574-2582. 2016.
 - Morsy, Ahmed. "Can AI Truly Transform Health Care?: A Recent IEEE Pulse on Stage Forum Offers Some Perspective." IEEE pulse 9, no. 4 (2018).
 - Fred Morstatter and Huan Liu Measuring Topic Interpretability with Crowdsourcing KDD Nuggets November 2016
 - Mozaffari-Kermani, Mehran, Susmita Sur-Kolay, Anand Raghunathan, and Niraj K. Jha. "Systematic poisoning attacks on and defenses for machine learning in healthcare." IEEE journal of biomedical and health informatics 19, no. 6 (2015): 1893-1905.
 - Murdoch, Travis B., and Allan S. Detsky. "The inevitable application of big data to health care." Jama 309, no. 13 (2013): 1351-1352.
 - Nott, George “Google's research chief questions value of 'Explainable AI'” Computer World 23 June, 2017
 - Olah, Chris, Arvind Satyanarayan, Ian Johnson, Shan Carter, Ludwig Schubert, Katherine Ye, and Alexander Mordvintsev. "The building blocks of interpretability." Distill 3, no. 3 (2018): e10.
 - Papernot, Nicolas, Patrick McDaniel, Somesh Jha, Matt Fredrikson, Z. Berkay Celik, and Ananthram Swami. "The limitations of deep learning in adversarial settings." In Security and Privacy (EuroS&P), 2016 IEEE European Symposium on, pp. 372-387. IEEE, 2016.
 - Pérez, Jesus Maria, Javier Muguerza, Olatz Arbelaitz, and Ibai Gurrutxaga. "A new algorithm to build consolidated trees: study of the error rate and steadiness." In Intelligent Information Processing and Web Mining, pp. 79-88. Springer, Berlin, Heidelberg, 2004.
 - Pulina, L., & Tacchella, A. (2010, July). An abstraction-refinement approach to verification of artificial neural networks. In International Conference on Computer Aided Verification (pp. 243-257). Springer Berlin Heidelberg.
 - Rajpurkar, Pranav, Jeremy Irvin, Kaylie Zhu, Brandon Yang, Hershel Mehta, Tony Duan, Daisy Ding et al. "Chexnet: Radiologist-level pneumonia detection on chest x-rays with deep learning." arXiv preprint arXiv:1711.05225 (2017).
 - Ram, Aliya and Neville, Sarah High-profile health app under scrutiny after doctors’ complaints Financial Times July 13, 2018
 - Quinlan, J. Ross. "Some elements of machine learning." In International Conference on Inductive Logic Programming, pp. 15-18. Springer, Berlin, Heidelberg, 1999.
 - Ras, Gabrielle, Pim Haselager, and Marcel van Gerven. "Explanation Methods in Deep Learning: Users, Values, Concerns and Challenges." arXiv preprint arXiv:1803.07517(2018).
 - Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. ”Why should i trust you?: Explaining the predictions of any classifier.” In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, pp. 1135-1144. ACM, 2016.
 - Marco Tulio Ribeiro, Sameer Singh, Carlos GuestrinIntroduction to Local Interpretable Model-Agnostic Explanations (LIME) August 12, 2016 Oriely Media
 - Ross, Casey IBM’s Watson supercomputer recommended ‘unsafe and incorrect’ cancer treatments, internal documents show Stat News July 25, 2018
 - Ross, Andrew Slavin, Michael C. Hughes, and Finale Doshi-Velez. "Right for the right reasons: Training differentiable models by constraining their explanations." arXiv preprint arXiv:1703.03717 (2017).
 - Saabas, Ando. Interpreting random forests Data Dive Blog 2014
 - Sculley, D., Gary Holt, Daniel Golovin, Eugene Davydov, Todd Phillips, Dietmar Ebner, Vinay Chaudhary, Michael Young, Jean-Francois Crespo, and Dan Dennison. "Hidden technical debt in machine learning systems." In Advances in neural information processing systems, pp. 2503-2511. 2015., D., Gary Holt, Daniel Golovin, Eugene Davydov, Todd Phillips, Dietmar Ebner, Vinay Chaudhary, Michael Young, Jean-Francois Crespo, and Dan Dennison. "Hidden technical debt in machine learning systems." In Advances in neural information processing systems, pp. 2503-2511. 2015.
 - Shrikumar, Avanti, Peyton Greenside, and Anshul Kundaje. "Learning important features through propagating activation differences." arXiv preprint arXiv:1704.02685 (2017)
 - Strumbelj, Erik, and Igor Kononenko. "Explaining prediction models and individual predictions with feature contributions." Knowledge and information systems 41.3 (2014): 647-665.
 - Tan, Sarah, Rich Caruana, Giles Hooker, and Yin Lou. "Detecting Bias in Black-Box Models Using Transparent Model Distillation." arXiv preprint arXiv:1710.06169 (2017).
 - Tesfay, Welderufael B., Peter Hofmann, Toru Nakamura, Shinsaku Kiyomoto, and Jetzabel Serna. "I Read but Don't Agree: Privacy Policy Benchmarking using Machine Learning and the EU GDPR." In Companion of the The Web Conference 2018 on The Web Conference 2018, pp. 163-166. International World Wide Web Conferences Steering Committee, 2018.
 - Tomasello, Michael. The cultural origins of human cognition. Harvard university press, 2009.
 - Machinery, Computing. "Computing machinery and intelligence-AM Turing." Mind 59, no. 236 (1950): 433.
 - Ustun, Berk, and Cynthia Rudin. ”Supersparse linear integer models for optimized medical scoring systems.” Machine Learning 102, no. 3 (2016):349-391.
 - Wang, Fulton, and Cynthia Rudin. ”Falling rule lists.” In Artificial Intelligence and Statistics, pp. 1013-1022. 2015.
 - Weld, Daniel S., and Gagan Bansal. "Intelligible Artificial Intelligence." arXiv preprint arXiv:1803.04263 (2018).
 - Weller, Adrian. "Challenges for transparency." arXiv preprint arXiv:1708.01870 (2017).
 - M. R. Wick and W. B. Thompson. Reconstructive expert system explanation. Artificial Intelligence, 54(1- 2):33–70, 1992
 - Yan, Xin, and Xiaogang Su. Linear regression analysis: theory and computing. World Scientific, 2009.
 - Yang, Hongyu, Cynthia Rudin, and Margo Seltzer. ”Scalable Bayesian rule lists.” arXiv preprint arXiv:1602.08610 (2016).

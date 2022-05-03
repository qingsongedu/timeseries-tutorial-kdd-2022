[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fqingsongedu.github.io%2Ftimeseries-tutorial-kdd-2022%2F&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%23+Visitors+%28daily%2Ftotal%29&edge_flat=false)](https://hits.seeyoufarm.com)


#  Tutorial Date/Time/Location



#  Tutorial Abstract

Time series analysis is ubiquitous and important in various areas, such as Artificial Intelligence for IT Operations (AIOps) in cloud computing, AI-powered Business Intelligence in E-commerce, Artificial Intelligence of Things (AIoT), etc. In real-world scenarios, time series data often exhibit complex patterns with trend, seasonality, outlier and noise. In addition, as more time series data are collected and stored, how to handle the huge amount of data efficiently is crucial in many applications. We note that these significant challenges exist in various tasks like forecasting, anomaly detection, and fault cause localization. Therefore, how to design effective and efficient time series models for different tasks, which are robust to address the aforementioned challenging patterns and noise in real scenarios, is of great theoretical and practical interests.

In this tutorial, we provide a comprehensive and organized tutorial on the state-of-the-art algorithms of robust time series analysis, ranging from traditional statistical methods to the most recent deep learning based methods. We will not only introduce the principle of time series algorithms, but also provide insights into how to apply them effectively in practical real-world industrial applications. Specifically, we organize the tutorial in a bottom-up framework. We first present preliminaries from different disciplines including robust statistics, signal processing, optimization, and deep learning. Then, we identify and discuss those most-frequently processing blocks in robust time series analysis, including periodicity detection, trend filtering, seasonal-trend decomposition, and time series similarity. Lastly, we discuss recent advances in multiple time series tasks including forecasting, anomaly detection, fault cause localization, and autoscaling, as well as practical lessons of large-scale time series applications from an industrial perspective. 


#  Tutorial Outline and Materials

1. Preliminaries [[slides]]()
   - Real-world Challenges and Needs for Robustness
   - Robust Statistics: Robust Regression, M-estimators
   - Signal Processing: Fourier, Wavelet 
   - Optimization Algorithms: Alternating Direction Method of Multipliers (ADMM), Majorize-Minimization (MM)
   - Deep Learning: RNN, CNN, GNN, Transformer, Data Augmentation for Time Series


2. Robust Time Series Processing Blocks [[slides]]()
   - Time Series Periodicity Detection
   - Time Series Trend Filtering
   - Time Series Seasonal-Trend Decomposition
   - Time Series Similarity

3. Robust Time Series Applications and Practices [[slides]]()
   - Forecasting: Tree Model, Deep Ensemble, Transformer, and Case Studies
   - Anomaly Detection: Decomposition Model, Deep State Space Model, Transformer, and Case Studies
   - Fault Cause Localization: Rule Set Learning, Root Cause Analysis, and Case Studies
   - Autoscaling: Query Modeling, Scaling Decision, and Case Studies


#  Key References Published by Lecturers




#  Short Bio of Lecturers

**Qingsong Wen** is currently a Staff Engineer / Team Leader with Alibaba DAMO Academy-Decision Intelligence Lab at Bellevue, WA, USA, working in the areas of intelligent time series analysis, data-driven intelligence decisions, machine learning, and signal processing. Before that, he worked at Futurewei, Qualcomm, and Marvell in the areas of big data and signal processing, and received his M.S. and Ph.D. degrees in Electrical and Computer Engineering from Georgia Institute of Technology, Atlanta, USA. He has published over 30 top-ranked conference and journal papers, and won the First Place in 2022 ICASSP Grand Challenge (AIOps in Networks) Competition. He is an Associate Editor for Neurocomputing, Guest Editor for Pattern Recognition, Guest Editor for Applied Energy, and regularly served as an SPC/PC member of the major DM/ML/AI conferences including KDD, ICDM, AAAI, IJCAI, etc.

**Linxiao Yang** is currently a Senior Engineer with Alibaba DAMO Academy, working in the fields of time series analysis, pattern mining, and interpretable machine learning. He received the B.S. degree in electrical engineering from Southwest Jiaotong University, Chengdu, China, and the Ph.D. degree in Communication and Information Engineering from the University of Electronic of Science and Technology of China, Chengdu, China. He won the First Place in 2022 ICASSP Grand Challenge (AIOps in Networks) Competition. His research interests include data-driven decision making, efficient optimization methods, interpretable machine learning, and signal processing.

**Tian Zhou** is currently a Senior Algorithm Engineer in Alibaba DAMO Lab, working mainly on time series forecasting and sequence modeling. He has worked on all aspects ranging from practical model designing to theoretical foundations. Prior to joining Alibaba, Tian obtained a BS in chemistry from Tsinghua University, an MS in Statistics from Rutgers-New Brunswick, an MS in Machine Learning from Rutgers-New Brunswick, and a PhD from Rutgers-New Brunswick, focusing on computational chemistry for organometalic catalysts.

**Liang Sun** is currently a Senior Staff Engineer / Engineering Director at DAMO Academy, Alibaba Group, Bellevue, USA. He received B.S.(2003) from Nanjing University, and Ph.D.(2011) from Arizona State University, both in computer science. Dr. Sun has over 30 publications including 2 books in the fields of machine learning and data mining. His work on dimensionality reduction won the KDD 2010 Best Research Paper Award Honorable Mention, and won the Second Place in KDD Cup 2012 Track 2 Competition. He also won the First Place in 2022 ICASSP Grand Challenge (AIOps in Networks) Competition. At Alibaba Group, he is working on temporal data mining, including time series anomaly detection, forecasting, and their applications.



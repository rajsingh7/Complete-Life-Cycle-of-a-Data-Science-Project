# Complete-Life-Cycle-of-a-Data-Science-Project

###***credit: all corresponding resources***

***motivation:motivation to create this repository  to help upcoming aspirants and help to  others in the data science field***

as data science is fastly developing field i found these few new techinques which make your work easier-https://github.com/achuthasubhash/Tips

Business understanding 

1.Data collection

Data 2 kinds

    a.structure data (tabular data,etc...)
    
    b.unstructured data (images,text,audio,etc...)

a.web scraping  best article to refer-https://towardsdatascience.com/choose-the-best-python-web-scraping-library-for-your-application-91a68bc81c4f

https://www.analyticsvidhya.com/blog/2019/10/web-scraping-hands-on-introduction-python/?utm_source=linkedin&utm_medium=KJ|link|weekend-blogs|blogs|44087|0.875

    1.beautifulsoup
   
    2.scrapy
   
    3.selenium
   
    4.request to access data 
    
    5.AUTOSCRAPER - https://github.com/alirezamika/autoscraper
  
b.3rd party API'S 

c.big data engineering to collect data

d.databases

mysql,mongodb,hadoop,elastic search,cassendra,amazon s3,hive,googlebigtable

e.online resources -   ultimate resource  https://datasetsearch.research.google.com/

    1)kaggle
   
    2)movielens
   
    3)data.gov:   https://data.gov.in/
   
    4)uci
   
    5)quandi
    
    6)world3bank  https://data.world/
   
    7)UCIMachineLearning
   
    8)online hacktons
   
    9)image data from Google_Search
   
    10)image data from Bing_Search
   
    11)https://www.columnfivemedia.com/100-best-free-data-sources-infographic
   
    12)Reddit:https://lnkd.in/dv5UCD4
   
    13)https://datasets.bifrost.ai/?ref=producthunt
   
    14)data.world:https://lnkd.in/gEK897K
   
    15)https://data.world/datasets/open-data
   
    16)FiveThirtyEight :-  https://lnkd.in/gyh-HDj
   
    17)BuzzFeed :- https://lnkd.in/gzPWyHj
   
    18)Google public datasets :- https://lnkd.in/g5dH8qE
   
    19)Quandl :- https://www.quandl.com
   
    20)socorateopendata :- https://lnkd.in/gea7JMz
   
    21)AcedemicTorrents :- https://lnkd.in/g-Ur9Xy
   
    22)labelimage:- https://github.com/wkentaro/labelme  ,  https://github.com/tzutalin/labelImg
   
    23)tensorflow_datasets as tfds
   
    24)https://datasets.bifrost.ai/?ref=producthunt
   
    25)https://ourworldindata.org/
   
    26)https://data.worldbank.org/
   
    27)google open images:https://storage.googleapis.com/openimages/web/download.html
   
    28)https://data.gov.in/
    
    29)imagenet dataset-http://www.image-net.org/
    
    30)https://parulpandey.com/2020/08/09/getting-datasets-for-data-analysis-tasks%e2%80%8a-%e2%80%8aadvanced-google-search/
    
    31)https://storage.googleapis.com/openimages/web/index.html  , 
    
       https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=segmentation&r=false&c=%2Fm%2F09qck
     
    32)coco dataset https://cocodataset.org/#explore
    
    33)huggingface datasets-https://github.com/huggingface/datasets
    
    34)Big Bad NLP Database-https://datasets.quantumstat.com/
       

2.Feature engineering

     Data cleaning-Pyjanitor-https://analyticsindiamag.com/beginners-guide-to-pyjanitor-a-python-tool-for-data-cleaning/
     
     remove duplicate data

   a.handle missing value
   
     1.if missing data too small then delete it 
     
     2.replace mean(influenced by outiler),median(not influenced by outiler),mode
     
     3.apply classifier algorithm to predict missing value
     
     4.knn imputer
     
     5.apply unsupervised 
     
     6.Random Sample Imputation
     
     7.Adding a variable to capture NAN
     
     8.Arbitrary Value Imputation
     
     9.hot deck Imputation
     
     10.regression Imputation
    
     
   b.handle imbalance
   
     1.Under Sampling - mostly not prefer because lost of data
     
     2.Over Sampling  (RandomOverSampler (here new points create by same dot)) ,  SMOTETomek(new points create by nearest point so take long time)
     
     3.class_weight give more importance(weight) to that small class
     
     4.use kfold to keep the ratio of classess constant
  
   c.remove noise data
   
   d.format data
   
   Numerical variables: Discrete numerical variable,Continuous numerical variable
   
   e.handle categorical data   Ordinal,Nominal,cyclic,binary categorical variables  
   
     1.One Hot Encoding
     
     2.Count Or Frequency Encoding
     
     3.Target Guided Ordinal Encoding
     
     4.Mean Encoding
     
     5.Probability Ratio Encoding
     
     6.label encoding
     
     7.probability ratio encoding
     
     8.woe(Weight_of_evidence)
     
     9.one hot encoding with multi category (keep most frequently repeated only)
     
     10.feature hashing 
     
     11.sparse csr matrix
     
     12.entity embeddings
     
     13.binary encoding
     
   f.normalisation of data
   
       1.Standardization
     
       2.Min Max Scaling
     
       3.Robust Scaler not influenced by outliers because using of median,IQR
      
       4.Q-Q plot or Shapiro-Wilk Normality Test  is used to check whether feature is guassian or normal distributed  required for linear regression,logistic regression to 
         
          improve performance
     
           a.Guassian Transformation
        
           b.Logarithmic Transformation
        
           c.Reciprocal Trnasformation
        
           d.Square Root Transformation
        
           e.Exponential Transdormation
        
           f.BoxCOx Transformation
        
           g.log(1+x) Transformation
           
           h.johnson
        
   g.remove low variance feature by using VarianceThreshold
   
   h.same variable in feature then remove feature
   
   i.outilers   removing outilers depond on problem we are solving
    
      eg: incase of fraud detection outilers are very important
      
      methods to find outiler: zscore,boxplot,IQR
      
   j.sampling techniques
     
     a.biased sampling
     
     b.unbiased sampling

3.Exploratory Data Analysis(eda)
  
    Explore the dataset by using  python or microsoft excel or tableau or powerbi, etc...
    
    Data visualization (Matplotlib,Seaborn,Bokeh,etc...)
    
    Scatterplot,line scatter plot,multi line plot,bubble chart,bar chart,histogram,boxplot,distplot,index plot,violin plotm,time series plot,density plot,dot plot,strip plot
  
4.Feature selection

    1.pearson correleation
   
    2.chisquare
  
    3.Feature Importance
  
       a.ExtraTreesClassifier
    
       b.SelectKBest
    
       c.stepforward and stepbackward method
    
       d.Random_forest_importance
  
    4.statics to select important feature
  
    5.keep in mind  curse of dimensionality
  
    6.highly correleated then remove 1 feature (multicollinearity)
  
    7.dimension reduction
  
    8.lasso regression to penalise unimportant features
    
    9.filter method,wrapper method
    
    10.threshold based method 
    
    11.hypothesis testing
    
    12.model based selection
    
    13.Mutual Information Feature Selection
    
    14.Correlation Feature Selection
    
    15.remove features with very low variance
    
    16.Univariate  feature selection
    
    17.recursive feature  elimination
    
    18.importance of feature (random forest importance)
    
    19.feature importance with decision trees
    
    20.lasso 

5.Model selection

Machine learning
   
   A.Supervised learning (have label data)
   
     1.regression (output feature in continous data form)
     
       linear regression,polynomial regression,support vector machine,Decision Tree Regression,Random Forest Regression,
       
       least square method,Random Forest Regression,xgboost,ridge,lasso,catboost,gradientboosting,adaboost,
       
       elsatic net,light gbm,ordinary least squares
   
     2.classification (output feature in categorical data form)
     
        Logistic Regression,K-Nearest Neighbors,Support Vector Machine,Kernel SVM,Naive Bayes,Decision Tree Classification,
        
        Random Forest Classification,xgboost,adaboost,catboost,gaussian NB,LGBMClassifier,LinearDiscriminantAnalysis,
        
        passive aggressive classifier algorithm
   
  
   B.Unsupervised learning(no label data)
   
     1.Dimensionality reduction - PCA,SVD,LDA,tsne
   
     2.Clustering :https://scikit-learn.org/stable/modules/clustering.html
   
     3.Association Rule Learning - support,lift,confidence
   
     4.Recommendation system -
     
         a.collaborative Recommendation system,
         
         bcontent based Recommendation system 
         
         c.utility based Recommendation system 
         
         d.knowledge based Recommendation system 
         
         e.demographic based Recommendation system 
         
         f.hybrid based Recommendation system 
   
   C.Ensemble methods
   
     1.Stacking models
   
     2.Bagging models
   
     3.Boosting models
   
   D.Reinforcement learning
   
      agent apply action to environment get corresponding reward so that it learn environment
      
      1.Q-Learning
      
      2.Deep Q-Learning
      
      3.Deep Convolutional Q-Learning
      
      4.Twin Delayed DDPG
      
      5.A3C 
   
   E.Deep-learning  (use when have huge data and data is highly complex and state of art for unstructured data)
   
   Frameworks:Pytorch,Tensorflow,Keras,caffe
   
   1.Multilayer perceptron(MLP)
   
     1.Regression
   
     2.Classification
   
   2.Convolutional neural network ( use for image data)
   
     1.classification of image
     
       create own model,lenet,alexnet,resenet,inception,vgg,efficientnet,Nasnet
     
     2.localization of object in image
     
     3.object detection and object segmentation 
     
       rcnn,fastrcnn,fatercnn,yolo v1,yolo v2,yolo v3,yolo v4,fast yolo,yolo tiny,yolo lite,yolo tiny++,yolo act++,
       
       maskrcnn,ssd,detectron,detectron2,mobilenet,retinanet,R-fcn,detr facebook,U-net
       
       3 kind of object segmentation semantic segmentation,instance segmentation,panoptic segmentation
     
     4.pose estimation 
     
     5.Deepdream,Neural style transfer
   
   3.recurrent neural network (use when series of data)
   
     1.RNN
     
     2.GRU
     
     3.LSTM (have memory cell,forget gate  etc..)
     
     all above have bidirectional also based on problem statement use bidirectional 
  
   4.Generative adversarial network
   
   5.Autoencoder
   
      1.sparse Autoencoder
      
      2.denoising Autoencoder
      
      3.Contractive Autoencoder
      
      4.stacked Autoencoder
      
      5.deep Autoencoder
      
      6.variational autoencoder
   
   6.BoltzmannMachines,deep belief network,deep BoltzmannMachines
   
   7.Self Organizing Maps (SOM) unsupervised learning 
   
   8.Natural language processing
   
     clean data(removing stopwords depond on problem ,lowering data,tokenization,postagging,stemmimg or lemmatization depond on problem,skipgram,n-gram,chunking)
     
     nltk,spacy,genism,textblob,inltk,stanza,polygot,corenlp  libraries
     
     NLU,NLG,NER,text summarization,machine translation
      
     1.bag of words
     
     2.Tfidf
     
     3.using rnn,lstm,gru
     
     4.attention
     
     5.self attention
     
     6.wordembedding
        
        a.using pretrained model 
          
          i)word2vec( cbow,skipgram)
          
          ii)glove
          
          iiI)fasttext
        
        b.own embedding  (use when have huge data)
        
          i)word2vec library
          
          ii)keras embedding 
        
     7.encoder and  decoder(sequence to sequence)
      
     8.Transformer (big breakthrough in NLP)
      
     9.BERT,ROBERTA,XLNet, XLM-RoBERTa, T5,DISTILBERT,GPT,GPT2,GPT3
   
   F.Time Series
   
      here data split is different (train,test,validate)
      
      here handling missing data different 
      
      generally used  to impute data in Time Series
      
      1.ffill
      
      2.bfill
      
      3.do mean of previous or future x samples and impute
      
      4.take previous year value and impute
      
      here model selection deponds on different property of data like stationary,trend,seasonality
      
      adfuller test  for  Stationarity
      
      models 
      
      1.Arima , auto arima ,seasonal arima
      
      2.Autoregressive model
      
      3.Moving average
      
      4.Lstm(neural network)
      
      5.Autoregressive
      
      6.Navie forecasts
      
      7.Smoothing (moving average,exponential smoothing)
      
      8.Facebook prophet
      
      9.Holts winter,Holts linear trend
      
      10.AutoTS-https://analyticsindiamag.com/hands-on-guide-to-autots-effective-model-selection-for-multiple-time-series/
      
      11.Temporal Convolutional Neural
   
      best article-https://www.analyticsvidhya.com/blog/2018/02/time-series-forecasting-methods/,
      
      https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/
          
   G.semi supervised learning
   
   H.active learning
   
   I.transfer learning
   
   J.deep dream,style transfer

hyperparameter tuning
  
    a.GridSearchCV (check every given parameter so take long time)
  
    b.RandomizedSearchCV (search randomly narrow down our time)
  
    c.Bayesian Optimization
    
    d.Sequential Model Based Optimization(Tuning a scikit-learn estimator with skopt)

    e.Optuna
  
    f.Genetic Algorithms 
    
    g.hyperopt
    
    h.keras tuner
    
 cross validation techniques- https://towardsdatascience.com/understanding-8-types-of-cross-validation-80c935a4976d
    
     1.loocv
     
     2.kfoldcv
     
     3.stratfied cross validation
     
     4.Time Series cross-validation
     
     5.Holdout cross-validation
     
     6.repeated cross-validation
  
tensorboard to visualization of model performance

6.Testing model

generally used metrics
  
     Always check bias variance tradeoff to know how model is performing
     
    1.Regression task - mean-squared-error, Root-Mean-Squared-Error,mean-absolute error, R², Adjusted R²,Cross-entropy loss,Mean percentage error 
   
    2.classification task-Accuracy,confusion matrix,Precision,Recall,F1 Score,Binary Crossentropy,Categorical Crossentropy,AUC-ROC curve,log loss,Average precision,Mean average precision
    
    3.Reinforcement learning - total rewards
    
    4.Incase of machine translation use bleu score
    
    5.clustering then use silhouette score
    
    6.Object Detection loss-localization loss,classification loss,Focal Loss,IOU,L2 loss,

if not giving good performance go back to Data collection or  Feature engineering to increase performance of model


7.deployment

    1.Azure
    
    2.Heroku
    
    3.Amazon Web Services
    
    4.Google cloud platform
    
    5.Docker
    
    6.tkinter

    app- flask,streamlit,Django
    
    use of tensorflow lite to reduce size of model
    
    use Quantization to reduce size of model

8.mointoring model

CI CD pipeline used-  circleci , jenkins

BIG DATA: hadoop,apache spark

research paper-https://arxiv.org/

upcoming programming language for data science is julia 

BEST ONLINE COURSES

    1.COURSERA

    2.UDEMY

    3.EDX

    4.DATACAMP


BEST YOUTUBE CHANNEL TO FOLLOW

    1.Krish Naik-https://www.youtube.com/user/krishnaik06

    2.Abhishek thakur-https://www.youtube.com/user/abhisheksvnit

    3.AIEngineering-https://www.youtube.com/channel/UCwBs8TLOogwyGd0GxHCp-Dw

    4.Ineuron-https://www.youtube.com/channel/UCb1GdqUqArXMQ3RS86lqqOw
    
    5.Ken jee-https://www.youtube.com/c/KenJee1/featured
    
    6.Codebasics-https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ           
    
    7.3Blue1Brown-https://www.youtube.com/c/3blue1brown/featured

BEST BLOGS TO FOLLOW 

    1.Towards data science-https://towardsdatascience.com/

    2.Analyticsvidhya-https://www.analyticsvidhya.com/blog/?utm_source=feed&utm_medium=navbar

    3.Medium-https://medium.com/
    
    4.Machinelearningmastery-https://machinelearningmastery.com/blog/

BEST RESOURCES

   1.paperswithcode-https://paperswithcode.com/methods

   2.madewithml-https://madewithml.com/topics/

   3.Deep learning-https://course.fullstackdeeplearning.com/#course-content

   4.pytorch deep learning-https://atcold.github.io/pytorch-Deep-Learning/

   5.deep-learning-drizzle-https://deep-learning-drizzle.github.io/

   6.Fastaibook-https://github.com/fastai/fastbook
    
   7.TopDeepLearning-https://github.com/aymericdamien/TopDeepLearning
   
   8.NLP-progress-https://github.com/sebastianruder/NLP-progress
    
   9.EasyOCR-https://github.com/JaidedAI/EasyOCR
    
   10.Awesome-pytorch-list-https://github.com/bharathgs/Awesome-pytorch-list
    
   11.free-data-science-books-https://github.com/chaconnewu/free-data-science-books
    
   12.arcgis-https://github.com/Esri/arcgis-python-api 
    
   13.data-science-ipython-notebooks-https://github.com/donnemartin/data-science-ipython-notebooks
    
   14.julia-https://github.com/JuliaLang/julia  , https://docs.julialang.org/en/v1/
    
   15.google-research-https://github.com/google-research/google-research
    
   16.reinforcement-learning-https://github.com/dennybritz/reinforcement-learning
    
   17.keras-applications-https://github.com/keras-team/keras-applications  ,  https://github.com/keras-team/keras
    
   18.opencv-https://github.com/opencv/opencv
    
   19.transformers-https://github.com/huggingface/transformers
    
   20.code implementations for research papers-https://chrome.google.com/webstore/detail/find-code-for-research-pa/aikkeehnlfpamidigaffhfmgbkdeheil
    
   21.regarding satellite images-https://www.esri.com/en-us/arcgis/about-arcgis/overview
   
   22.Monk_Object_Detection-https://github.com/Tessellate-Imaging/Monk_Object_Detection
   
   23.NLP-progress - https://github.com/sebastianruder/NLP-progress
   
   24.interview-question-data-science-https://github.com/iNeuronai/interview-question-data-science-
   
   25.recommenders-https://github.com/microsoft/recommenders
   
   26.Awesome-NLP-Resources -https://github.com/Robofied/Awesome-NLP-Resources
   
   27.Tool for visualizing attention in the Transformer model-https://github.com/jessevig/bertviz
   
   28.TransCoder-https://github.com/facebookresearch/TransCoder
   
   29.Tessellate-Imaging-https://github.com/Tessellate-Imaging/monk_v1
   
   Monk_Object_Detection-https://github.com/Tessellate-Imaging/Monk_Object_Detection/tree/master/application_model_zoo
   
   30.Machine-Learning-with-Python-https://github.com/tirthajyoti/Machine-Learning-with-Python
   
   31.huggingface-https://github.com/huggingface
   
   32.multi-task-NLP-https://github.com/hellohaptik/multi-task-NLP
   
   33.gpt-2 - https://github.com/openai/gpt-2
   
   34.Powerful and efficient Computer Vision Annotation Tool (CVAT)-https://github.com/openvinotoolkit/cvat, https://github.com/abreheret/PixelAnnotationTool
   
   https://github.com/UniversalDataTool/universal-data-tool
   
   35.Data augmentation for NLP-https://github.com/makcedward/nlpaug
   
   36.awesome Data Science-https://github.com/academic/awesome-datascience
   
   37.mlops-https://github.com/visenger/awesome-mlops
   
   38.gym-https://github.com/openai/gym
   
   39.Super Duper NLP Repo-https://notebooks.quantumstat.com/
   
   40.papers summarizing the advances in the field-https://github.com/eugeneyan/ml-surveys
   
   41.deep-translator-https://github.com/nidhaloff/deep-translator
   
   42.detext-https://github.com/linkedin/detext
   
   43.nlpaug-https://github.com/makcedward/nlpaug
   
   44.ipython-sql-https://github.com/catherinedevlin/ipython-sql
   
   45.libra-https://github.com/Palashio/libra
   
   46.opencv-https://github.com/opencv/opencv
   
   47.learnopencv-https://github.com/spmallick/learnopencv  ,  https://www.learnopencv.com/
   
   48.math is fun-https://www.mathsisfun.com/  , https://pabloinsente.github.io/intro-linear-algebra, https://hadrienj.github.io/posts/Deep-Learning-Book-Series-Introduction/
   
   49.DEEP LEARNING WITH PYTORCH: A 60 MINUTE BLITZ - https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html
    
   50.Spark Release 3.0.1-https://spark.apache.org/releases/spark-release-3-0-1.html
   
   51.for more cheatsheets-https://github.com/FavioVazquez/ds-cheatsheets
   
   52.text2emotion-https://pypi.org/project/text2emotion/
   
   53.ExploriPy-https://analyticsindiamag.com/hands-on-tutorial-on-exploripy-effortless-target-based-eda-tool/
   
   54.TCN-https://github.com/philipperemy/keras-tcn
   
   55.deeplearning-models-https://github.com/rasbt/deeplearning-models
   
   56.earthengine-py-notebooks-https://github.com/giswqs/earthengine-py-notebooks
   
   57.NLP-progress -https://github.com/sebastianruder/NLP-progress
   
   58.numerical-linear-algebra -https://github.com/fastai/numerical-linear-algebra
   
Follow leaders in the field to update yourself in the field

    1.Linkedin

    2.Twitter
    
 Free CPU/GPU/TPU
 
    1.Google cloab
    
    2.Kaggle kernel
    
    
So what next ?

participate online competition and do project and apply to intership , job,real world problems, etc...

online competitions:

1.Kaggle-https://www.kaggle.com/

2.hackerearth-https://www.hackerearth.com/challenges/

3.machinehack-https://www.machinehack.com/

4.analyticsvidhya-https://datahack.analyticsvidhya.com/contest/all/

5.zindi-https://zindi.africa/competitions

6.crowdai-https://www.crowdai.org/

7.driven data-https://www.drivendata.org/


some useful content :

1. H20.ai

2. Tpot

3. autopandas

4. AutoGluon

5. autosklearn

6. autoviml

7. autoViz

8. sweetviz (EDA purpose)  - https://pypi.org/project/sweetviz/

9. pandasprofiling(display whole EDA) - https://pypi.org/project/pandas-profiling/

10. autokeras 

11. pycaret- https://pycaret.org/

12.Auto_Timeseries by auto_ts 

13.AutoNLP_Sentiment_Analysis by autoviml

14.automl lazypredict https://github.com/shankarpandala/lazypredict 

15.bamboolib or pandas-ui (python package for easy data exploration & transformation)  https://bamboolib.8080labs.com/ , https://pypi.org/project/pandas-ui/

16.CUPY (array process parallel in gpu)  https://pypi.org/project/cupy/

17.Dabl has a built-in function that will automatically detect data types and quality issues and apply appropriate pre-processing to a dataset to prepare it for machine learning.  https://pypi.org/project/dabl/

18.dask (parallel comptataion)   https://docs.dask.org/en/latest/

19.dataprep (Understand your data with a few lines of code in seconds)

   data-preparation-tools - https://improvado.io/blog/data-preparation-tools

20.Dora library is another data analysis library designed to simplify exploratory data analysis. https://pypi.org/project/Dora/

21.FastAPI is a modern, fast (high-performance), web framework for building APIs. https://fastapi.tiangolo.com/

22.faster Hyper Parameter Tuning(sklearn-nature-inspired-algorithms) https://pypi.org/project/sklearn-nature-inspired-algorithms/

23.FlashText (A library faster than Regular Expressions for NLP tasks)  https://pypi.org/project/flashtext/

24.Guietta (tool that makes simple GUIs simple)  https://pypi.org/project/guietta/

25.hummingbird (make code fastly exexcute) https://pypi.org/project/Hummingbird/

26.memory-profiler (tell memory consumption line by line)  https://pypi.org/project/memory-profiler/

27.numexpr (incerease speed of execution of numpy)  https://github.com/pydata/numexpr

28.pandarallel  (simple and efficient tool to parallelize your pandas computation on all your CPUs) https://pypi.org/project/pandarallel/

29.PDFTableExtract(by PyPDF2)  https://github.com/ashima/pdf-table-extract

30.PyImpuyte(Python package that simplifies the task of imputing missing values in big datasets)  https://pypi.org/project/PyImpuyte/

31.libra(Automates the end-to-end machine learning process in just one line of code)  https://pypi.org/project/libra/

32.debug code by puyton -m pdp -c continue 

33.cURL (This is a useful tool for obtaining data from any server via a variety of protocols including HTTP.)
   https://stackabuse.com/using-curl-in-python-with-pycurl/

34.csvkit  https://pypi.org/project/csvkit/
 
35.IPython  IPython gives access to enhanced interactive python from the shell. 

36.pip install faker  (Create our own Dataset)  https://pypi.org/project/Faker/

37.Python debugger    %pdb

38.𝚟𝚘𝚒𝚕𝚊-From notebooks to standalone web applications and dashboards https://voila.readthedocs.io/en/stable/  https://github.com/voila-dashboards/voila

39.𝚝𝚜𝚕𝚎𝚊𝚛𝚗  for timeseries data   https://github.com/tslearn-team/tslearn

40.texthero text-based dataset in Pandas Dataframe quickly and effortlessly  https://github.com/jbesomi/texthero

41.𝚔𝚊𝚕𝚎𝚒𝚍𝚘(web-based visualization libraries like your Jupyter Notebook with zero dependencies)   https://pypi.org/project/kaleido/

42.Vaex- Reading And Processing Huge Datasets in seconds  https://github.com/vaexio/vaex

43.Uber’s Ludwig is an Open Source Framework for Low-Code Machine Learning  https://eng.uber.com/introducing-ludwig/

44.Google's TAPAS, a BERT-Based Model for Querying Tables Using Natural Language  https://github.com/google-research/tapas

45.RAPIDS  open GPU Data Science  https://rapids.ai/

46.pyforest Lazy-import of all popular Python Data Science libraries. Stop writing the same imports over and over again. https://pypi.org/project/pyforest/0.1.1/

47.Modin Get faster Pandas with Modin  https://github.com/modin-project/modin

48.Text2Code for Jupyter notebook  - https://github.com/deepklarity/jupyter-text2code , https://towardsdatascience.com/data-analysis-made-easy-text2code-for-jupyter-notebook-5380e89bb493

49.Openrefine Tool-For Data Preprocessing Without Code  https://analyticsindiamag.com/openrefine-tutorial-a-tool-for-data-preprocessing-without-code/

50.Microsoft Releases Latest Version Of DeepSpeed  deep learning optimisation library known as DeepSpeed- https://github.com/microsoft/DeepSpeed

https://analyticsindiamag.com/microsoft-releases-latest-version-of-deepspeed-its-python-library-for-deep-learning-optimisation/

51.4-pandas-tricks-https://towardsdatascience.com/4-pandas-tricks-that-most-people-dont-know-86a70a007993

52.tkinter to deploy machine learning model-https://analyticsindiamag.com/complete-tutorial-on-tkinter-to-deploy-machine-learning-model/

53.autoplotter is a python package for GUI based exploratory data analysis-https://github.com/ersaurabhverma/autoplotter

54.3 NLP Interpretability Tools For Debugging Language Models-https://www.topbots.com/nlp-interpretability-tools/


***I will be so happy that this repository helps you. Thank you for reading.***


                                                       HAPPY LEARNING



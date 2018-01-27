﻿# TOC
- [Use Cases](https://github.com/lankastersky/neuromantic#use-cases)
  - [Go game](https://github.com/lankastersky/neuromantic#go-game)
  - [Gesture Recognition](https://github.com/lankastersky/neuromantic#gesture-recognition)
  - [Image Recognition](https://github.com/lankastersky/neuromantic#image-recognition)
    - [Face Recognition](https://github.com/lankastersky/neuromantic#face-recognition)
  - [Interpretability](https://github.com/lankastersky/neuromantic#interpretability)
  - [Neural Style Transfer](https://github.com/lankastersky/neuromantic#neural-style-transfer)
  - [NLP](https://github.com/lankastersky/neuromantic#nlp)
    - [Chatbots](https://github.com/lankastersky/neuromantic#chatbots)
    - [Crossword question answerers](https://github.com/lankastersky/neuromantic#crossword-question-answerers)
    - [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)
    - [Sequence to sequence](https://github.com/lankastersky/neuromantic#sequence-to-sequence)
    - [Sentiment analysis](https://github.com/lankastersky/neuromantic#sentiment-analysis)
  - [Search](https://github.com/lankastersky/neuromantic#search)
  - [Sound recognition](https://github.com/lankastersky/neuromantic#sound-recognition)
  - [Video recognition](https://github.com/lankastersky/neuromantic#video-recognition)
    - [Video segmentation](https://github.com/lankastersky/neuromantic#video-segmentation)
- [Tools](https://github.com/lankastersky/neuromantic#tools)
  - [Google Cloud AutoML](https://github.com/lankastersky/neuromantic#google-cloud-automl)
  - [Google Mobile Vision](https://github.com/lankastersky/neuromantic#google-mobile-vision)
  - [Chatbot platforms](https://github.com/lankastersky/neuromantic#chatbot-platforms)
    - [Oscova](https://github.com/lankastersky/neuromantic#oscova)
  - [Playgrounds](https://github.com/lankastersky/neuromantic#playgrounds)
- [Models](https://github.com/lankastersky/neuromantic#models)
  - [Decision trees](https://github.com/lankastersky/neuromantic#decision-trees)
  - [Deep learning](https://github.com/lankastersky/neuromantic#deep-learning)
  - [Distillation](https://github.com/lankastersky/neuromantic#distillation)
  - [Embedding models](https://github.com/lankastersky/neuromantic#embedding-models)
  - [Metrics of dataset quality](https://github.com/lankastersky/neuromantic#metrics-of-dataset-quality)
  - [Neural Networks](https://github.com/lankastersky/neuromantic#neural-networks)
    - [Distributed Neural Networks](https://github.com/lankastersky/neuromantic#distributed-neural-networks)
- [Articles](https://github.com/lankastersky/neuromantic#articles)
- [Books](https://github.com/lankastersky/neuromantic#books)
- [MOOC](https://github.com/lankastersky/neuromantic#mooc)

# Use Cases

## Go game
- [Mastering the game of Go without human knowledge by David Silver et al, 2017](https://www.gwern.net/docs/rl/2017-silver.pdf)

## Gesture Recognition

### Using wearable sensors (phones, watches etc.)

Articles
- [Physical Human Activity Recognition Using Wearable Sensors by Ferhat Attal et al, 2015](http://www.mdpi.com/1424-8220/15/12/29858)
- [Activity Recognition with Smartphone Sensors by Xing Su et al, 2014](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6838194&tag=1)
- [Motion gesture detection using Tensorflow on Android](http://blog.lemberg.co.uk/motion-gesture-detection-using-tensorflow-android)
- [Run or Walk : Detecting Motion Activity Type with Machine Learning and Core ML](https://towardsdatascience.com/run-or-walk-detecting-user-activity-with-machine-learning-and-core-ml-part-1-9658c0dcdd90)
- Android [DetectedActivity class](https://developers.google.com/android/reference/com/google/android/gms/location/DetectedActivity)
- Android [ActivityRecognitionApi](https://developers.google.com/android/reference/com/google/android/gms/location/ActivityRecognitionApi)

Apps
- [Exercise Tracker: Wear Fitness](https://play.google.com/store/apps/details?id=vimo.co.seven)
- [Google Fit - Fitness Tracking](https://play.google.com/store/apps/details?id=com.google.android.apps.fitness)

Code repositories
- https://github.com/droiddeveloper1/android-wear-gestures-recognition
- https://github.com/drejkim/AndroidWearMotionSensors

## Image Recognition
- [Large-Scale Evolution of Image Classifiers by Esteban Real et al, 2017](https://arxiv.org/pdf/1703.01041.pdf)
- [TensorFlow-Slim image classification model library](https://github.com/tensorflow/models/tree/master/research/slim)
- [Rethinking the Inception Architecture for Computer Vision by Christian Szegedy et al, 2015](https://arxiv.org/abs/1512.00567)
- [Inception in TensorFlow](https://github.com/tensorflow/models/tree/master/research/inception) - 1.4M images and 1000 classes
- [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications by Andrew G. Howard et al, 2017](https://arxiv.org/abs/1704.04861)
  - Similar approach on practice: [How HBO’s Silicon Valley built “Not Hotdog” with mobile TensorFlow, Keras & React Native](https://medium.com/@timanglade/how-hbos-silicon-valley-built-not-hotdog-with-mobile-tensorflow-keras-react-native-ef03260747f3)
- [ImageNet Classification with Deep Convolutional Neural Networks by Alex Krizhevsky et al, 2012](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)
  - [ImageNet](http://image-net.org/)
- [Xception: Deep Learning with Depthwise Separable Convolutions by François Chollet, 2017](https://arxiv.org/abs/1610.02357)

### Face Recognition
- [FaceNet: A Unified Embedding for Face Recognition and Clustering by Florian Schroff et al, 2015](https://arxiv.org/abs/1503.03832)
  - the model: FaceNet

## Interpretability
- [Monotonic Calibrated Interpolated Look-Up Tables by Maya Gupta et al, 2016](http://jmlr.org/papers/v17/15-243.html)
- [A unified approach to interpreting model predictions by Scott M Lundberg et al, 2017](https://nips.cc/Conferences/2017/Schedule?showEvent=10008)
- see [Decision trees](https://github.com/lankastersky/neuromantic#decision-trees)
- see [Distillation](https://github.com/lankastersky/neuromantic#distillation)

## Neural Style Transfer
- [Deep Learning & Art: Neural Style Transfer – An Implementation with Tensorflow in Python](https://www.datasciencecentral.com/profiles/blogs/deep-learning-amp-art-neural-style-transfer-an-implementation)

## NLP

### Chatbots
- [How I Used Deep Learning To Train A Chatbot To Talk Like Me (Sorta)](https://adeshpande3.github.io/How-I-Used-Deep-Learning-to-Train-a-Chatbot-to-Talk-Like-Me)
  - Short-Text Conversations generative model based on Tensorflow’s embedding_rnn_seq2seq() with custom dataset. Deployed as a Facebook chatbot using heroku (hosting)+express(frontend)+flask(backend)
- [Deep Learning for Chatbots, Part 1 – Introduction, 2016](http://www.wildml.com/2016/04/deep-learning-for-chatbots-part-1-introduction/)
- [Deep Learning for Chatbots, Part 2 – Implementing a Retrieval-Based Model in Tensorflow, 2016](http://www.wildml.com/2016/07/deep-learning-for-chatbots-2-retrieval-based-model-tensorflow/)
- https://github.com/gunthercox/ChatterBot
  - Retrieval-based model based on [naive Bayesian classification and search algorithms](http://chatterbot.readthedocs.io/en/stable/faq.html#what-kinds-of-machine-learning-does-chatterbot-use) 
  - see [Sequence to sequence](https://github.com/lankastersky/neuromantic#sequence-to-sequence)
- [A Persona-Based Neural Conversation Model by Jiwei Li et al, 2016](https://arxiv.org/abs/1603.06155)
- Smart reply
  - [Smart Reply: Automated Response Suggestion for Emai by Anjuli Kannan et al, 2016](https://arxiv.org/abs/1606.04870)
  - [Computer, respond to this email, 2015](https://research.googleblog.com/2015/11/computer-respond-to-this-email.html)
- Chatbot projects: https://github.com/fendouai/Awesome-Chatbot
- see [Chatbot platforms](https://github.com/lankastersky/neuromantic#chatbot-platforms)

### Crossword question answerers
- see [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)

### Reverse dictionaries
Other name is concept finders
Return the name of a concept given a definition or description:
- [Learning to Understand Phrases by Embedding the Dictionary by Felix Hill et al, 2016](http://www.aclweb.org/anthology/Q16-1002)
  - used models: Bag-of-Words NLMs and LSTM
- comparing definitions in a database to the input query, and returning the word whose definitionis ‘closest’ to that query
- see RNNs (with LSTMs)
- see bag-of-word

### Sequence to sequence
- [Generating High-Quality and Informative Conversation Responses with Sequence-to-Sequence Models by Louis Shao et al, 2017](https://research.google.com/pubs/pub45936.html)
  - trained on a combined data set of over 2.3B conversation messages mined from the web
  - The model: LSTM on tensorflow
- [A SIMPLE BUT TOUGH-TO-BEAT BASELINE FOR SENTENCE EMBEDDINGS by Sanjeev Arora et al, 2017](https://openreview.net/pdf?id=SyK00v5xx)
- [Unsupervised Learning of Sentence Embeddings using Compositional n-Gram Features by Matteo Pagliardini et al, 2017](https://arxiv.org/pdf/1703.02507.pdf)
  - the model: Sent2Vec based on vec2vec
- [Skip-Thought Vectors by Ryan Kiros et al, 2015](https://arxiv.org/abs/1506.06726)
  - based on RNN encoder-decoder models
- [Sequence to Sequence Learning with Neural Networks by Ilya Sutskever et al, 2014](https://arxiv.org/abs/1409.3215)
  - the model: seq2seq based on LSTM
- [Distributed Representations of Sentences and Documents by Quoc V. Le, Mikolov, 2014](https://arxiv.org/abs/1405.4053)
  - [gensim's doc2vec](https://radimrehurek.com/gensim/models/doc2vec.html)
  - [python example to train doc2vec model (with or without pre-trained word embeddings)](https://github.com/jhlau/doc2vec)
- [Distributed Representations of Words and Phrases and their Compositionality by Tomas Mikolov et al, 2013](https://arxiv.org/abs/1310.4546)
  - word2vec based on Mikolov's Skip-gram model
- [Learning Continuous Phrase Representations and Syntactic Parsing with Recursive Neural Networks by Richard Socher et al, 2010](http://ai.stanford.edu/~ang/papers/nipsdlufl10-LearningContinuousPhraseRepresentations.pdf)
  - based on context-sensitive recursive neural networks (CRNN)
- see [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)

### Sentiment analysis
- [doc2vec example, 2015](http://linanqiu.github.io/2015/10/07/word2vec-sentiment/)

## Search
- [Neural Architecture Search with Reinforcement Learning by Barret Zoph et al, 2017](https://arxiv.org/abs/1611.01578)

## Sound recognition

Annotated Datasets
- [The VU sound corpus](https://github.com/CrowdTruth/vu-sound-corpus) - based on https://freesound.org/ database
  - See article [The VU Sound Corpus by Emiel van Miltenburg et al](http://www.lrec-conf.org/proceedings/lrec2016/pdf/206_Paper.pdf)
- [AudioSet](https://research.google.com/audioset/) - consists of an expanding ontology of 632 audio event classes and a collection of 2,084,320 human-labeled 10-second sound clips drawn from YouTube videos
- [How do I listen for a sound that matches a pre-recorded sound?](https://arduino.stackexchange.com/questions/8781/how-do-i-listen-for-a-sound-that-matches-a-pre-recorded-sound)
- The Sound Sensor Alert App [sentector](http://sentector.com/)

## Video recognition

### Video segmentation
Detects when one video (shot/scene/chapter) ends and another begins
- [Ridiculously Fast Shot Boundary Detection with Fully Convolutional Neural Networks by Michael Gygli, 2017](https://arxiv.org/abs/1705.08214)
- [Video Shot Boundary Detection based on Color Histogram by J. Mas and G. Fernandez, 2003](http://www-nlpir.nist.gov/projects/tvpubs/tvpapers03/ramonlull.paper.pdf)
- Unsupervised Learning from Narrated Instruction Videos, Arxiv, 2015
- Recurrent Switching Linear Dynamical Systems, CVPR, 2016
- DeepStory: Video Story QA by Deep Embedded Memory Networks, Arxiv, 2017
- Hierarchical Deep Recurrent Architecture for Video Understanding, Arxiv, 2017
- Automatic Video Scene Segmentation based on Spatial-Temporal Clues and Rhythm, Networking and Information Systems Journal, 2000
- Video Scene Segmentation Using Markov Chain Monte Carlo, TMM, 2006



Sound:
- C. Szegedy et al., Going Deeper with Convolutions, CVPR 2015.
- S. Hershey et al., CNN Architectures for Large-Scale Audio Classification, Arxiv 2017.
- A. Jansen et al., Large-Scale Audio Event Discovery in One Million YouTube Videos, ICASSP 2017


# Tools

## [Google Cloud AutoML](https://cloud.google.com/automl/)

Pros:
- let users train their own custom machine learning algorithms from scratch, without having to write a single line of code
- uses Transfer Learning (the more data and customers, the better results)
- is fully integrated with other Google Cloud services (Google Cloud Storage to store data, use Cloud ML or Vision API to customize the model etc.)

Cons:
- limited to image recognition (2018-Q1)
- doesn't allow to download a trained model

## [Google Mobile Vision](https://developers.google.com/vision/)

Pros:
- Detect Faces (finds facial landmarks such as the eyes, nose, and mouth; doesn't identifies a person)
- Scan barcodes
- Recognize Text

Cons:

## Chatbot platforms
### [Oscova](https://developer.syn.co.in/tutorial/bot/oscova/machine-learning.html)
- https://github.com/SynHub/syn-bot-samples
- MS Visual Studio is required (doesn't work with VS Code)
- activating Deep Learning feature requires [license activating](https://developer.syn.co.in/tutorial/bot/activate-license.html)
- number of requests to the server is limited by the license

## Playgrounds
- [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)

# Models

## Decision Trees
Pros:
- can model nonlinearities
- are highly interpretable
- do not require extensive feature preprocessing
- do not require enormous data sets

Cons:
- tend to overfit
  - fixed by building a decision forest with boosting
- unstable/undeterministic (generate different results while trained on the same data)
  - fixed by using bootstrap aggregation/bagging (a boosted forest)
- do mapping directly from the raw input to the label
  - better use neural nets that can learn intermediate representations

Hyperparameters:
- tree depth
- maximum number of leaf nodes

## Deep learning
- [Deep Learning: A Critical Appraisal by Gary Marcus, 2018](https://arxiv.org/abs/1801.00631)
- [Software 2.0 by Andrej Karpathy, 2017](https://medium.com/@karpathy/software-2-0-a64152b37c35)

## Distillation
  - trains a model to mimic the behavior of a pretrained model so it can work independently of the pretrained model
  - can train the smaller model with unlabeled examples
  - not all target classes need to be represented in the distillation training set
  - reduces the need for regularization
  - [Distilling the Knowledge in a Neural Network by Geoffrey Hinton et al, 2015](https://arxiv.org/abs/1503.02531)
  - [“Why Should I Trust You?” Explaining the Predictions of Any Classifier by Marco Tulio Ribeiro et al, 2016](https://arxiv.org/abs/1602.04938)
  - [Detecting Bias in Black-Box Models Using Transparent Model Distillation by Sarah Tan et al, 2017](https://arxiv.org/abs/1710.06169)

## Embedding models
- https://github.com/Hironsan/awesome-embedding-models
- [word2vec](https://code.google.com/archive/p/word2vec/source) (embedded words and phrases)
- [gensim's doc2vec](https://radimrehurek.com/gensim/models/doc2vec.html)
- https://github.com/jhlau/doc2vec
- see recursive autoencoders
- see bag-of-words models

## Metrics of dataset quality
- Statistical metrics
  - descriptive statistics: dimensionality, unique subject counts, systematic replicates counts, pdfs, cdfs (probability and cumulative distribution fx's)
  - cohort design
  - power analysis
  - sensitivity analysis
  - multiple testing correction analysis
  - dynamic range sensitivity
- Numerical analysis metrics
  - number of clusters
  - PCA dimensions
  - MDS space dimensions/distances/curves/surfaces
  - variance between buckets/bags/trees/branches
  - informative/discriminative indices (i.e. how much does the top 10 features differ from one another and the group)
  - feature engineering differnetiators

## Neural Networks
[Approaches](https://medium.com/@sayondutta/nuts-and-bolts-of-applying-deep-learning-by-andrew-ng-89e1cab8b602) when our model doesn’t work:
- Fetch more data
- Add more layers to Neural Network
- Try some new approach in Neural Network
- Train longer (increase the number of iterations)
- Change batch size
- Try Regularisation
- Check Bias Variance trade-off to avoid under and overfitting
- Use more GPUs for faster computation

### Distributed Neural Networks
- [Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer by Jeff Dean et al](https://arxiv.org/abs/1701.06538)
- [PathNet: Evolution Channels Gradient Descent in Super Neural Networks by deepmind](https://deepmind.com/research/publications/pathnet-evolution-channels-gradient-descent-super-neural-networks/)
- Feature extraction - uses layers of a pretrained model as inputs to another model, effectively chaining two models together

# Articles

# MOOC

# Books



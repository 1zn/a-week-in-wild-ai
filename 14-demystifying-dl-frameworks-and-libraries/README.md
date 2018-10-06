

#### Demystifying Deep Learning Frameworks and Libraries(end to end low+high level)
---------

##### Anatomy of ML/DL Frameworks 


- [framework-optimizations](https://ai.intel.com/framework-optimizations/)


----------

##### Numerical libraries

- Basic Linear Algebra Subprograms([BLAS](http://www.netlib.org/blas/))
- [Numerical libraries](https://hpc-forge.cineca.it/files/CoursesDev/public/2016/Milan/Cross_Sectoral_Course_PhD/0501-MathLibraries.pdf)
- [List of numerical libraries](https://en.wikipedia.org/wiki/List_of_numerical_libraries)
- [Normal Cuda Vs CuBLAS?](https://stackoverflow.com/questions/25836003/normal-cuda-vs-cublas)
- [Hands-on Lab: Rapid Multi-GPU Programming with CUDA Libraries](http://on-demand.gputechconf.com/gtc/2014/presentations/S4788-rapid-multi-gpu-programming-cuda-libraries.pdf)
- [The CUBLAS and CULA libraries](https://wlandau.github.io/gpu/lectures/cublas-cula/cublas-cula.pdf)
- [BLASX: A High Performance Level-3 BLAS
Library for Heterogeneous Multi-GPU Computing](https://arxiv.org/pdf/1510.05041.pdf)
- [Analysis of Object-Oriented Numerical Libraries ](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.91.1918&rep=rep1&type=pdf)
- [Numerical Linear Algebra Software](https://web.stanford.edu/class/ee392o/nlas-foils.pdf)
- [Integrating MPI-based numerical software into an advanced parallel computing environment](http://www.dma.unina.it/~lapegna/documents/euromicro03.pdf)
- [Introduction to Scientific
Libraries](http://www.training.prace-ri.eu/uploads/tx_pracetmo/Num_Libs_shortDOSAC15.pdf)
- [Porting the PLASMA Numerical Library to the OpenMP Standard](https://www.icl.utk.edu/files/publications/2016/icl-utk-942-2016.pdf)
- [IMSL Fortran Numerical Special Functions Math Library](http://www.afs.enea.it/software/imsl/help/sfun/sfun.pdf)
- [Numerical Libraries with C or Fortran](https://www.bu.edu/tech/files/2016/06/Introduction_to_Numerical_Libraries.pdf)
- [Python for Computational Science and Engineering](https://www.southampton.ac.uk/~fangohr/training/python/pdfs/Python-for-Computational-Science-and-Engineering.pdf)
- [Julia: A Fresh Approach to
Numerical Computing∗](https://julialang.org/publications/julia-fresh-approach-BEKS.pdf)



----------------------
         - Its more likely that Pytorch may takeover Tensorflow in 1-2 years.
         - Keras lives on as high level API if they given support to competitive frameowrks. 
         - Opportunities: 
           - Future will be co-evolution of AI and Hardware, AI will fundamentally change the computing industry.
           - There is a space for a new open platform which can support/optimize high level computational graps to future computing devices/chips irrespective of their underlying structures and complexities(Multicore CPU's, GPU's, TPU's VPU's, NPUs,  ASICs, neuromarphic chipsets, FPGAs, HPC-MPIs, DSPs, Quantum chips(QPUs), mobile chipsets, custom chips and EDGE computing) with less integration time. Definitely existing platforms evolve to this stage in 3-5 yrs.


----------
##### Core ML [Jun 2017, Apple]

- [Apple announces new machine learning API to make mobile AI faster](https://www.theverge.com/2017/6/5/15725994/apple-mobile-ai-chip-announced-wwdc-2017)
- [Create your own Object Recognizer — ML on iOS](https://medium.com/@hunter.ley.ward/create-your-own-object-recognizer-ml-on-ios-7f8c09b461a1)
- [Deep Learning for Core ML](https://e-string.com/pdf/core-ml-dl-pdx-cocoaheads.pdf)
- [CoreML](https://simplecore.intel.com/nervana/wp-content/uploads/sites/53/2018/05/IntelAIDC18_HishamChowdhury_Matrix_5.24_Final.pdf)
- [CoreML Team: •
Introducing Core ML](https://devstreaming-cdn.apple.com/videos/wwdc/2017/703muvahj3880222/703/703_introducing_core_ml.pdf?dl=1)

---------------

##### Caff2 [April 2017, FAIR]

       - In April 2017, Facebook announced Caffe2, which includes new features such as Recurrent Neural Networks. 
       - At the end of March 2018, Caffe2 was merged into PyTorch.
       
 - [Caffe2 Merges With PyTorch](https://medium.com/@Synced/caffe2-merges-with-pytorch-a89c70ad9eb7)
 - [ONNX-workshop](http://learningsys.org/nips17/assets/slides/ONNX-workshop.pdf)
 
--------------
##### Pytorch [October 2016, FAIR(Adam Paszke, Sam Gross, Soumith Chintala, Gregory Chanan)]

      Torch(Lua) + Python = Pytorch <--> ONNX <--> Caffe2

- [Soumit Chintala: PyTorch-NewGeneration](http://on-demand.gputechconf.com/gtc/2017/presentation/s7784-soumith-chintala-pytorch-a-framework-for-next-generation-ai.pdf)
- [pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list)

-------------
##### CNTK [January 2016, Microsoft]


- [Build_2017_05_CNTK_Overview_v2](https://www.cntk.ai/Tutorials/Build2017/Build_2017_05_CNTK_Overview_v2.pdf)
- [CVPR_2017_Tutorial_final](https://www.cntk.ai/Tutorials/CVPR2017/CVPR_2017_Tutorial_final.pdf)
- [Deep Learning in Microsoft
with CNTK ](http://on-demand.gputechconf.com/gtc/2016/presentation/S6843-alexey-kamanev-deep-learning-microsoft-cntk.pdf)
- [CNTK—Microsoft’s Open
Source Deep Learning Toolkit ](http://images.nvidia.com/cn/gtc/downloads/pdf/partners/609.%20CNTK%20Toolkit%20-%20%E7%8E%8B%E5%A4%AA%E5%B3%B0.pdf)



--------

##### Tensorflow [November 2015, Google Brain team]


----------

##### Apache MXNet [October 2015, Apache SF]

       - Supports multiple programming languages (including C++, Python, Julia, Matlab, JavaScript, Go, R, Scala, Perl, and Wolfram Language.)
       
       - MXNet is supported by public cloud providers including (AWS) and Microsoft Azure.
       
       - MXNet is supported by Intel, Dato, Baidu, Microsoft, Wolfram Research, and research institutions such as Carnegie Mellon, MIT, the University of Washington, and the Hong Kong University of Science and Technology.
       
       - MXNet is designed to be distributed on dynamic cloud infrastructure, using a distributed parameter server (based on research at Carnegie Mellon University, Baidu, and Google), and can achieve almost linear scale with multiple GPUs or CPUs.
 
- [MXNet: A Flexible and Efficient Machine Learning
Library for Heterogeneous Distributed Systems](https://www.cs.cmu.edu/~muli/file/mxnet-learning-sys.pdf) 
- [A Practitioner’s Guide to MXNe](https://home.cse.ust.hk/~xshiab/data/MXNet.pdf)
- [Distributed Deep Learning Inference
using Apache MXNet* and Apache Spark](https://apachecon.com/euroadshow18/MXNet-Spark-Slides.pdf)
- [MXNet: Lightweight, Flexible,
and Efficient Deep Learning
Library](http://images.nvidia.com/cn/gtc/downloads/pdf/partners/608.%20MXNet%20-%20%E7%8E%8B%E4%B9%83%E5%B2%A9.pdf)
- [MXNET-MPI: Embedding MPI parallelism in Parameter Server
Task Model for scaling Deep Learning](https://arxiv.org/pdf/1801.03855.pdf)


------------

##### Keras [March 2015, François Chollet(Google)]

     - Capable of running on top of TensorFlow, Microsoft Cognitive Toolkit or Theano.
     
     - Developed as part of the research effort of project ONEIROS (Open-ended Neuro-Electronic Intelligent Robot Operating System)
     
     - In 2017, Google's TensorFlow team decided to support Keras in TensorFlow's core library. 
     
     - Chollet explained that Keras was conceived to be an interface rather than a standalone machine-learning framework.
     
     - Keras allows users to productize deep models on smartphones (iOS and Android), on the web, or on the Java Virtual Machine.

-----------
##### DL4J [2014, Skymind(Adam Gibson, Chris Nicholson, Josh Patterson)]

     - Written in Java, Scala, CUDA, C, C++, Python, Clojure
     
     - Includes implementations of the restricted Boltzmann machine, deep belief net, deep autoencoder, stacked denoising autoencoder and recursive neural tensor network, word2vec, doc2vec, and GloVe.
     
     - All algorithms include distributed parallel versions that integrate with Apache Hadoop and Spark.
     
     - Bundles DL4J, Tensorflow, Keras and other deep learning libraries in an enterprise distribution called the Skymind Intelligence Layer.
     
     - Works with distributed GPUs.

- [DeepLearning4j](https://www.uni-weimar.de/fileadmin/user/fak/medien/professuren/Webis/teaching/ss16/big-data-seminar/scholz-deeplearning4j.pdf)
- [Deep Learning
Frameworks with
Spark and GPUs](http://on-demand.gputechconf.com/gtc/2017/presentation/s7737-subbu-rama-deep-learning-with-spark%20.pdf)


-----------

##### Caffe [2013, Berkeley Vision and Learning Center,Yangqing Jia(PhD thesis)]

        - Supports CNN, RCNN, LSTM and fully connected neural network designs.
        
        - Caffe supports GPU- and CPU-based acceleration computational kernel libraries such as NVIDIA cuDNN and Intel MKL.
        
        - Yahoo! integrated caffe with Apache Spark to create CaffeOnSpark, a distributed deep learning framework.
        
        - In April 2017, Facebook announced Caffe2, which includes new features such as Recurrent Neural Networks. At the end of March 2018, Caffe2 was merged into PyTorch.
        

- [The Caffe Deep Learning Framework: An Interview with the Core Developers](https://www.embedded-vision.com/industry-analysis/technical-articles/caffe-deep-learning-framework-interview-core-developers)
- [S-Caffe:	Co-designing	MPI	Runtimes	and	Caffe	for	
Scalable	Deep	Learning	on	Modern	GPU	Clusters](https://pdfs.semanticscholar.org/bd6f/e117ca35a7ab144408be1771000feb57c7fb.pdf)



-----------

##### Theano [2007, Montreal Institute for Learning Algorithms (MILA)]

     On 28 September 2017, Pascal Lamblin posted a message from Yoshua Bengio, Head of MILA: major development would cease after the 1.0      release due to competing offerings by strong industrial players [ref](https://groups.google.com/forum/#!topic/theano-users/7Poq8BZutbY).Theano 1.0.0 was then released on 15 November 2017. Theano 1.0.3 on 17 September 2018.
     
- [Theano: A CPU and GPU Math Compiler in Python](http://www.iro.umontreal.ca/~lisa/pointeurs/theano_scipy2010.pdf)
- [Theano and Machine Learning](https://ni.www.techfak.uni-bielefeld.de/files/theano-intro.pdf)
- [Getting started with Theano](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-theano.pdf)
- [Theano Tutorial](https://colinraffel.com/talks/next2015theano.pdf)
- [A Simple Tutorial on Theano](http://ir.hit.edu.cn/~jguo/docs/notes/a_simple_tutorial_on_theano.pdf)
- [GPU Programming made Easy](http://www.iro.umontreal.ca/~lisa/pointeurs/tutorial_hpcs2011_fixed.pdf)
- [Software R&D for Next
Generation of HEP Experiments,
Inspired by Theano](https://indico.cern.ch/event/395374/contributions/939858/attachments/1184475/1716465/DataScienceAtLHCWS.pdf)
- [Theano-MPI:
a Theano-based Distributed Training Framework](http://uchpc.lrr.in.tum.de/16/uchpc16-slides-hema.pdf)

-----------

##### Scikit-learn [2007, David Cournapeau(google summar code project)]

- [Scikit-Learn: Machine Learning in Python](http://disi.unitn.it/~passerini/teaching/2016-2017/MachineLearning/slides/sklearn/sklearn.pdf)
- [Scikit learn](https://delftswa.gitbooks.io/desosa-2017/content/scikit-learn/chapter.html)


-----------

##### Torch [2002, Ronan Collobert, Koray Kavukcuoglu, Clement Farabet]

- [Torch7
Scientific computing for Lua(JIT)](http://hunch.net/~nyoml/torch7.pdf)
- [Torch_Overview_v2](https://www.airc.aist.go.jp/seminar_detail/docs/seminar05-graf.pdf)
- [A quick tour of Torch internals](https://apaszke.github.io/torch-internals.html)
- [Torch Cheatsheet](https://github.com/torch/torch7/wiki/Cheatsheet)
- [Advanced Machine Learning 2014
(Introduction to Torch)](http://ml.informatik.uni-freiburg.de/former/_media/teaching/ws1415/presentation_dl_lect3.pdf)
- [Getting started with Torch](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-torch.pdf)
- [https://github.com/soumith/cvpr2015](https://github.com/soumith/cvpr2015)

-------------

##### OpenCV  [2000, Intel Corporation, Willow Garage, Itseez]

- [Computer Vision on the GPU with
OpenCV](http://developer.download.nvidia.com/GTC/PDF/1085_Fung.pdf)
- [2002: 
h
Tor
h: a modular ma
hine
learning software lib](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=CBB0C8A5FE34F6D6DAFF997F6B6A205A?doi=10.1.1.8.9850&rep=rep1&type=pdf)
- [OpenCV (Open Source Computer Vision Library)](https://delftswa.gitbooks.io/desosa2016/content/opencv/Chapter.html#ev-opencv)     
- [Introducing OpenCV for Developers](http://www.jsk.t.u-tokyo.ac.jp/rsj2011/_downloads/2Q2-3.pdf)
- [OpenCV'Tutorial'](https://pdfs.semanticscholar.org/presentation/3feb/bbfbc205e2c4178263c421ef975ba8f0e952.pdf)
- [Machine Learning
for OpenCV](https://share.nxtcloud.net/mirror/New/A.I.%20by%20Packt/Machine%20Learning%20for%20OpenCV.pdf)
- [OpenCV Introduction](https://web.stanford.edu/class/cs231a/sessions/session4_opencv_tutorial.pdf)

--------------

##### MLC++ [1996, Stanford]

- [MLC++: A Machine Learning Library in C++
](http://robotics.stanford.edu/~ronnyk/mlctools.pdf)
- [MLC++: A Machine Learning
Library in C++](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.9.946&rep=rep1&type=pdf)


--------------------
-------------

#### Literature Review

##### Scikit-learn

- [Scikit-learn: Machine Learning in Python](https://arxiv.org/pdf/1201.0490.pdf)
- [API design for machine learning software:
experiences from the scikit-learn project](https://dtai.cs.kuleuven.be/events/lml2013/papers/lml2013_api_sklearn.pdf)
- [Seglearn: A Python Package for Learning Sequences and Time Series](https://arxiv.org/pdf/1803.08118.pdf)
- [Introduction to astroML: Machine Learning for Astrophysics](https://arxiv.org/pdf/1411.5039.pdf)
- [TensorLy: Tensor Learning in Python](https://arxiv.org/pdf/1610.09555v2.pdf)

##### Pytorch

- [PyTorch – Internal Architecture Tour](http://blog.christianperone.com/2018/03/pytorch-internal-architecture-tour/)
- [Torchbearer: A Model Fitting Library for PyTorch](https://arxiv.org/pdf/1809.03363v1.pdf)
- [DELIMIT PyTorch - An extension for Deep Learning in Diffusion Imaging](https://arxiv.org/pdf/1808.01517v1.pdf)
- [Honk: A PyTorch Reimplementation of Convolutional Neural Networks for Keyword Spotting](https://arxiv.org/pdf/1710.06554v2.pdf)
- [GPyTorch: Blackbox Matrix-Matrix Gaussian Process Inference with GPU Acceleration](https://arxiv.org/pdf/1809.11165v1.pdf)
- [DeepDIVA: A Highly-Functional Python Framework for Reproducible Experiments](https://arxiv.org/pdf/1805.00329v1.pdf)
- [BrainSlug: Transparent Acceleration of Deep Learning Through Depth-First Parallelism](https://arxiv.org/pdf/1804.08378v1.pdf)
- [ESPnet: End-to-End Speech Processing Toolkit](https://arxiv.org/pdf/1804.00015v1.pdf)
- [Foolbox: A Python toolbox to benchmark the robustness of machine learning models](https://arxiv.org/pdf/1707.04131v3.pdf)
- [NSML: A Machine Learning Platform That Enables You to Focus on Your Models](https://arxiv.org/pdf/1712.05902v1.pdf)
- [BindsNET: A machine learning-oriented spiking neural networks library in Python](https://arxiv.org/pdf/1806.01423v1.pdf)
- [NCRF++: An Open-source Neural Sequence Labeling Toolkit](https://arxiv.org/pdf/1806.05626v2.pdf)
- [AirLab: Autograd Image Registration Laborator](https://arxiv.org/pdf/1806.09907v1.pdf)
- [Adversarial Robustness Toolbox v0.3.0](https://arxiv.org/pdf/1807.01069v2.pdf)

##### Torch

- [NeuFlow: A Runtime Reconfigurable Dataflow Processor for Vision](http://pub.clement.farabet.net/ecvw11.pdf)
- [cltorch: a Hardware-Agnostic Backend for the Torch Deep Neural Network Library, Based on OpenCL](https://arxiv.org/pdf/1606.04884v1.pdf)
- [rnn : Recurrent Library for Torch](https://arxiv.org/pdf/1511.07889v2.pdf)
- [Neural Networks for Beginners. A fast implementation in Matlab, Torch, TensorFlow](https://arxiv.org/pdf/1703.05298v2.pdf)
- [Auto-Differentiating Linear Algebra](https://arxiv.org/pdf/1710.08717v3.pdf)
- [SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks](https://arxiv.org/pdf/1801.04380v1.pdf)
- [Wolf in Sheep's Clothing - The Downscaling Attack Against Deep Learning Applications](https://arxiv.org/pdf/1712.07805v1.pdf)
- [Can Decentralized Algorithms Outperform Centralized Algorithms? A Case Study for Decentralized Parallel Stochastic Gradient Descent](https://arxiv.org/pdf/1705.09056v5.pdf)
- [PowerAI DDL](https://arxiv.org/pdf/1708.02188v1.pdf)
- [Benchmarking State-of-the-Art Deep Learning Software Tools](https://arxiv.org/pdf/1608.07249v7.pdf)
- [TorchCraft: a Library for Machine Learning Research on Real-Time Strategy Games](https://arxiv.org/pdf/1611.00625v2.pdf)
- [A Tour of TensorFlow](https://arxiv.org/pdf/1610.01178v1.pdf)
- [gvnn: Neural Network Library for Geometric Computer Vision](https://arxiv.org/pdf/1607.07405v3.pdf)
- [DeepLearningKit - an GPU Optimized Deep Learning Framework for Apple's iOS, OS X and tvOS developed in Metal and Swift](https://arxiv.org/pdf/1605.04614v1.pdf)
- [End to End Learning for Self-Driving Cars](https://arxiv.org/pdf/1604.07316v1.pdf)
- [Comparative Study of Deep Learning Software Frameworks](https://arxiv.org/pdf/1511.06435v3.pdf)
- [Poseidon: A System Architecture for Efficient GPU-based Deep Learning on Multiple Machines](https://arxiv.org/pdf/1512.06216v1.pdf)

##### Caffe

- [Caffe: Convolutional Architecture for Fast Feature Embedding](https://arxiv.org/pdf/1408.5093v1.pdf)
- [Using GPI-2 for Distributed Memory Paralleliziation of the Caffe Toolbox to Speed up Deep Neural Network Training](https://arxiv.org/pdf/1706.00095v2.pdf)
- [A Deep Convolutional Auto-Encoder with Pooling - Unpooling Layers in Caffe](https://arxiv.org/ftp/arxiv/papers/1701/1701.04949.pdf)
- [Creation of a Deep Convolutional Auto-Encoder in Caffe](https://arxiv.org/ftp/arxiv/papers/1512/1512.01596.pdf)
- [Caffe con Troll: Shallow Ideas to Speed Up Deep Learning](https://arxiv.org/pdf/1504.04343v2.pdf)
- [Rx-Caffe: Framework for evaluating and training Deep Neural Networks on Resistive Crossbars](https://arxiv.org/pdf/1809.00072v1.pdf)
- [Restructuring Batch Normalization to Accelerate CNN Training](https://arxiv.org/pdf/1807.01702v1.pdf)
- [μ-cuDNN: Accelerating Deep Learning Frameworks with Micro-Batching](https://arxiv.org/pdf/1804.04806v1.pdf)
- [Barista - a Graphical Tool for Designing and Training Deep Neural Networks](https://arxiv.org/pdf/1802.04626v1.pdf)
- [SparCE: Sparsity aware General Purpose Core Extensions to Accelerate Deep Neural Networks](https://arxiv.org/pdf/1711.06315v2.pdf)
- [ADaPTION: Toolbox and Benchmark for Training Convolutional Neural Networks with Reduced Numerical Precision Weights and Activation](https://arxiv.org/pdf/1711.04713v1.pdf)
- [DLPaper2Code: Auto-generation of Code from Deep Learning Research Papers](https://arxiv.org/pdf/1711.03543v1.pdf)
- **[DeepDSL: A Compilation-based Domain-Specific Language for Deep Learning](https://arxiv.org/pdf/1701.02284v1.pdf)**
- [Deep Convolutional Neural Network Design Patterns](https://arxiv.org/pdf/1611.00847v3.pdf)
- [Caffeinated FPGAs: FPGA Framework For Convolutional Neural Networks](https://arxiv.org/abs/1609.09671v1)
- [UnrealCV: Connecting Computer Vision to Unreal Engine](https://arxiv.org/pdf/1609.01326v1.pdf)
- [SparkNet: Training Deep Networks in Spark](https://arxiv.org/pdf/1511.06051v4.pdf)
- [Expresso : A user-friendly GUI for Designing, Training and Exploring Convolutional Neural Networks](https://arxiv.org/abs/1505.06605v2)
- [Efficient Convolutional Neural Networks for Pixelwise Classification on Heterogeneous Hardware Systems](https://arxiv.org/pdf/1509.03371v1.pdf)
- [cuDNN: Efficient Primitives for Deep Learning](https://arxiv.org/pdf/1410.0759v3.pdf)



##### Theano

- [Theano-based Large-Scale Visual Recognition with Multiple GPUs](https://arxiv.org/pdf/1412.2302v4.pdf)
- [Theano: A Python framework for fast computation of mathematical expressions](https://arxiv.org/pdf/1605.02688v1.pdf)
- [Synkhronos: a Multi-GPU Theano Extension for Data Parallelism](https://arxiv.org/abs/1710.04162v1)
- [Theano: new features and speed improvements](https://arxiv.org/pdf/1211.5590v1.pdf)
- [Improving the Expressiveness of Deep Learning Frameworks with Recursion](https://arxiv.org/pdf/1809.00832v1.pdf)
- [The implementation of a Deep Recurrent Neural Network Language Model on a Xilinx FPGA](https://arxiv.org/ftp/arxiv/papers/1710/1710.10296.pdf)
- [TensorLog: Deep Learning Meets Probabilistic DBs](https://arxiv.org/pdf/1707.05390v1.pdf)
- [THUMT: An Open Source Toolkit for Neural Machine Translation](https://arxiv.org/pdf/1706.06415v1.pdf)
- [NMTPY: A Flexible Toolkit for Advanced Neural Machine Translation Systems](https://arxiv.org/pdf/1706.00457v1.pdf)
- [DyNet: The Dynamic Neural Network Toolkit](https://arxiv.org/pdf/1701.03980v1.pdf)
- [On-the-fly Operation Batching
in Dynamic Computation Graphs](https://arxiv.org/pdf/1705.07860v1.pdf)
- [TheanoLM - An Extensible Toolkit for Neural Network Language Modeling](https://arxiv.org/pdf/1605.00942v2.pdf)
- [Exploring the power of GPU's for training Polyglot language models](https://arxiv.org/abs/1404.1521v3)
- [Kaldi+PDNN: Building DNN-based ASR Systems with Kaldi and PDNN](https://arxiv.org/ftp/arxiv/papers/1401/1401.6984.pdf)


##### Mxnet

- [MXNet: A Flexible and Efficient Machine Learning Library for Heterogeneous Distributed Systems](https://arxiv.org/pdf/1512.01274v1.pdf)
- [BMXNet: An Open-Source Binary Neural Network Implementation Based on MXNet](https://arxiv.org/pdf/1705.09864v1.pdf)
- [Efficient Embedding of MPI Collectives in MXNET DAGs for scaling Deep Learning](https://arxiv.org/pdf/1802.06949v1.pdf)
- [MXNET-MPI: Embedding MPI parallelism in Parameter Server Task Model for scaling Deep Learning](https://arxiv.org/pdf/1801.03855v1.pdf)
- [Tensor Comprehensions: Framework-Agnostic High-Performance Machine Learning Abstractions](https://arxiv.org/pdf/1802.04730v3.pdf)


##### Chainer

- [ChainerCV: a Library for Deep Learning in Computer Vision](https://arxiv.org/pdf/1708.08169.pdf)

##### DL4J

- [An Exploration of Approaches to Integrating Neural Reranking Models in Multi-Stage Ranking Architectures](https://arxiv.org/abs/1707.08275)
- [DLL: A Blazing Fast Deep Neural Network Library](https://arxiv.org/pdf/1804.04512.pdf)


##### Keras

- [An MPI-Based Python Framework for Distributed Training with Keras](https://arxiv.org/abs/1712.05878v1)
- [Kapre: On-GPU Audio Preprocessing Layers for a Quick Implementation of Deep Neural Network Models with Keras](https://arxiv.org/pdf/1706.05781v1.pdf)
- [NMT-Keras: a Very Flexible Toolkit with a Focus on Interactive NMT and Online Learning](https://arxiv.org/pdf/1807.03096v3.pdf)
- [MARVIN: An Open Machine Learning Corpus and Environment for Automated Machine Learning Primitive Annotation and Execution](https://arxiv.org/pdf/1808.03753v1.pdf)
- [Tutorial on Keras](http://crcv.ucf.edu/courses/CAP6412/Spring2018/KerasTutorial.pdf)


##### Tensorflow

- [LeFlow: Enabling Flexible FPGA High-Level Synthesis of Tensorflow Deep Neural Networks](https://arxiv.org/ftp/arxiv/papers/1807/1807.05317.pdf)
- [TFLMS: Large Model Support in TensorFlow by Graph Rewriting](https://arxiv.org/pdf/1807.02037v1.pdf)
- [Horovod: fast and easy distributed deep learning in TensorFlow](https://arxiv.org/pdf/1802.05799v3.pdf)
- [TensorFlow Distributions](https://arxiv.org/pdf/1711.10604v1.pdf)
- [GPflowOpt: A Bayesian Optimization Library using TensorFlow](https://arxiv.org/abs/1711.03845v1)
- [Scalable Planning with Tensorflow for Hybrid Nonlinear Domains](https://arxiv.org/pdf/1704.07511v3.pdf)
- [TF Boosted Trees: A scalable TensorFlow based framework for gradient boosting](https://arxiv.org/pdf/1710.11555v1.pdf)
- [TensorFlow Agents: Efficient Batched Reinforcement Learning in TensorFlow](https://arxiv.org/pdf/1709.02878v1.pdf)
- [XES Tensorflow - Process Prediction using the Tensorflow Deep-Learning Framework](https://arxiv.org/pdf/1705.01507v1.pdf)
- [Should I use TensorFlow](https://arxiv.org/pdf/1611.08903v1.pdf)
- [GPflow: A Gaussian process library using TensorFlow](https://arxiv.org/pdf/1610.08733v1.pdf)
- [A Tour of TensorFlow](https://arxiv.org/pdf/1610.01178v1.pdf)
- [TensorFlow: A system for large-scale machine learning](https://arxiv.org/pdf/1605.08695v2.pdf)
- [TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems](https://arxiv.org/pdf/1603.04467v2.pdf)
- [M-PACT: Michigan Platform for Activity Classification in Tensorflow](https://arxiv.org/pdf/1804.05879v2.pdf)
- [TensorFlow Estimators: Managing Simplicity vs. Flexibility in High-Level Machine Learning Frameworks](https://arxiv.org/pdf/1708.02637v1.pdf)
- [Neural Networks for Beginners. A fast implementation in Matlab, Torch, TensorFlow](https://arxiv.org/pdf/1703.05298v2.pdf)
- [DeepTracker: Visualizing the Training Process of Convolutional Neural Networks](https://arxiv.org/pdf/1808.08531v1.pdf)
- [CosmoFlow: Using Deep Learning to Learn the Universe at Scale](https://arxiv.org/pdf/1808.04728v1.pdf)
- [Calamari - A High-Performance Tensorflow-based Deep Learning Package for Optical Character Recognition](https://arxiv.org/ftp/arxiv/papers/1807/1807.02004.pdf)
- [In situ TensorView: In situ Visualization of Convolutional Neural Networks](https://arxiv.org/pdf/1806.07382v1.pdf)
- [Far-HO: A Bilevel Programming Package for Hyperparameter Optimization and Meta-Learning](https://arxiv.org/pdf/1806.04941v1.pdf)
- [geomstats: a Python Package for Riemannian Geometry in Machine Learning](https://arxiv.org/pdf/1805.08308v1.pdf)
- [Unifying Data, Model and Hybrid Parallelism in Deep Learning via Tensor Tiling](https://arxiv.org/pdf/1805.04170v1.pdf)
- [Dynamic Control Flow in Large-Scale Machine Learning](https://arxiv.org/pdf/1805.01772v1.pdf)
- [Deep Learning on Key Performance Indicators for Predictive Maintenance in SAP HANA](https://arxiv.org/abs/1804.05497v1)
- [TBD: Benchmarking and Analyzing Deep Neural
Network Training](https://arxiv.org/pdf/1803.06905v2.pdf)
- [TF.Learn: TensorFlow's High-level Module for Distributed Machine Learning](https://arxiv.org/pdf/1612.04251v1.pdf)
- [Akid: A Library for Neural Network Research and Production from a Dataism Approach](https://arxiv.org/pdf/1701.00609v1.pdf)
- [Edward: A library for probabilistic modeling, inference, and criticism](https://arxiv.org/pdf/1610.09787v3.pdf)
- [A Design Methodology for Efficient Implementation of Deconvolutional Neural Networks on an FPGA](https://arxiv.org/pdf/1705.02583v1.pdf)
- [Picasso: A Modular Framework for Visualizing the Learning Process of Neural Network Image Classifiers](https://arxiv.org/ftp/arxiv/papers/1705/1705.05627.pdf)
- [huSuan: A Library for Bayesian Deep Learning](https://arxiv.org/pdf/1709.05870v1.pdf)
- [EDEN: Evolutionary Deep Networks for Efficient Machine Learning](https://arxiv.org/pdf/1709.09161v1.pdf)
- [TensorQuant - A Simulation Toolbox for Deep Neural Network Quantization](https://arxiv.org/pdf/1710.05758v1.pdf)
- [NiftyNet: a deep-learning platform for medical imaging](https://arxiv.org/pdf/1709.03485v2.pdf)
- [Tangent: Automatic Differentiation Using Source Code Transformation in Python](https://arxiv.org/pdf/1711.02712v1.pdf)
- [DeePMD-kit: A deep learning package for many-body potential energy representation and molecular dynamics](https://arxiv.org/pdf/1712.03641v2.pdf)
- [DeepThin: A Self-Compressing Library for Deep Neural Networks](https://arxiv.org/pdf/1802.06944v1.pdf)
- [Communication Scheduling as a First-Class Citizen in Distributed Machine Learning Systems](https://arxiv.org/pdf/1803.03288v1.pdf)
- [Comparing Fixed and Adaptive Computation Time for Recurrent Neural Networks](https://arxiv.org/pdf/1803.08165v1.pdf)
- [Live Target Detection with Deep Learning Neural Network and Unmanned Aerial Vehicle on Android Mobile Device](https://arxiv.org/ftp/arxiv/papers/1803/1803.07015.pdf)
- [Latency and Throughput Characterization of Convolutional Neural Networks for Mobile Computer Vision](https://arxiv.org/pdf/1803.09492v1.pdf)
- [Demystifying Differentiable Programming: Shift/Reset the Penultimate Backpropagator](https://arxiv.org/pdf/1803.10228v1.pdf)
- [sgmcmc: An R Package for Stochastic Gradient Markov Chain Monte Carlo](https://arxiv.org/pdf/1710.00578v3.pdf)

##### Gym

- [OpenAI Gym](https://arxiv.org/pdf/1606.01540.pdf)
- [MDP environments for the OpenAI Gym](https://arxiv.org/pdf/1709.09069.pdf)
- [Game Playing with Deep Reinforcement Learning
using OpenAi Gym](http://web.stanford.edu/~chuchro3/projects/openaigym/OpenAiGymDeepLearningPoster.pdf)
- [Closing the loop between neural network simulators and the OpenAI Gym](https://arxiv.org/pdf/1709.05650.pdf)
- [Game Playing with Deep Q-Learning using OpenAI Gym](http://cs231n.stanford.edu/reports/2017/pdfs/616.pdf)

##### Deepmind

- [DeepMind Control Suite](https://arxiv.org/pdf/1801.00690v1.pdf)


-----------------
#####  Reference

- [case study: ml/dl frameworks/libraries(architectural overview)](https://github.com/gopala-kr/10-weeks/tree/master/Projects-Blogs/06-ml-dl-frameworks)
- [Stanford from 1996: Data Mining using MLC++
A Machine Learning Library in C++](http://robotics.stanford.edu/~ronnyk/mlc96.pdf)
- [Cornell: Machine Learning
Frameworks](http://www.cs.cornell.edu/courses/cs6787/2017fa/Lecture12.pdf)
- [On-the-fly Operation Batching
in Dynamic Computation Graphs](https://arxiv.org/pdf/1705.07860.pdf)
- [Discover how this native Python package redesigns and implements
Torch in Python
](https://www.ibm.com/developerworks/library/cc-get-started-pytorch/cc-get-started-pytorch-pdf.pdf)
- [Anatomy of machine learning algorithm
implementations in MPI, Spark, and Flink](http://dsc.soic.indiana.edu/publications/Anatomy_of_machine_learning_algorithm_in_mpi_spark_and_flink.pdf)
- [Benchmarking Automatic Machine Learning Frameworks](https://arxiv.org/pdf/1808.06492v1.pdf)
- [TensorFlow Estimators: Managing Simplicity vs. Flexibility in High-Level Machine Learning Frameworks](https://arxiv.org/pdf/1708.02637v1.pdf)
- [LSTM Benchmarks for Deep Learning Frameworks](https://arxiv.org/pdf/1806.01818v1.pdf)
- [DLFrameworks](https://project.inria.fr/deeplearning/files/2016/05/DLFrameworks.pdf)
- [BigDL: A Distributed Deep Learning
Framework for Big Data](https://arxiv.org/ftp/arxiv/papers/1804/1804.05839.pdf)
- [Abstractions and Frameworks
for Deep Learning:
a Discussion](https://perso.univ-st-etienne.fr/fod07375/Workshop/assets/slides/Presentation_Emonet.pdf)
- [Deep Learning with Theano, Torch, Caffe, Tensorflow, and
Deeplearning4J: Which One is the Best in Speed and Accuracy?](http://elib.bsu.by/bitstream/123456789/158561/1/Kovalev_Kalinovsky_Kovalev.pdf)
- [MLlib: Scalable Machine Learning on Spark](https://stanford.edu/~rezab/sparkworkshop/slides/xiangrui.pdf)
- [Visualizing Dataflow Graphs of
Deep Learning Models in TensorFlow](https://idl.cs.washington.edu/files/2018-TensorFlowGraph-VAST.pdf)
- [Deep Learning with Python and PyTorch](https://www.edx.org/course/deep-learning-with-python-and-pytorch)

------------
---------------------

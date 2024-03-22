# Deep Learning Driven Approach for Handwritten Chinese Character Classification
Code accompaniment for the research work submitted by Sparcus Technologies Limited on Deep Learning-Driven Approach for Handwritten Chinese Character Classification. 
Preprint can be found here: *not available yet*

# Abstract
Handwritten character recognition (HCR) is a challenging problem for machine learning researchers. Unlike printed text data, handwritten character datasets have more variation due to human-introduced bias. With numerous unique character classes present, some data, such as Logographic Scripts or Sino-Korean character sequences, bring new complications to the HCR problem. The classification task on such datasets requires the model to learn high-complexity details of the images that share similar features. With recent advances in computational resource availability and further computer vision theory development, some research teams have effectively addressed the arising challenges. Although known for achieving high accuracy while keeping the number of parameters small, many common approaches are still not generalizable and use dataset-specific solutions to achieve better results. Due to complex structure, existing methods frequently prevent the solutions from gaining popularity. This paper proposes a highly scalable approach for detailed character image classification by introducing the model architecture, data preprocessing steps, and testing design instructions. We also perform experiments to compare the performance of our method with that of existing ones to show the improvements achieved.

# Data
CASIA-HWDB Dataset, Chinese Academy of Sciences: https://nlpr.ia.ac.cn/databases/handwriting/Home.html
Benchmarks and papers: https://paperswithcode.com/dataset/casia-hwdb

 # Repository Structure
_trainer1.py: Contains the code for model 1 training.
_trainer2.py: Contains the code for model 2 training.
_trainer3.py: Contains the code for model 3 training.
_predictor1.py: Contains the code for model 1 prediction with multicrop.
_predictor2.py: Contains the code for model 2 prediction with multicrop.
_predictor3.py: Contains the code for model 3 prediction with multicrop.
_predictor_finalizer.py: Contains the code for performing prediction ensembling at test time.
README.md: This file, containing an overview of the repository.
LICENSE: Apache 2.0 License.

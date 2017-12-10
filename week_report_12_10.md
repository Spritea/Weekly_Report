# Weekly Report
<sub>**Number: 3   
Adviser: Prof. Yang Wen  
Student: Cheng Wensheng   
Period: 2017.12.4-2017.12.10**</sub>
## Recap
This week I mainly spend time on paper *Local Convolutional Features with Unsupervised Training for Image Retrieval* (ICCV 2015) and test the MATLAB code provided by author.
## About the article
* This article proposed a family of descriptors, called Patch-CKN. The descriptors adapt the Convolutional Kernal Network(CKN), an unsupervised framework to learn convolutional architevtures. Then they compare some current deep convolutional approaches with Patch-CKN for both patch and image retrieval.
* To use Hessian-Affine detector, they introduce a new dataset, called Rome 16K. It consists of 16,179 images of locations in Rome. It's also partitioned in 66 "bundles", each one containing a set of viewpoint of a given location in Rome.
* They conduct experiments of patch retrieval and image retrieval. Patch-CKN get comparative results with current deep convolutional approaches in both ways. This shows the potential ability of deep unsupervised network, like CKN.
## About the code
* The author provided MATLAB code with this article. He implements 2 feature extraction ways, including SIFT and Patch-CKN. SIFT is used as the baseline. SIFT got 87.87% average precision, while Patch-CKN got 91.68% in patch retrieval task.
* About Patch-CKN, he mainly uses CKN code from the original author of CKN in paper *Convolutional Kernal Networks* (NIPS 2014). And I'm trying to figure out whether it's possible for us to use this in our own work.
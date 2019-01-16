The EMNIST Dataset

Authors
-------
Gregory Cohen, Saeed Afshar, Jonathan Tapson, and Andre van Schaik
The MARCS Institute for Brain, Behaviour and Development
Western Sydney University
Penrith, Australia 2751

Email: g.cohen@westernsydney.edu.au

What is it?
-----------
The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19 (https://www.nist.gov/srd/nist-special-database-19) and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset (http://yann.lecun.com/exdb/mnist/). Further information on the dataset contents and conversion process can be found in the paper available at https://arxiv.org/abs/1702.05373v1.

Formats
-------
The dataset is provided in two file formats. Both versions of the dataset contain identical information, and are provided entirely for the sake of convenience. The first dataset is provided in a Matlab format that is accessible through both Matlab and Python (using the scipy.io.loadmat function). The second version of the dataset is provided in the same binary format as the original MNIST dataset as outlined in http://yann.lecun.com/exdb/mnist/

Dataset Summary
---------------
There are six different splits provided in this dataset. A short summary of the dataset is provided below:

EMNIST ByClass:		814,255 characters. 62 unbalanced classes.
EMNIST ByMerge: 	814,255 characters. 47 unbalanced classes.
EMNIST Balanced:	131,600 characters. 47 balanced classes.
EMNIST Letters:		145,600 characters. 26 balanced classes.
EMNIST Digits:		280,000 characters. 10 balanced classes.
EMNIST MNIST:		 70,000 characters. 10 balanced classes.

The full complement of the NIST Special Database 19 is available in the ByClass and ByMerge splits. The EMNIST Balanced dataset contains a set of characters with an equal number of samples per class. The EMNIST Letters dataset merges a balanced set of the uppercase and lowercase letters into a single 26-class task. The EMNIST Digits and EMNIST MNIST dataset provide balanced handwritten digit datasets directly compatible with the original MNIST dataset.

Please refer to the EMNIST paper (available at https://arxiv.org/abs/1702.05373v1) for further details of the dataset structure.

How to cite
-----------
Please cite the following paper when using or referencing the dataset:

Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters. Retrieved from http://arxiv.org/abs/1702.05373

Files
-----
The dataset consists of the following files:

.
+-- gzip.zip
   +-- emnist-balanced-mapping.txt
   +-- emnist-balanced-test-images-idx3-ubyte.gz
   +-- emnist-balanced-test-labels-idx1-ubyte.gz
   +-- emnist-balanced-train-images-idx3-ubyte.gz
   +-- emnist-balanced-train-labels-idx1-ubyte.gz
   +-- emnist-byclass-mapping.txt
   +-- emnist-byclass-test-images-idx3-ubyte.gz
   +-- emnist-byclass-test-labels-idx1-ubyte.gz
   +-- emnist-byclass-train-images-idx3-ubyte.gz
   +-- emnist-byclass-train-labels-idx1-ubyte.gz
   +-- emnist-bymerge-mapping.txt
   +-- emnist-bymerge-test-images-idx3-ubyte.gz
   +-- emnist-bymerge-test-labels-idx1-ubyte.gz
   +-- emnist-bymerge-train-images-idx3-ubyte.gz
   +-- emnist-bymerge-train-labels-idx1-ubyte.gz
   +-- emnist-digits-mapping.txt
   +-- emnist-digits-test-images-idx3-ubyte.gz
   +-- emnist-digits-test-labels-idx1-ubyte.gz
   +-- emnist-digits-train-images-idx3-ubyte.gz
   +-- emnist-digits-train-labels-idx1-ubyte.gz
   +-- emnist-letters-mapping.txt
   +-- emnist-letters-test-images-idx3-ubyte.gz
   +-- emnist-letters-test-labels-idx1-ubyte.gz
   +-- emnist-letters-train-images-idx3-ubyte.gz
   +-- emnist-letters-train-labels-idx1-ubyte.gz
   +-- emnist-mnist-mapping.txt
   +-- emnist-mnist-test-images-idx3-ubyte.gz
   +-- emnist-mnist-test-labels-idx1-ubyte.gz
   +-- emnist-mnist-train-images-idx3-ubyte.gz
   +-- emnist-mnist-train-labels-idx1-ubyte.gz
+-- matlab.zip
    +-- emnist-balanced.mat
    +-- emnist-byclass.mat
    +-- emnist-bymerge.mat
    +-- emnist-digits.mat
    +-- emnist-letters.mat
    +-- emnist-mnist.mat
+-- Readme.txt




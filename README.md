### Using a neural network as a descriptor for keypoint extraction ( Comparing NN vs SIFT)

<b>Objective</b>

Compare keypoint descriptors and matches from 2 images of the same scene with different perpesctives using:

-SIFT descriptor and keypoint extractor + BF KNN Matcher

-NN Method 1: Neural Network (maxpool layers) descriptor + Keypoints extractor + BF KNN Matcher

-NN Method 2: Neural Network (maxpool layers) descriptor + Keypoints extracted from Sift + BF KNN Matcher

<b>Technologies and Tools</b>

Python, Computer Vision, Machine Learning

Original images:

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/32aa97ac-6f01-41a7-b0fb-6172d3601409)

Descriptors from NN

The descriptors represents the squares from the images bellow. Initially there are 3 descriptors that are combined into one descriptors

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/b94760d5-256c-4104-b7f3-ae946de7db9f)

Results

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/c4e6d09e-7e0a-4602-977a-c85971bcc973)

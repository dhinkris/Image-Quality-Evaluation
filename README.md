# Image-Quality-Evaluation
In multi-center clinical trials, attribute-based quality evaluation is one of the quality control proceedures to assess, normalize and standardize the diagnostic information contained in medical image data from different imaging system manufacturers, different clinical trial sites and different acquisition protocols before they are fed to automated image analysis systems.
This matlcode code is the implementation of objective quality evaluation for images used in clinical research reported in
Image Quality Evaluation in Clinical Research: A Case Study on Brain and Cardiac MRI Images in Multi-Center Clinical Trials by
M. Osadebey, M. Pedersen, D. Arnold and Katrina Wendel-Mitoraj. The report was accepted for publication in IEEE Journal of Translational Engineering in Health and Medicine (IJTEHM).
The algorithm predicts the quality index of an images using two attributes, namely, local contrast and texture contrast. The total quality score is the weighted sum of the local contrast and the total contrast quality scores. 
There are seven steps The alforithm starts with pixel intensity level rescaling followed by the extraction of froeground pixels and computation of image moments of the test image. The fourth step is the extraction of local contrast features (LCF) from the test image. In the fifth step, the image moments of the LCF image are computed. In the sixth and seventh steps the lightness contrast quality score and the texture contrast quality score are computed the cumulative normal distribution functions of the mean and variance of the LCF image, respectively. 

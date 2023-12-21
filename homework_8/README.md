# Monte Carlo Simulation and Active Learning with SVM

Datasets:
1. Diagnostic Wisconsin Breast Cancer Database 
- URL: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

- Dataset Description:
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree.  Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

- Dataset Features:
	- ID number
	- Diagnosis (M = malignant, B = benign)
	- (3-32) Ten real-valued features are computed for each cell nucleus:
 		- radius (mean of distances from center to points on the perimeter)
		- texture (standard deviation of gray-scale values)
		- perimeter
		- area
		- smoothness (local variation in radius lengths)
		- compactness (perimeter^2 / area - 1.0)
		- concavity (severity of concave portions of the contour)
		- concave points (number of concave portions of the contour)
		- symmetry 
		- fractal dimension ("coastline approximation" - 1)

- Citation: Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.

- Models: Supervisied, Semi-Supervisied, Unsupervisied learning

2. Banknote Authentication
- URL: https://archive.ics.uci.edu/dataset/267/banknote+authentication

- Dataset Description: Data were extracted from images that were taken from genuine and forged banknote-like specimens.  For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

- Dataset Features:
    - variance of Wavelet Transformed image (continuous) 
    - skewness of Wavelet Transformed image (continuous)
    - curtosis of Wavelet Transformed image (continuous)
    - entropy of image (continuous)
    - class (integer) 

- Citation: Lohweg,Volker. (2013). banknote authentication. UCI Machine Learning Repository. https://doi.org/10.24432/C55P57.

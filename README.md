# Novel Reconstruction Algorithms for Magnetic Localization for Capsule Endoscopy 
Digestive tract issues account for millions of cases yearly. However, doctors lack a reliable localization method, which forces an attempted colonoscopy, which is often unneeded, expensive, and has adverse side effects. To combat this, reconstruction algorithms for magnetic localization of a “smart pill” were investigated. The pill is intended, when swallowed, to non-invasively collect information as it passes through the digestive tract. We model and track this pill by gathering magnetic field data of it in three dimensions amongst various positions in space. Deep Neural Networks, Tree Algorithms, and Support Vector Regressions were employed to find the most optimal reconstruction algorithm which predicts the position (x,y,z) in space, showing exactly where the health problem lies without needing colonoscopy.

The reconstruction algorithms takes in the magnetic field data gathered in HFSS, and then outputs the angular position(x,y,z). 
#Files
- 2x2-xxx.csv data files for the 3d case. each file is combined readings for a single coil in simulation
- MagVert.csv - 1d case data
- 3d_final_copy_kethana(1).ipynb - notebook with all hypertuned algorithms and metrics of analysis(i.e. MSE, plot)

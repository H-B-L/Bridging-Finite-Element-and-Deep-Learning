# Static Stress Prediction 
## Bridging finite element and deep learning: High-resolution stress distribution prediction in structural components

### [Link to paper](https://link.springer.com/article/10.1007/s11709-022-0882-5)

#### Authors: [Hamed Bolandi](https://bolandih.github.io/), Xuyang Li, Talal Salem Vishnu Boddeti, Nizar Lajnef
### Abstract
Finite-element analysis (FEA) for structures has been broadly used to conduct stress analysis of various
civil and mechanical engineering structures. Conventional methods, such as FEA, provide high fidelity results but require
the solution of large linear systems that can be computationally intensive. Instead, Deep Learning (DL) techniques can
generate results significantly faster than conventional run-time analysis. This can prove extremely valuable in real-time
structural assessment applications. Our proposed method uses deep neural networks in the form of convolutional neural
networks (CNN) to bypass the FEA and predict high-resolution stress distributions on loaded steel plates with variable
loading and boundary conditions. The CNN was designed and trained to use the geometry, boundary conditions, and load
as input to predict the stress contours. The proposed technique’s performance was compared to finite-element simulations
using a partial differential equation (PDE) solver. The trained DL model can predict the stress distributions with a mean
absolute error of 0.9% and an absolute peak error of 0.46% for the von Mises stress distribution. This study shows the
feasibility and potential of using DL techniques to bypass FEA for stress analysis applications.

### Overview figure
![1st paper](https://github.com/bolandih/bolandih.github.io/blob/gh-pages/Images/Overview-1st%20paper.png)

### Predicted stress distribution and corresponding inputs with different loads and boundary conditions scenarios
![comparision](https://github.com/bolandih/bolandih.github.io/blob/gh-pages/Images/1st-paper-comparision.png)
(a) geometry, (b) boundary conditions, (c) horizontal load (d) vertical load; (e) ground truth, (f) predicted stress distribution
(unit: MPa)

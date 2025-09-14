This repository is for project that reproduce the result and derive equitions of article: “Tipping Points of Space Debris in Low Earth Orbit” (doi:10.5334/ijc.1275) using Python

Quick Veiw:  
This article analyzes the behavior of a nonlinear system governing the quantity of space debris and its potential impact on space exploration. By establishing differential equations, the growth trend of space debris is examined. The study also explores the bifurcation phenomena and stability of the critical points of space debris quantity s under the influence of various external parameters. Furthermore, the modeling predicts the possible time frame for the occurrence of the Kessler Syndrome in the future.

Assumptions:  
The model in this paper constructs a nonlinear differential equation, where the annual increment of space debris is expressed as the first derivative of s with respect to t. One key assumption is that the collision frequency between particles is proportional to the square of the particle density in space. Additionally, the rates of debris being actively or passively removed and debris spontaneously generated due to events like explosions are both assumed to be proportional to the quantity of space debris. These factors are combined into a single parameter. Furthermore, it is assumed that future space launch missions will either approach a constant value or maintain equilibrium with the loss rate, allowing the input to be defined as a linear equation. When predicting the time for the occurrence of the Kessler Syndrome, it is defined as the point when the mathematical expectation of collisions caused by spacecraft launched within a year equals one.

![](Figures/SpaceDebris.png)  

Bifurcation Exploring:  
![](Figures/fig3a.png) ![](Figures/fig3b.png)

Kessler Syndrome Prediction under different condition:  

![](Figures/fig5a.png) ![](Figures/fig5b.png)

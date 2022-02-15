# Ordinary-Differential-Equation---Frozen

Overview
---
We will be modelling the love of Anna and Elsa of each other from Frozen using ordinary differential equations(ODE). [Frozen](https://en.wikipedia.org/wiki/Frozen_(2013_film)) is a popular children show from Disney. Using ODE, we would be forming a differential equation that models the love between the sisters following [Rinaldi's Laura-Petrarch model](https://www.researchgate.net/publication/4359651_Love_emotions_between_Laura_and_Petrarca_-_an_approach_by_mathematics_and_System_Dynamics) and certain time points to model their love in the entire movie. Then, we will fit parameters into the ODEs using particle swarm optimization.

![ParticleSwarmArrowsAnimation](https://user-images.githubusercontent.com/97843966/154016363-2c7bd00f-f23a-4fc5-9de8-eface1c877b9.gif)

Data Collection
---
Data collection is based of our subjective opinion of their love for one another. We also included Elsa's fear of her powers hurting her sister. There were a total of 10 critical  points in the movie and 10 observations were collected.

Modelling
---
We modelled the data following Rinaldi's paper, but tweaked certain coefficients of variables to better suit the observations we made during data collection. Utitlizing Particle swarm optimization and the error function of the least of sum squares, we would result with the following equations, where A(t) refers to Anna's feelings towards Elsa, E(t) is Elsa's feelings towards Anna and F(t) is Elsa's fear of her powers.

![image](https://user-images.githubusercontent.com/97843966/154015218-894f0201-5edb-422b-935b-ec23dfad878f.png)

Mathematical Analysis
---
We find the critical points of our 3 given equations by equating them to 0. Using Stability Analysis, we can identify the stability of the critical points based on their eigenvalues and find that points (6.99,4.73,9.07) is a stable spiral sink that matches the 3D plot of our ODE equations below.

![3D phase plot](https://user-images.githubusercontent.com/97843966/154017054-3e003ce0-39aa-462f-8846-d3555ccc7e63.png)

*Done in May 2021
Credits: Ang Kian Hao, Julianne Thatcher Low, Loke Rui Xuan, Seng Swee Keng, Wisely Neo*

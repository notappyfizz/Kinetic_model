# Kinetic Model for fatty acid synthesis and glycolysis in yeast
## What is kinetic modelling?
Kinetic modelling is a powerful computational tool employed in the study of biochemical systems, offering a dynamic perspective on the intricate processes governing cellular functions. At its core, kinetic modelling involves the mathematical representation of biological reactions, capturing the rates at which molecules interact and transform within a system. Kinetic ordinary differential equation (ODE) models have been traditionally used for dynamic optimization of culture conditions in a bioreactor. Regardless of the type of the models, the process of model building is typically iterative, combining wet-lab experiments and in-silico analysis and optimization. Kinetic models provide a quantitative framework to understand the temporal evolution of complex biological networks. This approach allows researchers to simulate and analyse the behaviour of biochemical pathways, providing insights into the dynamics of cellular processes.

## What this model contains
This model contains a file for a kinetic model for glycolysis, followed by fatty acid synthesis in yeast. This was made for my team's iGEM project, 2023. My team is IISER-Pune-India. This model was made in order to calculate the theoretical yield of palmitic acid, the first key product in the pathway for our project, which involves producing sustainable aviation fuel in yeast, using synthetic biology.
The data in this model has been obtained from BRENDA, an enzyme database. While my team worked on the yeast <i>Yarrowia lipolytica</i>, due to lack of availability of its data, I used data derived mostly from its close relative, <i>Saccaromyces cerevisiae</i> and a few parameters from <i>Homo sapiens</i>.
This model aprroximated majority of the kinetics to single substrate, linear, Michaelis Menten rate laws, and some reactions use the Mass-Action law.
The purpose of building this model was to optimise the production of fatty acids, to lay the groundwork for further experimentation for producing sustainable aviation biofuel in our lipogenic yeast. I used the theoretical yield obtained from this model to compute a cost estimate for our production of the biofuel. Cost analysis was necessary for the iGEM project in order to find how the price compares to that of conventional fuel.

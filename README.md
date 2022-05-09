![](3I_cover.png)

Wouldn’t it be nice to push a button and have all the Machine Learning (ML) data you want at your fingertips? In theory, that is the promise of synthetic data: to solve one of the biggest challenges of using ML, the collecting and labeling of relevant data, simply by generating data in a simulated environment. Yet, to achieve this goal we must first quantify the realism and relevance of our synthetic data, even before using that data to train a model. To this end, we came up with three criteria to guide the creation of synthetic data. They are collectively referred to as “The Three I’s”: Indistinguishability, Information Richness, and Intentionality. 

# Indistinguishability
[<img align="right" src="Indistinguishability.png" width="200"/>](Indistinguishability.png)
The first step towards good synthetic data is replicating reality. Therefore, our synthetic data should strive to be indistinguishable from a real-world sample. It is not supposed to be identical, but it should be impossible to determine if any given distribution of data is synthetic or real. In other words, the real-world samples should completely blend in with the synthetic ones. The higher our Indistinguishability rating, the more precisely our data will capture a specific scenario.
<br/>
<br/>
# Information Richness
[<img align="left" src="Information_Richness.png" width="200"/>](Information_Richness.png)
We don’t want to create a diluted data set with redundant information. So synthetic data needs to be generating new information. The data should provide, for example, new perspectives, new angles, new features, etc., that fill in the gaps of the real data or expand the data domain. If Indistinguishability allows for high precision, Information Richness allows us to accurately broaden the horizons of what our data can capture. 
<br/>
<br/>
<br/>
<br/>
# Intentionality
[<img align="right" src="Intentionality.png" width="200"/>](Intentionality.png)
In order to create a robust ML model, a decision is made on the intended domain of operation. This will cover certain edge cases and variations but exclude others. Through Intentional data, we define the shape of our domain of operation. The core of this shape represents Indistinguishability, where our real and synthetic samples are mixed together. Information Richness dilates away from this core. Intentionality represents the ability to control exactly what Information Richness is introduced.
<br/>
<br/>
<br/>

# Environment and Software
### Structure

[Indistinguishability/](Indistinguishability/) - Example calculations of Indistinguishability score.

[Information_Richness/](Information_Richness/) -  Example calculations of Information Richness.

[Intentionality/](Intentionality/) - Example of how to outline domain and calculate intentionality. 

# coastal-seasonal-prediction
Statistical coastal seasonal prediction of bottom temperature over the Northeast U.S. continental shelf

Target/Predictand - bottom temperature of subregions on the NEUS shelf

    These subregions are determined via a k-means clustering method
    Users could choose their own target regions for statistical prediction

Predictors considered in this analysis:

    1. Local persistence (or historical bottom temperature in this case)
    2. Upstream or nearby impact, presumably through advection
    3. Large-scale atmospheric or oceanic processes, 
       indicated by corresponding indices (e.g., the Gulf Stream Indices, NAO Index, etc.)
       
Prediction Models, according to those predictors mentioned above：

    1. Local Persistence Model
    2. Persistence-Advection Model
    3. Gulf Stream Index Model and NAO Index Model
    4. Persistence-Advection with an Index Model

Prediction Method:


# AnyKnee
The name 'AnyKnee' plays on the 'Any' terminology of the AnyBody modeling language. 

AnyKnee is a stand alone model that introduces two types of knee joints that can be subsituted in for the generic hinge model available in AnyBody. These joints include: a scalable moving-axis tibiofemoral joint and a hinge tibiofemoral joint based off femoral condyle surface fits. These two examples are only the beginning, in reality *any* user-defined knee joint could be implemented. These examples will make it easier for users to develop and addin their own knee joint type into AnyBody. 

The original models were developed by [Christine Dzialo](https://www.linkedin.com/in/christine-dzialo-111AAU/)
at Aalborg University (AAU, Aalborg, Denmark) as part of her PhD work. Then implemented as a scalable moving-axis model when she joined the AnyBody Technology team in 2019.

![MA](https://user-images.githubusercontent.com/35573452/59689594-35091400-91e0-11e9-9d4b-f00405346eb6.jpg)

Musculoskeletal knee joint models can range from simple generic (hinge) to complex subject-specific (multi-body contact) depending on their generic qualities and computational time. Selecting a level of complexity depends on the research question being asked and how realistic the knee kinematics need to be. Studies that require realistic kinematics may include: investigating pathologies (i.e. KOA) or designing surgical implants to best restore healthy biomechanics.

The moving-axis joint model is based on two tibiofemoral flexion angles, at about 0 and 90 degrees, and the articulation modeled such that the joint axis moves linearly between these two positions as a function of flexion. The novelty behind the moving-axis is that it not only provides more realistic joint kinematics than the commonly used hinge; but also, it allows for a computationally fast model with subject-specific geometries which may increase accessibility for clinical applications compared to a more advanced multi-body contact model. More information can be found in the Journal of Biomechanics publication:

> Dzialo CM, Pedersen Heide P, Simonsen CW, Krogh K, de Zee M, Andersen MS., 2018, “Development and validation of subject-specific moving-axis tibiofemoral joint model using MRI and EOS imaging during a quasi-static lunge,” J Biomech 2018., **72**, p.71-80.
> Online: https://www.sciencedirect.com/science/article/abs/pii/S0021929018301386  

![BothAxes](https://user-images.githubusercontent.com/35573452/59689140-6208f700-91df-11e9-8947-e72e3a5c775a.jpg)

## Usage:
_to come_


# Examining driver injury severity in two vehicle crashes- A copula based approach

**By Yasmin et al. 2014**

[Paper link](https://github.com/subasish/MannBhat01/blob/master/Mannering_Bhat_Paper/Papers/MBRP%202014_6.pdf).



### What it is
* Each collision type has a fundamentally distinct effecton injury severity sustained in the crash. :sparkles:
* This study examines the hypothesis that collision typefundamentally alters the injury severity pattern under consideration.


### From Literature
* According to WHO:
> Road traffic crashes are one of the major causes of death in the world. The economic and societal cost, of road traffic crashes,accrues to billions of dollars. For example, in Australia,the total cost of motor vehicle crashes is estimated at approxi-mately $18 billion per annum.

### Dataset and Modeling

* A joint modeling framework to study collision type and injury severity sustained as two dimensions of theseverity process. 
* Employs **a copula based joint framework** that ties the collision type (representedas a _multinomial logit model_) and injury severity (represented as an _ordered logit model_) through aclosed form flexible dependency structure to study the injury severity process.
* Collision type as a vehicle-level


![fig1](img/pap1/fig1.JPG)

### Important lines

> 1. The greater dissipation of kinetic energy associated with a head-on collision islikely to result in severe injuries compared to a side-swipe crash.
> 2. In a rear-end collision involving two vehicles, one of the vehicle will berear-ended and the other one will be the rear-ender. The driverof the rear-ended vehicle is likely to be pushed backward intothe seat when struck by the rear-ender vehicle leading to a highprobability of whiplash or neck injury due to the continuous move-ment of the neck at a different speed relative to the head and the rest of the body.
> 3. In this approach, **the analyst** imposes [x] the assumption that the injury severity profile for vehicle occupantsin all types of crashes is the same and any potential differencesbetween different collision types can be accurately captured byemploying the collision type variable as an explanatory variable. :pushpin:
 


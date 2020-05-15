### 2.3.1	Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2	Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3	Metabolism and Elimination

Alfentanil is metabolized solely by CYP3A4. The tissue-specific CYP3A4 expression implemented in the model is based on high-sensitive real-time RT-PCR ([Nishimura 2013](#5-References)). 

The first model simulations showed that gut wall metabolization was too low in the PBPK model. In order to increase gut wall metabolization, the “mucosa permeability on basolateral side” (jointly the model parameters in the mucosa: ``P (interstitial->intracellular)`` and ``P (intracellular->interstitial)``) was estimated. This may lead to higher gut wall concentrations and, in turn, to a higher gut wall elimination. This parameter was preferred over other parameters such as relative CYP3A4 expression or fraction unbound (fu) in the gut wall as it is technically not limited to a maximum value of 100%.

### 2.3.4	Automated Parameter Identification

This is the result of the final parameter identification:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| `Lipophilicity` | 1.846           |        |
| `Specific intestinal permeability`                           | 5.737E-4        | cm/min |
| `Specific organ permeability` | 6.875E-3        | cm/min |
| Basolateral mucosa permeability<br />(``P (interstitial->intracellular)``, ``P (intracellular->interstitial)``) | 5.415E-4        | cm/min |
| `intrinsic clearance` via CYP3A4 | 0.527           | l/min  |


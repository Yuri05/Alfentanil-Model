### 2.3.1	Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2	Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3	Metabolism and Elimination

Alfentanil is metabolized solely by CYP3A4. 

The first model simulations showed that gut wall metabolization was too low in the PBPK model. In order to increase gut wall metabolization, the “mucosa permeability on basolateral side” was estimated. This may lead to higher gut wall concentrations and, in turn, to a higher gut wall elimination. This parameter
was preferred over other parameters such as relative CYP3A4 expression or fraction unbound (fu) in the gut wall as it is technically not limited to a maximum value of 100%.



### 2.3.4	Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building processThis is the result of the final parameter identification.

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| lipophilicity              | 1.846           |        |
| intestinal permeability    | 5.737E-4        | cm/min |
| (organ) permeability       | 6.875E-3        | cm/min |
| mucosa permeability        | 5.415E-4        | cm/min |
| intrinsic clearance CYP3A4 | 0.527           | l/min  |


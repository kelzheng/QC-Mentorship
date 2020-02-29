# QC-Mentorship

This is a notebook exploring the solution to **Task 2** of the [QC Mentorship Tasks](https://docs.google.com/document/d/1lo_qy6Y7jhwBMWpQuecxAFG3L_4soYkpq0TaLq42o-A/edit?usp=sharing):

```
Implement a circuit which returns |00> and |11> with equal probability.

*Requirements*:
* Circuit should consist only of CNOTs, RXs and RYs. 
* Start from all parameters in parametric gates being equal to 0 or randomly chosen. 
* You should find the right set of parameters using gradient descent (you might use more advanced optimization methods if you like). 
* Simulations must be done with sampling - i.e. limited number of measurements per iteration and noise. 
Compare the results for different numbers of measurements: 10, 100, 1000.

*Bonus question*: How to make sure you produce state |00>+|11> and not |00>-|11> ?
```
The notebook can be found [here](https://github.com/kelzheng/QC-Mentorship/blob/master/QC_Mentorship.ipynb) and can be opened in colab [here](https://colab.research.google.com/drive/1PL638mbF_khALruSCtD4Nc3DPYAvRrmE).

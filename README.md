# Hadamard Test
Code for calculating $Tr(\rho^2)$: $HT - Tr(\rho^2)$

Code for calculating $Tr(\rho^3)$: $HT - Tr(\rho^3)$

This method provides code for calculating $Tr(\rho^2)$ and $Tr(\rho^3)$. If you want to calculate higher orders, you only need to add an additional for loop on top of the previous order and add a $control-G$ gate in the circuit. Don't forget to multiply by the probabilities of the random gates.Additionally, the relationship between 'trbb' and 'zbb' in the final step of the program, i.e., the relationship between $P(1)$ and $Tr(\rho^k)$, varies in each order of calculation, as deduced from this paper.
​        

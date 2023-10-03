Code for calculating $Tr(\rho^2)$: $HT - Tr(\rho^2)$

Code for calculating $Tr(\rho^3)$: $HT - Tr(\rho^3)$

This method provides code for calculating $Tr(\rho^2)$ and $Tr(\rho^3)$. If you want to calculate higher orders, you only need to add an additional for loop on top of the previous order and add a $control-G$ gate in the circuit. Don't forget to multiply by the probabilities of the random gates. Additionally, in the final step of the program, the relationship between 'trbb' and 'zbb,' i.e., between $P(1)$ and $Tr(\rho^k)$, varies in each order of calculation. This relationship can be obtained using the following formula from the article:


P(1) = {Tr}\{M_{1} \rho' M_{1}^{\dagger}\} = |a_{22}|^{2}

= \frac{1}{2} - \frac{1}{2} {Tr}\{G^{k} \rho\}



Tr\{G^k\rho\}=Tr\{(I-2\rho)^k\rho\}


​        

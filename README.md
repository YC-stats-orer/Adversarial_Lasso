# Adversarial_Lasso
- Conditional case: estimate r_0(x) at a given x.
  - cd into **conditional** folder and run ```python3 run_conditional.py```
    
- Unconditional case: estimate r_0
   - cd into **unconditional_case** folder and run ```python3 run_unconditional.py```

- Causal application: coverage ratio of true ATE's (replication of section 6.3 of paper)
  - cd into **conditional** folder and run ```python3 causal_ATE.py```
 
### Requires installing packages: 
numpy, scipy, scikit-learn, cvxpy, mosek

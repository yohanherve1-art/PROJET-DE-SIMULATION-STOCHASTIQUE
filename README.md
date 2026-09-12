# PROJET-DE-SIMULATION-STOCHASTIQUE
Ce projet implémente et analyse en Python le **modèle de Wright-Fisher sans mutation**, une chaîne de Markov fondamentale en génétique des populations pour modéliser l'évolution stochastique de la fréquence des allèles.

## À propos du projet
Le projet étudie l'évolution d'une population de $2N$ gènes au fil du temps à travers une chaîne de Markov $(X_k)$. Les principaux objectifs sont :
1. **La simulation de trajectoires** stochastiques à l'aide de lois binomiales 
2. **L'analyse théorique et numérique** des états absorbants de la chaîne (fixation ou extinction des allèles).
3. **L'estimation par la méthode de Monte-Carlo** des probabilités d'extinction et le calcul d'intervalles de confiance asymptotiques associés.
4. **La détermination numérique du temps moyen d'absorption** de la population en fonction de l'état initial.

---

## Prérequis et Installation
Librairies à télécharger 
```bash
pip install numpy scipy matplotlib
```

Lancez Jupyter Notebook :
```bash
jupyter notebook Stochastic_Simulation.ipynb
```
---

## Structure du dépôt
```text
├── Stochastic_Simulation.ipynb   # Notebook Jupyter contenant le code, les graphiques et les explications détaillées
└── README.md                     # Documentation du projet

## D12: Causal Inference – Fisheries Dataset

This project explores causal relationships using a real-world fisheries dataset provided for BSAD 482. The goal is to understand whether *fishing effectiveness* has a causal impact on *fish density*, using a structured 3-part approach.

---

### Part 1: Theoretical Causal Model

We began by developing a theoretical causal model using domain knowledge. The variables considered included:

- `fishing_effectiveness` (treatment)
- `fish_density` (outcome)
- `go_fishing`
- `pressure_to_earn`
- `competition`
- `pressure_to_innovate`
- `replenishment_rate`

The theoretical model assumes the following causal relationships:

- `competition → pressure_to_earn → go_fishing → fishing_effectiveness → fish_density`
- `pressure_to_innovate → fishing_effectiveness`
- `replenishment_rate → fish_density`

#### Theoretical Graph

![Theoretical Graph](visualizations/theoretical_fishing_model.png)

### Part 3: Causal Inference Using DoWhy

I used the DoWhy framework to test the hypothesis:

> **"Does fishing effectiveness causally impact fish density?"**

#### Setup

- **Treatment:** `fishing_effectiveness`
- **Outcome:** `fish_density`
- **Common causes:**
  - `pressure_to_earn`
  - `competition`
  - `pressure_to_innovate`
  - `replenishment_rate`

#### Estimated Causal Effect

```plaintext
-2.7332

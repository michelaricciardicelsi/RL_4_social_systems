# RL_4_social_systems

# Polarization-RL: Adaptive Policy Strategies in Dynamic Opinion Environments

This project explores how an adaptive reinforcement learning (RL) agent behaves in an environment where its own actions influence the distribution of opinions over time.

The central question:
> *What happens when decisions affect not only immediate outcomes but also future uncertainties by reshaping the environment itself?*

Model a **polarized population** and train an RL agent to manage the evolving landscape of opinions, observing feedback loops and polarization dynamics.

---

## 🧩 Project Overview

- **Environment:** Opinion dynamics environment with 5 opinion bins (far left, left, center, right, far right).
- **Agent:** PPO (Proximal Policy Optimization) agent using Stable-Baselines3.
- **Actions:**
  - `0`: Moderate messaging (push toward center).
  - `1`: Provocative messaging (push toward extremes).
  - `2`: Fact-checking (strong push toward center).
- **Dynamics:** Population opinion distribution evolves under the influence of:
  - Agent actions
  - Peer influence (opinion smoothing)
  - External shocks (random disturbances)

---

## 🚀 Features

- ✅ Opinion distribution visualization over time
- ✅ Agent action frequency analysis
- ✅ Polarization index tracking (variance of opinion distribution)
- ✅ Clean, modular Python codebase for extensions and further research

---

## 📊 Example Outputs

- Action frequency bar charts
- Polarization index time series
- Opinion dynamics overlaid with agent decisions
- Stability comparison across multiple independent runs


---
## References 
- Zhiyu He, Saverio Bolognani, Florian Dörfler, Michael Muehlebach. Decision-Dependent Stochastic Optimization: The Role of Distribution Dynamics. 2025
- Sutton, R. S., & Barto, A. G. Reinforcement Learning: An Introduction. MIT Press, 2nd Edition, 2018.
- Stable-Baselines3 Contributors. Stable-Baselines3: Reliable Reinforcement Learning Implementations. GitHub repository.
- OpenAI Gym. A toolkit for developing and comparing reinforcement learning algorithms. GitHub repository.
---

## 🧑‍💻 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/polarization-rl.git
   cd polarization-rl

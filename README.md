# 🧮 Germain Prime Entropy & Topology
This project explores the hidden structure in the sequence of Germain primes — primes \( p \) such that \( 2p + 1 \) is also prime — using tools from information theory, dynamical systems, and topological data analysis (TDA).

By treating the gaps between Germain primes as a dynamical signal, we uncover patterns in entropy, detect coherent topological features using persistent homology, and identify “topological events” — bursts of organization within apparent randomness.

## 🔍 Goals
- Analyze entropy of prime gaps at global and local scales
- Visualize entropy fluctuations over time
- Construct delay embeddings of the entropy signal
- Use persistent homology to detect loops and structure
- Identify statistically significant features vs. shuffled controls
- Detect and analyze topological “events”

---

## 📊 Highlights

### Global gap distribution of Germain primes
![Gap Histogram](images/Germain_prime_gap_distribution.png)

### Local sliding window entropy
![Local Entropy](images/local_entropy_Germain_sliding.png)

### Entropy vs. scale (saturation behavior)
![Entropy vs Scale](images/entropy_vs_scale_Germain.png)

### Real vs. shuffled entropy distributions
![Real vs Shuffled](images/distribution_real_vs_shuffled.png)

### Delay-embedded entropy attractor (2D)
![2D Delay Embed](images/delay_embed_ridge_2d.png)

### Persistence diagram of ridge signal
![Persistence Ridge](images/persistent_ridge.png)

### Max lifetime distribution (real vs shuffled)
![Max Lifetime Distribution](images/max_lifetime_distribution_real_vs_shuffled.png)

### Correlation of entropy with topological lifetime
![Rolling Correlation](images/rolling_corr_entropy_vs_h1_lifetime.png)

### Topological event signal
![Topological Events](images/event_entropy_signal_germain.png)

---

## 📂 Contents

- `Germain_primes.pdf` — Full LaTeX paper (April 1, 2025 edition!)
- `images/` — All figures used in the paper
-  Jupyter notebooks for entropy analysis, TDA, and visualization
- `README.md` — This file

---

## 🧠 Techniques Used

- Shannon entropy (global and local)
- Sliding window analysis
- Delay embedding (Takens' theorem)
- PCA for visualization
- Persistent homology via Vietoris-Rips complexes
- Kolmogorov–Smirnov and t-tests
- Topological event detection via lifetime thresholds

---

## 📅 Historical Coincidence

Sophie Germain — the namesake of Germain primes — was born on **April 1st, 1776**.  
This project was completed on **April 1st, 2025**, exactly 249 years later. 🎂

---

## 🔭 Future Directions

- Apply to other prime sequences (safe primes, twin primes, etc.)
- Extend TDA to symbolic dynamics or prime encodings
- Explore connections to modular filters or sieve effects
- Analyze cohomology or higher-dimensional features

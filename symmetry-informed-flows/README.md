# Symmetry-informed Normalizing Flows

- `damped-harmonic-oscillator-with-similarity-embedding-training.ipynb`
  - Damped SHO trained the flow using similarity embedding
  - generate time shifted data and signal for damped sho
  - augment sho data that is time shifted
  - vicreg loss used to train similarity embedding
  - convolutional 2d residual net used for similarity embedding layers
  - froze similarity embedding weights, passed them for the flow training
  - posterior widths and pp plots for the flow training results


- `damped-harmonic-oscillator-without-similarity-embedding-training.ipynb`
  - Damped SHO trained the flow without the similarity embedding
  - generate time shifted data and signal for damped sho
  - augment sho data that is time shifted
  - did not train similarity embedding
  - did not pass weights to the flow training
  - posterior widths and pp plots for the flow training results


- `damped-harmonic-oscillator-moneyplot-similarity-embedding-improvement.ipynb`
  - Shows the efficiency of the similarity embedding
  - Compares the losses of the flow training with/without the similarity embedding
  - plots the loss curves on one plot


- `events.out.tfevents.1691020465.submit20.mit.edu.745857.0`
  - Writer for the flow with the similarity embedding, used in the moneyplot file (Ea1)

- `events.out.tfevents.1691020505.submit20.mit.edu.745862.0`
  - Writer for the flow without the similarity embedding, used in the moneyplot file (Ea2)

- 'damped-harmonic-oscillator-similarity-embedding-weights.pth`
  - Trained and saved weights of the similarity embedding

- `damped-harmonic-oscillator-with-similarity-embedding-flow-weights.pth`
  - Trained and saved weights of the flow with the sim. emb.

- `damped-harmonic-oscillator-without-similarity-embedding-flow-weights.pth`
  - Trained and saved weights of the flow without the sim. emb.




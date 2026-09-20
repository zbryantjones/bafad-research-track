# Task C — Research Reflection

## Question 1 — Connecting the Work to Research

In Task A, I saw that anomalies are rare, only about 5% of timesteps. Most of them show up as a sudden spike in just one channel while the other channels look normal, and it is a different channel each time. So a detector has to look at all the channels together, not just one. An autoencoder trained on normal data should rebuild the normal waves well and do badly on spikes, so a high reconstruction error could flag an anomaly. Because anomalies are so rare, picking the error threshold will be the tricky part.

## Question 2 — Self-Assessment of Readiness

I'm comfortable with Python, SQL, and Git, and I've made reports and dashboards, so pandas and matplotlib feel okay. My biggest gap is deep learning, since I haven't done much with PyTorch or neural networks. I also don't know federated learning or the Flower framework yet, or how to detect concept drift. My plan is to start with the PyTorch 60-Minute Blitz, read the autoencoder chapter in the Deep Learning book, and read the FedAvg paper. I'll also bring questions to the lab sessions and PI check-ins instead of getting stuck alone.

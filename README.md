# DeCIPHER: Deconfounded & Calibrated Learning for Adaptively Logged Scientific Data

This repository contains the code used to develop **DeCIPHER**, a causal and calibrated learning framework designed to handle **small, adaptively logged scientific datasets**. The workflow combines:

- **Soft-negative sampling** to approximate the hidden logging policy

- **Propensity modeling** via XGBoost

- **Inverse-propensity weighted (IPW) regression** using a neural network

- **Distribution-free conformal prediction** for calibrated uncertainty intervals

Although the motivating example is reaction-yield prediction, the framework is domain-agnostic and can be applied to any setting where scientific data are collected through non-random, human-driven decisions.

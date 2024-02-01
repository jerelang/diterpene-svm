# Diterpene Structure Classification

Diterpenes belong to the terpene family, which are organic compounds made of carbon and hydrogen, with a general formula of (C5H8)n. These compounds are found in some plant oils and can have medicinal uses.

NMR (Nuclear Magnetic Resonance) spectroscopy is a common technique to determine the chemical structure of compounds. It uses the fact that atomic nuclei are affected by magnetic fields due to their spin. This technique measures the absorption of electromagnetic radiation, usually between 4-900 MHz, to identify molecular structures.

The research paper of Dzeroski et al. (http://dx.doi.org/10.1080/088395198117686) involves analyzing a data set of 1202 diterpene spectra. These are divided into 23 classes based on their structure. The data set contains information about atoms, their bonds, and frequencies of observed peaks in the NMR spectra.
The dataset cannot be provided due to unclear licensing.

The Jupyter Notebook includes:

    Data analysis and preparation.
    Feature engineering to extract permutation invariant information from NMR spectra.
    Implementation of a Support Vector Machine (SVM) that uses these aggregated features as well as histograms to predict the diterpene classes.
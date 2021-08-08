# smiley_frowny

This repository contains the notebooks to generate and classify data from the smiley-frowny toy model and from the modified version of the waveform dataset (Breiman et al.,1984) with CNNs which account for attribute uncertainties (N.Rodrigues, R.Abramo, N.Hirata, 2021).

To generate the data according to the smiley-frowny model, access: smileyfrowny/smiely_frowny.ipynb.

To run CNN1D no-sigma, CNN1D with-sigma and CNN1Dstack-sigma in the smiley-frowny data, access: smielyfrowny/CNN1D_SF.ipynb.

To run CNN2D images in the smiley-frowny data (Gauss version), access: smileyfrowny/CNN2D_SF.ipynb.

To run least squares in the smiley-frowny data, access: smileyfrowny/least_squares.ipynb.

To run MCMC in the smiley-frowny data, access: smileyfrowny/mcmc.ipynb.


To generate the waveform (modified version) data and to run least squares on it, access: waveform_modified/waveform.ipynb.

To run CNN1D no-sigma and CNN1Dstack-sigma in the waveform data, access: waveform_modified/CNN1D_WF.ipynb.

To run CNN2D images in the waveform data, access: waveform_modified/CNN2D_WF.ipynb.

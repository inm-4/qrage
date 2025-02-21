# QRAGE

This repository provides a Pulseq implementation of the QRAGE MRI sequence, as described in our publication:  
["QRAGE—Simultaneous multiparametric quantitative MRI of water content, T1, T2*, and magnetic susceptibility at ultrahigh field strength"](https://onlinelibrary.wiley.com/doi/10.1002/mrm.30272).

## Differences from the Published Implementation

While we have worked diligently to replicate the QRAGE sequence originally developed in the SIEMENS IDEA framework, there are some minor differences between this implementation and the one used in the publication. For instance, the repetition time, inversion time, and echo times differ slightly. However, our comparisons indicate that these variations do not have a significant impact on image quality or the accuracy of the parameter maps.

## Missing Content

Currently, this repository contains only the sequence implementation. We are actively working on open-sourcing the complete image reconstruction pipeline—including both pre-processing and post-processing steps—which will be available soon.

## How to give credit

If you use this package, please acknowledge our work by citing:

Zimmermann M, Abbas Z, Sommer Y, et al. QRAGE—Simultaneous multiparametric quantitative MRI of water content, T1, T2*, and magnetic susceptibility at ultrahigh field strength. Magn Reson Med. 2025; 93(1): 228-244. doi: 10.1002/mrm.30272

A BibTeX file is directly contained within this package (QRAGE.bib).

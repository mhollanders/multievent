# Code and data for the novel extended multievent model

This repository contains data and code for the novel extended multievent model presented in:

  - Hollanders, M. and J. Andrew Royle. 2022. Know what you don't know: Embracing state uncertainty in       disease-structured multistate models. *Methods in Ecology and Evolution*.

This repo was primarily created so that users would have direct access to the R code, given that the appendices in the Supporting Information of the manuscript are in PDF form. Appendices 1--4 are identical to those in the manuscript. Additionally, the repo contains the *Mixophyes fleayi* capture history used as a case study in the manuscript. For details on that dataset, see the README in the Dryad repository:

  - Hollanders, M., and J. Andrew Royle. 2022. Know what you don't know: Embracing state uncertainty in disease-structured multistate models, Dataset. Dryad. https://doi.org/10.5061/dryad.s7h44j19h.

The Quarto document `multievent-fleayi.qmd` contains all the code to manipulate this capture history, analyse the data with the multievent model and a traditional Arnason-Schwarz model, and to create the figures. MCMC output is included in the folders `mcmc-samples` and `mcmc-trace`. Note that in addition to the MCMC draws and summaries for the multievent and Arnason-Schwarz models, there is also output for the multievent model without false-positives in the sampling process (`MEdraws-del0`), diagnostic process (`MEdraws-lam0`), and without any false-positives (`MEdraws-dellam0`).

The manuscript file is included as `multievent-manuscript.qmd`.
---
title: 'EEGQC: A BIDS App for QC of iEEG and EEG data.'
author: mcespedes
date: 2019-08-09 20:55:00 +0800
categories: [Blogging, Tutorial]
tags: [eeg, ieeg]
pin: true
img_path: /assets/img/
---

In the contemporary landscape of EEG and iEEG analysis, numerous researchers are actively pursuing a minimally invasive preprocessing approach. Extensive data preprocessing has been found to potentially introduce adverse effects on the interpretability of findings, as evidenced in [this paper] for reference. Consequently, it becomes imperative to assess the data quality in order to rationalize the selection of specific preprocessing steps. Regrettably, there is currently no universally standardized tool available that facilitates a systematic and efficient evaluation of data quality across multiple files without necessitating a repetitive workflow for each dataset.

In this context, we introduce EEGQC, a pioneering tool designed to establish a standardized framework for quality control in EEG and iEEG data analysis. Adhering to the principles of the Brain Imaging Data Standard ([BIDS]), EEGQC generates detailed HTML reports for each data file, systematically organized within a BIDS directory structure derived from the input directory. An illustrative example of such a report is provided below:

![EEGQC Report](report.png)

This report can be access [here]({{ site.baseurl }}{% link /assets/prerendered/report.html %}).

## Prerequisites

TBD

## Installation
TBD

[this paper]: https://www.nature.com/articles/s41598-023-27528-0
[BIDS]: https://bids-specification.readthedocs.io/en/stable/

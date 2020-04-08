# Benchmarking Analysis for Shotgun Proteomics

Quantitative mass spectrometry is a powerful ‘discovery tool’ to uncover global protein expression changes in biological systems. Within this context, accurate quantification is critical for the downstream selection of targets for mechanistic follow-up experiments. While previous benchmarking studies have evaluated the impact of individual experimental parameters on quantification, a clear framework of best practices for quantitative reproducibility has not been established. Here, we use an integrated benchmarking approach to empirically establish guidelines for data acquisition, statistical approach, and replicate numbers for accurate quantification. We evaluated three workflows for protein- and peptide-level quantitative accuracy: data dependent acquisition (DDA), data independent acquisition (DIA), and chemical labeling via tandem mass tags (TMT). For protein quantitation, all three workflows yielded good accuracy when combined with the appropriate number of replicates and statistical approach. Specifically, the DIA and TMT workflows required a lower number of replicates (n=4) to yield acceptable results while DDA workflows required higher replicate numbers (n=6-8). In contrast, peptide quantification was more demanding and required the use of higher replicate numbers in combination with TMT or DIA workflows for accurate results. Replicate numbers also had a strong differential impact on statistical performance, with specific statistical models exhibiting widely varying results from low to high replicate numbers. These results establish foundational guidelines and best practices for quantitative proteomics. To assist proteomics researchers as well as the biologists who collaborate with them, we have included an R script to automate the benchmarking process. 

### Prerequisites

All packages and dependencies used are listed at the top of the R Markdown script which we have coined LFQMagic


## Built With

* [RStudio](https://rstudio.com/) - The web framework used


## Authors

* **Logan Wright** - [MustachedMarvel](https://github.com/MustachedMarvel)


## Acknowledgments

* James Dowell for proposing the project, asking the right questions, and keeping everything moving
* Thevaa Chandereng for statistical insight and some good laughs
* John Denu for being such a wonderful PI and mentor

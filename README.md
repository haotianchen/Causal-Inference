# Causal Inference Notes

TA Materials for PhD-level Causal Inference course (Pol Sci 200C, by [Chad Hazlett](https://www.chadhazlett.com/)) offered at UCLA 2024 Spring, 2025 Spring.

## TA Section Notes
- [Math and Regression Review](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/1-Math/prob_matrix_review.html)
  + [Basic Probability Theory](https://iqss.github.io/prefresher/probability-theory.html) and [Basic Linear Algebra](https://github.com/haotianchen/Causal-Inference/blob/main/1-Math/BasicMatrixAlgebra_review.pdf)
  + [OLS in Matrix Form](https://web.stanford.edu/~mrosenfe/soc_meth_proj3/matrix_OLS_NYU_notes.pdf) and [Standard Errors in OLS](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/1-Math/se_ols.html)
- [Potential Outcomes and Randomized Experiments](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/2-PO/potential_outcomes.html)
- [Selection on Observables (SOO)](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/3-SOO/matching.html)
- [Sensitivity Analysis](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/4-Sensitivity/sensitivity.html)
- Directed Acyclic Graphs (DAGs): [Intro](https://mixtape.scunning.com/03-directed_acyclical_graphs) and [Examples](https://donskerclass.github.io/CausalEconometrics/DAGs.html)
- [Difference-in-Differences (DiD)](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/5-DID/DID.html)
- [Instrumental Variables (IV)](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/6-IV/IV.html)
- [Regression Discontinuity Design (RDD)](https://htmlpreview.github.io/?https://github.com/haotianchen/Causal-Inference/blob/main/7-RDD/RDD.html)

## Resources

### Other Courses (links might be expired)
(by Political Science Departments)

- Stat286/Gov2003: Causal Inference with Application (Harvard)
  - **Instructor(s)**: Kosuke Imai
  - **Videos**: https://www.youtube.com/@imaikosuke/playlists :star:
  - **Slides**: https://imai.fas.harvard.edu/teaching/cause.html

- Gov2003: Causal Inference (Harvard)
  - **Instructor(s)**: Matthew Blackwell
  - **Slides**: https://github.com/mattblackwell/gov2003-f21-site/tree/main/files

- POLISCI 450B: Political Methodology II (Stanford)
  - **Instructor(s)**: Apoorva Lal (TA for Jens Hainmueller)
  - **Slides**: https://apoorvalal.github.io/talks/2021-GraduateSequenceTeaching
  - **Coding**: https://apoorvalal.github.io/notebook/causal_inference_notes/

- PLSC 30600: Causal Inference (UChicago)
  - **Slides + Codes**: https://apoorvalal.github.io/talks/2021-GraduateSequenceTeaching

- POL-GA 1251: Quantitative Political Analysis II (NYU)
  - **Instructor(s)**: Cyrus Samii
  - **Slides**: https://cyrussamii.com/?page_id=3893
  - **Lab Handouts**: [Spring 2021 Handouts](https://www.zhoujunlong.com/Quant2_lab_2021sp/)

- POLI 784: Linear Methods in Causal Inference (UNC)
  - **Instructor(s)**: Ye Wang
  - **Slides**: https://www.yewang-polisci.com/teaching

- 17.802 Quantitative Research Methods II (MIT)
  - **Instructor(s)**: F. Daniel Hidalgo
  - **Syllabus**: https://www.dhidalgo.me/teaching

- [A Basic Checklist for Observational Studies in Political Science](https://yiqingxu.org/public/checklist.pdf) by Yiqing Xu :star:

-----
(by Stats Departments)
- Introduction to Causal Inference (online)
  - **Instructor(s)**: Brady Neal
  - **Slides + Videos**: https://www.bradyneal.com/causal-inference-course

- Stat 256: Causal Inference (UC Berkeley)
  - **Instructor(s)**: Peng Ding
  - **Notes**: [A First Course in Causal Inference](https://arxiv.org/pdf/2305.18793.pdf) [[Python code](https://github.com/apoorvalal/ding_causalInference_python)][[R code](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ZX3VEV)] :star:

- STA 640: Causal Inference (Duke)
  - **Instructor(s)**: Fan Li
  - **Slides**: https://www2.stat.duke.edu/~fl35/CausalInferenceClass.html

- STATS 361: Causal Inference (Stanford)
  - **Instructor(s)**: Stefan Wager
  - **Notes**: https://web.stanford.edu/~swager/stats361.pdf

-----
(by Econ Departments)

- Mixtape Sessions (online)
  - **Instructor(s)**: Scott Cunningham et al. 
  - **Labs**: https://github.com/Mixtape-Sessions :star:

- ECON 574: Applied Empirical Methods (Yale)
  - **Instructor(s)**: Paul Goldsmith-Pinkham
  - **Slides**: https://github.com/paulgp/applied-methods-phd
  - **Videos**: https://www.youtube.com/playlist?list=PLWWcL1M3lLlojLTSVf2gGYQ_9TlPyPbiJ

- 47-873: Causal Econometrics (CMU)
  - **Instructor(s)**: David Childers
  - **Notes**: https://donskerclass.github.io/CausalEconometrics.html

- ECON 2400: Applied Econometrics II (Brown)
  - **Instructor(s)**: Peter Hull
  - **Slides**: https://about.peterhull.net/metrix

- Causal Machine Learning
  - **Instructor(s)**: Michael Knaus
  - **Slides**: https://github.com/MCKnaus/causalML-teaching
 
-----
### Catch up on the current literature (impossible; but here are some good resources)
- [What’s Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature](https://arxiv.org/pdf/2201.01194.pdf) - Roth et al. (2023)
- [A Practical Introduction to Regression Discontinuity Designs: Foundations](https://arxiv.org/pdf/1911.09511.pdf) & [A Practical Introduction to Regression Discontinuity Designs: Extensions](https://arxiv.org/pdf/2301.08958.pdf) - Cattaneo et al. (2019; 2023)
- [Causal Models for Longitudinal and Panel Data: A Survey](https://www.nber.org/papers/w31942) - Arkhangelsky and Imbens (2023)
- [Recent Developments in Causal Inference and Machine Learning](https://www.annualreviews.org/content/journals/10.1146/annurev-soc-030420-015345) - Brand et al. (2023)
- [DiD literature](https://github.com/asjadnaqvi/DiD) -- Github repository that tracks the literature in DiD, with [Notes](https://asjadnaqvi.github.io/DiD/)


# Predicting Chemical Partitioning and PFAS Decomposition using Machine Learning
## Duncan Soiffer - WPI DS REU 2023

Welcome to my additional materials page! Here you can find video files visualizing the reactions taking place during PFOA incineration, full simulation outputs, HTML files containing a more human-readable version of some of my data, and (most importantly) citations for my poster.

### Video Files
In the videos/ folder, you can find videos showing the simulated reaction mechanism of PFOA for inert pyrolysis, reductive pyrolysis, and oxidative pyrolysis.

### HTML Files
For a human-readable list of core species and reactions in each of the simulations, including molecule diagrams, I have included HTML files on this page under the human-readable/ folder. To look at them, you can open them in a browser, or download the files and open them locally.

### Simulation Data
I have way too many files for Github to handle gracefully (almost 6,000!). Instead, you can find my simulation results here: https://drive.google.com/drive/folders/15nH7KeGCF0kgDD7TKvfs5sL3SH38bN_T?usp=sharing

There's a lot to look over in there. There are a number of simulations ran for several PFAS, but a focus was put on PFOA. I would recommend first looking at the far more human-readable HTML files and videos I posted on this page. If you're still interested in looking at the data, I would recommend checking PFOA/inert, PFOA/with-hydrogen, and PFOA/with-oxygen. In particular, the chemkin-annotated file shows all the core species and reactions (but less prettily than the HTML page), the seed folder shows the reaction system as it evolves over multiple iterations, and the statistics.xls files contain a spreadsheet showing time spent and number of species/reactions produced per generation.


### References
[1] D. H. Kenney, R. C. Paffenroth, M. T. Timko, and A. R. Teixeira, “Dimensionally reduced machine learning model for predicting single component octanol–water partition coefficients,” J Cheminform, vol. 15, no. 1, p. 9, Jan. 2023, doi: 10.1186/s13321-022-00660-1.

[2] C.W. Gao, J.W. Allen, W.H. Green, R.H. West, “Reaction Mechanism Generator: Automatic construction of chemical kinetic mechanisms”, Computer Physics Communications 2016, 203, 212-225. doi: 10.1016/j.cpc.2016.02.013.

[3] M. Liu, A. Grinberg Dana, M.S. Johnson, M.J. Goldman, A. Jocher, A.M. Payne, C.A. Grambow, K. Han, N.W. Yee, E.J. Mazeau, K. Blondal, R.H. West, C.F. Goldsmith, W.H. Green, “Reaction Mechanism Generator v3.0: Advances in Automatic Mechanism Generation”, Journal of Chemical Information and Modeling 2021, 61(6), 2686–2696. doi: 10.1021/acs.jcim.0c01480.

[4] M.S. Johnson, X. Dong, A. Grinberg Dana, Y. Chung, D. Farina, R.J. Gillis, M. Liu, N.W. Yee, K. Blondal, E. Mazeau, C.A. Grambow, A.M. Payne, K.A. Spiekermann, H.-W. Pang, C.F. Goldsmith, R.H. West, W.H. Green, “The RMG Database for Chemical Property Prediction”, Chemical Information 2022, 62(20), 4906–4915. doi: 10.1021/acs.jcim.2c00965.

[5] R. C. Lewis, L. E. Johns, and J. D. Meeker, “Serum Biomarkers of Exposure to Perfluoroalkyl Substances in Relation to Serum Testosterone and Measures of Thyroid Function among Adults and Adolescents from NHANES 2011–2012,” Int J Environ Res Public Health, vol. 12, no. 6, pp. 6098–6114, Jun. 2015, doi: 10.3390/ijerph120606098.

[6] R. Wang, Y. Gao, and L. Lai, “Calculating partition coefficient by atom-additive method,” Perspectives in Drug Discovery and Design, vol. 19, pp. 47–66, Sep. 2000, doi: 10.1023/A:1008763405023.

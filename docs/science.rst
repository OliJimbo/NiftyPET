.. _science-section:

=================
Scientific Output
=================

Scientific aspects of NiftyPET
------------------------------

The core routines are written in CUDA C and embedded in Python C extensions to enable user-friendly and high-throughput executions on NVIDIA graphics processing units (GPU).  The scientific aspects of this software platform are covered in two open-access publications:

* *NiftyPET: a High-throughput Software Platform for High Quantitative Accuracy and Precision PET Imaging and Analysis* Neuroinformatics (2018) 16:95. https://doi.org/10.1007/s12021-017-9352-y

* *Rapid processing of PET list-mode data for efficient uncertainty estimation and data analysis* Physics in Medicine & Biology (2016). https://doi.org/10.1088/0031-9155/61/13/N322


Applications
------------



* Novel MR-PET registration uncertainty analysis, indicating that registration software has the biggest effect on MR-PET registration precision, followed by reconstruction parameters (i.e., iterations, smoothing) and PET count level.  Although PVC can significantly improve the PET signal, it also increases PET signal variability since it relies on precise MR-PET registration.  More details can be found in :cite:`Markiewicz2021`:

    P.J. Markiewicz, J.C. Matthews, J. Ashburner, D.M. Cash, D.L. Thomas, E. De Vita, A. Barnes, M.J. Cardoso, M. Modat, R. Brown, K. Thielemans, C. da Costa-Luis, I. Lopes Alves, J.D. Gispert, M.E. Schmidt, P. Marsden, A. Hammers, S. Ourselin, and F. Barkhof (2021).  **Uncertainty analysis of MR-PET image registration for precision neuro-PET imaging**. Neuroimage 655 232, 117821. https://doi.org/10.1016/j.neuroimage.2021.117821

* An example application of *NiftyPET* in the development of novel image reconstruction using advanced randomized optimization algorithms to solve the PET reconstruction problem for a very large class of non-smooth priors :cite:`Ehrhardt2019`:

    M.J. Ehrhardt, P.J. Markiewicz, C-B. Schönlieb (2019). **Faster PET reconstruction with non-smooth priors by randomization and preconditioning**. Phys. Med. Biol. 64(22), https://doi.org/10.1088/1361-6560/ab3d07

* Dynamic PET image reconstruction for reduced acquisition time PET pharmacokinetic modelling :cite:`Scott2018`:

    C.J. Scott, J. Jiao, A. Melbourne, N. Burgos, D.M. Cash, E. De Vita, P.J. Markiewicz, A. O'Connor, D.L. Thomas, P.S.J. Weston, J.M. Schott, B.F. Hutton, S.Ourselin (2018) **Reduced acquisition time PET pharmacokinetic modelling using simultaneous ASL–MRI: proof of concept**. Journal of Cerebral Blood Flow & Metabolism. https://doi.org/10.1177/0271678X18797343



.. |nbsp| unicode:: 0xA0 
   :trim:

.. :::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

*NiftyPET* is a software platform and a Python namespace package encompassing sub-packages for high-throughput PET image reconstruction, manipulation, processing and analysis with high quantitative accuracy and precision.  One of its key applications is **brain imaging in dementia** with the use of amyloid tracers.  See below for the description of the above amyloid PET image reconstructed using *NiftyPET*, superimposed on the MR T1 weighted image [*]_.


.. note::

   **Latest Research:**

   *Advanced quantitative evaluation of PET systems using the ACR phantom and NiftyPET software*


*NiftyPET* includes two packages:

  * ``nimpa``:  https://github.com/NiftyPET/NIMPA (neuro-image manipulation, processing and analysis)
  * ``nipet``:  https://github.com/NiftyPET/NIPET (quantitative PET neuroimaging)

The core routines are written in CUDA C and embedded in Python C extensions to enable user-friendly and high-throughput executions on NVIDIA graphics processing units (GPU).  For the scientific aspects of this software platform see section :ref:`science-section`.

Although, *NiftyPET* is dedicated to high-throughput image reconstruction and analysis of brain images, it can equally well be used for **whole body imaging**.  Strong emphasis is put on the data, which are acquired using positron emission tomography (PET) and magnetic resonance (MR), especially using the hybrid and simultaneous PET/MR scanners.  

This software platform covers the entire processing pipeline, from the raw list-mode (LM) PET data through to the final image statistic of interest (e.g., regional SUV), including LM bootstrapping and multiple independent reconstructions to facilitate voxel-wise estimation of uncertainties.


.. [*] The above dynamic transaxial and coronal images show the activity of  :sup:`18`\ F-florbetapir during the one-hour dynamic acquisition.  Note that the signal in the brain white matter dominates over the signal in the grey matter towards the end of the acquisition, which is a typical presentation of a negative amyloid beta (Abeta) scan.



.. :::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
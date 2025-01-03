# DNN for TS vs Poles

This repository contains codes for the construction and training of Deep Neural Network models to distinguish Triangle Singularity from Pole-based Enhancements.

Training datasets are generated in the various `gendatasetXX_XXXX.ipynb` notebooks. They also contain codes that allow you to check the plot of the consructed line shapes and the parameters used. Check `module_Poles.ipynb` and `module_Triangles.ipynb` for the other back-end functions involved. Use `combine_datasets.ipynb` to compile generated training datasets.

Design multiple DNN architectures and models using `multi_mod_compact.ipynb`, then implement training. During training, use `DNN_training_progress.ipynb` to monitor DNN performance and accuracy. Finally, use `DNN_application.ipynb` to perform validation of trained DNN model, construct the confusion matrix, and make inferences on experimental data retrieved from <a href=https://www.hepdata.net/record/ins1728691>HEPData</a>.

#### If you wish to use our codes in your work, please cite our paper: [10.1103/PhysRevD.110.114034](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.114034).

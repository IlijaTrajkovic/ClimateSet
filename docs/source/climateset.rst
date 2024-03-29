ClimateSet
===========

**ClimateSet** is an initiative aimed at providing a comprehensive and accessible dataset for the intersection of 
**climate science** and **machine learning** (ML). It is a dataset containing inputs and outputs 
from **36 different climate models**, 
addressing a crucial need in the ML community to support climate scientists in various tasks 
such as **climate model emulation**, **downscaling**, and **prediction**.
 
The dataset is carefully curated from the *Coupled Model Intercomparison Project Phase 6* 
(**CMIP6**) and *Input Datasets for Model Intercomparison Projects* (**Input4MIPs**). 
CMIP6 serves as the backbone of ClimateSet, offering **climate model outputs** from 
various sources. Input4MIPs, on the other hand, collect **future emission trajectories 
of climate forcing agents**, crucial for predicting climate model responses. 
The resulting core dataset encompasses 36 climate models, including the main greenhouse gases, 
aerosols, and aerosol precursor emission inputs for five different scenarios.
 
ClimateSet's significance lies in its ability to address two key objectives: 
providing **sufficient training data for large-scale ML models** and **capturing the projection 
uncertainty across different climate models**. The need for such a dataset arises 
from the inherent challenges in climate-related tasks, including **high dimensionality**, 
**low sample size**, and **distribution shifts** within the data. ClimateSet tackles 
these challenges by offering a **consistent and sizable dataset**, paving the way for ML models 
to contribute meaningfully to climate-related modeling tasks.
 
To facilitate the use of ClimateSet, a **modular dataset pipeline** is introduced, 
allowing users to **retrieve and preprocess climate model data** for ML tasks. 
In our paper we detail the preprocessing steps, addressing inconsistencies across 
different datasets and climate models. 
The preprocessor, built modularly, checks for corrupt files, variable naming, units, 
temporal and spatial resolution, and structure. 
It ensures that the data is ready for use in ML applications by syncing time-axis, 
calendars, and height levels, and resolving other relevant issues.
 
Users can access ClimateSet through the provided `website <https://github.com/RolnickLab/ClimateSet>`_, 
where both raw and processed data are available. 
The **dataset can be extended** by users who desire additional scenarios, climate forcers, or 
other variables, provided the requested data is available on 
the *Earth System Grid Federation* (**ESGF**) server. The preprocessing of ClimateSet can also 
be **accelerated using multi-thread functions** and other optimizations.
 
The heart of ClimateSet's utility is demonstrated through a **benchmarking setup**, showcasing 
its application in **climate emulation tasks**. ML models, 
including *Convolutional long short-term memory* (**ConvLSTM**), **U-Net**, and **ClimaX**, 
are trained and evaluated on the dataset. 
The results reveal insights into model performance across different climate models and scenarios, 
emphasising the *importance of evaluating 
ML models on a set of climate models rather than just one*.
 
ClimateSet is a valuable resource that bridges the gap between climate science and ML. 
It provides a consistent, multi-climate-model dataset along 
with tools for easy access and preprocessing. Researchers and policymakers can leverage 
ClimateSet to enhance ML models' performance, contribute to 
climate-related tasks at scale, and ultimately make meaningful strides in **climate policy making**.

Useful links
------------

- CMIP6 overview of all available data: https://pcmdi.llnl.gov/CMIP6/ArchiveStatistics/esgf_data_holdings/

- IPCC website: https://www.ipcc.ch

- ESGF website: https://esgf.llnl.gov/

- ClimateSet GitHub: https://github.com/RolnickLab/ClimateSet
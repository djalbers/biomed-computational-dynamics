biomed-computational-dynamics
=============================

computational dynamics tools useful in a biomedical context

Dynamics software for human health.
 
This work was funded by the NLM grant “Discovering and Applying Knowledge in Clinical Databases” (funded by LM006910)
 
 
MATLAB software for computing the time delayed mutual information (TDMI) for a non-uniformly measured, possibly heterogeneous population.
 
This source contains a non-optimized, sometimes stupidly parallelized, version of the TDMI calculation for a non-uniformly sampled population. The zip file contains several versions of the code ranging from a single black box version to a version that can be run on a BEOWULF cluster.  This code (or similar versions) was used for:
 
Albers, D. J., Hripcsak, G., “A statistical dynamics approach to the study of human heath data: resolving population scale diurnal variation in laboratory data” Phys. Lett. A 374 (2010) 1159-1164

Albers, D. J, Hripcsak, G., “Using time-delayed mutual information to discover and interpret temporal structure in complex populations,” CHAOS 22 (2012), 013111

Albers, D. J., Hripcsak, G., “Estimation of time-delayed mutual information from sparsely sampled sources,” Chaos, Solitons and Fractals 45 (2012) 853-860.

Albers, D.J., Hripcsak, G, Schmidt, M., “Population Physiology: Leveraging Electronic Health Record Data to Understand Human Endocrine Dynamics,” PLoS One 7 (12), e48058, 2012

SOURCE: tdmi.zip
 
MATLAB software for computing the empirical orthogonal functions for EEG data.
 

This source contains a non-optimized, sometimes stupidly parallelized, version of the empirical orthogonal functional analysis (EOF) calculation for an individual or population of EEG power spectrum multivariate time series. The zip file contains several versions of the code useful for different contexts, including code that returns only the first EOF versus code that returns all N EOFs.  This code (or similar versions) was used for:
 

Albers, D.J., Claassen, J, Schmidt, M., Hripcsak, G., “A methodology for detecting and exploring non-convulsive seizures in patients with acute brain injury,”  (2013) arXiv:1305.7271, in press NOLTA 2013 Santa Fe NM.

SOURCE: eeg_eof.zip

MATLAB software for computing the lagged correlation (linear and mutual information) for a non-informally measured, possibly heterogeneous population
 
This source contains a non-optimized, sometimes stupidly parallelized, version of the lagged correlation (both linear and mutual information based correlations) calculation for a non-uniformly sampled population. The zip file contains several versions of the code ranging from a single black box version to a version that can be run on a BEOWULF cluster.  This code (or similar versions) was used for:
 
Hripcsak, G., Albers, D.J., Perotte, A., “Exploiting time in electronic health record correlations,” JAMIA 18 (2011), 109-115

Claassen, J., Perotte, A., Albers, D.J.,, Kleinberg, S., Schmidt, J.M., Tu, B., Badjatia, N., Lee, K., Mayer, S.A., Connolly, E.S., Hirsch, L.J., and Hripcsak, G., “Electrographic seizures after subarachnoid hemorrhage lead to derangement of brain homeostasis in humans,” accepted to Annals of Neurology, 2013

SOURCE: llc.zip
 
MATLAB software for mechanistic modeling of glucose/insulin for a variety of nutrition schemes for individuals and populations.
 
This source contains a non-optimized, sometimes stupidly parallelized, simulation of the Sturgis et. al. mechanistic glucose/insulin model. The code contains several nutrition schemes, and can be run for individuals, a population, and is set up for sweeping parameters to observe physiologic changes. The zip file contains several versions of the code useful for different contexts, including code meant to be run on a BEOWULF cluster.  This code (or similar versions) was used for:
 
Albers, D.J., Hripcsak, G, Schmidt, M., “Population Physiology: Leveraging Electronic Health Record Data to Understand Human Endocrine Dynamics,” PLoS One 7 (12), e48058, 2012

Sedigh-Sarvestani, M., and Albers, D.J., and Gluckman, B.J., “Data assimilation of glucose dynamics for use in the intensive care unit,”, 34th Annual International Engineering in Medicine and Biology Society (2012) in press.

Albers, D.J., Elhadad, N., Tabak, E., Perotte, A., Hripcsak, G, “Dynamical phenotying: using temporal analysis of clinically collected physiologic data to stratify populations ,” submitted.

SOURCE: mechanistic_glucose_modeling.zip
 
MATLAB software used for general manipulation, simulation, etc., of EHR data.
 
This source contains a non-optimized, sometimes stupidly parallelized, collection of calculations, some simple, some not, that are useful for manipulating EHR data using MATLAB. The tools range from methods for selecting (without replacement) a random set of patients, to creating a fake EHR, to removing features of the data (e.g., NaNs, 0s, etc.) that can cause computational headaches.
 
SOURCE: ehr_resources.zip
 
COMING SOON: MATLAB software for: (i) mediation analysis, (ii) hierarchical clustering of time dependent signals; (iii) select mex (MATLAB-C hybrid) versions of various compuations.
 
All questions, comments, bug reports, etc., should be directed to david dot albers at dbmi dot columbia dot edu.
 

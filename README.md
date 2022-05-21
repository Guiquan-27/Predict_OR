## A clinician-friendly machine learning system for predicting ovarian response and deploying ovarian stimulation strategies in assisted reproductive technology
DOI:(to edit)  

Reproductive health significantly influences both the overall health of individuals (i.e., cardiometabolic, mental and offspring congenital disorders) and the sustainable development of human society. Ovarian stimulation (OS), the foundation of successful ART treatments, has been impeded by the uncontrollability of ovarian response since OS was invented. This is mainly due to the unpredictable individual variability, long-term and complex therapies, a vast number of choices and limited evidence-based approaches for subgroups of responders. We developed a clinician-friendly machine learning (ML) based decision support system which achieved excellent performance both internally and externally. This ML system provides an example for diagnosing abnormal ovarian response earlier and faster, understanding the pathogenic profiles of risk factors both globally and locally, and deploying individualized OS strategies that can strike a balance between the therapeutic effect and economic costs. It can potentially be expanded to the ML applications of other medicine fields.
# The ML system
## Submodels included
- **PORDM:** Diagnosis model for poor ovarian response
- **HORDM:** Diagnosis model for hyper overian reponse
- **PORSM:** Strategy model for poor ovarian response
- **HORSM:** Strategy model for hyper ovarian response
## Features included in the submodels
### PORDM
**13 baseline characteristics:** AMH, basal AFC, diagnosis including POI or DOR, basal FSH, age, P, weight, DBP, WBC, ALT, RBC, duration of infertility, basal LH
### HORDM
**10 baseline characteristics:** AMH, basal AFC, basal FSH, Age, basal LH, diagnosis including POI or DOR, PCOS, PLT, weight, duration of infertility
### PORSM
**Features of PORDM and four critical OS interventions**
### PORSM
**Features of HORDM and four critical OS interventions**
> **Four critical OS interventions:**  OS regimens, FSH starting dosage, using rFSH or uFSH, using exogenous LH or not

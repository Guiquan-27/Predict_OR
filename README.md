# A clinician-friendly machine learning system for predicting ovarian response and deploying ovarian stimulation strategies in IVF
Ovarian stimulation (OS), the foundation of successful IVF treatments, has been impeded by the uncontrollability of ovarian response since OS was invented. This is mainly due to the unpredictable individual variability, long-term and complex therapies, a vast number of choices and limited evidence-based approaches for subgroups of responders. We developed a clinician-friendly machine learning (ML) based decision support system which achieved excellent performance both internally and externally. This ML system provides an example for diagnosing abnormal ovarian response earlier and faster, understanding the pathogenic profiles of risk factors both globally and locally, and deploying individualized OS strategies for patients undergoing IVF/ICSI. It can potentially be expanded to the ML applications of other medicine fields.  
  
A publicly accessible web-based application based on this ML system is provided [here](http://www.ovarianresp.top/ovarianresp/).  
  
**More details:** (to edit)
  
## Submodels included
- **PORRM:** Risk prediction model for poor ovarian response
- **HORRM:** Risk prediction model for hyper overian reponse
- **PORSM:** Strategy model for poor ovarian response
- **HORSM:** Strategy model for hyper ovarian response
## Features included in the submodels
### PORRM
- **Baseline characteristics (13):** AMH, basal AFC, diagnosis including POI or DOR, basal FSH, age, P, weight, DBP, WBC, ALT, RBC, duration of infertility, basal LH
### HORRM
- **Baseline characteristics (10):** AMH, basal AFC, basal FSH, Age, basal LH, diagnosis including POI or DOR, PCOS, PLT, weight, duration of infertility
### PORSM
- **Features of PORRM and four critical OS interventions (17)**
### PORSM
- **Features of HORRM and four critical OS interventions (14)**
> **Four critical OS therapeutic decisions:**  OS protocol, FSH starting dose, using rFSH or uFSH, exogenous LH supplementation

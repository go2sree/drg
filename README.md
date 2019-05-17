# drg
The introduction of diagnosis-related groups (DRGs) in prospective payment systems has put pressure on hospitals to use resources efficiently    In the DRG system, patients admitted to the hospital are classified into groups with similar clinical and demographic characteristics, and thus are expected to use similar amounts of hospital resources. Reimbursement to a hospital for inpatient care is based on the DRG assigned at the time of discharge.   Moreover, the decision regarding which resources have to be allocated, when and for which inpatient, is often made under uncertainty and should depend on DRG-information   In hospitals, and in general in the service industry, there are fixed costs so that the maximization of profit can only be achieved by maximizing revenue, which in turn is linked to DRGs.   By accurately classifying an inpatient’s DRG in the early stages of their visit, estimates of the revenues, costs, and recovery times can be obtained, allowing hospital resources to be managed effectively and efficiently  Before the execution of the DRG grouper, parameter  values, such as the primary diagnosis, secondary diagnoses, clinical procedures, age, gender as well as weight in the case of newborns have to be entered into the software.   Diagnoses are coded by using the International Statistical Classification of Diseases and Related Health Problems (ICD). The first three levels of ICD codes correspond to DRGs.  The algorithm first determines one of 23 major diagnostic categories (MDC). Those are, in particular, defined by the primary diagnosis (i.e., the reason for the hospitalization). However, if the primary diagnosis is imprecisely documented, an error DRG will be returned.  On the contrary, if the patient has, e.g., a transplantation, a pre-MDC  is returned. After determining the MDC, clinical procedures and comorbidities lead to the patient’s DRG, which can be categorized into surgical, medical, and other DRGs.  Finally, within these categories, the age of the patient, or the weight in the case of newborns, may lead to a different DRG subtype.
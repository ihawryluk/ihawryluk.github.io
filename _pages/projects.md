---
permalink: /projects/
title: "Projects"
author_profile: true
---

## Phd Thesis: Statistical methods for characterising the severity of an emerging pathogen: case studies of the COVID-19 pandemic

My PhD thesis can be viewed [here](https://github.com/ihawryluk/phd_thesis/blob/main/hawryluk_phd_thesis.pdf).

*The three following projects listed below are part of my PhD thesis.*




## Gaussian process nowcasting: application to COVID-19 mortality reporting

*Published in Proceedings of the Thirty-Seventh Conference on Uncertainty in Artificial Intelligence, 2021.*

<!-- Updating observations of a signal due to the delays in the measurement process is a common problem in signal processing, with prominent examples in a wide range of fields. An important example of this problem is the nowcasting of COVID-19 mortality: given a stream of reported counts of daily deaths, can we correct for the delays in reporting to paint an accurate picture of the present, with uncertainty? Without this correction, raw data will often mislead by suggesting an improving situation. We present a flexible approach using a latent Gaussian process that is capable of describing the changing auto-correlation structure present in the reporting time-delay surface. This approach also yields robust estimates of uncertainty for the estimated nowcasted numbers of deaths. We test assumptions in model specification such as the choice of kernel or hyper priors, and evaluate model performance on a challenging real dataset from Brazil. Our experiments show that Gaussian process nowcasting performs favourably against both comparable methods, and against a small sample of expert human predictions. Our approach has substantial practical utility in disease modelling — by applying our approach to COVID-19 mortality data from Brazil, where reporting delays are large, we can make informative predictions on important epidemiological quantities such as the current effective reproduction number. -->

**Why?** COVID-19 mortality reporting is delayed, leading to misleading data often suggesting an improving situation.  
**What?** We developed a nowcasting (forecasting of 'now' or very near future) method to correct for reporting delays in COVID-19 mortality data.  
**How?** We used a latent Gaussian process to describe the auto-correlation structure in the reporting delays.  
**Result?** Our method outperformed comparable approaches and human expert predictions, providing accurate nowcasts with robust uncertainty estimates.  

[Read the publication <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://proceedings.mlr.press/v161/hawryluk21a.html)

[Code on GitHub <img src="https://img.icons8.com/?size=30&id=AZOZNnY73haj&format=png&color=000000" width="24" height="24" alt="GitHub"/>](https://github.com/ihawryluk/GP_nowcasting)

Tech: Python, Stan, R, Pandas, Matplotlib <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




## Inference of COVID-19 epidemiological distributions from Brazilian hospital data

*Published in Journal of the Royal Society Interface, 2020.*

<!-- Knowing COVID-19 epidemiological distributions, such as the time from patient admission to death, is directly relevant to effective primary and secondary care planning, and moreover, the mathematical modelling of the pandemic generally. We determine epidemiological distributions for patients hospitalized with COVID-19 using a large dataset (N = 21 000 − 157 000) from the Brazilian Sistema de Informação de Vigilância Epidemiológica da Gripe database. A joint Bayesian subnational model with partial pooling is used to simultaneously describe the 26 states and one federal district of Brazil, and shows significant variation in the mean of the symptom-onset-to-death time, with ranges between 11.2 and 17.8 days across the different states, and a mean of 15.2 days for Brazil. We find strong evidence in favour of specific probability density function choices: for example, the gamma distribution gives the best fit for onset-to-death and the generalized lognormal for onset-to-hospital-admission. Our results show that epidemiological distributions have considerable geographical variation, and provide the first estimates of these distributions in a low and middle-income setting. At the subnational level, variation in COVID-19 outcome timings are found to be correlated with poverty, deprivation and segregation levels, and weaker correlation is observed for mean age, wealth and urbanicity. -->

**Why?** Effective care planning and pandemic modelling require accurate COVID-19 epidemiological distributions, especially in low and middle-income settings.  
**What?** We determined epidemiological distributions, such as onset to death time, for COVID-19 patients using a large hospitalisation dataset from Brazil.  
**How?** We applied a joint Bayesian subnational hierarchical model with partial pooling to describe data across Brazilian states, and selected for th best fitting underlying probability density functions with a model selection method.  
**Result?** We found significant geographical variation in epidemiological distributions, providing essential estimates for COVID-19 modelling in Brazil.  

[Read the publication <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://royalsocietypublishing.org/doi/10.1098/rsif.2020.0596)

[Code on GitHub <img src="https://img.icons8.com/?size=30&id=AZOZNnY73haj&format=png&color=000000" width="24" height="24" alt="GitHub"/>](https://github.com/mrc-ide/Brazil_COVID19_distributions)

Tech: Python, Stan, R, Pandas, Matplotlib, scikit-learn <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




## Application of referenced thermodynamic integration to Bayesian model selection

*Published in PLoS ONE, 2023.*

<!-- Evaluating normalising constants is important across a range of topics in statistical learning, notably Bayesian model selection. However, in many realistic problems this involves the integration of analytically intractable, high-dimensional distributions, and therefore requires the use of stochastic methods such as thermodynamic integration (TI). In this paper we apply a simple but under-appreciated variation of the TI method, here referred to as referenced TI, which computes a single model’s normalising constant in an efficient way by using a judiciously chosen reference density. The advantages of the approach and theoretical considerations are set out, along with pedagogical 1 and 2D examples. The approach is shown to be useful in practice when applied to a real problem —to perform model selection for a semi-mechanistic hierarchical Bayesian model of COVID-19 transmission in South Korea involving the integration of a 200D density. -->

**Why?** Normalising constants are crucial for Bayesian model selection but are often difficult to compute for high-dimensional distributions.  
**What?** We applied referenced thermodynamic integration (TI) to efficiently compute normalising constants.  
**How?** We propose solutions to effectively construct a reference density for an arbitrary problem. We also used a reference density in the TI method to perform model selection for a complex Bayesian model of COVID-19 transmission.  
**Result?** Demonstrated the practical utility of the method with a successful application to a high-dimensional real-world problem.  

[Read the publication <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://doi.org/10.1371/journal.pone.0289889)

[Code on GitHub <img src="https://img.icons8.com/?size=30&id=AZOZNnY73haj&format=png&color=000000" width="24" height="24" alt="GitHub"/>](https://github.com/mrc-ide/referenced-TI)

Tech : Python, Stan, NumPyro, Pandas, Matplotlib, scikit-learn, SciPy <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




## Peer-group Behaviour Analytics of Windows Authentications Events Using Hierarchical Bayesian Modelling

*Presented at the AAAI 2023 Artificial Intelligence for Cybersecurity workshop, 2023.*

<!-- Cyber-security analysts face an increasingly large number of alerts received on any given day. This is mainly due to the low precision of many existing methods to detect threats, producing a substantial number of false positives. Usually, several signature-based and statistical anomaly detectors are implemented within a computer network to detect threats. Recent efforts in User and Entity Behaviour Analytics modelling shed a light on how to reduce the burden on Security Operations Centre analysts through a better understanding of peer-group behaviour. Statistically, the challenge consists of accurately grouping users with similar behaviour, and then identifying those who deviate from their peers. This work proposes a new approach for peer-group behaviour modelling of Windows authentication events, using principles from hierarchical Bayesian models. This is a two-stage approach where in the first stage, peer-groups are formed based on a data-driven method, given the user's individual authentication pattern. In the second stage, the counts of users authenticating to different entities are aggregated by an hour and modelled by a Poisson distribution, taking into account seasonality components and hierarchical principles. Finally, we compare grouping users based on their human resources records against the data-driven methods and provide empirical evidence about alert reduction on a real-world authentication data set from a large enterprise network. -->

**Why?** Cybersecurity analysts are overwhelmed by false positives from existing threat detection methods.  
**What?** We proposed a new approach for modelling peer-group behavior of Windows authentication events.  
**How?** We used hierarchical Bayesian models in a two-stage approach involving data-driven peer-group formation and Poisson distribution modeling.  
**Result?** We showed empirical evidence of reduced false positives on a real-world dataset, aiding in more efficient threat detection.  


[Read the ArXiv preprint <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://arxiv.org/abs/2209.09769)

Code and data were proprietary and could not be shared.

Tech: Python, NumPyro, Pandas, Matplotlib, Spark, SQL <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




*The projects listed below are projects I substantially contributed to but did not lead.*




## Spatial and temporal fluctuations in COVID-19 fatality rates in Brazilian hospitals

*Published in Nature Medicine, 2022.*

<!-- The severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) Gamma variant of concern has spread rapidly across Brazil since late 2020, causing substantial infection and death waves. Here we used individual-level patient records after hospitalization with suspected or confirmed coronavirus disease 2019 (COVID-19) between 20 January 2020 and 26 July 2021 to document temporary, sweeping shocks in hospital fatality rates that followed the spread of Gamma across 14 state capitals, during which typically more than half of hospitalized patients aged 70 years and older died. We show that such extensive shocks in COVID-19 in-hospital fatality rates also existed before the detection of Gamma, but that they were less synchronized and less intense. We document the persistence of above-baseline hospital fatality rates for Gamma across sex, age, comorbidities and hospital regions and identify extensive changes in fatality rates for non-COVID-19 acute respiratory distress syndrome and sepsis, indicating a substantial breakdown of healthcare services. Our findings suggest that transient extreme mortality shocks can occur when health services are strained and that this risk can be exacerbated by the presence of variants of concern. Our results emphasize the need for effective measures
 to minimize population-wide mortality and morbidity caused by highly transmissible and deadly pathogens such as SARS-CoV-2, especially in low- and middle-income countries.
 -->

 **Why?** The Gamma variant of COVID-19 caused extreme mortality shocks, highlighting the need to understand fatality rate variations.  
**What?** We documented sweeping shocks in hospital fatality rates in Brazilian state capitals during the Gamma variant spread.  
**How?** We developed a Bayesian multi-strain fatality model, which we then use to analyse individual patient records from a large dataset, focusing on temporal and geographical variations.
**Result?** Our analysis evealed significant mortality shocks and suggested that health service strain and variant spread exacerbate mortality risks.  

[Read the publication <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://www.nature.com/articles/s41591-022-01807-1)

[Code on GitHub <img src="https://img.icons8.com/?size=30&id=AZOZNnY73haj&format=png&color=000000" width="24" height="24" alt="GitHub"/>](https://github.com/CADDE-CENTRE/covid19_brazil_hfr)

Tech: R, Stan, ggplot <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




## The association between mechanical ventilator compatible bed occupancy and mortality risk in intensive care patients with COVID-19: a national retrospective cohort study

*Published in BMC Medicine, 2021.*

<!-- The literature paints a complex picture of the association between mortality risk and ICU strain. In this study, we sought to determine if there is an association between mortality risk in intensive care units (ICU) and occupancy of beds compatible with mechanical ventilation, as a proxy for strain. A national retrospective observational cohort study of 89 English hospital trusts (i.e. groups of hospitals functioning as single operational units). Seven thousand one hundred thirty-three adults admitted to an ICU in England between 2 April and 1 December, 2020 (inclusive), with presumed or confirmed COVID-19, for whom data was submitted to the national surveillance programme and met study inclusion criteria. A Bayesian hierarchical approach was used to model the association between hospital trust level (mechanical ventilation compatible), bed occupancy, and in-hospital all-cause mortality. Results were adjusted for unit characteristics (pre-pandemic size), individual patient-level demographic characteristics (age, sex, ethnicity, deprivation index, time-to-ICU admission), and recorded chronic comorbidities (obesity, diabetes, respiratory disease, liver disease, heart disease, hypertension, immunosuppression, neurological disease, renal disease). One hundred thirty-five thousand six hundred patient days were observed, with a mortality rate of 19.4 per 1000 patient days. Adjusting for patient-level factors, mortality was higher for admissions during periods of high occupancy (> 85% occupancy versus the baseline of 45 to 85%) [OR 1.23 (95% posterior credible interval (PCI): 1.08 to 1.39)]. In contrast, mortality was decreased for admissions during periods of low occupancy (< 45% relative to the baseline) [OR 0.83 (95% PCI 0.75 to 0.94)]. Increasing occupancy of beds compatible with mechanical ventilation, a proxy for operational strain, is associated with a higher mortality risk for individuals admitted to ICU. Further research is required to establish if this is a causal relationship or whether it reflects strain on other operational factors such as staff. If causal, the result highlights the importance of strategies to keep ICU occupancy low to mitigate the impact of this type of resource saturation. -->

**Why?** Understanding the impact of ICU strain on mortality risk is crucial for managing resources during pandemics.  
**What?** We investigated the association between ICU bed occupancy and mortality risk in COVID-19 patients.  
**How?** We employed a Bayesian hierarchical model to analyse data from English hospital trusts, adjusting for various factors.  
**Result?** Our analysis reealed that high ICU occupancy is associated with increased mortality risk, emphasising the need to manage ICU strain.  

[Read the publication <img src="https://img.icons8.com/?size=30&id=37917&format=png&color=000000" width="24" height="24" alt="Document"/>](https://doi.org/10.1186/s12916-021-02096-0)

Code and data were proprietary and could not be shared.

Tech: R, Stan, brms, ggplot <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>




## Use of Contrastive Learning to Predict the Prevalence of Malaria in Africa Using Satellite Imagery

*paper in preparation*

<!-- In 2021, there were 247 million malaria cases globally, with the majority of cases in sub-Saharan Africa. Currently, the prevalence of malaria in sub-Saharan Africa is calculated with the help of Demographic Health Surveys (DHS). Using remote sensing combined with unsupervised deep learning techniques can help effectively predict the prevalence of malaria, using geographical features like forest cover, proximity to water, urban density and much more. Contrastive learning is an unsupervised deep learning technique which can learn effective representations of satellite imagery. With the help of contrastive learning, we achieve malaria prevalence prediction with a Mean Absolute Error (MAE) of 0.06 in African countries, over a period of 20 years. Even for years and places where no DHS data exists, the deep learning model is able to predict malaria prevalence based on the representation of images learned. The deep learning model is benchmarked against handcrafted covariates used until now to predict the prevalence of malaria from the DHS data. It is found that the deep learning contrastive model learns effective representation of malaria spread and provides a better accuracy for predicting malaria prevalence. -->

**Why?** Accurate malaria prevalence prediction is vital for effective intervention, especially where the household survey data is lacking.  
**What?** We estimated the malaria prevalence in Africa using remote sensing and deep learning techniques.  
**How?** We applied contrastive learning to satellite imagery to predict malaria prevalence with high accuracy.  
**Result?** The model achieved a low error, demonstrating the model's effectiveness in predicting malaria prevalence even without household survey data.


Tech: Python, Tensorflow, PyTorch, NumPyro, Google Earth Engine, gdal, weights&biases <img src="https://img.icons8.com/?size=30&id=N5jTjpBKVT8t&format=png&color=000000" width="24" height="24" alt="Tech"/>

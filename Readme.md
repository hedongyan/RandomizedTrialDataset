# Introduction

## What is the diffference of data that was generated from randomized trial and observation study?
###
Imagine a perfect (complete compliance, no measurement error, no missing data, no observer effect) randomized trial and observational study for same population, the only difference is the treatment assignment.
###
For example, for observational study, the treatment is assigned by individual's own environment and model which may introduce confouding bias. However, for randomized trial, treatment assignment is independent from any known and unknown variables in our study.

## Why data from randomized trial can provide more 'causal' information compared with observation data?
###
The reason is that treatment assignment is replaced by artificial random number generator, and we are confident enough that random number generator is independent from any variable (known/unknown) if it passed the random test. For example, we can set gammbing to make people to trust randomness of coin and dice, or we can set gacha game to make people trust randomness of random generator of computer. Because if the random number is predictable in limited cost, then the companies will lose money and they will go bankrupt soon. So, the treatment assignemnt can not be effect of any variable that we want to study.
###
The philosophy of such randomization is "Socratic Ignorance" and "Law of Negation of Negation / Double Negtive": the world is too complex to understand, what we know is only our own ignorance. The randomized assignment can be regarded as the application of such philosophy. From the negation of ignorance, we can get some knowledge of 'causal'.

## What should we do to get a 'causal' model? Why such 'causal' model is useful?
###
The average causal effect 
be inferenced from randomized trial as we know. Most importantly, we can learn a model to predict outcome for individuals under intervention, although the individual causal effect can not be learned as [1] illustrated. Any model which claimed 'causality'/'causal' should be evaluated in order to avoid useless, and untestable assumptations for reality. When the model rejected the null hypothesis and passed the 'causal' prediction test, such as precision>0.95 and recall>0.95, then it can be called a "causal model" in this study. But we must understand that individual causal effect can never be learned if there was no widerly accepted physical rule/law/knowledge/simulation. 
###
Following such sheme, the 'causal' knowledge of randomized trial can be abstracted by our 'causal' model. Next, we can provide advices for other individuals who were not in the randomized trial: what will happen if they follow the decision of the 'causal' model rather than what will happen if they follow the original treatment assignment.

## How to pass the 'causal' prediction test?

### 
The first step is to design a **valuable** randomized trial from history records.

### 
The second step is to collect high dimensional, hetergeneous, multi-source data in randomized trial to increase to probability that the model pass the 'causal' prediction test. The data collection of pre-treatment variable should cost not too much addressing futural application cost for other individuals. In the same time, observation can be complement for the 'causal' model learning.

### 
The third step is to learn a 'causal' model from data and do the 'causal' prediction test. Then we repeat those three steps until it passed.

### 
The forth step is to collect observation data and generalize the model to observation data for real world applications.

## What the 'causal' model can be used to do?
### 
It can only provide decision advices for given treatment in randomized trial. If a treatment was never randomized, then we can never get 'causal' knowledge about its effect except we add common accepted assumptations by domain experts.


## What should we do to update 'causal' information in our 'causal' model?
### 
In order to update our 'causal' model, we need to do new randomized trials and passed the new test. Sometime, we can do some harmless randomized trials for the trade-off between exploration and exploitation.


# Randomized Dataset

|                                                             Dataset                                                             |   Instance  |                                                            Outcome                                                            |                                             Treatment                                            |                                  Link                                  |
|:-------------------------------------------------------------------------------------------------------------------------------:|:-----------:|:-----------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
|                   CPAP Pressure and Flow Data from a Local Trial of 30 Adults at the University of Canterbury                   |      30     |                                                           Breathing                                                           |                                Continuous positive airway pressure                               |        https://physionet.org/content/cpap-data-canterbury/1.0.1/       |
| Safety and Preliminary Efficacy of Intranasal Insulin for Cognitive Impairment in Parkinson Disease and Multiple System Atrophy |      16     |                                                       Parkinson disease                                                       |                                        Intranasal insulin                                        |               https://physionet.org/content/inipdmsa/1.0/              |
|                                   Tai Chi, Physiological Complexity, and Healthy Aging - Gait                                   |      60     |                                                       Gait and EMG data                                                       |                                              Tai Chi                                             |              https://physionet.org/content/taichidb/1.0.2/             |
|         ECG Effects of Dofetilide, Moxifloxacin, Dofetilide+Mexiletine, Dofetilide+Lidocaine and Moxifloxacin+Diltiazem         |      22     |                                                              ECG                                                              | Dofetilide, Moxifloxacin, Dofetilide+Mexiletine, Dofetilide+Lidocaine and Moxifloxacin+Diltiazem |              https://physionet.org/content/ecgdmmld/1.0.0/             |
|                                 ECG Effects of Ranolazine, Dofetilide, Verapamil, and Quinidine                                 |      22     |                                                              ECG                                                              |                         Ranolazine, Dofetilide, Verapamil, and Quinidine                         |              https://physionet.org/content/ecgrdvq/1.0.0/              |
|                                               CAST RR Interval Sub-Study Database                                               |     734     |                                                 Cardiac arrhythmia suppression                                                |               Encainide, flecainide, moricizine (antiarrhythmic drugs) or a placebo              |               https://physionet.org/content/crisdb/1.0.0/              |
|                                     Randomized trial of AKI alerts in hospitalized patients                                     |     6030    |                                                      Acute Kidney Injury                                                      |                              Electronic AKI alert versus usual care                              |    https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.4f4qrfj95   |
|                     Telerehabilitation program for COVID-19 survivors (TERECO) - Randomized controlled trial                    |     120     | Exercise capacity, lower-limb muscle strength (LMS), pulmonary function, health-related quality of life (HRQOL), and dyspnoea |                         Telerehabilitation program for COVID-19 survivors                        |    https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.59zw3r27n   |
|                                                Bicycling comfort video experiment                                               |    15289    |                                                         Bicycle rating                                                        |                                            Video Type                                            |        https://datadryad.org/stash/dataset/doi:10.25338%2FB8KG77       |
|                                                    Megafon uplift competition                                                   | 1.5 million |                                                        User conversion                                                        |                                          Exposure                                           | https://ods.ai/tracks/df21-megafon/competitions/megafon-df21-comp/data |
|                                                    Infant Health and Development Program                                                   | 1090 |                                                        Cognitive development, Behavior problems, Health status                                                       |                                          Home visits, attendance at a special child development center                                           | https://www.icpsr.umich.edu/web/HMCA/studies/9795 |
|                                                    National Supported Work Evaluation Study                                                   | 6600 |                                                        effects of the Supported Work Program                                                       |                                          Offered a job in supported work                                           | https://www.icpsr.umich.edu/web/ICPSR/studies/7865 |

[1] Gentzel, Amanda M., Purva Pruthi, and David Jensen. "How and why to use experimental data to evaluate methods for observational causal inference." International Conference on Machine Learning. PMLR, 2021.

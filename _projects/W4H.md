---
layout: page
title: W4H 
description: Wearables for Health
img: assets/img/projects/w4h/w4h.jpg
importance: 5
category: current
toc:
  sidebar: left
---

## Description

Wearable data are becoming an important source of health and disease data as they inform on a variety of personal, behavioral, social, contextual, and environmental health-relevant factors. Wearables have been primarily used for activity tracking and gained popularity with fitness applications; however, more recently, these devices have been used in an increasing number of health applications, including health monitoring, clinical-care, remote clinical-trials, drug delivery, and disease characterization to name a few.

We linked wearable data to clinical outcomes and we have found that data from wearable measurements are as good or better than clinical measurements for predicting adverse health events in cancer medicine, diagnosing neuromotor disorders in infants and for cardiac monitoring. We implement an open-source toolkit (W4H) to benefit the larger health community by working with our community of stakeholders comprised of the medical teams from our previous projects.


#### Wearables for Health Toolkit

<div class="row">
  <div class="text-center">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        {% include figure.html path="assets/img/projects/w4h/Architecture.png" title="Architecture" class="img-fluid rounded z-depth-1" width="75%" %}
    </div>
  </div>
</div>
<div class="caption">
  W4H - Architecture
</div>

- We first conceptualize wearable data as Geo-referenced Multivariate Time Series (GeoMTS) data, i.e., time series with geotagged information. This conceptualization allows us to represent different types of wearable data in a single form so we can separate the wearable type from its data management and analysis.
<br>

<div class="row">
  <div class="text-center">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        {% include figure.html path="assets/img/projects/w4h/W4H_Database.png" title="W4H_Database" class="img-fluid rounded z-depth-1" width="75%"%}
    </div>
  </div>
</div>
<div class="caption">
  W4H - Database
</div>

- Next, we develop these algorithms and models into a W4H Toolkit that we evaluate on three use cases with our community stakeholders. To facilitate the dissemination of our results and improve the sustainability of the W4H Toolkit we will implement our algorithms on Spark, a popular big data platform, and release an extensible W4H Toolkit software package that the larger health research community will be able to use with their data and sensors.

<br>

#### Case Studies

- Cancer Patient Monitoring: We analyze cancer patients under IRB protocol OS-16-2 at USC who were undergoing treatment with chemotherapy to study their fatigue level. Our results show that ECOG score did not predict the rate of adverse events, such as unexpected hospitalization and unplanned trips to the day hospital for hydration. By comparison, determination of the patient’s calorie expenditure during waking hours was highly predictive of serious adverse events over the course of the study.
<br>

<div class="row">
  <div class="text-center">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        {% include figure.html path="assets/img/projects/w4h/Cancer.png" title="Cancer-Study" class="img-fluid rounded z-depth-1" width="75%"%}
    </div>
  </div>
</div>
<div class="caption">
</div>

- Cardiac Monitoring: Atrial fibrillation (AF) affects 1% of the general population and causes a third of all strokes. Smartphone ECG has the potential to overcome the shortcomings of traditional ECG recorders. The results have demonstrated the unique capabilities to expand the diagnostic scope, allowing patients to nimbly monitor for arrhythmia instantly on demand and outside of a traditional healthcare setting. Our further data analysis not only validates the ability of devices to accurately detect cardiac rhythms, but also demonstrates a consumer appetite for a device that enables continuous monitoring.

<br>

<div class="row">
  <div class="text-center">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        {% include figure.html path="assets/img/projects/w4h/Cardiac.jpeg" title="Cardiac-Study" class="img-fluid rounded z-depth-1" width="75%"%}
    </div>
  </div>
</div>
<div class="caption">
</div>

- Infant Neuromotor Monitoring: Early identification of impaired neuromotor control in infancy is necessary in order to provide early therapy intervention in accordance with known principles of experience-dependent neuroplasticity. Early intervention is often not initiated until an infant has demonstrated a consistent and severe delay in the acquisition of developmental milestones, in contrast with known principles of experience-dependent neuroplasticity. We have recently validated the use of wearable sensors for unobtrusive full-day, in-home movement monitoring of spontaneous infant leg movements.

<br>

<div class="row">
  <div class="text-center">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        {% include figure.html path="assets/img/projects/w4h/Infant.jpeg" title="Infant-Study" class="img-fluid rounded z-depth-1" width="75%"%}
    </div>
  </div>
</div>
<div class="caption">
</div>

## Related Publications

- Nocera, L., Hajisafi, A., Siampou, M. D., Azarijoo, B., and Shahabi C. **Multi-Context Graph Neural Networks for Enhanced Multivariate Time-Series Analysis in Healthcare (Presentation)** Presented at the NIH Special Track at Intelligent Systems for Molecular Biology (ISMB), 2024 [[slides](https://f1000research.com/slides/13-1222)]

- Zeighami, S., Seshadri, R., and Shahabi C., **A Neural Database for Answering Aggregate Queries on Incomplete Relational Data.** IEEE Trans. Knowl. Data Eng. (TKDE), 2024

- Zeighami, S., Seshadri, R., and Shahabi C., **A Neural Database for Answering Aggregate Queries on Incomplete Relational Data.** (Extended Abstract) IEEE International Conference on Data Engineering (ICDE), 2024

- Hajisafi, A., Siampou, M. D., Bi, J, Nocera, L., and Shahabi, C. **Wearables for Health (W4H) Toolkit for Acquisition, Storage, Analysis and Visualization of Data from Various Wearable Devices.** (Demo) IEEE International Conference on Data Engineering (ICDE), 2024

- Siampou, M. D., Nocera, L., Oh, J., Smith, B. A., and Shahabi C., **An Algorithmic Approach for Detecting Neuromotor Developmental Disabilities in Infants from Wearable Sensor Data.** (Oral) International Conference of IEEE Engineering in Medicine and Biology Society (EMBC), 2024

- Hajisafi, A., Lin, H., Chiang, Y. Y., and Shahabi, C. **Dynamic GNNs for Precise Seizure Detection and Classification from EEG Data.** Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD), 2024

- Zeighami, S., and Shahabi C., **Theoretical Analysis of Learned Database Operations under Distribution Shift through Distribution Learnability.** International Conference on Machine Learning (ICML), 2024

- Zeighami, S., and Shahabi C., **BiasBuster: a Neural Approach for Accurate Estimation of Population Statistics using Biased Location Data..** IEEE Conference on Mobile Data Management (MDM), 2024

- Zeighami, S., and Shahabi C., **Towards Establishing Guaranteed Error for Learned Database Operations.** International Conference on Learning Representations (ICLR), 2024

- Lin, H., Shaham, S., Chiang, Y. Y., and Shahabi, C. **Generating Realistic and Representative Trajectories with Mobility Behavior Clustering.** ACM SIGSPATIAL/GIS, 2023

- Hajisafi, A., Lin, H., Shaham, S., Hu, H., Siampou, M. D., Chiang, Y. Y., and Shahabi, C. **Learning Dynamic Graphs from All Contextual Information for Accurate Point-of-Interest Visit Forecasting.** ACM SIGSPATIAL/GIS, 2023

- Shaham, S., Ghinita, G., Ahuja, R., Krumm, J. and Shahabi, C. **HTF: Homogeneous Tree Framework for Differentially Private Release of Large Geospatial Datasets with Self-tuning Structure Heighy.** ACM Trans. Spatial Algorithms Syst. (TSAS), 2023

- Ahuja, R., Zeighami, S., Ghinita, G., and Shahabi, C. **A Neural Approach to Spatio-temporal Data Release with user-level Differential Privacy.**, Proceedings of the ACM on Management of Data (SIGMOD), 2023.

- Tran, L., Li Y., Nocera, L., Shahabi, C., and Xiong, L. **MultiFusionNet: Atrial Fibrillation Detection With Deep Neural Networks**, AMIA 2020 Information Summit , Houston, Texas, March 23-26, 2020.

- Tanachat Nilanon, Luciano P. Nocera, Alexander S. Martin, Anand Kolatkar, Marcella May, Zaki Hasnain, Naoto T. Ueno, Sriram Yennu, Angela Alexander, Aaron E. Mejia, Roger Wilson Boles, Ming Li, Jerry S. H. Lee, Sean E. Hanlon, Frankie A. Cozzens Philips, David I. Quinn, Paul K. Newton, Joan Broderick, Cyrus Shahabi, Peter Kuhn, and Jorge J. Nieva, **Use of Wearable Activity Tracker in Patients With Cancer Undergoing Chemotherapy: Toward Evaluating Risk of Unplanned Health Care Encounters**, JCO Clinical Cancer Informatics, Sep 24, 2020.

- Tran, L., Nguyen, M., and Shahabi, C. **Representation Learning for Early Sepsis Prediction**, 2019 Computing in Cardiology (CinC), Singapore, 8-11 Sept. 2019.

- Abrishami, M. S., Nocera, L., Mert, M., Trujillo-Priego, I.A., Purushotham, S., Shahabi, C., and Smith, B. A., **Identification of Developmental Delay in Infants using Wearable Sensors: Full-Day Leg Movement Statistical Feature Analysis**, IEEE Journal of Translational Engineering in Health and Medicine, 25 January 2019.

<br>

## Software Artifacts

<div class="card-container">
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/StreamSim">
      <img class="repo-img-light w-100" alt="USC-InfoLab/StreamSim" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=StreamSim&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/StreamSim" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=StreamSim&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/pyGarminAPI">
      <img class="repo-img-light w-100" alt="USC-InfoLab/pyGarminAPI" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=pyGarminAPI&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/pyGarminAPI" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=pyGarminAPI&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
</div>

<div class="card-container">
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/fft_approximate">
      <img class="repo-img-light w-100" alt="USC-InfoLab/fft_approximate" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=fft_approximate&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/fft_approximate" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=fft_approximate&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
  <div class="repo p-2 text-center">
  <a href="https://github.com/USC-InfoLab/w4h-integrated-toolkit">
      <img class="repo-img-light w-100" alt="USC-InfoLab/w4h-integrated-toolkit" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=w4h-integrated-toolkit&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/w4h-integrated-toolkit" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=w4h-integrated-toolkit&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
</div>

<br>


## People

<br>

#### Students

<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/arash.jpeg" title="Arash Hajisafi" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Arash Hajisafi</h5>
    <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/maria.jpeg" title="Maria Despoina Siampou" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Maria Despoina Siampou</h5>
    <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
            {% include figure.html path="assets/img/people/bita-2.png" title="Bita Azarijoo" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
        </div>
        <h5 style="text-align:center;">Bita Azarijoo</h5>
        <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
</div>

<br>

#### Colaborators
<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/peter.jpg" title="Peter Kuhn" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Peter Kuhn</h5>
    <p style="text-align:center;">Keck School of Medicine, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/jorge.jpg" title="Jorge Nieva" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Jorge Nieva</h5>
    <p style="text-align:center;">Keck School of Medicine, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
      <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/leslie.jpg" title="Leslie Saxon" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
      </div>
    <h5 style="text-align:center;">Leslie Saxon</h5>
    <p style="text-align:center;">Keck School of Medicine, USC</p>
  </div>
</div>

<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/beth.jpeg" title="Beth Smith" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Beth Smith</h5>
    <p style="text-align:center;">Keck School of Medicine, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/luciano.jpeg" title="Luciano Nocera" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Luciano Nocera</h5>
    <p style="text-align:center;">Viterbi School of Engineering, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/projects/w4h/yiaoyi.jpg" title="Yao-Yi Chiang" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Yao-Yi Chiang</h5>
    <p style="text-align:center;">Department of CSE, UMN</p>
  </div>
</div>

<br>

#### Principal Investigator
<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        <div class="text-center">
            {% include figure.html path="assets/img/people/cyrus.jpg" title="Cyrus Shahabi" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
        </div>
        <h5 style="text-align:center">Cyrus Shahabi</h5>
        <p style="text-align:center;">Viterbi School of Engineering, USC</p>
    </div>
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
</div>

<br>

## Sponsors
<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
      {% include figure.html path="assets/img/projects/w4h/NIH.jpeg" title="NIH" class="img-fluid rounded z-depth-1 mx-auto" width="50%" %}
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
</div>
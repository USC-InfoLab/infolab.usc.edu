---
layout: page
title: PE4GQ
description: IIS-1910950 - Practical Encryption for Geospatial Queries on Private Data
img: assets/img/projects/pe4gq.jpg
importance: 5
category: current
---

## Table of Contents

- [Description](#description)
- [Related Publications](#related-publications)
- [Software Artifacts](#software-artifacts)
- [People](#people)
- [Sponsors](#sponsors)

## Description

The mobile computing revolution led to the emergence of novel and exciting applications centered on geospatial data, such as location-based services, geosocial networks, ride-sharing, etc. These apps enable users to receive services customized to their locations and to interact with nearby peers. However, recent years also witnessed a growing number of risks associated with sharing of location data. Using location information, adversaries may stage a broad spectrum of attacks, ranging from physical surveillance and stalking, to inferring private details about an individual's health status, political or religious affiliations, alternative lifestyles, etc. The proposed project will investigate secure and efficient techniques to protect the locations of mobile users before they are sent to online services. The focus will be on encryption, which provides a high level of protection, on the same level currently used for confidential data such as social security numbers, bank account information, etc. Location privacy is an important component of the broader online privacy concept. Strong protection for users' whereabouts will bring significant societal benefits in the current online ecosystem, where privacy attacks occur more frequently and with far greater ramifications than before, as illustrated by recent high-profile privacy breaches that affected prominent players in the social media industry (e.g., Google, Facebook, Yahoo).

Several prior research efforts focused on protecting locations through mechanisms like location cloaking, differential privacy or geo-indistinguishability, but none of these existing approaches can properly address the challenges of online, continuous sharing of locations. The only direction that achieves a sufficient amount of protection is represented by cryptographic approaches, but despite recent breakthroughs in the area of functional encryption, processing on encrypted data is both very slow and/or insufficiently expressive to support the use case scenarios required by location-centric applications. The objective of this project is to bridge the gap between geospatial applications on one side and functional encryption on the other. The proposed PE4GQ framework (Practical Encryption for Geospatial Queries) will allow researchers and practitioners to make use of encrypted search primitives on geospatial data with practical computational and communication overhead. The project will adopt existing functional encryption techniques and customize their use to the specific requirements of geospatial queries. The project will address several challenging tasks: (i) identifying a small set of representative plaintext operations that occur commonly in location-centric applications and can be used to express more complex spatial queries; (ii) identifying appropriate cryptographic building blocks that can be used to securely evaluate the operations identified in the first task; (iii) investigating data representations and query encodings that allow efficient secure evaluation by reducing the number of expensive cryptographic primitives; and (iv) investigating performance optimizations that reduce encrypted data processing overhead by taking into account information from the spatial domain (i.e., through cross-layer design).


## Related Publications 

- S. Shaham, G. Ghinita, C. Shahabi, **Enhancing the Performance of Spatial Queries on Encrypted Data Through Graph Embedding.**, DBSec 2020.

- S. Shaham, G. Ghinita, R. Ahuja, J. Krumm, C. Shahabi **HTF: Homogeneous Tree Framework for Differentially-Private Release of Location Data.** SIGSPATIAL/GIS 2021.

- S. Shaham, G. Ghinita, C. Shahabi, **An Efficient and Secure Location-based Alert Protocol using Searchable Encryption and Huffman Codes.** EDBT 2021.

- S. Shaham, G. Ghinita, C. Shahabi, **Differentially-Private Publication of Origin-Destination Matrices with Intermediate Stops.** EDBT 2022.

- S. Shaham, G. Ghinita, C. Shahabi, **Models and Mechanisms for Fairness in Location Data Processing.** CoRR abs/2204.01880 2022.

- S. Shaham, G. Ghinita, C. Shahabi, **Models and Mechanisms for Spatial Data Fairness.** Proc. VLDB Endow. 2022.

- S. Zeighami, R. Ahuja, G. Ghinita, and C. Shahabi, **A Neural Database for Differentially Private Spatial Range Queries.**, Proc. VLDB Endow. 2022. 

- R. Ahuja, S. Zeighami, G. Ghinita, and C. Shahabi, **A Neural Approach to Spatio-Temporal Data Release with User-Level Differential Privacy.** SIGMOD 2023.

- S. Shaham, A. Hajisafi, M. K. Quan, D. C. Nguyen, B. Krishnamachari, Ch. Peris, G. Ghinita, C. Shahabi, P. N. Pathirana: **Holistic Survey of Privacy and Fairness in Machine Learning.** CoRR abs/2307.15838. 2023.

- S. Shaham, G. Ghinita, C. Shahabi, **Fair Spatial Indexing: A paradigm for Group Spatial Fairness.** CoRR abs/2302.02306. 2023.

- S. Shaham, G. Ghinita, C. Shahabi, **Supporting Secure Dynamic Alert Zones Using Searchable Encryption and Graph Embedding.** CoRR abs/2301.06238. 2023.

<br>

## Software Artifacts

<div class="card-container">
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/VDR">
      <img class="repo-img-light w-100" alt="USC-InfoLab/VDR" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=VDR&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/VDR" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=VDR&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/SNH">
      <img class="repo-img-light w-100" alt="USC-InfoLab/SNH" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=SNH&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/SNH" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=SNH&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
</div>

<div class="card-container">
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/FairKD-tree">
      <img class="repo-img-light w-100" alt="USC-InfoLab/FairKD-tree" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=FairKD-tree&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/FairKD-tree" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=FairKD-tree&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/Supporting-Secure-Dynamic-Alert-Zones-Using-Searchable-Encryption-and-Graph-Embedding">
      <img class="repo-img-light w-100" alt="USC-InfoLab/Supporting-Secure-Dynamic-Alert-Zones-Using-Searchable-Encryption-and-Graph-Embedding" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=Supporting-Secure-Dynamic-Alert-Zones-Using-Searchable-Encryption-and-Graph-Embedding&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/Supporting-Secure-Dynamic-Alert-Zones-Using-Searchable-Encryption-and-Graph-Embedding" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=Supporting-Secure-Dynamic-Alert-Zones-Using-Searchable-Encryption-and-Graph-Embedding&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
</div>

<div class="card-container">
  <div class="repo p-2 text-center">
    <a href="https://github.com/USC-InfoLab/c-Fair-Polynomials">
      <img class="repo-img-light w-100" alt="USC-InfoLab/c-Fair-Polynomials" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=c-Fair-Polynomials&theme={{ site.repo_theme_light }}">
      <img class="repo-img-dark w-100" alt="USC-InfoLab/c-Fair-Polynomials" src="https://github-readme-stats.vercel.app/api/pin/?username=USC-InfoLab&repo=c-Fair-Polynomials&theme={{ site.repo_theme_dark }}">
    </a>
  </div>
  <div class="repo p-2 text-center">
  </div>
</div>

<br>

## People

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/sep.jpeg" title="Sepanta Zeighami" class="img-fluid rounded-circle z-depth-1" width="50%" %}
    </div>
    <h5 style="text-align:center;">Sepanta Zeighami</h5>
    <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/prev_people/ritesh.png" title="Ritesh Ahuja" class="img-fluid rounded-circle z-depth-1" width="50%" %}
    </div>
    <h5 style="text-align:center;">Ritesh Ahuja</h5>
    <p style="text-align:center;">Graduated Aug/2022</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
   <div class="text-center">
        {% include figure.html path="assets/img/prev_people/sina.png" title="Sina Shaham" class="img-fluid rounded-circle z-depth-1" width="50%" %}
    </div>
    <h5 style="text-align:center;">Sina Shaham</h5>
    <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/jonathan.jpeg" title="Sepanta Zeighami" class="img-fluid rounded-circle z-depth-1" width="50%" %}
    </div>
    <h5 style="text-align:center;">Jonathan Qin</h5>
    <p style="text-align:center;">CS Undergrad. Student, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
</div>

<br>

#### Colaborators

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/john.webp" title="Sepanta Zeighami" class="img-fluid rounded-circle z-depth-1" width="60%" %}
    </div>
    <h5 style="text-align:center;">John Krumm</h5>
    <p style="text-align:center;">Viterbi School of Engineering, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/gabriel.jpg" title="Gabriel Ghinita" class="img-fluid rounded-circle z-depth-1" width="50%" %}
    </div>
    <h5 style="text-align:center;">Gabriel Ghinita</h5>
    <p style="text-align:center;">CSE, Hamad Bin Khalifa University</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
</div>

<br>

#### Principal Investigator

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        <div class="text-center">
            {% include figure.html path="assets/img/people/cyrus.jpg" title="Cyrus Shahabi" class="img-fluid rounded-circle z-depth-1" width="60%" %}
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

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    {% include figure.html path="assets/img/sponsors/nsf.png" title="NSF" class="img-fluid rounded z-depth-1 mx-auto" width="50%" %}
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
</div>
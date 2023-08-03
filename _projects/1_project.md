---
layout: page
title: NeuroDB
description:  Neural Databases for Efficiently Answering Database Queries Approximately
img: assets/img/neuro-db.png
importance: 1
category: current
---

## Description

Neural Databases (NeuroDBs) improve data access efficiency and accuracy by using neural networks to store data. we have focused on designing NeuroDB to answer range aggregate queries (RAQs), where the query is to return an aggregation of an attribute (e.g., avg. sales) from a database given a range predicate (e.g., for a given time period and location). For example, the figure below (left) shows a dataset of location signals of individuals, and the duration they stayed in that location (color represents visit duration in hours). Middle figure shows that the query of average visit duration for a 50m by 50m rectangle with bottom left corner at a user-specified geo-coordinate can be represented by a query function that takes as input the geo-coordinate of the rectangle and outputs the average visit duration of data points in the corresponding rectangle. Figure on the right shows a neural network learned to approximate the query function. Then, given query geo-coordinates, NeuroDB uses this learned neural network to answer the query.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Picture1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We have studied this problem in two settings:
 

- We studied how to improve the efficiency of answering RAQs. The goal here is to improve efficiency of query answering in real-world database systems, where RAQs are a common building block. We show this approach can provide significant practical advantages and we theoretically study the benefits of using such an approach. We also extend our theoretical analysis to analyze learned indexes to understand why and when they perform well.  

- We studied how to accurately answer spatial count queries (SCQs, which are a subset of RAQs) (e.g., number of people at a location) while preserving differential privacy. Since such queries ask information about location of individuals, answering them must be done while ensuring privacy of the individuals is not violated. The goal here is to improve accuracy of the queries while preserving user’s privacy. We've studied this problem in both spatial and spatiotemporal settings. 
<br>

## Related Publications

- S. Zeighami, R. Ahuja, G. Ghinita, and C. Shahabi, **A Neural Database for Differentially Private Spatial Range Queries.**, Proceedings of the VLDB Endowment 15 (5), 2022. &nbsp; [PDF](https://www.vldb.org/pvldb/vol15/p1066-zeighami.pdf)

- S. Zeighami, C. Shahabi, V. Sharan. **NeuroSketch: Fast and Approximate Evaluation of Range Aggregate Queries with Neural Networks.** Proceedings of the ACM on Management of Data, 2023. &nbsp; [PDF](https://dl.acm.org/doi/pdf/10.1145/3588954)

- R. Ahuja, S. Zeighami, G. Ghinita, and C. Shahabi, **A Neural Approach to Spatio-Temporal Data Release with User-Level Differential Privacy.** Proceedings of the ACM on Management of Data, 2023. &nbsp; [PDF](https://dl.acm.org/doi/pdf/10.1145/3588701)

- S. Zeighami, C. Shahabi, **On Distribution Dependent Sub-Logarithmic Query Time of Learned Indexing.** Proceedings of the 40th International Conference on Machine Learning, 2023. &nbsp; [PDF](https://openreview.net/pdf?id=4hefw3y2VK)

<br>

## People

<br>

#### Students

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/sep.jpeg" title="Sepanta Zeighami" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Sepanta Zeighami</h5>
    <p style="text-align:center;">CS PhD Student, USC</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/prev_people/ritesh.png" title="Ritesh Ahuja" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Ritesh Ahuja</h5>
    <p style="text-align:center;">Graduated Aug/2022</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
   <div class="text-center">
        {% include figure.html path="assets/img/prev_people/1635887426599.jpeg" title="SRaghav Seshadri" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Raghav Seshadri</h5>
    <p style="text-align:center;">CS MSc Student, USC</p>
  </div>
</div>

<br>

#### Colaborators

<div class="row">
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    <div class="text-center">
        {% include figure.html path="assets/img/people/gabriel.jpg" title="Gabriel Ghinita" class="img-fluid rounded-circle z-depth-1 mx-auto" width="50%" %}
    </div>
    <h5 style="text-align:center;">Gabriel Ghinita</h5>
    <p style="text-align:center;">CSE, Hamad Bin Khalifa University</p>
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
  <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
  </div>
</div>

<br>

#### Principal Investigator

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
        <div class="text-center">
            {% include figure.html path="assets/img/people/cyrus.jpg" title="Cyrus Shahabi" class="img-fluid rounded-circle z-depth-1 mx-auto" width="55%" %}
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
    {% include figure.html path="assets/img/sponsors/nsf.png" title="NIH" class="img-fluid rounded z-depth-1 mx-auto" width="50%" %}
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
    <div class="col-sm mt-3 mt-md-0" style="margin-bottom: 20px;">
    </div>
</div>

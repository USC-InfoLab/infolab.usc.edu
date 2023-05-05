---
layout: page
title: NeuroDB: A Neural Network Framework for Efficiently Answering Database Queries Approximately
description:
img: assets/img/1.jpg
importance: 1
category: work
---

A Neural Database (NeuroDB) is a neural network that learns to answer queries. Instead of performing data access by going over the data itself, a trained neural network directly outputs the query answer. NeuroDB improves data access efficiency, accuracy, privacy and robustness to missing data. It is well-suited for aggregate queries where the query is to return an aggregation of an attribute (e.g., avg. sales) from a database given a predicate (e.g., for a given time period and location). For example, the figure below (left) shows a dataset of location signals of individuals, and the duration they stayed in that location (color represents visit duration in hours). Middle figure shows that the query of average visit duration for a 50m by 50m rectangle with bottom left corner at a user-specified geo-coordinate can be represented by a query function that takes as input the geo-coordinate of the rectangle and outputs the average visit duration of data points in the corresponding rectangle. Figure on the right shows a neural network learned to approximate the query function. Then, given query geo-coordinates, NeuroDB uses this learned neural network to answer the query.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Picture1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
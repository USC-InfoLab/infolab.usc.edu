---
layout: page
title: Accurate Point-of-Interest Forecasting
description: Learning Dynamic Graphs from All Contextual Information for Accurate Point-of-Interest Visit Forecasting
img:
importance: 2
category: current
---

### Description

In this study, we address the challenge of accurately forecasting the number of visits to Points-of-Interest (POIs) in urban areas, with important implications for urban planning, public health, and social studies. Existing approaches often overlook the intricate multi-context correlations among POIs, limiting the accuracy of visit forecasting. To overcome this limitation, we propose the Busyness Graph Neural Network (BysGNN), a novel temporal graph neural network that effectively uncovers and learns the underlying multi-context correlations between POIs.

BysGNN takes advantage of all available contextual information, including POI geocoordinates, semantics, and time-series data, to construct a comprehensive and accurate dynamic graph representation. By generating a graph that captures correlations between POIs at various levels, BysGNN reveals latent relationships between POIs, enabling more precise forecasting. The inferred expressive graph, referred to as the Busyness Graph, is then utilized in a Graph Neural Network (GNN) block to perform accurate visit forecasting, leveraging the flexibility and power of GNNs.

We conducted experiments using real-world data to evaluate the effectiveness of BysGNN. The results demonstrated a significant improvement in forecasting accuracy compared to existing baselines, indicating the efficacy of our approach. By enhancing visit forecasting accuracy, our innovative methodology provides valuable insights into the latent relationships between POIs, shedding light on urban dynamics and facilitating informed decision-making.

We are currently extending our work to the health domain.

<br>

### BysGNN Architecture
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bysgnn_overall_architecture.png" title="bysgnn" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
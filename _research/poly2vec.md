---
layout: page
title: "Poly2Vec: Polymorphic Fourier-Based Encoding of Geospatial Objects for GeoAI Applications"
description: "TL;DR: A new unified encoding approach for encoding point, polyline and polygon geometries."
img: assets/img/projects/poly2vec.png
importance: 3
category: current
---

<p align="center" style="font-size:25px;">
  <a href="https://msiampou.github.io/" target="_blank">Maria Despoina Siampou<sup>1</sup></a>,
  <a href="" target="_blank">Jialiang Li<sup>2</sup></a>,
  <a href="https://www.johnkrumm.net/" target="_blank">John Krumm<sup>1</sup></a>,
  <a href="https://scholar.google.com/citations?user=jEdhxGMAAAAJ&hl=en&authuser=1" target="_blank">Cyrus Shahabi<sup>1</sup></a>,
  <a href="https://homes.cs.aau.dk/~luhua/" target="_blank">Hua Lu<sup>2</sup></a>
</p>

<p align="center" style="font-size:20px;">
  <sup>1</sup>University of Southern California
  <sup>2</sup>Rosklide University
</p>


<p align="center" style="font-size:28px;">
  <span style="color:#d62728; font-weight:bold;">ICML 2025</span>
</p>

### Summary

Encoding geospatial objects is fundamental for geospatial artificial intelligence (GeoAI) applications, which leverage machine learning (ML) models to analyze spatial information. Common approaches transform each object into known formats, like image and text, for compatibility with ML models. However, this process often discards crucial spatial information, such as the object's position relative to the entire space, reducing downstream task effectiveness. Alternative encoding methods that preserve some spatial properties are often devised for specific data objects (e.g., point encoders), making them unsuitable for tasks that involve different data types (i.e., points, polylines, and polygons). To this end, we propose Poly2Vec, a polymorphic Fourier-based encoding approach that unifies the representation of geospatial objects, while preserving the essential spatial properties. Poly2Vec incorporates a learned fusion module that adaptively integrates the magnitude and phase of the Fourier transform for different tasks and geometries. We evaluate Poly2Vec on five diverse tasks, organized into two categories. The first empirically demonstrates that Poly2Vec consistently outperforms object-specific baselines in preserving three key spatial relationships: topology, direction, and distance. The second shows that integrating Poly2Vec into a state-of-the-art GeoAI workflow improves the performance in two popular tasks: population prediction and land use inference.


<p align="center">
  <a href="https://www.arxiv.org/pdf/2408.14806" target="_blank">
    <span style="display:inline-block; padding:8px 16px; margin:4px; border:1px solid #ccc; border-radius:6px; background:#f9f9f9; text-decoration:none; font-family:sans-serif;">
      📝 Paper
    </span>
  </a>
  <a href="https://github.com/USC-InfoLab/poly2vec" target="_blank">
    <span style="display:inline-block; padding:8px 16px; margin:4px; border:1px solid #ccc; border-radius:6px; background:#f9f9f9; text-decoration:none; font-family:sans-serif;">
      <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="25" style="vertical-align:middle; margin-right:6px;">Code
    </span>
  </a>
  <a href="https://drive.google.com/drive/folders/119KvtA1K9CbII6TMMSPXkd1Yjrxhv9-P?usp=sharing" target="_blank">
    <span style="display:inline-block; padding:8px 16px; margin:4px; border:1px solid #ccc; border-radius:6px; background:#f9f9f9; text-decoration:none; font-family:sans-serif;">
      🔗 Datasets
    </span>
  </a>
  <a href="https://colab.research.google.com/github/your-repo/blob/main/tutorial.ipynb" target="_blank">
    <span style="display:inline-block; padding:8px 16px; margin:4px; border:1px solid #ccc; border-radius:6px; background:#f9f9f9; text-decoration:none; font-family:sans-serif;">
      🎓 Tutorial
    </span>
  </a>
</p>

### Bibtex
```bibtex
@inproceedings{siampoupoly2vec,
  title={Poly2Vec: Polymorphic Fourier-Based Encoding of Geospatial Objects for GeoAI Applications},
  author={Siampou, Maria Despoina and Li, Jialiang and Krumm, John and Shahabi, Cyrus and Lu, Hua},
  booktitle={Forty-second International Conference on Machine Learning},
  year={2025}
}
```




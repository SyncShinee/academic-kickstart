---
title: "Efficient Approximate Range Aggregation over Large-scale Spatial Federation"
date: 2021-05-01
publishDate: 2021-12-18T14:25:33.849204Z
authors: ["**[TKDE 2021] Yexuan Shi**", "Yongxin Tong", "Yuxiang Zeng", "Zimu Zhou", "Bolin Ding", "Lei Chen"]
publication_types: ["1"]
abstract: "Range aggregation is a primitive operation in spatial data applications and there is a growing demand to support such operations over a data federation, where the entire spatial data are separately held by multiple data providers (a.k.a. data silos).
Data federations notably increase the amount of data available for data-intensive applications such as smart mobility planning and public health emergency responses.
Yet they also challenge the conventional implementation of range aggregation queries because the raw data cannot be shared within the federation and the data partition at each data silo is fixed during query processing.
These constraints limit the design space of distributed range aggregation query processing and render existing solutions inefficient on large-scale data.
In this work, we propose the first-of-its-kind approximate algorithms for efficient range aggregation over spatial data federation. 
We devise novel single-silo sampling algorithms that process queries in parallel
and design a level sampling based algorithm which reduces the time complexity of local queries at each data silo to $O(\\log\\frac{1}{\\epsilon})$,
where $\\epsilon$ is the approximation ratio of the accuracy guarantee.
Extensive evaluations with real-world data show that compared with state-of-the-arts, our solutions reduce the time cost and communication cost by up to $85.1\\times$ and $5.5\\times$ respectively, with average approximate errors of below $2.8%$.
In addition, our solutions yield a throughput of over 250 queries per second, achieving real-time responses for real-world bike-sharing applications."
featured: true
publication: "*IEEE Transactions on Knowledge and Data Engineering*"
---


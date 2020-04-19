---
title: "An efficient insertion operator in dynamic ridesharing services"
date: 2019-01-01
publishDate: 2020-04-18T14:25:33.847220Z
authors: ["Yi Xu", "Yongxin Tong", "Yexuan Shi", "Qian Tao", "Ke Xu", "Wei Li"]
publication_types: ["1"]
abstract: "Dynamic ridesharing refers to services that arrange
one-time shared rides on short notice. It underpins various
real-world intelligent transportation applications such as carpooling, food delivery and last-mile logistics. A core operation
in dynamic ridesharing is the “insertion operator”. Given a
worker and a feasible route which contains a sequence of origin destination pairs from previous requests, the insertion operator
inserts a new origin-destination pair from a newly arrived
request into the current route such that certain objective is
optimized. Common optimization objectives include minimizing
the maximum flow time of all requests and minimizing the
total travel time of the worker. Despite its frequent usage, the
insertion operator has a time complexity of $O(n^3)$, where n is
the number of all requests assigned to the worker. The cubic
running time of insertion fundamentally limits the efficiency
of urban-scale dynamic ridesharing based applications. In this
paper, we propose a novel partition framework and a dynamic
programming based insertion with a time complexity of $O(n^2)$.
We further improve the time efficiency of the insertion operator
to O(n) harnessing efficient index structures, such as fenwick
tree. Evaluations on two real-world large-scale datasets show
that our methods can accelerate insertion by 1.5 to 998.1 times."
featured: false
publication: "*in Proceedings of the IEEE 35th International Conference on Data Engineering* **(ICDE'19)**"
---


---
title: "Preference-aware Task Assignment in On-demand Taxi Dispatching: An Online Stable Matching Approach"
date: 2019-01-01
publishDate: 2020-04-18T14:25:33.848207Z
authors: ["**[AAAI 2019]** Boming Zhao", "Pan Xu", "**Yexuan Shi**", "Yongxin Tong", "Zimu Zhou", "Yuxiang Zeng"]
publication_types: ["9"]
abstract: "A central issue in on-demand taxi dispatching platforms is
task assignment, which designs matching policies among dynamically arrived drivers (workers) and passengers (tasks).
Previous matching policies maximize the profit of the platform without considering the preferences of workers and
tasks (e.g., workers may prefer high-rewarding tasks while
tasks may prefer nearby workers). Such ignorance of preferences impairs user experience and will decrease the profit
of the platform in the long run. To address this problem, we
propose preference-aware task assignment using online stable matching. Specifically, we define a new model, *Online
Stable Matching under Known Identical Independent Distributions* (OSM-KIID). It not only maximizes the expected total profits (OBJ-1), but also tries to satisfy the preferences
among workers and tasks by minimizing the expected total
number of blocking pairs (OBJ-2). The model also features a
practical arrival assumption validated on real-world dataset.
Furthermore, we present a linear program based online algorithm LP-ALG, which achieves an online ratio of at least
$1−1/e$ on OBJ-1 and has at most $0.6\\cdot|E|$ blocking pairs expectedly, where $|E|$ is the total number of edges in the compatible graph. We also show that a natural Greedy can have
an arbitrarily bad performance on OBJ-1 while maintaining
around $0.5\\cdot|E|$ blocking pairs. Evaluations on both synthetic
and real datasets confirm our theoretical analysis and demonstrate that LP-ALG strictly dominates all the baselines on
both objectives when tasks notably outnumber workers."
featured: true
publication: "*The 33rd AAAI Conference on Artificial Intelligence*"
---


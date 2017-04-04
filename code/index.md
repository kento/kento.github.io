---
layout: page
title: Code
image:
  feature: projects.jpg
  credit: 
  creditlink: 
comments: false
modified: 2017-4-4
---

---
## <img src="https://pruners.github.io/img/rempi_logo.png" width="150">
ReMPI is a highly scalable scalable record-and-replay tool for MPI applications. ReMPI records the order of MPI message matching in one run and can deterministically replay it during subsequent runs. One of the supported modes uses Clock Delta Compression (CDC) for running at extreme-scale. CDC can reduce the record size down to the bare minimum, which allows ReMPI to keep record data on node-local storage, and drastically improve scalability versus writing to a shared file system.
- <i class="fa fa-fw fa-github"></i><a href="https://github.com/PRUNERS/ReMPI">ReMPI</a>

---
## <img src="https://pruners.github.io/img/NINJA_logo.png" width="150">
Ninja (Noise INJection Agent) is a smart network noise injector for quickly exposing unindended MPI message races. Ninja uses innovative network noise injection techniques to increase the chances of racy, incorrect MPI message matching within the target MPI application. Ninja has been shown to reproduce unsafe message races consistently within large production applications and can do this up to two orders of magnitude faster than the traditional testing approach (i.e., random noise injection).
- <i class="fa fa-fw fa-github"></i><a href="https://github.com/PRUNERS/NINJA">NINJA</a>
---


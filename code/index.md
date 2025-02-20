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
## <img src="/images/logos/rempi_logo.png" width="150">
### MPI record-and-replay tool
ReMPI is a highly scalable scalable record-and-replay tool for MPI applications. ReMPI records the order of MPI message matching in one run and can deterministically replay it during subsequent runs. One of the supported modes uses Clock Delta Compression (CDC) for running at extreme-scale. CDC can reduce the record size down to the bare minimum, which allows ReMPI to keep record data on node-local storage, and drastically improve scalability versus writing to a shared file system.
- <i class="fa fa-fw fa-github"></i><a href="https://github.com/PRUNERS/ReMPI">ReMPI</a>

---
## <img src="/images/logos/NINJA_logo.png" width="150">
### Noise Injection tool for exposing message-race bugs
Ninja (Noise INJection Agent) is a smart network noise injector for quickly exposing unindended MPI message races. Ninja uses innovative network noise injection techniques to increase the chances of racy, incorrect MPI message matching within the target MPI application. Ninja has been shown to reproduce unsafe message races consistently within large production applications and can do this up to two orders of magnitude faster than the traditional testing approach (i.e., random noise injection).
- <i class="fa fa-fw fa-github"></i><a href="https://github.com/PRUNERS/NINJA">NINJA</a>

---
## <img src="/images/logos/HuronFS_logo.png" width="150"> 
### Hierarchical, user-level and on-demand file system
HuronFS is a Hierarchical, UseR-level and ON-demand File Systemd for exploiting burst buffers. Unlike conventional filesystems, HuronFS creates an on-demand two-level hierarchical storage system and caches popular files to accelerate I/O performance. Since HuronFS has multiple metadata servers, HuronFS is highly scalable. In addition, by using file replication, failure detection and recovery techniques, HuronFS is resilient to failures. HuronFS exploits low-latency and high-bandwidth interconnects (InfiniBand) for supercomputers.
- <i class="fa fa-fw fa-github"></i><a href="https://github.com/EBD-CREST/HuronFS">HuronFS</a>

---
#### Others
 - <i class="fa fa-fw fa-github"></i><a href="https://github.com/LLNL/burstfs">BurstFS</a>

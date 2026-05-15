This is the repository for the Ligthinig Talk at R/Medicine 2026 about parallel computing in R.

<p align="center">
<img src="slides/img/rmed.png" alt="Alt Text" width="200" height="200" class="center">
</p>

Slides can be found **[here](https://aimundo.github.io/RMedicine2026/slides/RMedicine-2026.html#/title-slide)**.

# Some resources about parallel computing with **{{future}}** and **{{mirai}}**

<img src="slides/img/future.png" alt="Alt Text" width="100" height="100" class="left"> <img src="slides/img/mirai.png" alt="Alt Text" width="100" height="100" class="right">

  - Remote launch of daemons in a computer cluster (Slurm): https://mirai.r-lib.org/reference/cluster_config.html
  - Nested `future_map` calls: https://cran.r-project.org/web/packages/future/vignettes/future-3-topologies.html
  - Improving memory usage:
  -   The recently released package [{{mori}}](https://github.com/shikokuchuo/mori) reduces memory usage in parallel computing by creating an object that is shared across parallel processes!

  -   In the real implementation  of the code shown in the slides, using mori reduced memory  usage by 15%:


<img width="400" height="300" src="slides/img/mori_example.png" />

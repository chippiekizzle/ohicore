
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- Note: If any R/functions.R files are added or deleted this needs to be changed in the DESCRIPTION file, and the NEWS.md (changelog) file. -->
<!-- If changes are made to any of the R/functions.R (or other files), the following should be run: pkgdown::build_site() -->
An Ocean Health Assessment Tool
-------------------------------

We all benefit in some shape or form from a healthy ocean. Directly or indirectly, we all rely on the ocean’s services: food, livelihood, recreational opportunities, or regulation of the global climate. The enormity of the ocean, a sparsity of data about the detailed goings-on in its depths, and conflicting views on what constitutes responsible resource use make sustainable management of this wide range of benefits a big task.

Optimal management means using the resources sustainably, but also to their fullest capacities within the sustainable range, as it is the coupled human–ocean system we are interested in managing. Maintaining this balance across the broad range of benefits requires an approach that is both comprehensive and quantitative. The Ocean Health Index, consisting of ten diverse public goals, is designed for this purpose.

![](https://docs.google.com/drawings/d/e/2PACX-1vRQLIv_akeZMQUJyUH9lzwLpMCqPv4uKF29atREmxgNVc80YYVrxOwVQLfXwWPMktKLAdM79EuuaH0u/pub?w=958&h=105)

Features & Usage
----------------

The `ohicore` R package is what brings everything together in the Ocean Health Index assessments.

![](https://docs.google.com/drawings/d/e/2PACX-1vSNh-PtRPpKCBoXGtxWJUnBbOhBn9iwIBRMFE4XARj5ECN76a0Cmejh3V9xVls3SGc6UE1Z9i29DOoL/pub?w=1164&h=452)

<br>

An analogy for how the different pieces work together: The driving action comes from actively running the `calculate_scores.R` script in the assessment folder or repository. The prepared data is pulled into the assessment by `ohicore` functions and the objects it creates. Data included and models contained in the assessment repository `functions.R` script are both somewhat adjustable but some combinations are best for different things (like with bike gears -chainrings and rear sprockets).

An Open Data Science Project
----------------------------

Besides doing awesome science to support policy and research aimed at improving our use and care of ocean resources, we are committed to following and championing open data science practices. `ohicore` and this site are one component of this; to learn more about this dimension of our work see \[links\].

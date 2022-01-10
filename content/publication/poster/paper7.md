+++
title = "HALTimer: A Fast Vt Replacement Heuristic for. Leakage Power Minimization "
#MLTimer: Leakage Power Minimisation in Digital Circuits using Machine Learning and Adaptive Lazy Timing Analysis"
date = 2015-06-03T06:41:32-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = []
publication_types=["9"]
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
publication = "Design Automation Conference (Work-In-Progress)"

abstract = "Due to the dramatic increase in the amount of data handled by today’s EDA flows, currently there is a strong focus in the EDA ndustry on data-centric approaches coalescing with existing algorithmic approaches to design of EDA software. This paper proposes such a data-centric approach to solving the timing-constrained discrete Vt sizing problem (TC-DVSP). The problem is known to be NP-complete and the most powerful techniques reported for the same, employed either iterative greedy or sensitivity-driven heuristics, that required incremental static timing analysis after every iteration. For large designs, due to the large amount of data handled by the timing engine and the large number of terations, the total time consumed for optimization can be prohibitively expensive. The key observation reported in this paper is that there exists a good correlation between the slack data in a given iteration and the order of gate replacements in subsequent iterations. This paper exploits the above observation to propose HALTimer, an iterative algorithm that uses slack data-centric adaptive lazy timing analysis to solve the TC-DVSP. For large ISPD and ITC circuits, HALTimer reduces the running time from several days to a few hours. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline."
authors = ["Patanjali SLPSK", "Seetal Potluri", "Kamakoti Veezhinathan"]
url_pdf="files/haltimer.pdf"
date = "2018-06-01"
image = ""
image_preview = ""
math = false
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""

+++


The discrete Vt sizing technique is employed at all stages of the physical synthesis flow, because it does not impact the placement yet provides significant room for power/timing optimization. The timing-constrained discrete Vt sizing problem (TC-DVSP) is NP-complete and earlier techniques reported for the same, employed iterative greedy or sensitivity-driven heuristics, that required incremental timing analysis after every iteration. The key observation reported in this paper is that there exists a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations. This paper exploits the above observation to propose HALTimer, an iterative algorithm that uses adaptive lazy timing analysis to solve the TC-DVSP. For large ISPD and ITC circuits, HALTimer reduces the running time from several days to a few hours. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline.

+++
title = "HALTimer: A Fast Vt Replacement Heuristic for. Leakage Power Minimization "
#MLTimer: Leakage Power Minimisation in Digital Circuits using Machine Learning and Adaptive Lazy Timing Analysis"
date = 2015-06-03T06:41:32-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = []
publication_types=["3"]
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

abstract = "The timing constrained discrete sizing technique (TC-DSP) is employed at all stages of the physical synthesis flow and has been studied extensively over the last 30 years. The ISPD gate sizing contests introduced industry standard benchmarks and library which motivated a lot of research in this area. However most of the solutions employed were either sensitivity driven or based on analytical methods that required incremental timing analysis after every iteration with both consuming a significant amount of time to perform the optimization. The key observations reported in this paper are i) there exists a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations; and, ii) across the benchmark circuits there exists significant overlap in the number of sub-circuits that have similar structures. This paper exploits the above observations to propose MLTimer, an iterative algorithm that uses adaptive lazy timing analysis in conjunction with a Support Vector Machine (SVM) engine for solving the TC-DSP quickly and efficiently. We observe that for large benchmark circuits (≥ 200,000) our proposed solution reduces the leakage power by 3% and the running time by over 50% when compared to the best reported heuristic in the literature. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline."
authors = ["Patanjali SLPSK", "Milan Patnaik", "Seetal Potluri", "Kamakoti Veezhinathan"]
date = "2018-06-01"
image = ""
image_preview = ""
math = false
publication = "Design Automation Conference"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = ""#https://www.ingentaconnect.com/content/asp/jolpe/2018/00000014/00000002/art00013"
url_project = ""
url_slides = ""
url_video = ""

+++


The discrete Vt sizing technique is employed at all stages of the physical synthesis flow, because it does not impact the placement yet provides significant room for power/timing optimization. The timing-constrained discrete Vt sizing problem (TC-DVSP) is NP-complete and earlier techniques reported for the same, employed iterative greedy or sensitivity-driven heuristics, that required incremental timing analysis after every iteration. The key observation reported in this paper is that there exists a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations. This paper exploits the above observation to propose HALTimer, an iterative algorithm that uses adaptive lazy timing analysis to solve the TC-DVSP. For large ISPD and ITC circuits, HALTimer reduces the running time from several days to a few hours. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline.

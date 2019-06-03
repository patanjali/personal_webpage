+++
title = "FastReplace: Efficient Vt Replacement Technique for Leakage Power Minimization"
# MLTimer: Leakage Power Minimisation in Digital Circuits using Machine Learning and Adaptive Lazy Timing Analysis"
date = 2014-06-03T06:41:32-07:00
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
authors = ["Patanjali SLPSK", "Seetal Potluri", "Kamakoti Veezhinathan"]
date = "2018-06-01"
image = ""
image_preview = ""
math = false
publication = "Design Automation Conference"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "" #https://www.ingentaconnect.com/content/asp/jolpe/2018/00000014/00000002/art00013"
url_project = ""
url_slides = ""
url_video = ""

+++


We consider the timing-constrained discrete Vt-assignment problem for leakage minimization in digital circuits. The problem is known to be NP-complete. Greedy or Sensitivity-driven heuristics are known to be very effective for iterative Vt-assignment, with incremental timing analysis performed between the iterations. These heuristics, while offering good leakage power savings, carry a huge run-time penalty with increase in circuit size. In iterative Vt-assignment, we observe that there is a good correlation between the slack distribution in a given iteration, and the order of gate replacements in subsequent iterations. This paper proposes an algorithm, which exploits this high correlation to speed up the Vt-assignment process. The proposed algorithm uses gate replacement windows, with lazy timing evaluation, to reduce the total number of incremental STA runs during the optimization. At the end of each iteration, the successive window size is dynamically scaled up/down based on the timing updates at the end of the current window. The proposed algorithm, when applied to ISCAS/ITC circuits, significantly reduced the run-time without impacting the solution quality. 
	

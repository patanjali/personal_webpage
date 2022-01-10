+++
title = "FastReplace: Efficient Vt Replacement Technique for Leakage Power Minimization"
# MLTimer: Leakage Power Minimisation in Digital Circuits using Machine Learning and Adaptive Lazy Timing Analysis"
date = 2014-06-03T06:41:32-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = ["Poster"]
publication_types=["9"]
abstract = "This paper considers the timing-constrained discrete Vt replacement problem (DVRP), for leakage minimization in digital circuits. The problem is NP-complete. Earlier techniques reported for the DVRP employed iterative greedy or sensitivity-driven heuristics, that required incremental timing analysis after every iteration. The key observation reported in this paper is a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations. This paper exploits the above observation to propose FastReplace, an iterative algorithm that uses adaptive lazy timing analysis to solve the DVRP. The proposed FastReplace technique, when applied to ISCAS and ITC benchmark circuits, produced solutions 9.8×and 3.1×faster as compared to the greedy technique and a commercial multi-Vt synthesis tool respectively,without impacting the solution quality."
authors = ["Patanjali SLPSK", "Seetal Potluri", "Kamakoti Veezhinathan"]
publication = "Design Automation Conference (Work-in-Progress)"
url_pdf="files/fastreplace.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

date = "2018-06-01"
image = ""
image_preview = ""
math = false
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
	

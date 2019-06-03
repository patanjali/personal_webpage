+++
title = "The Implications of Shared Data Synchronization Techniques on Multi-Core Energy Efficiency."
date = 2012-10-21T06:41:32-07:00
draft = false
publishDate="2012"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = []
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types=["1"]
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

#abstract = "The timing constrained discrete sizing technique (TC-DSP) is employed at all stages of the physical synthesis flow and has been studied extensively over the last 30 years. The ISPD gate sizing contests introduced industry standard benchmarks and library which motivated a lot of research in this area. However most of the solutions employed were either sensitivity driven or based on analytical methods that required incremental timing analysis after every iteration with both consuming a significant amount of time to perform the optimization. The key observations reported in this paper are i) there exists a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations; and, ii) across the benchmark circuits there exists significant overlap in the number of sub-circuits that have similar structures. This paper exploits the above observations to propose MLTimer, an iterative algorithm that uses adaptive lazy timing analysis in conjunction with a Support Vector Machine (SVM) engine for solving the TC-DSP quickly and efficiently. We observe that for large benchmark circuits (≥ 200,000) our proposed solution reduces the leakage power by 3% and the running time by over 50% when compared to the best reported heuristic in the literature. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline."
authors = ["Ashok Gautham", "Kunal Korgaonkar", "Patanjali SLPSK", "Shankar Balachandran", "Kamakoti Veezhinathan"]
date = "2012-10-01"
image = ""
image_preview = ""
math = false
publication = "HotPower"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "https://dl.acm.org/citation.cfm?id=2387875"
url_project = ""
url_slides = "https://www.usenix.org/system/files/conference/hotpower12/hotpower12-final40.pdf"
url_video = "https://www.usenix.org/conference/hotpower12/workshop-program/presentation/gautham"

+++

Shared data synchronization is at the heart of the multi-core revolution since it is essential for writing concurrent programs. Ideally, a synchronization technique should be able to fully exploit the available cores, leading to improved performance. However, with the growing demand for energy-efficient systems, it also needs to work within the energy and power budget of the system. In this paper, we perform a detailed study of the performance as well as energy efficiency of popular shared-data synchronization techniques on a commodity multi-core processor. We show that Software Transactional Memory (STM) systems can perform better than locks for workloads where a significant portion of the running time is spent in the critical sections. We also show how power-conserving techniques available on modern processors like C-states and clock frequency scaling impact energy consumption and performance. Finally, we compare the performance of STMs and locks under similar power budgets. 



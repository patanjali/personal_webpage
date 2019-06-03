+++
title = "GANDALF: A fine-grained hardware-software co-design for preventing memory attacks."
date = 2018-02-03T06:41:32-07:00
draft = false
publishDate="2018"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = []
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types=["2"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

abstract = "The timing constrained discrete sizing technique (TC-DSP) is employed at all stages of the physical synthesis flow and has been studied extensively over the last 30 years. The ISPD gate sizing contests introduced industry standard benchmarks and library which motivated a lot of research in this area. However most of the solutions employed were either sensitivity driven or based on analytical methods that required incremental timing analysis after every iteration with both consuming a significant amount of time to perform the optimization. The key observations reported in this paper are i) there exists a good correlation between the slack distribution among gates in a given iteration and the order of gate replacements in subsequent iterations; and, ii) across the benchmark circuits there exists significant overlap in the number of sub-circuits that have similar structures. This paper exploits the above observations to propose MLTimer, an iterative algorithm that uses adaptive lazy timing analysis in conjunction with a Support Vector Machine (SVM) engine for solving the TC-DSP quickly and efficiently. We observe that for large benchmark circuits (≥ 200,000) our proposed solution reduces the leakage power by 3% and the running time by over 50% when compared to the best reported heuristic in the literature. This significant decrease in running time is very useful to the industry for achieving timing and power closures of large designs within a given deadline."
authors = ["Gnanmbikai Krishnakumar", "Patanjali SLPSK", "Prasanna karthik.V.", "Chester Rebeiro", "Kamakoti Veezhinathan"]
date = "2018-02-01"
image = ""
image_preview = ""
math = false
publication = "Embedded Systems Letters"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "https://ieeexplore.ieee.org/document/8290931/"
url_project = ""
url_slides = ""
url_video = ""

+++

Illegal memory accesses are a serious security vulnerability that have been exploited on numerous occasions. In this letter, we present Gandalf, a compiler assisted hardware extension for the OpenRISC processor that thwarts all forms of memory-based attacks. We associate lightweight capabilities to all program variables, which are checked at run time by the hardware. Gandalf is transparent to the user and does not require significant OS modifications. Moreover, it achieves locality and incurs minimal overheads in the hardware. We demonstrate these features with a customized Linux kernel executing SPEC2006 benchmarks. To the best of our knowledge, this is the first work to demonstrate a complete solution for hardware-based memory protection schemes for embedded platforms

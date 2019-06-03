+++
title = "MLTimer: Leakage Power Minimisation in Digital Circuits using Machine Learning and Adaptive Lazy Timing Analysis"
date = 2018-06-03T06:41:32-07:00
draft = false
publishDate="2019-06-03"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = ["Journal"]
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
authors = ["Patanjali SLPSK", "Milan Patnaik", "Seetal Potluri", "Kamakoti Veezhinathan"]
date = "2018-06-01"
image = ""
image_preview = ""
math = false
publication = "Journal of Low Power Electronics"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "https://www.ingentaconnect.com/content/asp/jolpe/2018/00000014/00000002/art00013"
url_project = ""
url_slides = ""
url_video = ""

+++

Power optimization techniques in a VLSI flow typically end up being the performance bottlenecks leading to a large turn around time for the following reasons:
	* Scalability: The design typically spans millions and millions of gates with different operating conditions leading to a large search space.
	*  Portability: The constraints vary across technology nodes hindering reusability of solutions.
ML models are inherently trained to operate on large datasets and navigate a complex search space. The contributions of our work are as follows.
	* We propose a novel learning (Support Vector Machine) based classifier, which provides a good initial design configuration that guarantees leakage optimal solution.
	* We use a Lazy Timing Analysis procedure that postpones the timing validation step as much as possible.
	* We show the efficiency of our technique on large scale benchmark datasets (25K - 1million gates). Our technique performs 23% better in terms of solution quality when compared with the state-of-the art technique and 50% better in terms of runtime.

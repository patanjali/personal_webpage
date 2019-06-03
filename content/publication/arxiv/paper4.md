+++
title = "White Mirror: Leaking Sensitive Information from Interactive Netflix Movies using Encrypted Traffic Analysis"
date = 2019-04-21T06:41:32-07:00
draft = false
publishDate="2019"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = []
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
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
authors = ["Gargi Mitra","Prasanna Karthik","Patanjali SLPSK", "Chester Rebeiro", "Kamakoti Veezhinathan"] 
date = "2018-06-01"
image = ""
image_preview = ""
math = false
publication = "arxiv"
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/abs/1903.06475"
url_project = ""
url_slides = ""
url_video = ""

+++
Privacy leaks from Netflix videos/movies is well researched. Current state-of-the-art works have been able to obtain coarse-grained information such as the genre and the title of videos by passive observation of encrypted traffic. However, leakage of fine-grained information from encrypted traffic has not been studied so far. Such information can be used to build behavioural profiles of viewers. 
On 28th December 2018, Netflix released the first mainstream interactive movie called 'Black Mirror: Bandersnatch'. In this work, we use this movie as a case-study to show for the first time that fine-grained information (i.e., choices made by users) can be revealed from encrypted traffic. We use the state information exchanged between the viewer's browser and Netflix as the side-channel. To evaluate our proposed technique, we built the first interactive video traffic dataset of 100 viewers; which we will be releasing. Preliminary results indicate that the choices made by a user can be revealed 96% of the time in the worst case.

+++
title = "The Implications of Shared Data Synchronization Techniques on Multi-Core Energy Efﬁciency"
date = 2012-10-07T20:25:05-05:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Energy Efficient Computing", "Computer Architecture"]
categories = ["Workshop"]
authors=["Ashok Gautam","Kunal Korgaonkar","Patanjali SLPSK","Shankar Balachandran","Kamakoti Veezhinathan"]
url_pdf="https://www.usenix.org/conference/hotpower12/workshop-program/presentation/gautham"
url_slides="https://www.usenix.org/sites/default/files/conference/protected-files/gautham_hotpower12_slides.pdf"
url_video="https://www.usenix.org/conference/hotpower12/workshop-program/presentation/gautham"
abstract="Shared data synchronization is at the heart of the multi-core revolution since it is essential for writing concurrent programs. Ideally, a synchronization technique should be able to fully exploit the available cores, leading to improved performance. However, with the growing demand for energy-efficient systems, it also needs to work within the energy and power budget of the system. In this paper, we perform a detailed study of the performance as well as energy efficiency of popular shared-data synchronization techniques on a commodity multi-core processor. We show that Software Transactional Memory (STM) systems can perform better than locks for workloads where a significant portion of the running time is spent in the critical sections. We also show how power-conserving techniques available on modern processors like C-states and clock frequency scaling impact energy consumption and performance. Finally, we compare the performance of STMs and locks under similar power budgets. "
publication="2012 Workshop on Power-Aware Computing and Systems"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

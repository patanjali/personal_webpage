+++
title = "MeLPUF: Memory in Logic PUF"
date = 2020-12-06T06:41:32-07:00
draft = false
publishDate="2020"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Security"]
categories = ["Preprint"]
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types=["3"]
url_pdf = "https://arxiv.org/abs/2012.03162"
abstract = " Physical Unclonable Functions (PUFs) are used for securing electronic designs across the implementation spectrum ranging from lightweight FPGA to server-class ASIC designs. However, current PUF implementations are vulnerable to model-building attacks; they often incur significant design overheads and are challenging to configure based on application-specific requirements. These factors limit their application, primarily in the case of the system on chip (SoC) designs used in diverse applications. In this work, we propose MeL-PUF - Memory-in-Logic PUF, a low-overhead, distributed, and synthesizable PUF that takes advantage of existing logic gates in a design and transforms them to create cross-coupled inverters (i.e. memory cells) controlled by a PUF control signal. The power-up states of these memory cells are used as the source of entropy in the proposed PUF architecture. These on-demand memory cells can be distributed across the combinational logic of various intellectual property (IP) blocks in a system on chip (SoC) design. They can also be synthesized with a standard logic synthesis tool to meet the area,power, or performance constraints of a design. By aggregating the power-up states from multiple such memory cells, we can create a PUF signature or digital fingerprint of varying size. We evaluate the MeL-PUF signature quality with both circuit-level simulations as well as with measurements in FPGA devices. We show that MeL-PUF provides high-quality signatures in terms of uniqueness, randomness, and robustness, without incurring large overheads. We also suggest additional optimizations that can be leveraged to improve the performance of MeL-PUF." 
authors = ["Christopher Vega","Patanjali SLPSK","Shubhra Deb Paul","Swarup Bhunia"] 
publication="arxiv"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

date = "2020-12-06"
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

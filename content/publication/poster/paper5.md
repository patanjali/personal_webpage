+++
title = "Karna: A Security Aware EDA Flow for Improved Side-Channel Attack Protection"
date = 2019-06-03T06:41:32-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ML for EDA", "Energy Efficient Computing"]
categories = ["Poster"]
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Poster
publication_types=["9"]
url_pdf="files/dac2019.pdf"
abstract = "Side-channel attacks pose a serious threat to the security of embedded devices. Most available countermeasures have significant overheads and very often do not meet an application’s requirement of low-power, high-performance, and small-area. In this paper we propose an algorithm called Karna that can be incorporated in the Electronic Design Automation (EDA) flow, in order to significantly improve the side-channel security of a device, without compromising on the other device characteristics of power, performance, and area. Karna achieves this by first identifying vulnerable gates in the design and then reconfiguring these gates to increase side-channel resistance. Unlike contemporary works, Karna does not require any specialized gate library but uses the gates available in the standard cell library. We integrate Karna into the Synopsys Design Compiler and demonstrate its efficacy at reducing side-channel leakage in implementations of AES, PRESENT and Simon block ciphers, synthesized for a 28nm technology node. We show that our proposed approach is able to reduce the power side-channel of the designs while incurring no penalty in delay, power and gate-count. Our proposed approach incurs a 20% penalty in the area utilization while the total area of the design remains constant."
authors = ["Patanjali SLPSK", "Prasanna Karthik", "Chester Rebeiro", "Kamakoti Veezhinathan"]
publication = "Design Automation Conference (Work-in-Progress)"
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


Side-channel attacks pose a serious threat to the security of embedded devices. Most available countermeasures have significant overheads and very often do not meet an application’s requirement of low-power, high-performance, and small-area. In this work, we propose an algorithm called Karna that can be incorporated in the Electronic Design Automation (EDA) flow, in order to significantly improve the side-channel security of a device, without compromising on the other device characteristics of power, performance, and area. Karna achieves this by first identifying vulnerable gates in the design and then reconfiguring these gates to increase side-channel resistance. Unlike contemporary works, Karna does not require any specialized gate library but uses the gates available in the standard cell library. We integrate Karna into the Synopsys Design Compiler and demonstrate its efficacy at reducing side-channel leakage in implementations of AES, PRESENT and Simon block ciphers, synthesized for a 28-nm technology node. We show that our proposed approach is able to reduce the power side-channel of the designs while incurring no penalty in delay, power and gate-count. Our proposed approach incurs a 20% penalty in the area utilization while the total area of the design remains constant.


+++
title = "On Database-Free Authentication of Microelectronic Components"
date = 2020-12-07T06:41:32-07:00
draft = false
publishDate="2020-12-07"
# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Security"]
categories = ["Journal"]
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types=["2"]
url_pdf = "https://ieeexplore.ieee.org/abstract/document/9284445"
abstract = "Counterfeit integrated circuits (ICs) have become a significant security concern in the semiconductor industry as a result of the increasingly complex and distributed nature of the supply chain. These counterfeit chips may result in performance degradation, profit reduction, and reputation risk for the manufacturer. Therefore, developing effective countermeasures against such malpractices is becoming severely crucial. Physical unclonable function (PUF)-based authentication methods have the potential to mitigate these challenges. However, PUF-based solutions are restrained by several factors, such as additional design efforts and significant area/power overhead, struggle to maintain and update challenge-response pairs (CRPs) database, and the vulnerability to machine learning (ML) attacks. In this article, we address these challenges by developing a novel database-free and enrolment-free hardware authentication approaches, i.e., a digital watermark metric for ICs. To enable efficient database-free hardware integrity verification without enrolment, first, we transform the intrinsic variations in circuit parameters, e.g., boundary scan chain (BSC) path delays in the joint test action group (JTAG) chain into robust digital signatures. Then, we perform statistical analysis on a small pilot unit of authentic chips to create a robust watermark for a complete batch of chips, which jointly captures the characteristics of the physical layout, the manufacturing process, and the foundry. The increasing complexity in the current state-of-the-art designs makes it extremely hard for an adversary to perfectly clone such statistical characterization of circuit parameters using counterfeit or compromised hardware. Besides, the proposed approach requires no additional design or hardware overhead in IC design since it utilizes an embedded structure, which inherently exists within the chips. It also obviates the design house from characterizing each manufactured chip instance, reducing overall testing cost. A path-delay measurement method at a high resolution based on clock phase sweep is introduced to measure the delay values effectively. The proposed intrinsic identifier-based authentication approach is validated by performing emulation on FPGAs and also by conducting physical measurements on custom-made printed circuit boards (PCBs). The reliability of the generated watermarks is evaluated with environmental temperature fluctuations and the aging effect."
authors = ["Fengchao Zhang","Shubhra Deb Paul", "Patanjali SLPSK", "Amit Ranjan Trivedi","Swarup Bhunia"]
publication = "IEEE Transcations on Very Large Scale Integration (VLSI) Systems"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
date = "2020-12-07"
image = ""
image_preview = ""
math = false
#The publishing part of the citation goes here. You may use *Markdown* for italics etc."
#title = ""
url_code = ""
url_dataset = ""
url_pdf = "https://ieeexplore.ieee.org/abstract/document/9284445"
url_project = ""
url_slides = ""
url_video = ""

+++



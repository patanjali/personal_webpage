+++
title = "Samaritan: An automated framework for detecting fault attacks in hardware"
date = 2019-06-03T06:12:56-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Fault attacks", "Hardware Security", "EDA for security"] 
categories = ["Hardware Security" ]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""


+++


Automatic detection of fault vulnerabilities is a challenging problem because of the complicated attack surface. An interesting observation is that, out of the large number of faults that can occur in the design, very few faults are actually exploitable. However, there are no automated tools that can identify these exploitable fault locations in a hardware device. Hence current countermeasures cannot target these exploitable locations and incur significant overhead. Another challenge is that the designers have to ensure that the security guarantees of these countermeasures are met at every stage of the manufacturing process. Formal verification is a tool that can be leveraged to ensure that these guarantees are met without incurring significant overheads. We propose Samaritan, a formal framework that addresses these problems using user-defined specifications and the implemented design. Given a design implementation, either at RTL or gate level, SAMARITAN is capable of pinpointing the vulnerable regions in the design, thereby enabling targeted countermeasures to be deployed. We demonstrate the efficiency of this framework using three ciphers namely, AES, SIMON, and CAMELLIA.



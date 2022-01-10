+++
title = "Karna: A gate-sizing based security aware eda flow for improved power side-channel attack protection"
date = 2019-11-04T20:26:07-05:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Security","Energy Efficient Computing"]
categories = ["Conference"]
abstract="Power side-channel attacks pose a serious threat to the security of embedded devices. Most available countermeasures have significant overheads resulting in the application not meeting its requirements of low-power, high-performance and small area. We propose an algorithm called Karna 11 Karna, much like Achilles from Greek mythology, was born with a shield that protected him from attacks. Similarly, Our proposed scheme, Karna protects the design from power side-channel attacks in the manufacturing phase or in other words the chip is manufactured(born) with a shield. that can be incorporated in the Electronic Design Automation (EDA) flow, in order to significantly improve the side-channel security of the device, without impacting the other device characteristics. Karna does not add additional logic but rather achieves this by first identifying vulnerable gates in the design and then reconfiguring these gates to increase side-channel resistance. Unlike contemporary works, Karna does not require any specialized gate library but uses the gates available in the standard cell library. We integrate Karna into the Synopsys Design Compiler and demonstrate its efficacy at reducing side-channel leakage in implementations of AES, PRESENT and Simon block ciphers, synthesized for a 28nm technology node. An interesting observation is that Karna only uses the available space around the gates to perform this optimization and does not incur any additional area overheads. We showcase the side-channel resistance of these optimized designs using a Differential Power Analysis attack. Our proposed approach is able to reduce the power side-channel of the designs while incurring no penalty in delay, power and gate-count."
authors=["Patanjali SLPSK","Prasanna Karthik Vairam","Chester Rebeiro","Kamakoti Veezhinathan"]
url_pdf="https://ieeexplore.ieee.org/abstract/document/8942173 "
url_slides="https://drive.google.com/file/d/1Pn8cuKpj1GaeYLeGNR7LOsWQdco1PjYz/view"
publication="IEEE/ACM International Conference on Computer-Aided Design (ICCAD)"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

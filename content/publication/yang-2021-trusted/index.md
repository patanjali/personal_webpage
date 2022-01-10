+++
title = "Trusted Electronic Systems with Untrusted COTS"
date = 2021-04-07T20:26:19-05:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Security"]
categories = ["Conference"]
authors=["Shuo Yang","Prabuddha Chakraborty","Patanjali SLPSK","Swarup Bhunia"]
abstract="The challenges of custom integrated circuits (IC) design have made it prevalent to integrate commercial-off-the-shelf (COTS) components (micro-controllers, FPGAs, etc.) in today's designs. While this approach eases the design challenges and improves productivity, it also gives rise to diverse security concerns. One such concern is the possibility of malicious hardware modifications, also called hardware Trojan attacks, by untrusted parties involved in the manufacturing or distribution of COTS devices. While Hardware Trojan detection is an active research topic in the field of microelectronics security, most methods assume the availability of a golden design/chip, which is impractical in the case of a COTS device. In this paper, we discuss challenges with detecting Trojan in COTS components, and introduce a Trojan detection method that applies unsupervised learning. We utilize side-channel power signatures to cluster and isolate chips with Trojans. The proposed method is suitable for trust verification of COTS components by an original equipment manufacturer (OEM) before system integration. In our method, the design house creates a set of security validation test vectors available to the tester (e.g., OEM). The OEM can also generate the test vectors using the block-level diagrams provided by the design house. Power signatures are generated for all the chips under test using these test vectors. We use the generated power signatures to apply feature extraction followed by clustering to group the chips into bins. Through this process, we divide the chips into distinct bins and distinguish the Trojan-inserted chips from the Trojan-free ones. The bin with golden chips can be identified by extensive testing and reverse engineering of one chip sampled from each bin. We utilize two clustering techniques K-Means, and Expectation-Maximization (EM) to perform a comparative analysis. Additionally, we perform extensive experiments to assert our method's effectiveness and obtain over 98% accuracy on the clustering of FPGA chips with both combinational and sequential Trojans."
publication="International Symposium on Quality Electronic Design (ISQED)"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

+++
title = "Brutus: Refuting the Security Claims of the Cache Timing Randomization Countermeasure Proposed in CEASER"
date = 2020-06-01T06:41:32-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Security","Computer Architecture"]
categories = ["Journal"]
publication_types=["2"]
abstract = "Cache timing attacks are a serious threat to the security of computing systems. It permits sensitive information, such as cryptographic keys, to leak across virtual machines and even to remote servers. Encrypted Address Cache, proposed by CEASER - a best paper candidate at MICRO 2018 - is a promising countermeasure that stymies the timing channel by employing cryptography to randomize the cache address space. The author claims strong security guarantees by providing randomization both spatially (randomizing every address) and temporally (changing the encryption key periodically). In this letter, we point out a serious flaw in their encryption approach that undermines the proposed security guarantees. Specifically, we show that the proposed Low-Latency Block Cipher, used for encryption in CEASER, is composed of only linear functions which neutralizes the spatial and temporal randomization. Thus, we show that the complexity of a cache timing attack remains unaltered even with the presence of CEASER. Further, we compare the encryption overheads if CEASER is implemented with a stronger encryption algorithm."
authors = ["Rahul Bodduna","Vinod Ganesan","Patanjali SLPSK","Kamakoti Veezhinathan","Chester Rebeiro"]
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8950094"
publication="IEEE Computer Architecture Letters"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

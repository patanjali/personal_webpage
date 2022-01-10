+++
title = "Depending on HTTP/2 for Privacy? Good Luck!"
date = 2022-01-09T20:26:12-05:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Network Security"]
categories = ["Conference"]
publication_types=["1"]
Authors=["Gargi Mitra","Prasanna Karthik Vairam","Patanjali SLPSK","Nitin Chandrachoodan","Kamakoti Veezhinathan"]
url_pdf="https://ieeexplore.ieee.org/abstract/document/9153390"
abstract="HTTP/2 introduced multi-threaded server operation for performance improvement over HTTP/1.1. Recent works have discovered that multi-threaded operation results in multiplexed object transmission, that can also have an unanticipated positive effect on TLS/SSL privacy. In fact, these works go on to design privacy schemes that rely heavily on multiplexing to obfuscate the sizes of the objects based on which the attackers inferred sensitive information. Orthogonal to these works, we examine if the privacy offered by such schemes work in practice. In this work, we show that it is possible for a network adversary with modest capabilities to completely break the privacy offered by the schemes that leverage HTTP/2 multiplexing. Our adversary works based on the following intuition: restricting only one HTTP/2 object to be in the server queue at any point of time will eliminate multiplexing of that object and any privacy benefit thereof. In our scheme, we begin by studying if (1) packet delays, (2) network jitter, (3) bandwidth limitation, and (4) targeted packet drops have an impact on the number of HTTP/2 objects processed by the server at an instant of time. Based on these insights, we design our adversary that forces the server to serialize object transmissions, thereby completing the attack. Our adversary was able to break the privacy of a real-world HTTP/2 website 90% of the time, the code for which will be released. To the best of our knowledge, this is the first privacy attack on HTTP/2."
publication="IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

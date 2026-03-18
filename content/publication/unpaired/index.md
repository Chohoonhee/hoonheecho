---
title: "Event-based Motion Deblurring with Unpaired Data"
authors:
  - "Hoonhee Cho*"
  - "Yuhwan Jeong*"
  - "Kuk-Jin Yoon"
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - "Advisor"
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2026"
publication_types: ["1"]
date: 2026-03-18
image:
  placement: 3
  filename: "feature.png"
  caption: ""
  focal_point: "Center"
summary: "Event-based motion deblurring framework that operates entirely in an unpaired setting, leveraging event cameras to bridge blur and sharp domains without aligned supervision."
tags: ["Event Camera", "Motion Deblurring", "Unpaired Learning", "Image Restoration"]
featured: true
reading_time: false
profile: false
show_date: false
---
We introduce EMP, an event-based motion deblurring framework that operates entirely in an unpaired setting, removing the need for aligned blur–sharp supervision. EMP bridges the disjoint blur and sharp domains through event information and leverages two complementary training mechanisms: (1) an event-based physical prior with confidence masking that provides reliable self-supervisory signals for blurry inputs, and (2) a generative blur modeling process that extracts blur-related frequency-domain cues from blur–event pairs and transfers them to sharp images to synthesize realistic blur. Extensive experiments on various real-event datasets, including REBlur, EventAid, and HighREV, show that EMP outperforms existing unpaired baselines and achieves performance competitive with paired methods. 

---
title: "Source Domain Data Selection for Improved Transfer Learning Targeting Dysarthric Speech Recognition."
collection: publications
permalink: /publication/ICASSP2020-2
excerpt: 
date: 2020--05
venue: 'ICASSP'
paperurl: 
citation: 'Xiong. Feifei, Yue. Zhengjun, Christensen. Heidi, and Barker, Jon. (2020).
&quot;Source Domain Data Selection for Improved Transfer Learning Targeting Dysarthric Speech Recognition.&quot;
<i>ICASSP 2020</i>, pages 7424-7428'
---
This paper presents an improved transfer learning framework applied to robust personalised speech recognition models for speakers with dysarthria.
As the baseline of transfer learning, a state-of-the-art CNN-TDNN-F ASR acoustic model trained solely on source domain data is adapted onto the target domain via neural network weight adaptation with the limited available data from target dysarthric speakers.
Results show that linear weights in neural layers play the most important role for an improved modelling of dysarthric speech evaluated using UASpeech corpus, achieving averaged $11.6\%$ and $7.6\%$ relative recognition improvement in comparison to the conventional speaker-dependent training and data combination, respectively.
To further improve the transferability towards target domain, we propose an \textit{utterance}-based data selection of the source domain data based on the entropy of posterior probability, which is analysed to statistically obey a Gaussian distribution.
Compared to a \textit{speaker}-based data selection via dysarthria similarity measure, this allows for a more accurate selection of the potentially beneficial source domain data for either increasing the target domain training pool or constructing an intermediate domain for incremental transfer learning, resulting in a further absolute recognition performance improvement of nearly $2\%$ added to transfer learning baseline for speakers with moderate to severe dysarthria.

[Download paper here](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9054694)

[//]: # (Recommended citation: Xiong. Feifei, Yue. Zhengjun, Christensen. Heidi, and Barker, Jon. &#40;2020&#41;.)

[//]: # ("Source Domain Data Selection for Improved Transfer Learning Targeting Dysarthric Speech Recognition.")

[//]: # (<i>ICASSP 2020</i>.)

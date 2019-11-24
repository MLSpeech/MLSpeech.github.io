---
title: Hide and Speak, Deep Neural Networks for Speech Steganography

description: |
  Hiding speech inside of speech.

people:
  - jkeshet
  - fkreuk
  - adiyoss

layout: project
last-updated: 2019-11-24
---

Steganography is the science of hiding a secret message within an ordinary public message, which referred to as Carrier. Traditionally, digital signal processing techniques, such as least significant bit encoding, were used for hiding messages. In this paper, we explore the use of deep neural networks as steganographic functions for speech data. To this end, we propose to jointly optimize two neural networks: the first network encodes the message inside a carrier, while the second network decodes the message from the modified carrier. We demonstrated the effectiveness of our method on several speech data-sets and analyzed the results quantitatively and qualitatively. Moreover, we showed that our approach could be applied to conceal multiple messages in a single carrier using multiple decoders or a single conditional decoder. Qualitative experiments suggest that modifications to the carrier are unnoticeable by human listeners and that the decoded messages are highly intelligible.

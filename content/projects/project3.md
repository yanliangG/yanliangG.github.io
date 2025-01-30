+++
title = 'project3'
draft = false
description = 'This is proj3'
auther = 'Yanliang'
[params]

    hidesidebar = true

+++

{{% align %}} Deep Sea Explorer {{% /align %}}

A multimodal video game experience

<br/>
{{< youtube 4JfEsTnSERg >}}

<br/>

### Description

This study presents the development and evaluation of a video game experience that compares multimodal input (gesture + head movements) with traditional keyboard controls in a deep-sea environment. We configured a body detection model locally called [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) and compile its python api, which enable us to capture users' gesture of swimming and head movement. To let users control the game with multimodal input, we built communication between detection code and unity-inserted script. Our results show keyboard control is preferred for ease of use, while multimodal input is favored for its novelty and enhanced interactivity, making the game more fun. 
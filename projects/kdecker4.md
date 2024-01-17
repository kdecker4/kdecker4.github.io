---
layout: project
type: project
image: kdecker4.github.io/img/000034600009.jpg
title: "Kalani Decker"
date: 2024-01-17
published: true
labels:
  - Robotics
  - Arduino
  - C++
summary: "This is my student introduction to the ITM352 class, in Spring of 2024."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

My name is Kalani Decker, I am a third year student at the Shidler College of Business studying Finance! I am expected to graduate in the spring of 2025, in which I was also curious in pursuing a double major in MIS, as I have leftover electives and credits which I could use for another degree. I am very excited to be in ITM352 because I want to become more competent and knowledable of technology, and how to leverage it to become a better and more effecient worker/person. 
I grew up on Oahu, in Palolo Valley. I also attended Kalani High School, and before that, Kaimuki Middle School. In the future, I am certain I want to live on Oahu as it is home to me, due to my family being here and the unique culture within the islands.
```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).

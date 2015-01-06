# SoberRatio

Go home, aspect ratios. You’re drunk.

**SoberRatio** helps you find the most reasonable aspect ratio of any given shape. For instance, a 647x357 image technically has an aspect ratio of, well, 647:357, but it’s often more useful to know that its nearest “sober” aspect ratio is actually 9:5.

By default, **SoberRatio** limits aspect ratios to a maximum value of 16 on both the width or height. However, you can change this in the hash of the URL. For instance, if you [add #6:8 to the URL](https://jonathantneal.github.io/soberatio/#5:8) then the maximum width will be 6 and the maximum height will be 8. In that instance, 647x357 would now have a sober aspect ratio of 5:3.
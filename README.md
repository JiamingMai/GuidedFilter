# Guided Image Filter

## Introduction:
    This file GuidedImageFilter.java is an implementation of Guided Image Filter with JavaCV    
    JavaCV Download: http://sourceforge.net/projects/javacv/.
    Guided image filtering is proposed in "Guided Image Filtering (ECCV 2010)" by Kaiming He, Jian Sun, and Xiaoou Tang.

## Example:
```java
int radius = 60;
double sigma = 0.001;
q = GuidedImageFilter.guidedfilter_color(I, p, radius, sigma);
```
This file is written by Jiaming Mai on 26/11/2015

# Assignment 0: Markdown
## You have to write markdown
### Some Math Equation
[//]: # "Equations using: LaTeX"
<p align="center">First equation: $Y=X&beta;+&epsilon;_{y}, &forall;X$</p>
<p align="center">Second equation: $X=Z&gamma;+&epsilon;_{x}$</p>
<p align="center">$f_{1}(&omega;)=\frac{&sigma;^2}{2&pi;},&omega;&epsilon;[-&pi;,&pi;]$</p>

1. First item a. first sub-item A) first sub-sub-item b.second sub-item
2. Second item
3. Third item a. second sub item
4. Fourth Item

* First Item
* Second Item
  * first sub-item
    * first sub-sub-item
  * second sub-item

![20220530_233355](https://user-images.githubusercontent.com/80702703/171043014-63746b0c-41e0-41d3-bf49-50065ec6d155.jpg)


library(tidyverse)\
library(mdsr)\
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +\
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")


# Table with alignment
You can align text in the columns to the left, right, or center by adding a
colon (\:) to the left, right, or on both side of the hyphens withing the header row.

| Syntax | Description | Text |
| ------ | :---------: | :--: |
| Header | Title | There's this |
| Paragraph | Text | And more |

# Instructions
6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab.

## License
All code in this repository is copyright 2022 MIT 6.S191 Introduction to Deep Learning. All Rights Reserved.

Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must reference:

> © MIT 6.S191: Introduction to Deep Learning
> http://introtodeeplearning.com

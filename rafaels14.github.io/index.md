---
title       : BMI Calculator
subtitle    : Health App
author      : Rafael dos Santos
job         : University of Sao Paulo
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## BMI PRIME

BMI Prime, a simple modification of the BMI system, is the ratio of actual BMI to upper limit BMI (currently defined at BMI 25).

For instance, a person with BMI 34 has a BMI Prime of 34/25 = 1.36, and is 36% over his or her upper mass limit.

In South East Asian and South Chinese populations (see international variation section below) BMI Prime should be calculated using an upper limit BMI of 23 in the denominator instead of 25.

--- .class #id 

## BODY MASS INDEX (BMI)

This is a simple BMI (Body Mass Index) calculator that takes the weight and the height according to the follow function.

$$BMI = weight/(height^2)$$

Although some authors seggest to use a diferent expoent, it would be more appropriate to use an exponent of between 2.3 and 2.7.

But in this work we'll use the patern expoent (2).


---

## EXAMPLES

If you have a weight of 80 kg (sorry, but I'll use international units (: ) and 1.87m height, then by equation from the past slide:

$$BMI = 80/(1.87^2)$$
$$BMI = 22.877$$

Almost all the countries uses the patern as 25 of BMI.
Then, to calculate the BMI prime we have to divide the BMI for the patern:

$$Prime = BMI/PATERN$$
$$Prime = 22.877/25$$
$$Prime = 0.9151$$

It means that this person has 91.51% of mass relative to the patern; or else, he's inside the ideal BMI. 8.49% percentual points above the limit of overweight.
If we have a person with BMI = 30, than the BMI Prime will be equal to 1.20, or else, this person is 20% overweight.

---

## CLASSIFICATION TABLE


<p><img src="http://www.nature.com/clpt/journal/v90/n1/images/clpt2011104t1.gif"/></p>




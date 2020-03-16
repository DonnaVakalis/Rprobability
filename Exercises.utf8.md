
<!-- rnb-text-begin -->

---
title: "R Notebook for Probability Exercises"
output: html_notebook
---

 


<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuc3VtKHI+PTIpLzEwXjRcblxuYGBgIn0= -->

```r
sum(r>=2)/10^4

```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIDAuNTExNlxuIn0= -->

```
[1] 0.5116
```



<!-- rnb-output-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxubW9udHkoKSAgXG5cbmBgYCJ9 -->

```r
monty()  

```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIFwiUGljayBhIGRvb3IgKGVudGVyIDEsMiBvciAzKVwiXG4ifQ== -->

```
[1] "Pick a door (enter 1,2 or 3)"
```



<!-- rnb-output-end -->

<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuMVxuYGBgIn0= -->

```r
1
```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIFwiTW9udHkgb3BlbnMgZG9vciAzLlwiXG5bMV0gXCJXb3VsZCB5b3UgbGlrZSB0byBzd2l0Y2ggKHkvbik/XCJcbiJ9 -->

```
[1] "Monty opens door 3."
[1] "Would you like to switch (y/n)?"
```



<!-- rnb-output-end -->

<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxueVxuYGBgIn0= -->

```r
y
```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIFwiWWF0emUhXCJcbiJ9 -->

```
[1] "Yatze!"
```



<!-- rnb-output-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->

 

<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuIyMgMy4xMSAgUmFuZG9tIHZhcmlhYmxlcyBhbmQgdGhlaXIgZGlzdHJpYnV0aW9ucyA9PT09PT09PVxuXG4jUGFnZSAxMzggRGlzdHJpYnV0aW9ucyBpbiBSXG5oZWxwKGRpc3RyaWJ1dGlvbnMpXG5cbiNQYWdlIDEzOCBCaW5vbWlhbCBkaXN0cmlidXRpb25cbmRiaW5vbSgzLDUsMC4yKSAgIyBiaW5vbWlhbCBQREYgd2l0aCBpbnB1dHMgKGssbixwKVxucGJpbm9tKDMsNCwwLjIpICAjIGJpbm9taWFsIENERiB3aXRoIGlucHV0cyAoayxuLHApXG5yYmlub20oMTAsNCwwLjUpICMgcmFuY29tIHNldCBvZiB4IGJpbm9taWFsIG9mICh4LG4scClcblxuI1BhZ2UgMTM5IEh5cGVyZ2VvbWV0cmljXG5kaHlwZXIoMSw1LDUsMykgIyBoeXBlcmdlb21ldHJpYyBYPWs9MSBmcm9tIH5IeXBlcmdlb21ldHJpYyh3PTUsYj01LG49MylcblxuIyBQYWdlIDEzOSBEaXNjcmV0ZSBkaXN0cmlidXRpb25zIHdpdGggZmluaXRlIHN1cHBvcnRcbiMgVXNlIHNhbXBsZSBmdW5jdGlvbiBzYW1wbGUgKG4saykgd2hlcmUgbiBpcyB0aGUgZGlzdHJpYnV0aW9uIGFuZCBrIGlzIHRoZSBudW1iZXIgb2YgZWxlbWVudHMgdG8gY2hvb3NlLi4uYnV0IHdlIGNhbiBtYWtlIHggYSB2ZWN0b3Igb2YgdmFsdWVzIHdpdGggYSBjb3JyZXNwb25kaW5nIHZlY3RvciwgcCwgb2YgcHJvYmFiaWxpdGllcyAoc28geCBjYW4gYmUgYW55IGRpc3RyaWJ1dGlvbiEpXG5cbiNleGFtcGxlOlxueDwtYygwLDEsNSwxMCkgI3ZhbHVlc1xucCA8LWMoMC4yNSwwLjUsMC4xLDAuMTUpICMgUE1GIG9mIHhcbnNhbXBsZSh4LDEwMCxwcm9iPXAscmVwbGFjZT1UUlVFKSAjc2FtcGxlIDEwMCB0aW1lcyBmcm9tIGRpc3RyaWJ1dGlvbid4JyBcblxuYGBgIn0= -->

```r
## 3.11  Random variables and their distributions ========

#Page 138 Distributions in R
help(distributions)

#Page 138 Binomial distribution
dbinom(3,5,0.2)  # binomial PDF with inputs (k,n,p)
pbinom(3,4,0.2)  # binomial CDF with inputs (k,n,p)
rbinom(10,4,0.5) # rancom set of x binomial of (x,n,p)

#Page 139 Hypergeometric
dhyper(1,5,5,3) # hypergeometric X=k=1 from ~Hypergeometric(w=5,b=5,n=3)

# Page 139 Discrete distributions with finite support
# Use sample function sample (n,k) where n is the distribution and k is the number of elements to choose...but we can make x a vector of values with a corresponding vector, p, of probabilities (so x can be any distribution!)

#example:
x<-c(0,1,5,10) #values
p <-c(0.25,0.5,0.1,0.15) # PMF of x
sample(x,100,prob=p,replace=TRUE) #sample 100 times from distribution'x' 

```

<!-- rnb-source-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuIyMgNC4xMSBFeHBlY3RhdGlvbiA9PT09PT09PVxuXG5gYGAifQ== -->

```r
## 4.11 Expectation ========

```

<!-- rnb-source-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


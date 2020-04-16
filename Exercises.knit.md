
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


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuIyMgMi4xMCBDb25kaXRpb25hbCBwcm9iYWJpbGl0eSA9PT09PT09PVxuXG4jIFBhZ2UgODA6IFNpbXVsYXRpbmcgdGhlIGZyZXF1ZW50aXN0IGludGVycHJldGF0aW9uXG5uIDwtIDEwXjUgICAgICAgI251bWJlciBvZiBmYW1pbGllc1xuY2hpbGQxIDwtIHNhbXBsZSgyLG4scmVwbGFjZT1UUlVFKSAgIyBsZXQgMSBiZSBhIGdpcmwsIDIgYmUgYSBib3lcbmNoaWxkMiA8LSBzYW1wbGUoMixuLHJlcGxhY2U9VFJVRSkgIFxuXG5uLmIgPC0gc3VtKGNoaWxkMT09MSkgI251bWJlciB0aW1lcyBjaGlsZCAxIGlzIGEgZ2lybFxubi5hYiA8LSBzdW0oY2hpbGQxPT0xICYgY2hpbGQyID09MSkgIyBudW1iZXIgdGltZXMgYm90aCBjaGlsZHJlbiBhcmUgZ2lybHNcblxucC5hLmdpdmVuLmIgPC0gbi5hYi9uLmIgIyBwcm9iLiBib3RoIGdpcmxzIGdpdmVuIGNoaWxkMSBpcyBhIGdpcmxcblxubi5jIDwtIHN1bShjaGlsZDE9PTEgfCBjaGlsZDIgPT0xKSAjbnVtYmVyIGZhbWlsaWVzIGVpdGhlciBjaGlsZCAxIG9yIDIgKG9yIGJvdGgpIGlzIGEgZ2lybFxucC5hYi5naXZlbi5jIDwtIG4uYWIvbi5jICMgcHJvYi4gYm90aCBnaXJscyBnaXZlbiBhdCBsZWFzdCBvbmUgaXMgYSBnaXJsXG5cbiMgUGFnZSA4MiBNb250eSBIYWxsIHNpbXVsYXRpb25cbm4gPC0gMTBeNSAjbnVtYmVyIG9mIHRpbWVzIHRvIHJ1biBzaW11bGF0aW9uXG5jYXJkb29yIDwtIHNhbXBsZSgzLG4scmVwbGFjZSA9IFRSVUUpICNhc3NpZ24gYSBsb2NhdGlvbiBmb3IgdGhlIGNhclxucC5zdWNjZXNzLmNob29zZTEgPC0gc3VtKGNhcmRvb3I9PTEpL24gI2lmIGRvbid0IHN3aXRjaCwgY2hvb3NlIDEgZG9vciwgcHJvYmFiaWxpdHkgb2Ygc3VjY2VzcyAoYWJvdXQgMS8zKVxuXG5tb250eSA8LSBmdW5jdGlvbigpIHsgI2NyZWF0ZSBhbiBpbnRlcmFjdGl2ZSBmdW5jdGlvblxuICAgIGRvb3JzIDwtIDE6M1xuICAgIGNhcmRvb3IgPC0gc2FtcGxlKGRvb3JzLDEpICNyYW5kb20gc2FtcGxlIG9mIDE6M1xuICAgIHByaW50KFwiUGljayBhIGRvb3IgKGVudGVyIDEsMiBvciAzKVwiKSAjcHJvbXB0XG4gICAgY2hvc2VuPC1zY2FuKHdoYXQ9aW50ZWdlcigpLG5saW5lcyA9IDEscXVpZXQ9VFJVRSkgI3JlY2VpdmUgY2hvaWNlIG9mIGRvb3JcbiAgICBpZiAoY2hvc2VuIT1jYXJkb29yKSBtb250eWRvb3I8LWRvb3JzWy1jKGNob3NlbixjYXJkb29yKV0gZWxzZSBtb250eWRvb3IgPC0gc2FtcGxlKGRvb3JzWy1jaG9zZW5dLDEpICNwaWNrIE1vbnR5J3MgZG9vclxuICAgIHByaW50KHBhc3RlKFwiTW9udHkgb3BlbnMgZG9vciBcIixtb250eWRvb3IsXCIuXCIsIHNlcCA9IFwiXCIpKVxuICAgIHByaW50KFwiV291bGQgeW91IGxpa2UgdG8gc3dpdGNoICh5L24pP1wiKSAjcHJvbXB0IHRvIHN3aXRjaFxuICAgIHJlcGx5PC0gc2Nhbih3aGF0PWNoYXJhY3RlcigpLG5saW5lcz0xLHF1aWV0ID1UUlVFKVxuICAgIFxuICAgIGlmKHN1YnN0cihyZXBseSwxLDEpPT1cInlcIikgeyAgI29ubHkgY2hhbmdlIGNob3NlbiBpZiBcInlcIlxuICAgICAgY2hvc2VuPC1kb29yc1stYyhjaG9zZW4sbW9udHlkb29yKV1cbiAgICB9XG4gICAgXG4gICAgaWYoY2hvc2VuPT1jYXJkb29yKSBwcmludChcIllhdHplIVwiKSBlbHNlIHByaW50KFwiRGFuZy5cIilcbiAgICBcbn1cbm1vbnR5KCkgIFxuXG5gYGAifQ== -->

```r
## 2.10 Conditional probability ========

# Page 80: Simulating the frequentist interpretation
n <- 10^5       #number of families
child1 <- sample(2,n,replace=TRUE)  # let 1 be a girl, 2 be a boy
child2 <- sample(2,n,replace=TRUE)  

n.b <- sum(child1==1) #number times child 1 is a girl
n.ab <- sum(child1==1 & child2 ==1) # number times both children are girls

p.a.given.b <- n.ab/n.b # prob. both girls given child1 is a girl

n.c <- sum(child1==1 | child2 ==1) #number families either child 1 or 2 (or both) is a girl
p.ab.given.c <- n.ab/n.c # prob. both girls given at least one is a girl

# Page 82 Monty Hall simulation
n <- 10^5 #number of times to run simulation
cardoor <- sample(3,n,replace = TRUE) #assign a location for the car
p.success.choose1 <- sum(cardoor==1)/n #if don't switch, choose 1 door, probability of success (about 1/3)

monty <- function() { #create an interactive function
    doors <- 1:3
    cardoor <- sample(doors,1) #random sample of 1:3
    print("Pick a door (enter 1,2 or 3)") #prompt
    chosen<-scan(what=integer(),nlines = 1,quiet=TRUE) #receive choice of door
    if (chosen!=cardoor) montydoor<-doors[-c(chosen,cardoor)] else montydoor <- sample(doors[-chosen],1) #pick Monty's door
    print(paste("Monty opens door ",montydoor,".", sep = ""))
    print("Would you like to switch (y/n)?") #prompt to switch
    reply<- scan(what=character(),nlines=1,quiet =TRUE)
    
    if(substr(reply,1,1)=="y") {  #only change chosen if "y"
      chosen<-doors[-c(chosen,montydoor)]
    }
    
    if(chosen==cardoor) print("Yatze!") else print("Dang.")
    
}
monty()  

```

<!-- rnb-source-end -->

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


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuIG1lYW4ocilcblxuYGBgIn0= -->

```r
 mean(r)

```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIDE5LjQ3ODVcbiJ9 -->

```
[1] 19.4785
```



<!-- rnb-output-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuIyMgNS45IFIgQ29udGludW91cyBhbmQgUmFuZG9tIFZhcmlhYmxlcyAgPT09PT09PT1cblxuIyNQYWdlIDI1MyBVbmlmb3JtLCBOb3JtYWwsIGFuZCBFeHBvZW50aWFsIGRpc3RyaWJ1dGlvbnNcbmR1bmlmKDAuMSwwLDEpICNkdW5pZih4LGEsYikgaXMgUERGIG9mIFVuaWYoYSxiKSBhdCB4XG5wdW5pZigwLjUsMCwxKSAjQ0RGIGF0IHg9MC41XG5ydW5pZigxMCwwLDEpICMgZ2VuZXJhdGUgeD0xMCByYW5kb20gbnVtYmVycyBmcm9tIHVuaWYoMCwxKVxuXG5kbm9ybSgwLDAsMSkgI2Rub3JtKHgsbXUsc2QpIGlzIFBERiBvZiBub3JtYWwobXUsc2QpIGF0IHggKioqTk9URTogc2QgTk9UIHZhcmlhbmNlKipcbnJub3JtKDEwLDAsMSkgI2dlbmVyYXRlIDEwIHJhbmRvbSByZWFsaXphdGlvbnMgZnJvbSBhIHN0YW5kYXJkIG5vcm1hbFxuXG5kZXhwKDMsMykgI2RleHAoeCxsYW1kYSlcblxuIyMgUGFnZSAyNTQgUGxvdHMgaW4gUlxuY3VydmUoZG5vcm0sIGZyb209LTMsIHRvPTMsIG49MTApICMgcGxvdCB0aGUgc3RhbmRhcmQgbm9ybWFsIGZyb20gLTMgdG8gMyBldmF1bGF0ZWQgYXQgMTAgcG9pbnRzXG5cbnggPC0gc2VxKC0zLDMsMC4xKSAjbGlrZSBtYXRsYWJcbnkgPC0gZG5vcm0oeCwwLDEpICNzbyB5IGNvbnNpc3RzIG9mIHN0YW5kYXJkIG5vcm1hbCBldmFsdWF0ZWQgYXQgcG9pbnRzIHhcbiNwbG90KHgseSlcbnBsb3QoeCx5LHR5cGU9XCJiXCIsIGNvbD1cInJlZFwiLGx0eT0xLCBsd2Q9MSlcblxuIyMgUGFnZSAyNTQgVW5pdmVyc2FsaXR5IHdpdGggTG9naXN0aWNcblxudTwtIHJ1bmlmKDEwXjQpICMgc3RhcnQgd2l0aCByYW5kb20gcmVhbGl6YXRpb25zIGZyb20gYSB1bmlmb3JtIGRpc3RyYnV0aW9uXG54IDwtIGxvZyh1LygxLXUpKSAjIHVzZSBpbnZlcnNlIGZ1bmN0aW9uIHRvIGdldCB4IHZhbHVlcyB0aGF0IHNob3VsZCByZXNlbWJsZSBhIGxvZ2lzdGljIGRpc3RyaWJ1dGlvblxuaGlzdCh4LCBicmVha3M9MTAwKSAjIGNoZWNrIHRoYXQgaXQgXCJsb29rc1wiIGxpa2UgYSBsb2dpc3RpY1xuXG55PC1ybG9naXMoMTBeNCkgIyBjaGVjayBieSBtb3JlIGRpcmVjdGx5IGdlbmVyYXRpbmcgcmFuZG9tIHJlYWxpemF0aW9ucyBmcm9tIGEgbG9naXN0aWMgXG5oaXN0KHksIGJyZWFrcz0xMDApICMgeWVwIGxvb2tzIHRoZSBzYW1lIGFzIGFib3ZlXG5cbiMjIFBhZ2UgMjU1IFBvaXNzb24gcHJvY2VzcyBzaW11bGF0aW9uXG5cbiMgdGhlIHRpbWVzIGluIGJldHdlZW4gYXJyaXZhbHMgYXJlIGV4cG9uZW50aWFsLCBzbyBmaXJzdCB3ZSBnZW5lcmF0ZSBcImludGVyYXJyaXZhbFwiIHRpbWVzIGFzIGV4cG9uZW50aWFsIGRpc3RyaWJ1dGlvbiB3aXRoIHJhdGUgcGFyYW1ldGVyIGxhbWJkYVxubjwtIDUwICMgY291bGQgYmUgYW55dGhpbmdcbmxhbWJkYSA8LSAzICMgcmF0ZSAoMyBwZXIgdW5pdCBvZiB0aW1lKVxueCA8LSByZXhwKG4sbGFtYmRhKSBcbmhpc3QoeCkgIyB0YWtlIGEgbG9va1xudDwtIGN1bXN1bSh4KSAjIGZpbmFsIHN0ZXA6IGNvbnZlcnQgdGhlIGludGVyYXJyaXZhbCB0aW1lcyB0byBhcnJpdmFsIHRpbWVzIHVzaW5nIGN1bXVsYXRpdmUgc3VtIGZ1bmN0aW9uXG5cbnhfYXhpcyA8LSBzZXEoMTo1MClcbnBsb3QoeF9heGlzLHQpXG5gYGAifQ== -->

```r
## 5.9 R Continuous and Random Variables  ========

##Page 253 Uniform, Normal, and Expoential distributions
dunif(0.1,0,1) #dunif(x,a,b) is PDF of Unif(a,b) at x
punif(0.5,0,1) #CDF at x=0.5
runif(10,0,1) # generate x=10 random numbers from unif(0,1)

dnorm(0,0,1) #dnorm(x,mu,sd) is PDF of normal(mu,sd) at x ***NOTE: sd NOT variance**
rnorm(10,0,1) #generate 10 random realizations from a standard normal

dexp(3,3) #dexp(x,lamda)

## Page 254 Plots in R
curve(dnorm, from=-3, to=3, n=10) # plot the standard normal from -3 to 3 evaulated at 10 points

x <- seq(-3,3,0.1) #like matlab
y <- dnorm(x,0,1) #so y consists of standard normal evaluated at points x
#plot(x,y)
plot(x,y,type="b", col="red",lty=1, lwd=1)

## Page 254 Universality with Logistic

u<- runif(10^4) # start with random realizations from a uniform distrbution
x <- log(u/(1-u)) # use inverse function to get x values that should resemble a logistic distribution
hist(x, breaks=100) # check that it "looks" like a logistic

y<-rlogis(10^4) # check by more directly generating random realizations from a logistic 
hist(y, breaks=100) # yep looks the same as above

## Page 255 Poisson process simulation

# the times in between arrivals are exponential, so first we generate "interarrival" times as exponential distribution with rate parameter lambda
n<- 50 # could be anything
lambda <- 3 # rate (3 per unit of time)
x <- rexp(n,lambda) 
hist(x) # take a look
t<- cumsum(x) # final step: convert the interarrival times to arrival times using cumulative sum function

x_axis <- seq(1:50)
plot(x_axis,t)
```

<!-- rnb-source-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


<!-- rnb-chunk-begin -->


<!-- rnb-source-begin eyJkYXRhIjoiYGBgclxuc2tldyh4KVxuXG5gYGAifQ== -->

```r
skew(x)

```

<!-- rnb-source-end -->

<!-- rnb-output-begin eyJkYXRhIjoiWzFdIC0wLjA2NTM3MzlcbiJ9 -->

```
[1] -0.0653739
```



<!-- rnb-output-end -->

<!-- rnb-chunk-end -->


<!-- rnb-text-begin -->



<!-- rnb-text-end -->


# NingLi-CornellORIE-BDAOrg
STSCI-4780 Lab 01
STSCI-4780 Lab 01

Name: Ning Li 

Major: ORIE

Status: M.Eng, graduating in May, 2018

Bayesian statistics can be very usful whenever there is some extent of uncertainty. I am especially interested in its applications in Business/Operational problems. This article [Introduction To Bayesian Inference](https://www.datascience.com/blog/introduction-to-bayesian-inference-learn-data-science-tutorials) introduces some real-world applications, like evaluating new marketing campaigns, predicting effets of sales events, item pricing models for ecommerce, financial risk analysis, etc. 

Let me take evaluating new marketing campaigns for example. The campaign is to put an advertisement image of a yellow dress on Facebook to promote its sales on an ecommerce website. The data observed is that among 10 users presented this image to, 7 of them have clicked on it. The research question is, what is the probability that the next user will click on it?

![alt text](https://user-images.githubusercontent.com/36059888/35715683-0ff91e54-07a2-11e8-82f4-53f35662ed74.png)

Theta in the above graph is the probability in question. We assume "click" is a success and "not click" is a failure and the occurences of successes follow a binomial distribution with parameter theta. The prior probabilty line is the historical values estimate of theta in the past 100 campaigns.

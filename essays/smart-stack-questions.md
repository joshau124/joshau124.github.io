---
layout: essay
type: essay
title: "Smart People ask SMART Questions"
# All dates must be YYYY-MM-DD format!
date: 2026-01-28
published: true
labels:
  - Communication
  - Learning
  - Forums
---

## What's so SMART about questions?

In your schools, a teacher might've said that there's no such thing as a "dumb question." While this is true, it might be hard to get meaningful results off of bad questions. Rather, it would be easier to get useful information asking a question that had been previously thought out and explored. SMART Questions solves these issues by setting guidelines for askers to ask questions in a way that attracts others to give helpful responses to assist in solving the problem. Before continuing with this essay, learn more about SMART questions [here](http://www.catb.org/esr/faqs/smart-questions.html).

<img class="img-fluid" src="../img/stack-overflow.png">

## SMART == Good Responses

To show an example of how SMART questions can improve the quality of feedback given, I found a decent example on stack overflow, ["Highlight all values from single column"](https://stackoverflow.com/questions/79878258/highlight-all-values-from-single-column). While the title is not the greatest, the poster succeeds in other aspects of asking a SMART question. The overview is that they are "plotting likelihood ratios between several individuals along an array of genes." This enhances their question as those willing to answer now have an idea of what is happening. Also, the poster explains their goal, helping to give direction, going much further than explaining a single step to their goal. They include a visual image as well as the code for that image, both shown below. The poster also explains in their post what they've attempted to use, so answerers know that they might not have to explain certain concepts, saying "I have tinkered around with {gghighlight} and scale_color_manual() to assign colors to certain genes with the rest remaining black, but haven't gotten anything to work." To add onto this, the poster includes relevant tags that help identify what programs and software the poster is inquiring about. While it would've been more helpful to include this information in the title, its better to have it at least somewhere on the post. This poster got a response back, in part due to their SMART question, detailing that "[They] were right about scale_color_manual, the code below uses it..." This type of feedback is possible because the poster included how they attempted to solve the problem before going to stack overflow for help. The post got more than one answer, with multiple users giving different valid answers, giving the poster a variety of options to choose from. Overall, these excellent responses were, in part, possible due to the fact that the poster asked a SMART question and gave the responders information to work with and a good problem to solve.

<img class="img-fluid" src="../img/smart-question.png">


```cpp
df %>%
  pivot_longer(!Indiv) %>%
  ggplot(aes(x = Indiv, y = value)) + 
  geom_point() 
```

## !(SMART) == Bad Responses

On the other hand, not asking SMART questions will lead to bad or no responses at all. An example, also from stack overflow, is ["google play to big query data transfer using data transfer service cost issues"](https://stackoverflow.com/questions/79878490/google-play-to-big-query-data-transfer-using-data-transfer-service-cost-issues). This is not a SMART question for many different reasons. The easiest reason to spot is the grammar, there are no capitalization of nouns and many spelling mistakes present throughout the post. This except from the post shows the grammatical mistakes most clearly: "super confused thanks to chabots. if anyone can help pls do. thank you". Not only does the poster not use capital letters to start sentences, but they also use texting abbreviations. Furthermore, the first sentence of the except is not a complete sentence, lacking a subject, implying the poster is confused instead of outright stating it. This post was posted recently, but as of publishing this essay, it has zero responses and a -2 rating on stack overflow.

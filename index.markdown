---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home 
---

## What is it?

Choosistant is an ML-powered system which helps you decide which product to buy by summarizing the pros and cons from written product reviews.

At a high level, Choosistant leverages an NLP model (Extractive Question Answering) to predict which spans of text describe the advantages and disadvantages of the product under review.

![High level pipeline of choosistent](/assets/img/choosistant-high-level-pipeline.png)

If you want to more about how the NLP model works, please read the articles on Extractive Question Answering written by the folks at [Hugging Face](https://huggingface.co/tasks/question-answering) and [deepset](https://www.deepset.ai/blog/modern-question-answering-systems-explained).

## Who made it?

- Kimotho
- Murad Khalilov
    &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/muradkhalil/" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
    &nbsp;
    <a href="https://github.com/MuradKhalil" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
- Nam
    &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/changhyeon-nam-9306a616b/" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
    &nbsp;
    <a href="https://github.com/changhyeonnam" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
- Omar Ali Sheikh
    &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/osheikhomar/" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
    &nbsp;
    <a href="https://github.com/sheikhomar/" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
- Sofiane
    &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/sofiane-chami-a3259b87" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>

## Why is it useful?

We all experience it. You need to buy a new weighing scale. Your old scale stopped working. You want to replace it in a hurry. A quick search on amazon.com and you find a weighing scale with the Amazon’s Choice tag:

![Amazon.com's product card on a sleek weighing scale.](/assets/img/amazon-weight-scale-product-card.png)

The product looks slick, is highly rated and reasonably priced. But before clicking on the screaming Buy Now button, you are curious about what other people are saying about this product. Mostly the reviews are positive and say good things about the scale. But then you stumble on a seemingly positive review:

![A reviewer rates 5 stars but mentions that the scale is inaccurate.](/assets/img/amazon-review-five-star-negative-review.png)

Wait, what?! So this weighing scale cannot even provide its basic functionality correctly? You find other consumers reporting similar inaccuracies:

![A reviewer writes that the scale is inaccurate.](/assets/img/amazon-review-one-star-inaccurate.png)

It seems that this scale is neither consistent nor accurate with its measurements. You also find worrying reviews about the scale’s robustness.

![Two reviews state that the product stopped working after a while.](/assets/img/amazon-review-product-dies.png)

Now what? You look for alternative products and read their reviews. Soon, you are spending a huge amount of time reading a bunch of reviews, wishing there was a way to have a summary of all the reviews in one place. Enter choosistant!

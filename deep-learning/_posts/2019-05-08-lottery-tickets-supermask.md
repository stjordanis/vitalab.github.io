---
layout: review
title: "Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask"
tags: network-pruning
author: "Carl Lemaire"
cite:
    authors: "Hattie Zhou, Janice Lan, Rosanne Liu, Jason Yosinski"
    title:   "Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask"
    venue:   "arXiv:1905.01067"
pdf: "https://eng.uber.com/deconstructing-lottery-tickets/"
---

This review is based on the blog post linked above, which describes a paper on Arxiv with the same title. This paper builds upon the "Lottery Ticket Hypothesis" paper, which I have reviewed on this very website. By the way, the original Lottery Ticket paper has just been awarded Best Paper at ICLR 2019.

# The Lottery Ticket Hypothesis

The hypothesis can be coarsely summarized as follows: "When initializing the parameters of a network, each value is a lottery ticket: a winning ticket is a parameter value that will be useful; a losing ticket's value will move towards zero."
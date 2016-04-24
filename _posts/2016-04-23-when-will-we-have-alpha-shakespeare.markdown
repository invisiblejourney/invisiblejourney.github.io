---
layout:     post
title:      "When Will We Have Alpha-Shakespeare"
subtitle:   "In March, AlphaGo won the game with Lee Sedol, top professional Go player, 4 vs 1. When can we have Alpha-Shakespeare writing for us?"
date:       2016-04-23 20:00:00
author:     "Leo Zhao"
header-img: "img/contact-bg.jpg"
---

Go is a chess game originated in ancient China. Two players place stones on a 19X19 chess board. So, first play has 19x19=361 possible places. The next play has 361-1=360 possible places. Since the possible places are so many, using exhausting enumeration isn't possible.

Google DeepMind team already developed a DeepRL system with combines Deep Neural Networks with Reinforcement Learning to play Atari 2600 gaems. Just by using raw pixels and scores as inputs, with plenty of time, it could learn all the tricks a human would learn, and also find strategies that haven't been discovered, and reach a level that human couldn't reach.

Neural networks are not new. It has been used for decades as an alternative way to do categorization, clustering, filtering, etc. But Deep Neural networks are new. Since only up until now, we have powerful GPU cards that could host thousands of cores, and employ massive parallelization to speed up the calculation and scale of neural networks. 

I wouldn't go too much into the details. Just to show how massive it is. Let's say we have a game screen with 1024X768 pixels. To use this as input, we need to have a front layer with equal amount of node. That is 768,432 nodes. Two such layers fully connected would require 768,432x768,432=618 billion edges. Three such layers fully connected would have 486388 trillion edges. Assume one edge needs 8 bytes (a double) to store. That would require nearly a million 4 TB hard drives. Modern Deep Neural networks usually have around 20 layers. Fully connected layers are only used in upper layers where notes are quite limited. Input layers are usually partially connected to lower down the calculation burden.

Back to the topic, AlphaGo already won top human player. When can we have a program that can write stories for us? Well, don't put expection too high yet. Each play in Go chess only has up to 361 moves. A novel could have tenth of thousands word. Take Game of Thrones for example. George R. R. Martin used close to 40,000 words in it.

While it is possible to generate text that sorts of having some meanings using some simple statistic models, there hasn't been any major advancement that would make computer write anything entertaining. So, writers, you are safe, for now. 


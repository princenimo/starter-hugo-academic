---
title: Deep Reinforcement Learning for Automated Stock Trading
summary: Final Project for 2022 CS 394R Reinforcement Learning - Charles Nimo & Chima Ezeilo
tags:
- Reinforcement Learning
- Deep Learning
date: "2022-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:

url_code: "https://github.com/princenimo/DRL-for-Automated-Stock-Trading-"
url_pdf: "files/rl.pdf"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=xg-c_cOUEyo&t=0s&ab_channel=Rinato"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

Everyday millions of traders around the world aim to trade stocks to make money. However, stock trading has never been easy. Stock prices depend on multiple factors and it is very difficult to develop a good strategy and make decisions such as when to buy? when to hold? and when to sell?  Lately, Deep Reinforcement learning (DRL) agents have proven to show great promise in games such as Chess and Go. However, it remains a big challenge to design a profitable strategy in a complex and dynamic stock market. This paper explores the application of Trust Region Policy Optimization (TRPO), a policy gradient method,to learn an optimal strategy for high portfolio automated stock trading. We model the stock trading process as a Markov Decision Process (MDP) and then formulate our trading goal as a maximization problem. This agent learns to automatically position itself to win the market, specifically, it decides where to trade, at what price, and what quantity. We also train three other reinforcement learning algorithms, Soft Actor Critic (SAC), Proximal Policy Optimization(PPO), and Twin Delayed DDPG (TD3) to serve as baselines to compare their performances. In this experiment, we choose the Dow Jones Industrial Average (DJIA) 30 constituent stocks as they are the most popular stocks for portfolio allocation. We demonstrate the credibility and advantages of TRPO in financial markets for strategic decision making in portfolio allocation.

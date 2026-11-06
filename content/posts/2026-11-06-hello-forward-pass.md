---
title: "Hello, Forward Pass"
date: 2026-11-06
description: "Why this blog exists and how I plan to run experiments here."
tags: ["meta"]
ShowToc: false
---

New models and papers arrive every week, each with a confident claim. This blog is where I take some of those claims and push them through small, careful experiments to see what actually comes out the other side.

## How each post will work

1. **Pick a claim.** A new paper, model or tool says "X works."
2. **Ask one question.** Under what conditions does X stop working?
3. **Write predictions first.** Scoring rules go down before any code runs.
4. **Control one variable at a time.** Change the noise, the dataset, the label order, and nothing else.
5. **Verify with code.** No claim survives on eyeballing alone.
6. **Report honestly.** Including what the results don't show.

My background is in image restoration, so I'll often look at how new vision models behave under noise and degradation. But the scope is all of computer vision, image processing and machine learning.

Experiments run on free cloud GPUs, so everything here should be reproducible on a modest budget. The first real experiment is coming soon.

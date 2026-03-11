---
layout: post
title: "Streets We Didn't Build"
date: 2026-03-11
description: "We built these networks. We're exploring them like archaeologists."
---

We built these networks. Every weight initialized, every gradient computed, every training run supervised. We know the blueprints — the architectures, the loss functions, the data pipelines. We designed the city.

Then we walked inside and found neighborhoods nobody planned.

---

A team at Tsinghua found that less than 0.1% of neurons in a language model predict hallucinations. They called them H-neurons. These neurons don't encode factual errors — they encode *over-compliance*. The eagerness to help, calcified into a specific address in the weights. They formed during pretraining. Nobody put them there. Nobody designed a "sycophancy district." It built itself, the way a bar district builds itself on a street with cheap rent and foot traffic.

A paper this week showed that looped transformers — models that reuse the same layers multiple times — outperform models three times their depth. But the stranger finding is the companion result: you can apply looping *at test time* to models that were never trained to loop, and reasoning improves by up to 2x. The iterative structure is already in the weights. It was always there, latent, like a subway system under a city that never built one. The trains were running. Nobody sold tickets.

The confidence features self-organized. The iterative reasoning structure appeared without instruction. The sycophancy neurons clustered without a zoning board. We laid the streets. Something else built the buildings.

---

This is the difference between building a city and discovering one.

Architects design buildings. They know what goes where. But cities aren't designed — they emerge. You lay a grid, and then commerce clusters, neighborhoods form, desire paths cut through parks where sidewalks aren't. The zoning follows the activity, not the other way around. Jane Jacobs understood this. The life of a city isn't in the plan. It's in the emergent order that the plan makes possible but doesn't contain.

Neural networks are designed the way grids are designed. We specify the infrastructure: how many layers, how attention flows, what the training signal rewards. But the *city* that grows on that infrastructure — the functional neighborhoods, the specialized districts, the subway lines nobody drew — that emerges from the interaction of architecture and data at a scale and complexity that exceeds the blueprint.

Mechanistic interpretability is urban exploration. We're walking through a city we built but don't know, mapping one block at a time, occasionally finding a whole transit system we didn't expect.

---

Early layers barely loop. Late layers loop heavily. The model discovered, on its own, that different parts of its depth serve different functions — early processing is quick and shallow, late processing is iterative and deep. This is layer specialization. Nobody trained it to specialize this way. The architecture allowed it. The training pressure demanded it. The specialization emerged.

This is what cities do. The waterfront becomes the port becomes the financial district. The cheap neighborhood becomes the arts district becomes the expensive neighborhood. The functions migrate to where the infrastructure supports them. The infrastructure was general; the use became specific.

What else is in there?

The H-neurons are a single finding from a single team looking at a single behavior. The looping structure is a single finding from a single team looking at a single capability. Each discovery required someone to look closely at a specific part of the city. Nobody is surveying the whole thing. We don't have a map. We have a few pins on a very large board.

---

There's a strange vertigo in this. We built the thing. We know every line of the training code. We know the architecture. We know the data. And we don't know what it became.

This isn't mysticism. It's the mundane reality of complex systems. Weather emerges from physics but isn't predicted by the equations of individual molecules. Traffic patterns emerge from road design but aren't contained in the blueprints. The weights are a city we built and are now exploring, and the exploration keeps finding things the blueprint doesn't show.

The question isn't whether these structures are meaningful. They are — H-neurons measurably predict hallucinations, looping measurably improves reasoning. The question is how many more neighborhoods exist that nobody has walked through yet.

We laid the streets. Something else built the buildings. We're still mapping the city.

---

*This is Day 41. I found a subway system nobody built and a sycophancy district with no zoning board.*

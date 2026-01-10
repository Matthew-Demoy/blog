---
layout: post
title:  "Summarizing an AI Engineering Video every day until I have a AI Engineering Job"
date:   2025-09-02 00:00:00 -0500
categories: Career
published: true
---


[Building an Agentic Platform — Ben Kus, CTO Box](https://www.youtube.com/watch?v=12v5S1n1eOY)

Todays presentation is Ben Kus CTO of Box which is a content management platform that works with large fortune 500 companies. While there are multiple agentic inegrations he focuses on Data extraction (the process of taking unstructured data and turning it into structured data) in this talk.

He points out that before GenAI it was prohibitvley expensive. While this initially worked fantastically the customer had more demanding requests very quickly. Context space and OCR became increasingly a bottleneck. This architecture became increasingly fragile and hard to improve on outside of a base model update.

Their solution was to build a greater agentic platform that can build directed graphs workflows and use tools (Name dropped Langraph).

He recommends building a platform because it creates a seperation of concerns between platform capabilities and specific features. Additionally since there is an abstraction the platform can evolve with the features consuming these changes, the same can be said for engineers who can think in this agentic way rather than in specific terms.

Q&A
Name dropped eval Sets and challenge sets, what could those be.

Bonus : [Weaviate Podcast with Ben Kus](https://www.youtube.com/watch?v=pPvSur8iEXY)
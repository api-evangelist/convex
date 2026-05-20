---
title: "Reimplementing Mastra Workflows: Lessons Learned"
url: "https://stack.convex.dev/reimplementing-mastra-regrets"
date: "Fri, 28 Mar 2025 16:00:00 GMT"
author: "Stack"
feed_url: "https://stack.convex.dev/rss/feed.xml"
---
I reimplemented Mastra’s agentic workflows with durable functions in Convex, and it was the wrong decision. Look at three common strategies (reimplementation, API wrapping, and “blessed” plugin paths), along with learnings along the way and reflections on what I’d do differently next time. TL;DR: Do less, do it smarter, and prototype faster.

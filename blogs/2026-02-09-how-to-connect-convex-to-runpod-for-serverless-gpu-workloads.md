---
title: "How to connect Convex to RunPod for serverless GPU workloads"
url: "https://stack.convex.dev/convex-gpu-runpod-workflows"
date: "Mon, 09 Feb 2026 22:33:22 GMT"
author: "Stack"
feed_url: "https://stack.convex.dev/rss/feed.xml"
---
Every GPU task I've run from a backend has the same problem: you fire off the job, then poll for results or wire up webhooks to know when it's done. This walkthrough shows a different approach. Convex triggers a GPU job on RunPod, and the RunPod worker calls mutations directly on Convex using the Python client. The frontend stays in sync through live queries. No polling, no webhook infrastructure. I'll walk through the full implementation using video background removal as the example, but the pattern works for any GPU workload — compression, transcription, object detection, whatever you need.

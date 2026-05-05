---
title: "Efficient COUNT, SUM, MAX with the Aggregate Component"
url: "https://stack.convex.dev/efficient-count-sum-max-with-the-aggregate-component"
date: "Sat, 16 Aug 2025 05:46:00 GMT"
author: "Stack"
feed_url: "https://stack.convex.dev/rss/feed.xml"
---
Convex omits built-in aggregates because full-table scans don’t scale; the video shows how @convex-dev/aggregate (B-Tree powered) enables fast pagination, ranking, per-user stats, and randomization with fully reactive queries. It also covers keeping aggregates in sync via triggers/custom functions, backfilling with migrations, and the trade-offs that hint at possible platform-level support.

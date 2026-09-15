# Speculative Tool Calling Article Design

## Goal

Add a second research-focused post explaining how speculative programmatic tool calling can reduce agent latency.

## Content

The article will use Alex Zhang's 2026 sPTC article as the anchor source, then connect it to speculative decoding, asynchronous function calling, and real-time speculative tool calling. It will explain the latency problem, overlap opportunities, shadow execution, dependency and side-effect rules, caching/futures, expected trade-offs, and how to evaluate speed and correctness.

## Page Changes

- Add a second entry to `blog/index.html`.
- Add `blog/speculative-tool-calling.html` with the full article.
- Keep the existing homepage preview unchanged because it points to the featured memory-systems post.

## Presentation

Reuse the existing article style. Include a streaming timeline, pseudocode, a research comparison table, limitations, and numbered inline citations with a references section. Claims will distinguish the supplied blog's implementation discussion from results reported in the related papers.

## Validation

Check the new index link, article link, citation anchors, external references, mobile table overflow, and static relative paths.

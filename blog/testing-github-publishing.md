---
date: 2026-11-18
title: "Testing GitHub publishing"
permalink: "/blog/testing-github-publishing/"
---

We now publish articles to our own site through pull requests.

When an article is ready, Paragraph prepares a pull request with the article file in our site’s repository. The pull request gives us a chance to review the change before it becomes part of the site. We can check the text and formatting, then merge it when everything looks right.

This keeps the publishing step close to the way we already work with the site. Articles are added through the repository, and the site can build from the merged change. The pull request also gives us a clear record of what changed and when it was reviewed.

This is a test of the new setup. The goal is to make it easier to publish articles on our own site while keeping a review step before they go live. Once the pull request is merged and the site deploys, the article will be available there.

---
layout: page
title: MyPeople Video Service
description: Adaptive streaming pipeline with AI-powered content discovery and personalized recommendations for a social media platform.
img: assets/img/6.jpg
importance: 1
category: Software Engineering
---

**Technologies:** ASP.NET Core, PostgreSQL, AWS (S3, Lambda, MediaConvert), pgvector, Ollama, Claude API

---

### Overview

Contributed to *Fliks*, the short-form video feature of the **MyPeople** social media platform. The project focused on transforming raw video delivery into a scalable, AI-enriched adaptive streaming experience.

### Key Contributions

- **Adaptive Streaming Pipeline:** Replaced raw video delivery with a robust pipeline using **AWS S3**, **AWS MediaConvert**, and **AWS Lambda** — improving playback performance and reducing buffering significantly.

- **AI-Powered Content Enrichment:** Built an automated pipeline that generates video tags from snapshots using the **Claude API** and creates semantic vector embeddings via **Ollama**, storing them in **PostgreSQL** with the `pgvector` extension for similarity search.

- **Personalized Recommendation System:** Developed a recommendation engine combining vector similarity search with user behavior, watch history filtering, duplicate prevention, and recommendation prioritization.

- **Performance Optimization:** Optimized PostgreSQL queries and indexing, implemented region-based content restrictions, and collaborated with the mobile team to introduce video prefetching for a smoother user experience.

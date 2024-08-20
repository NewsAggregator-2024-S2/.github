# New Aggregator
## Overview
- Background:
In today's fast-paced world, sensational and profit-driven news often contributes to daily stress. There's a growing need for a platform that offers a relaxing and ethical news experience, free from sensationalism and clickbait.

 - Vision:
To reduce the stress caused by provocative and revenue-driven news, providing users with a more relaxing news experience based on ethical principles.

 - Mission:
To offer a smooth, stress-free news experience available where, when, and how users want it.

 - Project Brief:
News Aggregator utilizes Natural Language Processing (NLP) technology to scrape news websites and generate concise summaries of news articles based on topics users subscribe to. This ensures users receive up-to-date content tailored to their interests, all accessible from a single platform. The project also incorporates image generation technology to enhance the appeal of news articles, creating a unique style and offering a more personalized experience for users. Additionally, the integration of diverse comments and market predictions adds depth to the news articles, allowing users to engage with different perspectives and stay informed about public opinion and market trends.

## Goals and Tasks
Goals:
1. Develop a structured pipeline for enriching articles and creating images.

2. Create a workflow for identifying and visualizing key entities in articles.

3. Iterate and improve the visual presentation based on feedback and experimentation.

## Tasks:
 - Fetch and Enrich Articles:

Retrieve articles from the source and enhance them with additional information (e.g., summaries, relevant data).

 - Select and Process Articles:

Choose an article from the cached JSON for image creation, detect and select the primary person entity from the article.

 - Image Retrieval and Processing:

Use the Openverse API to search and download images of the primary person, apply extraction code to select the best image, and position the person on a 1920x1080 image using Pillow.

 - Iteration and Improvement:

Review and refine the image design, experiment with different elements, apply new designs to various articles and people, and explore future enhancements (e.g., adding a second person, incorporating symbols and text).


## Milestones
  * [x] Foundation and Basic Image Processing
  * [x] Entity Recognition and Text Overlay
  * [ ] Full Frame and Split Frame: Image-Text  **- ongoing**
  * [ ] Gradient Portraits and Split Frame: Scene-Portrait
  * [ ] Dual Portraits (Simple, Gradient, Diagonal
  * [ ] Triple Frame and Circular Focus
  * [ ] Quad Frame and Integration

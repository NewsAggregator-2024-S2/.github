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
Week 1 - Week 2
  * [x] Foundation and Basic Image Processing
      * [x]  1. Set up project repository and development environment
      * [x]  2. Implement image acquisition and caching from approved sources
      * [x]  3. Develop basic image quality assessment function
      * [x]  4. Create a simple background removal function
      * [x]  5. Implement basic color manipulation (including B&W conversion)
  * [x] Preparation for Audit 1
   
Week 3 - Week 4       
  * [x] Entity Recognition and Text Overlay
      * [x]  1. Develop entity recognition function to extract key entities from articles
      * [x]  2. Create text generation function for overlays
      * [x]  3. Implement text positioning and styling function
      * [x]  4. Integrate text overlay with existing image processing pipeline
      * [x]  5. Begin work on the "Full Frame" composition type
    
Week 5 - Week 6
  * [ ] Full Frame and Split Frame: Image-Text  **- ongoing**
      * [x] 1. Finalise "Full Frame" composition type
      * [ ] 2. Implement advanced cropping algorithm for "Split Frame: Image-Text"
      * [ ] 3. Develop text extraction and formatting for the text portion
      * [ ] 4. Create cohesive colour scheme function for image and text portions
      * [ ] 5. Integrate all components for "Split Frame: Image-Text
  * [x] Preparation for Audit 2

Week 7 - Week 8
  * [ ] Gradient Portraits and Split Frame: Scene-Portrait
      * [ ] 1. Develop gradient generation function
      * [ ] 2. Implement figure isolation and placement for "Gradient Portrait"
      * [ ] 3. Create scene selection and cropping for "Split Frame: Scene-Portrait"
      * [ ] 4. Develop blended gradient background for portrait in split frame
      * [ ] 5. Integrate components for both composition types
       
Week 9 - Week 10
  * [ ] Dual Portraits (Simple, Gradient, Diagonal
      * [ ] 1. Develop face detection and optimal cropping for dual portraits
      * [ ] 2. Implement "Dual Portrait: Simple" with balancing adjustments
      * [ ] 3. Create gradient background generation for "Dual Portrait: Gradient"
      * [ ] 4. Develop diagonal splitting and cropping for "Dual Portrait: Diagonal"
      * [ ] 5. Implement dynamic text placement for diagonal layout
   
Week 11
  * [ ] Triple Frame and Circular Focus
      * [ ] 1. Develop three-part image selection and cropping for "Triple Frame"
      * [ ] 2. Implement colour harmonisation across three images
      * [ ] 3. Create circular masking and feathering for "Circular Focus"
      * [ ] 4. Develop background blur and vignette effect for "Circular Focus"
      * [ ] 5. Implement text placement for both composition types
   
Week 12
  * [ ] Quad Frame and Integration
      * [ ] 1. Develop four-part image selection and cropping for "Quad Frame"
      * [ ] 2. Implement colour harmonisation across four images
      * [ ] 3. Create central overlapping element for "Quad Frame"
      * [ ] 4. Develop main interface for selecting composition types based on article content
      * [ ] 5. Integrate all components into a unified system
      * [ ] 6. Conduct thorough testing and bug fixing

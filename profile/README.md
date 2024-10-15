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
  * [x] Full Frame and Split Frame: Image-Text
      * [x] 1. Finalise "Full Frame" composition type
      * [x] 2. Implement advanced cropping algorithm for "Split Frame: Image-Text"
      * [x] 3. Develop text extraction and formatting for the text portion
      * [x] 4. Create cohesive colour scheme function for image and text portions
      * [x] 5. Integrate all components for "Split Frame: Image-Text
  * [x] Preparation for Audit 2

Week 7 - Week 8
  * [x] Code structure integration and optimisation
      * [x] 1. Divide the code into modular parts
      * [x] 2. Discuss on code reconstruction for improved optimization and testing
      * [x] 3. Define clear components for further development and testing phases
      * [x] 4. Optimize face recognition and segmentation features
      * [x] 5. Test and validation of the optimized components
      * [x] 6. Make the project video and showcase 
       
Week 9 - Week 10
  * [x] Preparation for video showcase **- ongoing**
      * [x] 1. Make the project video and showcase 
      * [x] 2. Make the poster
      * [x] 3. Make the testing with client, tutor and shadow team
  * [x] Preparation for Audit 3
   
Week 11 - Week 12
  * [ ] Project closure phase
      * [ ] 1. Develop main interface for selecting composition types based on article content
      * [ ] 2. Integrate all components into a unified system
      * [ ] 3. Conduct thorough testing and bug fixing
      * [ ] 4. Make personal Work Portfolio Package

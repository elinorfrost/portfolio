---
title: Survey Chatbots
draft: false
tags:
---
[View the repository](https://github.com/elinorfrost/SurveyLitReview)

[Read the preliminary paper](https://doi.org/10.48550/arXiv.2509.03391)

> [!tldr] TLDR
> I contributed to Professor Adam Eck's research lab at Oberlin College from September of 2023 through December of 2024. 
> - I learned how to use `R` and the `Shiny` package to generate interactive visualizations for our data.
> - I used `Python` for interacting with a research database's API for a literature review.

### Abstract:

Large language models and Artificial Intelligence (AI) Chatbots (e.g., ChatGPT, Bard, Meta AI, etc.) are increasingly commonplace tools for augmenting everyday human tasks, and are especially effective at composing text in a timely manner. However, research has yet to critically examine the quality of such compositions and the implications of using AI in professional or research settings. Our team investigated leveraging AI Chatbots in survey research by employing various strategies to prompt ChatGPT 3.5 for survey questions, and then analyzing the quality and relevance of ChatGPT’s responses.

Our initial experiments found that forgoing the word “survey” in the prompt often resulted in incorrect question format (i.e. ChatGPT generated a test question with a ‘correct’ answer). We continue to investigate responses from prompts of various specificities and reading levels, and we hope to provide general guidance in effectively utilizing ChatGPT for survey questionnaire design. Our foundational work has additional implications, as we are among the first to critically evaluate AI-produced survey content. Future research in AI-assisted survey generation may investigate and address the ethics of generating sensitive survey questions with AI, as well as the potential role of AI in designing surveys that minimize biases impacting survey research.

## Highlights

#### Data Visualization with R

During my research experience, I collected the responses from ChatGPT after prompts for various survey questions. This data reflected how prompt engineering for a large language model can produce responses of varying relevance and quality. Following data collection, my main task was to develop an interactive visualization platform of our results, which I did using `R`.
#### Literature Review

My second large task was to assist in the literature review process. I wrote a preliminary `Python` script to use the Semantic Scholar API, which compiled papers based on specific search terms related to the project. These were then formatted into BibTex to generate bibliographies.
#### Presentation at a Research Symposium

I presented an overview of the project and my contributions in the Oberlin Summer Research Institute Symposium in 2024. This allowed me to practice communicating technical information to an interdisciplinary audience. I also learned how to create professional presentation slides using the `Beamer` document class in `LaTeX`. 

![[PresentationSlides.pdf]]
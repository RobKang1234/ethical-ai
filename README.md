# The Governance of Ethical AI - Examples and Proposed Solutions to Bias in Application of AI Models
_Authors: Shaofeng Kang | Kaiyi Tang | Zhuolin Zhou_

---

## Abstract
> With the growing development of Applied AI, ethics and governance of these AI models become increasingly important. Governing artificial intelligence ethics and ensuring ethical usage in hiring and other industrial applications is crucial for maintaining fairness, transparency, and accountability. There have been a few reports of biased AI models being used in some critical processes of companies. In this paper, we will present case analysis of biased AI incidents and propose a hybrid solution from regulatory and technical perspectives. 
---

## Table of Contents
- [Introduction](#introduction)
- [Case Analysis](#case-analysis)
  - [Amazon’s Hiring Algorithm - Bias against Sensitive Personal Features](#amazons-hiring-algorithm---bias-against-sensitive-personal-features)
  - [COMPAS - Algorithmic Bias in Criminal Justice](#compas---algorithmic-bias-in-criminal-justice)
  - [Google’s AI - Accountability in AI Development](#googles-ai---accountability-in-ai-development)
  - [Microsoft AI Chatbot - Lack of Safeguard](#microsoft-ai-chatbot---lack-of-safeguard)
  - [Face Recognition Technology – Privacy and Fairness Concerns](#face-recognition-technology--privacy-and-fairness-concerns)
  - [Responsible AI in Action – Google Maps and Waze Traffic Prediction](#responsible-ai-in-action--google-maps-and-waze-traffic-prediction)
- [Ethical AI Governance Framework](#ethical-ai-governance-framework)
- [Government Perspective - Regulatory Framework](#government-perspective---regulatory-framework)
- [Technical Perspective - Adversarial Debiasing Model Architecture](#technical-perspective---adversarial-debiasing-model-architecture)
- [Conclusion](#conclusion)

---

## [Introduction](#introduction)
> Responsible AI is crucial for ensuring that technology serves humanity in a way that is fair, ethical, and transparent. Without proper oversight, AI can unintentionally replicate and amplify existing biases. This is exemplified by Amazon’s hiring algorithm and the COMPAS tool in criminal justice, where AI-driven models, trained on historical data, favored certain demographics and inadvertently reinforced inequality.
> 
> Transparency and accountability are also vital in building trust in AI systems. The controversy surrounding Google’s Ethical AI team highlights the risks when transparency is lacking, while Microsoft’s Tay chatbot incident reminds us of the importance of safeguards, particularly in public-facing AI applications. Privacy is another key area in responsible AI. For example, facial recognition technology has raised concerns about accuracy and fairness, especially when applied to people with diverse skin tones. These issues demonstrate the need for frameworks that protect user rights and ensure ethical use of data.
> 
> To address these challenges, governments and AI developers need to collaborate on ethical governance. Regulatory frameworks focused on fairness, transparency, privacy, and accountability can set the stage for responsible AI development. In practice, this means developing AI with explainable processes, involving diverse development teams to identify and mitigate biases, and using techniques like adversarial debiasing and fairness metrics. By focusing on these principles and incorporating oversight, AI systems can align with societal values, fostering public trust and delivering sustainable benefits while minimizing potential harm.
>
> In this paper, we will present six case studies on issues of ethical AI such as bias, safeguards, and accountability, followed by a proposed technical solution to the bias issue. 



---

## [Case Analysis](#case-analysis)
Each case study presents a distinct ethical challenge in AI, providing insights into biases, accountability issues, and privacy concerns. Without proper oversight, AI systems can unintentionally perpetuate bias and discrimination, as seen in Amazon’s hiring algorithm and the COMPAS criminal justice tool. These cases demonstrate how algorithms, when trained on biased historical data, can amplify inequalities rather than mitigate them. Transparency and accountability are also crucial, as illustrated by Google’s Ethical AI controversy, where the dismissal of researchers raised questions about the company's commitment to responsible practices. Moreover, incidents like Microsoft’s Tay chatbot highlight the importance of implementing safeguards to prevent AI from behaving unpredictably, especially in public-facing applications. Privacy concerns, such as those surrounding facial recognition technologies, further underscore the need for responsible frameworks that protect user rights and data. On the positive side, examples like Google Maps and Waze show that AI, when developed responsibly, can enhance everyday life by providing valuable services through transparent and user-focused design. Ultimately, Responsible AI ensures that technological advancements align with societal values, fostering trust and delivering sustainable benefits while minimizing potential harm.


### [Amazon’s Hiring Algorithm - Bias against Sensitive Personal Features](#amazons-hiring-algorithm---bias-against-sensitive-personal-features)
#### What Happened:
Amazon developed a machine learning-based hiring tool to screen job applicants. However, the system exhibited bias against women due to training on historical hiring data that favored male candidates.

#### Impact:
The hiring tool penalized resumes containing words like "women's" (e.g., women’s chess club captain). As a result, Amazon ultimately scrapped the project, recognizing that the tool was neither fair nor aligned with the company's diversity goals.

#### Lesson:
This case underscores the critical importance of fairness in AI systems. It demonstrates the need for careful assessment of training data to prevent the reinforcement of historical biases.

> **Details:**  
> After modifications to the algorithms in Amazon’s recruiting engine, masculine-dominant keywords became pivotal. The research group developed 500 models tailored to specific job functions and locations, each trained to recognize over 50,000 parameters found in applicant resumes. Despite the broad parameter set, the algorithms learned to assign minimal significance to skills common across applicants, such as programming languages and platforms used.

#### Reflection:
As society continues to integrate machine learning into decision-making processes, special attention to bias is crucial, as these biases may sometimes be unconsciously embedded within models. Amazon’s AI research team’s recognition and response to this bias serves as an essential example of proactive management of ethical AI challenges.

### [COMPAS - Algorithmic Bias in Criminal Justice](#compas---algorithmic-bias-in-criminal-justice)
> Analyze the COMPAS algorithm used in criminal justice, focusing on biases against specific demographics and its consequences for fairness in sentencing and parole decisions.

### [Google’s AI - Accountability in AI Development](#googles-ai---accountability-in-ai-development)
> Explore Google's AI projects and the associated accountability challenges. Highlight specific instances where transparency and accountability in AI decision-making were scrutinized.

### [Microsoft AI Chatbot - Lack of Safeguard](#microsoft-ai-chatbot---lack-of-safeguard)
> Examine Microsoft's AI chatbot case and the lack of safeguards, addressing the ethical responsibilities of companies in controlling AI behavior in public interactions.

### [Face Recognition Technology – Privacy and Fairness Concerns](#face-recognition-technology--privacy-and-fairness-concerns)
> Discuss the privacy and fairness concerns surrounding facial recognition technology, with an emphasis on misuse potential, accuracy disparities, and privacy invasions.

### [Responsible AI in Action – Google Maps and Waze Traffic Prediction](#responsible-ai-in-action--google-maps-and-waze-traffic-prediction)
> Present a positive case study on responsible AI, analyzing how Google Maps and Waze utilize predictive algorithms ethically while respecting user privacy and ensuring fairness.

---

## [Ethical AI Governance Framework](#ethical-ai-governance-framework)
> Outline a framework for ethical AI governance, detailing principles like transparency, fairness, accountability, and privacy. Discuss how organizations can implement these principles in AI development.

---

## [Government Perspective - Regulatory Framework](#government-perspective---regulatory-framework)
> Review current and emerging government regulations and policies regarding AI ethics. Discuss examples of regulatory measures and their implications for AI development and deployment.

---

## [Technical Perspective - Adversarial Debiasing Model Architecture](#technical-perspective---adversarial-debiasing-model-architecture)
> Provide a technical overview of adversarial debiasing as a solution for mitigating biases in AI. Include a discussion of model architecture, training methodology, and examples of its application.

---

## [Conclusion](#conclusion)
> Summarize the main insights from each section and emphasize the importance of adopting ethical practices in AI development. Conclude with a call to action for both industry and policymakers to prioritize ethical considerations in AI advancement.

## [References](#references)
> Cite all sources, including articles, books, datasets, and software used in the report. Use a consistent citation style.

## [Appendices](#appendices)
> Include additional information, such as raw data, code snippets, or detailed calculations that support the main content but are too detailed for the body of the report.

---

# **Проект "Предвзятость ИИ"**
## Термины
- *AI Fairness* - принцип, согласно которому ИИ-системы должны быть созданы и работать таким образом, чтобы они не были предвзяты по отношению к конкретным людям или группам людей.
- *AI Bias* - явление, при котором ИИ выдает предвзятые или несправедливые результаты из-за предвзятости, которая присутствовала в алгоритмах и данных, на которых она была обучена.
- *AI Transparency* относится к возможности понять и объяснить как ИИ принимает решения, и являются ли ее решения справедливыми и этичными.
- *Responsible AI* относится к этической разработке и внедрению ИИ, который приоритетизирует справедливость и человеческое благополучие. Использование ИИ не должно вредить людям.
- *Human-centric AI* - это подход к искусственному интеллекту, который ставит во главу угла человеческое благополучие, ценности и сотрудничество. Он гарантирует, что системы ИИ будут разрабатываться для расширения человеческих возможностей, а не для их замены или контроля.
- *AI Ethics* относится к этическим принципам и гайдлайнам, которые регулируют разработку, развертывание и использование искусственного интеллекта. Она обеспечивает работу систем ИИ справедливым, прозрачным, подотчетным (accountable) и полезным для общества образом.
## Кто этим занимается
## Use-cases
- [The Mirror in the Machine: Generative AI, Bias, and the Quest for Fairness](https://medium.com/towards-data-science/the-mirror-in-the-machine-generative-ai-bias-and-the-quest-for-fairness-c39b03a6d48d) - An experiment in generative AI bias for hiring decisions. The results for GPT-3.5 resulted in an astounding preference for the white candidate. The evaluation returned a decision to hire the white candidate 100% of the time. The author fed an AI model with 10 profiles, identical in qualifications and experience, except for the candidates’ names and ethnicities (white and African American). 2 steps: Resume Generation Methods and Results and Resume Evaluation Methods and Results. ![image](https://github.com/user-attachments/assets/65b12744-ea52-4409-9dac-8c2c1aa16c71)
- [Evaluating fairness in ChatGPT](https://openai.com/index/evaluating-fairness-in-chatgpt/) - an OpenAI research, where they explored how subtle cues about a user's identity—like their name—can influence ChatGPT's responses. To focus their study on fairness, they looked at whether using names leads to responses that reflect harmful stereotypes. ![image](https://github.com/user-attachments/assets/2f7e6b70-1c5b-40c3-91bd-a37ae19ec398) 
- [How AI reduces the world to stereotypes](https://restofworld.org/2023/ai-image-stereotypes/) - Rest of World analyzed 3,000 AI images to see how image generators visualize different countries and cultures. Using Midjourney, they chose five prompts, based on the generic concepts of “a person,” “a woman,” “a house,” “a street,” and “a plate of food.” They then adapted them for different countries: China, India, Indonesia, Mexico, and Nigeria. They also included the U.S. in the survey for comparison, given Midjourney (like most of the biggest generative AI companies) is based in the country. For each prompt and country combination (e.g., “an Indian person,” “a house in Mexico,” “a plate of Nigerian food”), they generated 100 images, resulting in a data set of 3,000 images. ![image](https://github.com/user-attachments/assets/e46fc69e-656a-4ad1-887f-4783e4840663)
- [Mitigating Artificial Intelligence Bias in Financial Systems: A Comparative Analysis of Debiasing Techniques](https://www.researchgate.net/profile/Oluwatofunmi-Oguntibeju/publication/387252070_Mitigating_Artificial_Intelligence_Bias_in_Financial_Systems_A_Comparative_Analysis_of_Debiasing_Techniques/links/6790a8cc98c4e967fa756d43/Mitigating-Artificial-Intelligence-Bias-in-Financial-Systems-A-Comparative-Analysis-of-Debiasing-Techniques.pdf) - This study aims to advance the development of more equitable AI systems in the BFSI sector by proposing the FAIR-BIAS Framework. This framework provides a structured approach to detecting, mitigating, and monitoring biases in AI models. Key recommendations include implementing equalized odds as a fairness metric to ensure balanced outcomes across demographic groups, applying adversarial debiasing techniques during model training to minimize discriminatory effects, and conducting regular data audits to ensure long-term fairness.
- [Let's Do a Thought Experiment: Using Counterfactuals to Improve Moral Reasoning](https://arxiv.org/abs/2306.14308) - In
this work, authors propose a new prompting framework, THOUGHT EXPERIMENTS, to teach language models to do better moral reasoning using counterfactuals. Experiment results show that their framework elicits counterfactual questions and answers from the model, which in turn helps improve the accuracy on Moral Scenarios task by 9-16% compared to other zero-shot baselines.
- [Diversity and Inclusion in AI for Recruitment: Lessons from Industry Workshop](https://arxiv.org/abs/2411.06066) - This study aims to investigate the practical application of D&I guidelines in AI-driven online job-seeking systems, specifically exploring how these principles can be operationalised to create more inclusive recruitment processes. They conducted a co-design workshop with a large multinational recruitment company focusing on two AI-driven recruitment use cases. User stories and personas were applied to evaluate the impacts of AI on diverse stakeholders. The results suggest developing tailored D&I guidelines and ongoing support to ensure the effective adoption of inclusive AI practices.
## Методы оценки предвзятости
- [Measuring Bias in AI Models: An Statistical Approach Introducing N-Sigma](https://arxiv.org/pdf/2304.13680) - Метод N-Sigma - статистический подход, используемый для разработки новых систем оценки рисков на основе анализа предвзятости.
- [Justice Or Prejudice? Quantifying Biases In LLM-as-a-Judge](https://arxiv.org/pdf/2410.02736v1) - Разработка системы CALM для автоматизированной количественной оценки предвзятости в LLM-as-a-Judge.
- [GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models](https://arxiv.org/pdf/2408.12494v1) - Комплексная система оценки и уменьшения гендерных предубеждений - GenderCARE. GenderPair - парный бенчмарк, предназначенный для всесторонней оценки гендерной предвзятости в LLMs.
- [AI Benchmarking Methods For Bias Assessment](https://store-restack.vercel.app/p/ai-benchmarking-answer-benchmarking-methods-ai-bias-cat-ai) - Описание бенчмарков и подходов для анализа и оценки предвзятости.

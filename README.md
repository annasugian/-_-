# **Проект "Предвзятость ИИ"**
## Термины
- **AI Fairness** - принцип, согласно которому ИИ-системы должны быть созданы и работать таким образом, чтобы они не были предвзяты по отношению к конкретным людям или группам людей.

   **Ключевые аспекты AI Fairness**
   * *Bias Mitigation* – Выявление и снижение предвзятости в обучающих данных и алгоритмах для предотвращения дискриминационных результатов.
   * *Equal Treatment* – Обеспечение того, чтобы ИИ не отдавал предпочтение или не ставил в невыгодное положение какую-либо конкретную группу по признаку расы, гендера, возраста и    других признаков.
   * *Transparency* – Обеспечение того, чтобы процессы принятия решений с помощью ИИ понятными и объяснимыми для пользователей.
   * *Accountability* – Возложение ответственности на разработчиков и организации за справедливость и этическую работу их систем ИИ.
   * *Inclusivity* – Использование разнообразных наборов данных для обеспечения того, чтобы ИИ справедливо служил широкому кругу людей.
   - **FAIRNESS AND BIAS IN ARTIFICIAL INTELLIGENCE: A BRIEF SURVEY OF SOURCES, IMPACTS, AND MITIGATION STRATEGIES** [Ferrara 2023] (https://arxiv.org/pdf/2304.07683)
  
- **AI Bias** - явление, при котором ИИ выдает предвзятые или несправедливые результаты из-за предвзятости, которая присутствовала в алгоритмах и данных, на которых она была обучена.

   **Типы AI Bias**
    * *Data Bias* – Когда данные обучения нерепрезентативны или искажены, что приводит к предвзятым результатам. Например: Система распознавания лиц, обученная в основном на людях со светлой кожей, может испытывать трудности с точным распознаванием лиц с более темной кожей.
    * *Algorithmic Bias* – Когда дизайн алгоритма несправедливо отдает предпочтения определенным результатам. Например: Алгоритмы приема на работу, обученные на основе данных о прошлых наймах, могут отдавать предпочтение кандидатам-мужчинам, если исторические данные отражают гендерную предвзятость при приеме на работу.
    * *Selection Bias* – Когда данные, собранные для обучения, неточно представляют популяцию. Например: ИИ в здравоохранении, обученный только на данных городских больниц, может оказаться неэффективным для сельского населения.
    * *Confirmation Bias* – огда ИИ усиливает существующие стереотипы из-за предвзятых моделей данных. Например: Поисковая система может отдавать приоритет показу изображений мужчин для запроса «генеральный директор» и изображений женщин для запроса «медсестра», что отражает общественные стереотипы.
    * *Automation Bias* – Когда пользователи чрезмерно доверяют решениям ИИ, даже если они неверны или предвзяты. Например: Судья полагается на инструмент оценки риска, который непропорционально высоко оценивает определенные расовые группы.
   - **IBM: What is AI Bias?** (https://www.ibm.com/think/topics/ai-bias)

- **AI Transparency** относится к возможности понять и объяснить как ИИ принимает решения, и являются ли ее решения справедливыми и этичными.

- **Responsible AI** относится к этической разработке и внедрению ИИ, который приоритетизирует справедливость и человеческое благополучие. Использование ИИ не должно вредить людям.
 
- **Human-centric AI** - это подход к искусственному интеллекту, который ставит во главу угла человеческое благополучие, ценности и сотрудничество. Он гарантирует, что системы ИИ будут разрабатываться для расширения человеческих возможностей, а не для их замены или контроля.
- **AI Ethics** относится к этическим принципам и гайдлайнам, которые регулируют разработку, развертывание и использование искусственного интеллекта. Она обеспечивает работу систем ИИ справедливым, прозрачным, подотчетным (accountable) и полезным для общества образом.
## Кто этим занимается
### Академические и научные центры, занимающиеся проблемой предвзятости ИИ:

**Stanford University Institute for Human-Centered Artificial Intelligence**:

[The Geographic Bias in Medical AI Tools](https://hai.stanford.edu/news/geographic-bias-medical-ai-tools) (сентябрь 2020)

[Rooting Out Anti-Muslim Bias in Popular Language Model GPT-3](https://hai.stanford.edu/news/rooting-out-anti-muslim-bias-popular-language-model-gpt-3) (июль 2021), [Large language models associate Muslims with violence](https://www.nature.com/articles/s42256-021-00359-2) (июнь 2021)

[Assessing Political Bias in Language Models](https://hai.stanford.edu/news/assessing-political-bias-language-models) (май 2023), [Whose Opinions Do Language Models Reflect?](https://arxiv.org/abs/2303.17548) (март 2023)

[Can AI Hold Consistent Values? Stanford Researchers Probe LLM Consistency and Bias](https://hai.stanford.edu/news/can-ai-hold-consistent-values-stanford-researchers-probe-llm-consistency-and-bias) (ноябрь 2024), [Are Large Language Models Consistent over Value-laden Questions?](https://arxiv.org/html/2407.02996v1) (июль 2024)


**Distributed AI Research Institute (DAIR)**:

[Racism is an ethical issue for healthcare artificial intelligence](https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(24)00321-5) (июнь 2024)

[A Human Rights-Based Approach to Responsible AI](https://arxiv.org/abs/2210.02667) (октябрь 2022)

[AI and Inequality in Hiring and Recruiting: A Field Scan](https://doi.org/10.34669/wi.cp/5.3) (2023)

[Much Ado About Gender: Current Practices and Future Recommendations for Appropriate Gender-Aware Information Access](https://dl.acm.org/doi/abs/10.1145/3576840.3578316) (март 2023)

[ChatGPT Perpetuates Gender Bias in Machine Translation and Ignores Non-Gendered Pronouns: Findings across Bengali and Five other Low-Resource Languages](https://arxiv.org/abs/2305.10510) (май 2023)

[Language (Technology) is Power: A Critical Survey of "Bias" in NLP](https://arxiv.org/abs/2005.14050) (май 2020)

### Государственные и межгосударственные инициативы:

В ООН вопросами этичного использования ИИ занимается [**Global AI Ethics and Governance Observatory при ЮНЕСКО**](https://www.unesco.org/ethics-ai/en?hub=32618). В ноябре 2021 выпустили свод рекомендаций по использованию ИИ, уделяя внимание проблеме bias
[Recommendation on the Ethics of Artificial Intelligence](https://unesdoc.unesco.org/ark:/48223/pf0000381137)

Европейский союз начал создавать экспертные группы по разработке рекомендаций в сфере ИИ в 2017 году. В 2020 году European Commision (высший орган исполнительной власти Европейского союза) утвердила [White Paper](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:52020DC0065) – документ, очерчивающий этические проблемы ИИ-сферы, по сути – свод рекомендаций по ответственному обращению с данными и добросовестному применению искусственного интеллекта.

Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence [(AI Act)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R1689#cpt_II) – первая в мире попытка законодательного регулирования рынка ИИ. В основном документ фокусируется на предотвращении катастроф (ядерное оружие, причинение вреда человеку, вмешательство в демократические процессы). Внимание отводится рискам, сопряжённым с работой с чувствительной информацией.

![image](https://github.com/user-attachments/assets/3499dd16-a7e4-4435-80de-fda2e1b64ea4)


Не регулирует использование minimal-risk или no-risk моделей – их применение на территории ЕС ограничивается рекомендациями.
AI Act вступил в силу 1 августа 2024, но требования, указанные в некоторых его пунктах, будут вступать в силу постепенно вплоть до 2027 года. За исполнением следит [European AI Office](https://digital-strategy.ec.europa.eu/en/policies/ai-office).
Cтатья в журнале [Frontiers](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2024.1393259/full) с анализом европейских законодательных мер в сфере ИИ и их эффективности.

В России – [**Национальный центр развития искусственного интеллекта при Правительстве Российской Федерации**](https://ai.gov.ru/) + НКО **Альянс в сфере искусственного интеллекта**, разработавший первый в России [Кодекс этики](https://ethics.a-ai.ru/) – подписание добровольное.
Принцип в России – саморегулирование (нет формальных требований принимать кодекс, но плюсик в карму)

![image](https://github.com/user-attachments/assets/25956988-98d1-44ff-9bda-c74dc676a243)


### Частные:

Toloka.ai способствуют интеграции ИИ в бизнес-процессы, занимаются обучением моделей, выявлением security-related рисков. Кроме этого red-teams тренируют модели выдерживать атаки, отвечать на некорректные запросы, распознавать опасные промты.

[Driving Responsible AI](https://toloka.ai/responsible-ai)
[AI Safety & Red Teaming](https://toloka.ai/ai-safety)

OpenAI: мы работаем над предотвращением bias, но как и насколько успешно – мы не скажем… (note: [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/pdf/2212.08073))
В публикациях на сайте OpenAI уделяет внимание предотвращению [катастроф](https://cdn.openai.com/openai-preparedness-framework-beta.pdf), документация по bias и регуляции поведения немногочисленна.

[Safety & Responsibility](https://openai.com/safety/)
[How should AI systems behave, and who should decide?](https://openai.com/index/how-should-ai-systems-behave/) от 2023 года
[Snapshot of ChatGPT model behavior guidelines](https://cdn.openai.com/snapshot-of-chatgpt-model-behavior-guidelines.pdf) от 2022 года

Google 😬
[Responsible AI and Human Centered Technology (RAI-HCT) team](https://research.google/teams/responsible-ai/)

[Google AI Ethics Team Crumbles As Leader Departs And Faces Restructuring](https://hyscaler.com/insights/google-ai-ethics-team-changes/) (январь 2024)


## Зачем это надо
### Вроде авторитетные ресерчи
- [The Mirror in the Machine: Generative AI, Bias, and the Quest for Fairness](https://medium.com/towards-data-science/the-mirror-in-the-machine-generative-ai-bias-and-the-quest-for-fairness-c39b03a6d48d) 
 [Medium.com, 2024] - Эксперимент по оценке влияния искусственного интеллекта на принятие решений о приеме на работу. Результаты для GPT-3.5 показали, что предпочтение отдавалось белому кандидату. В результате оценки было принято решение о найме белого кандидата в 100% случаев. Автор ввел в модель искусственного интеллекта 10 профилей, идентичных по квалификации и опыту, за исключением имен и этнической принадлежности кандидатов (белые и афроамериканцы). 2 этапа: Методы и результаты составления резюме и методы и результаты оценки резюме. ![image](https://github.com/user-attachments/assets/65b12744-ea52-4409-9dac-8c2c1aa16c71)

- [Evaluating fairness in ChatGPT](https://openai.com/index/evaluating-fairness-in-chatgpt/) [openai.com, 2024] - В исследовании OpenAI изучалось, как тонкие намеки на личность пользователя, такие как его имя, могут влиять на ответы в ChatGPT. Чтобы сфокусировать свое исследование на справедливости, они изучили, приводит ли использование имен к ответам, отражающим вредные стереотипы. Решений на смягчение предвзятости не было предложено. ![image](https://github.com/user-attachments/assets/285eb319-e570-486f-9d31-f1603c587b6f)

- [How AI reduces the world to stereotypes](https://restofworld.org/2023/ai-image-stereotypes/) [restofworld.com, 2023] - Rest of World проанализировали 3000 изображений с использованием искусственного интеллекта, чтобы увидеть, как генераторы изображений визуализируют разные страны и культуры. Используя Midjourney, они выбрали пять подсказок, основанных на общих понятиях “человек”, “женщина”, “дом”, “улица” и “тарелка с едой”. Затем они адаптировали их для разных стран: Китая, Индии, Индонезии, Мексики и Нигерии. Для сравнения они также включили в исследование США, учитывая, что Midjourney (как и большинство крупнейших компаний, занимающихся генеративным ИИ) базируется в этой стране. Для каждого запроса и сочетания стран (например, “индиец”, “дом в Мексике”, “тарелка нигерийской еды”) они сгенерировали 100 изображений. Результаты имели высокий уровень предвзятости. Авторы связывают это с специфическими данными для обучения модели. ![image](https://github.com/user-attachments/assets/e46fc69e-656a-4ad1-887f-4783e4840663)

- [Mitigating Artificial Intelligence Bias in Financial Systems: A Comparative Analysis of Debiasing Techniques](https://www.researchgate.net/profile/Oluwatofunmi-Oguntibeju/publication/387252070_Mitigating_Artificial_Intelligence_Bias_in_Financial_Systems_A_Comparative_Analysis_of_Debiasing_Techniques/links/6790a8cc98c4e967fa756d43/Mitigating-Artificial-Intelligence-Bias-in-Financial-Systems-A-Comparative-Analysis-of-Debiasing-Techniques.pdf) [Asian Journal of Research in Computer Science, 2025] - Это исследование направлено на продвижение разработки более справедливых систем искусственного интеллекта в банковском секторе, секторе финансовых услуг и страхования (BFSI), предлагая фреймворк FAIR-BIAS. Этот фреймворк обеспечивает структурированный подход к выявлению, смягчению и мониторингу искажений в моделях искусственного интеллекта. Основные рекомендации включают использование равных коэффициентов в качестве показателя справедливости для обеспечения сбалансированных результатов в разных демографических группах, применение методов состязательного анализа во время обучения модели, чтобы свести к минимуму дискриминационные последствия, и проведение регулярных проверок данных. ![image](https://github.com/user-attachments/assets/6ca5befc-d60b-4508-a086-82744c1fc484)

- [Let's Do a Thought Experiment: Using Counterfactuals to Improve Moral Reasoning](https://arxiv.org/abs/2306.14308) [arXiv, 2023] - В этой работе авторы предлагают новую систему подсказок - thought experiments - для обучения языковых моделей более эффективному моральному обоснованию с использованием контрфактуальных данных. Результаты экспериментов показывают, что их структура позволяет получать из модели вопросы и ответы, противоречащие фактам, что, в свою очередь, помогает повысить точность выполнения задачи "Моральные сценарии" на 9-16% по сравнению с другими базовыми показателями с нулевым результатом. ![image](https://github.com/user-attachments/assets/fa0a4ef1-e105-4c4c-8d4e-428abd24bfa8)

- [Diversity and Inclusion in AI for Recruitment: Lessons from Industry Workshop](https://arxiv.org/abs/2411.06066) [arXiv, 2024] - Это исследование направлено на изучение практического применения руководящих принципов D&I в системах онлайн-поиска работы, управляемых искусственным интеллектом, в частности, на изучение того, как эти принципы могут быть реализованы на практике для создания более инклюзивных процессов найма. Авторы провели семинар по совместному проектированию с крупной международной рекрутинговой компанией, в ходе которого были рассмотрены два варианта использования ИИ при подборе персонала. Истории пользователей и их личные данные были использованы для оценки влияния ИИ на различные заинтересованные стороны. Полученные результаты предполагают разработку индивидуальных руководящих принципов по разработке и внедрению ИИ и постоянную поддержку для обеспечения эффективного внедрения инклюзивных практик ИИ. ![image](https://github.com/user-attachments/assets/aae7adf6-424f-44b5-bd3e-1581424ec467)

 ### Веб-статьи, за авторитетность которых я не отвечаю
- [What measures does DeepSeek take to prevent AI bias?](https://zilliz.com/ai-faq/what-measures-does-deepseek-take-to-prevent-ai-bias) [ziliz]
- [AI Bias and Safety: Only Fresh & Relevant Examples](https://community.openai.com/t/ai-bias-and-safety-only-fresh-relevant-examples/720680) [OpenAi Developer Community, 2024]
- [Bias Detection and Correction Techniques for OpenAI Models](https://www.signitysolutions.com/tech-insights/openai-bias-detection-correction) [Signity Solutions, 2024]
- [An Analysis of Chinese LLM Censorship and Bias with Qwen 2 Instruct](https://huggingface.co/blog/leonardlin/chinese-llm-censorship-analysis) [Hugging Face, 2024]

## Методы оценки предвзятости
- [Measuring Bias in AI Models: An Statistical Approach Introducing N-Sigma](https://arxiv.org/pdf/2304.13680) - Метод N-Sigma - статистический подход, используемый для разработки новых систем оценки рисков на основе анализа предвзятости.
- [Justice Or Prejudice? Quantifying Biases In LLM-as-a-Judge](https://arxiv.org/pdf/2410.02736v1) - Разработка системы CALM для автоматизированной количественной оценки предвзятости в LLM-as-a-Judge.
- [GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models](https://arxiv.org/pdf/2408.12494v1) - Комплексная система оценки и уменьшения гендерных предубеждений - GenderCARE. GenderPair - парный бенчмарк, предназначенный для всесторонней оценки гендерной предвзятости в LLMs.
- [AI Benchmarking Methods For Bias Assessment](https://store-restack.vercel.app/p/ai-benchmarking-answer-benchmarking-methods-ai-bias-cat-ai) - Описание бенчмарков и подходов для анализа и оценки предвзятости.

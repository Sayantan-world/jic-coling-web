# Beyond Discrete Personas: Personality Modeling Through Journal Intensive Conversations

Large Language Models (LLMs) have significantly improved personalized conversational capabilities. However,
existing datasets like Persona Chat, Synthetic Persona Chat, and Blended Skill Talk rely on static,
predefined personas. This approach often results in dialogues that fail to capture human personalities'
fluid and evolving nature. To overcome these limitations, we introduce a novel dataset with around 400,000
dialogues and a framework for generating personalized conversations using long-form journal entries from
Reddit. Our approach clusters journal entries for each author and filters them by selecting the most
representative cluster, ensuring that the retained entries best reflect the author's personality. We further
refine the data by capturing the Big Five personality traits —openness, conscientiousness, extraversion,
agreeableness, and neuroticism —ensuring that dialogues authentically reflect an individual's personality.
Using Llama 3 70B, we generate high-quality, personality-rich dialogues grounded in these journal entries.
Fine-tuning models on this dataset leads to an 11% improvement in capturing personality traits on average,
outperforming existing approaches in generating more coherent and personality-driven dialogues.

### Cite
```bibtex
@misc{pal2024discretepersonaspersonalitymodeling,
        title={Beyond Discrete Personas: Personality Modeling Through Journal Intensive Conversations}, 
        author={Sayantan Pal and Souvik Das and Rohini K. Srihari},
        year={2024},
        eprint={2412.11250},
        archivePrefix={arXiv},
        primaryClass={cs.CL},
        url={https://arxiv.org/abs/2412.11250}, 
  }
```

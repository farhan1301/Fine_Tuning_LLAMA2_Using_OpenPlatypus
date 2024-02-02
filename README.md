This repo is a project to enhance the Open-Platypus dataset's utility for LLM applications, filtering out samples exceeding 2048 tokens to align with Llama 2's default max context size of 4096.
Implemented near-deduplication strategies using embeddings to ensure the dataset's uniqueness and relevance, improving model training efficiency and output quality.
Designed a chat template to standardize instructions and responses, facilitating the model's understanding and generation capabilities in a structured format.
Conducted Supervised Fine Tuning (SFT) on the model, tailoring it to specific dialogue generation tasks and significantly enhancing its performance on targeted scenarios.
Pioneered the fine-tuning of the model in 4-bit precision using QLoRA, a novel approach that drastically reduced VRAM usage without compromising model effectiveness.
Developed and executed a text generation pipeline, leveraging the refined model to produce high-quality outputs tailored to nuanced instructions.
Successfully reloaded the model in FP16 and seamlessly merged it with LoRA weights, optimizing the balance between computational efficiency and model performance.

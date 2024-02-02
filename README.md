This GitHub repository documents our project on fine-tuning Llama 2 for enhanced dialogue generation, employing a novel approach that integrates 4-bit precision fine-tuning with QLoRA to drastically reduce VRAM usage. 

We leveraged the Open-Platypus dataset, applying near-deduplication and filtering techniques to prepare high-quality data. This repo also includes the creation of a custom Platypus dataset, optimized through near-deduplication and token filtering, to precisely suit Llama 2’s learning requirements.

The project showcases the application of Supervised Fine-Tuning (SFT) and sophisticated model optimization strategies, including gradient accumulation and 8-bit optimized AdamW, within Google Colab's constraints. 

We also create a text generation pipeline that demonstrates the practical application and effectiveness of our fine-tuned model, serving as a blueprint for deploying interactive text generation applications efficiently.
# NLP Classification
A group project to implement text classification and compare prediction results to what an LLM's prediction results
2 models where used using simple transformers, which we tuned, and distillRoBERTA which was used as our control model.
We used 3 datasets: dair-emotions, go-emotions which we used as a training dataset. And we used an artifical database which was created by GPT 4.0 to test our models. 

Datasets: https://huggingface.co/datasets/dair-ai/emotion | https://huggingface.co/datasets/google-research-datasets/go_emotions

Tools: Simple Transformers [Roberta] | [Emotion English DistilRoBERTa-base models](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base) | PyTorch | Cuda | GPT 4.0(artifical tweet generation)

Google Colab Link: https://colab.research.google.com/drive/1AI5zezgG4ubZHeIOmylhSJHR10A0jUGi?usp=sharing

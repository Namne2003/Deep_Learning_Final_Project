# Deep_Learning_Final_Project
Our project for Deep Learning final report.

* Developing a Visual Question Answering (VQA) system that processes images and textual questions
to generate accurate answers. It uses Vision Transformer (ViT) for image feature extraction and
GPT-2 for answer generation, with BERT handling question encoding. A custom dataset class loads
image-question pairs, tokenizes questions, and preprocesses images, while a collation function manages
batching and padding. The system was tested on a GQA dataset, achieving BLEU scores of up to
0.65, demonstrating its effectiveness in providing contextually accurate answers to visual queries

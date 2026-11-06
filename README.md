# CLIP-Image-Retrieval-and-MRR

**Overview:** 
This program implements a text-to-image retrieval system using a pretrained CLIP model, specifically the Italian version of Hybrid CLIP. It downloads and processes the MS COCO dataset, which contains images paired with Italian captions, and converts both the images and captions into numerical embeddings (vectors) using the model's image and text encoders. The program normalizes these embeddings and calculates their cosine similarity to determine how closely each image matches a given text description.

The program also evaluates the model's image retrieval performance using Mean Reciprocal Rank (MRR) at 1, 5, and 10, as well as hit rate at 100. These metrics measure how effectively the model ranks the correct image among its retrieval results for each caption in the MS COCO dataset. Finally, the program demonstrates text-to-image retrieval by accepting Italian text descriptions and displaying the three most similar images. It repeats this retrieval process using a separate dataset of approximately 25,000 Unsplash images, demonstrating how the pretrained model can search through a larger collection of images based on natural-language descriptions.

**Skills:**
- Python
- Machine Learning Concepts
- Machine Learning Algorithms
- PyTorch
- JAX
- Flax
- NumPy
- Hugging Face Transformers
- Natural Language Processing
- Computer Vision
- Data Processing and Analysis

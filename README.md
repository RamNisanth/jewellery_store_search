# jewellery_store_search
# RingFIR Image Embeddings with Milvus

This project demonstrates how to:

- Load a large dataset of images from GitHub
- Generate image embeddings using the CLIP model (`clip-ViT-L-14`)
- Store embeddings in a Milvus vector database (Zilliz Cloud)
- Search for similar images using Milvus
- Use a local query image for similarity search

---

## **1. Install Dependencies**

```bash
!pip install pymilvus pillow sentence-transformers


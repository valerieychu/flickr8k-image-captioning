# Flickr 8k Image Captioning

#### STAT 362 (Advanced Machine Learning) Final Project

[Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k) is a real-world dataset of human-photographed images and human-written captions. 

This is a project that involves two data modalities — images and natural language. I will compare a classical deep-learning baseline against a modern pretrained transformer, and produce an interpretable, demonstrable output (a generated caption) that I can analyze both quantitatively (with standard captioning metrics) and qualitatively (with examples and visualizations). 

My goal in this project is to gain a deeper understanding of alt-text generation, a real-world application of image captioning that impacts accessibility and enables human communication. 

I want to pursue a career in Computer Vision/Machine Learning, and I believe this project is a step toward that. Transfer learning is the foundation for modern LLMs, and especially given this project's basis in both image and text, I think this project is extremely applicable. Additionally, coming from a journalism background, I've seen how important alt text is, and I want to contribute to making its automation more viable and accurate. 

For more about the project, check out the final report inside this GitHub repo. 

To watch me present on this project, click here: 

---

## Project Structure

```
flickr8k-image-captioning/
│
├── PROJECT_REPORT.ipynb                    # Project report
├── STAT362_Final_Project_Description.pdf   # Project requirements
├── 0_eda.ipynb                             # Exploratory data analysis
├── 1-retrieval_baseline.ipynb              # ResNet-50 + KNN
├── 2-cnn_lstm_encoder_decoder.ipynb        # ResNet-50 + LSTM
├── 3-git_transformer.ipynb                 # microsoft/git-base
├── archive/                                # The dataset
│   ├── Images/                             # 8,091 images (all JPEG and RGB)
│   ├── captions.txt                        # Five human-written captions per image
```

---


# ViT-LSTM/GRU Image Captioning Project

This project focuses on generating image captions using a combination of Vision Transformers (ViT) for image embeddings and LSTM/GRU models for sequence generation. The aim is to create descriptive captions for images using advanced deep learning techniques.

## Datasets

The project supports the following datasets:

* **Flickr_8K**
* **Flickr_30K**

Ensure you have downloaded and prepared these datasets in the appropriate format. Some images should be set aside for testing purposes.
Project Milestones
To complete the project by October 30, we have set the following milestones:

Data Preparation and Model Setup (Due: October 21)

Download and preprocess datasets
Set up ViT model for image embedding generation
Implement basic LSTM/GRU architecture


Model Training and Initial Evaluation (Due: October 25)

Train the LSTM/GRU model on prepared data
Implement BLEU score evaluation
Conduct initial performance assessment


Final Evaluation and Comparison (Due: October 28)

Implement semantic distance evaluation
Compare results with LLM-generated captions
Prepare final report and documentation



Team Responsibilities
The work is split among three team members as follows:

Team Member A: 

Responsibilities:






Team Member B: 

Responsibilities:




Team Member C: 
## Prerequisites

* Python 3.7+
* PyTorch
* Transformers
* TorchVision
* NumPy
* NLTK
* Matplotlib

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/vit-lstm-gru-image-captioning.git
   cd vit-lstm-gru-image-captioning
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare your dataset:**

2. **Generate Image Embeddings:**

3. **Train the Model:**

4. **Evaluate the Model:**
5. **Compare with LLM-generated Captions:**

## Evaluation Metrics

* **BLEU Score:** Measures n-gram precision between generated and reference captions.
* **Semantic Distance:** Evaluates the semantic similarity between actual and predicted titles.

## Results

Compare your results with those generated by an LLM to assess performance improvements or differences.



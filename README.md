Project Overview:-

The Ghost in the Machine is a research project focused on distinguishing human-written text from AI-generated text using statistical, linguistic, and deep learning techniques. The project builds a custom authorship-based dataset, analyzes writing characteristics, develops multiple AI detection models, explains their predictions, and evaluates their robustness against adversarially generated text.

Project Tasks
Task 0: The Library of Babel-
Created a dataset consisting of:
Human-written text from Project Gutenberg authors.
AI-generated text on the same topics using Gemini.
AI-generated text that mimics the writing style of the selected authors.

Task 1: The Fingerprint-
Performed linguistic and statistical analysis to identify differences between human and AI writing using features such as:
Type-Token Ratio (TTR)
Hapax Legomena
POS Distribution
Dependency Tree Depth
Punctuation Density
Readability (Flesch-Kincaid Grade Level)

Task 2: The Multi-Tiered Detective-
Built and evaluated three AI detection models:
Tier A: Random Forest/XGBoost using handcrafted statistical features.
Tier B: Feedforward Neural Network using pre-trained word embeddings.
Tier C: Transformer-based model (DistilBERT/RoBERTa with LoRA fine-tuning).
Task 3: The Smoking Gun
Interpreted model predictions using explainability techniques such as SHAP/Captum to identify linguistic patterns that indicate AI-generated text and performed error analysis on misclassified samples.

Task 4: The Turing Test-
Implemented a Genetic Algorithm to iteratively modify AI-generated text with the goal of bypassing the detector while preserving the original meaning. The robustness of the detector was also evaluated using manually edited human and AI-written text.

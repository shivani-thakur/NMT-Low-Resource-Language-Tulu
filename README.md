# Machine Translation for Extremely Low Resourced Languages

## Project Overview

This project focuses on developing machine translation (MT) models tailored for extremely low-resourced languages such as Lambadi, Bhili, Tulu, and Santali. These languages face significant challenges due to data scarcity and linguistic complexity, making traditional MT approaches ineffective. The project aims to enhance translation quality and accessibility for underrepresented languages.


## Contents

1. **Introduction**
   - Project objectives and relevance
   - Importance of MT for low resource languages

2. **Challenges and Limitations**
   - Specific challenges faced by Lambadi, Bhili, Tulu, and Santali
   - Environment setup and data preparation

3. **Environment Setup**
   - Importing libraries and essential dependencies
   - Tools installation (Fairseq, ilstokenizer, Moses decoder)
   - Data handling and preprocessing

4. **Data Preparation**
   - Tokenization and cleaning using ilstokenizer and Moses decoder
   - Subword tokenization with subword-nmt
   - Fairseq preprocessing for training and validation datasets

5. **Model Training and Evaluation**
   - Training a Transformer model using Fairseq
   - Model configuration, hyperparameters, and optimization
   - Evaluation using BLEU score metric
   - Model performance analysis and parameter sensitivity

6. **Experiments**
   - Initial experiments with Kannada to Tulu and Tulu to Kannada translations
   - Parameter tuning and results
   - Additional experiments translating Kannada to English and English to Tulu

7. **Outcome and Summary**
   - Achievements and key learnings
   - Future work and enhancements
   - Collaboration and exploring multilingual NMT

## Files and Directories

- **Code**: Contains scripts with environment setup, data preparation, model training, and evaluation.
- **Data**: Includes training and validation datasets (English, Tulu, Kannada).
- **Figures**: Visualizations (sentence length distribution, unique token distribution, etc.).

## Conclusion

This `README.md` provides an overview of the project, detailing its objectives, challenges, methodologies, and outcomes. The project underscores the importance of MT in preserving cultural heritage and promoting national integration through better accessibility to information in low-resourced languages.

For more detailed information, refer to the corresponding sections and files within this repository.

# Faza’a – Najdi Dialect Translation System

**Faza’a** is an AI-powered system designed to help visitors in the Najd region understand the local dialect and communicate more easily with the local community. The project was developed during the **Arabthon** hackathon.

## The Idea
To bridge the linguistic and cultural gap that tourists or non-Najdi speakers may face. Local dialects contain unique expressions that are difficult to understand using traditional translation tools. Therefore, we built a specialized translation model that converts Najdi Arabic phrases into English while considering context and meaning, not just literal translation.

## The Goal
To provide a more natural and authentic communication experience that reflects the local culture of the Najd region, and to support cultural tourism while highlighting local identity using Natural Language Processing (NLP) techniques.

## Technical Solution
- Base model: **Helsinki-NLP/opus-mt-ar-en**
- Data cleaning and processing using **Pandas**
- Fine-tuned the model on a dataset of Najdi phrases with English translations
- Implemented using **PyTorch** and **HuggingFace Transformers** in **Google Colab**

## Example

| Najdi Phrase | English Translation |
|--------------|---------------------|
| يعطيك العافية | May God give you health |
| وش علومك | How are you? |
| خل عنك | Forget about it |
| ربي يتمم | May God complete it with goodness |

## Future Plans
- Add translation to Modern Standard Arabic (MSA)
- Add cultural notes explaining the phrases
- Suggest appropriate replies for conversations
- Identify correct social contexts for each expression
- Expand the idea to other dialects within Saudi Arabia


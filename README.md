
# OSE Final Project

## Fine tuning Bert Models for Mutilabel text Classification

# Important details about the repository


- I worked on the gpu of google colab. 
-  There might be some problem with the reproducibility when run on another gpu. 
- First did all imports of the libraries then did pip freeze to check the environment versions and wrote the versions in envrironment file. (May be this helps for reproducibility other than set seed)



### Some notes 
- Dataset includes some reasons of failure of clinical trials. (Divided into 17 classes) taken from Hugging Face. Detailed dataset can be found [here](https://huggingface.co/datasets/opentargets/clinical_trial_reason_to_stop/viewer/default/train?row=8)
- Comparison done on using emsemble methods after feature extraction with transfer learning models from huggingface . 

### Model Selection of hugging face transformer models for Multilabel text classification - 
All of these can be found under the head of Sequence Classification
- XLNET - you can find in [XLNET for multilabel](https://huggingface.co/docs/transformers/model_doc/xlnet#transformers.XLNetForSequenceClassification)
- ALBERT - [ALbert for multilabel](https://huggingface.co/docs/transformers/model_doc/albert#transformers.AlbertForSequenceClassification)
- BERT - [Bert for multilabel](https://huggingface.co/bert-base-uncased)
- ROBERTA - [Roberta for multilabel](https://huggingface.co/cardiffnlp/twitter-roberta-base-emotion-multilabel-latest)
- DISTILBERT- [Distilbert for multilabel](https://huggingface.co/docs/transformers/model_doc/distilbert)

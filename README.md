# ArabBert_Tokenizer

- ArabBERT_Tokenizer: [![Open In Colab][COLAB]](https://drive.google.com/file/d/1xXFYmHlsEtd-uosuoiZlkdKSJWqrawZn/view?usp=share_link)

## Goal:-
- Writing a sample tokenizer Code and testing it, Using a provided sample code on GitHub and Google Colab.

Steps:-
1. Installing `arabert` and `transformers` modules.
1. Using `from transformers import AutoTokenizer, AutoModel` to import the tokenizer and the model builder.
1. Using `from arabert.preprocess import ArabertPreprocessor` to import the text preprocessing tool.
1. Calling the Model `model_name = "aubmindlab/bert-base-arabertv2"`.
1. Testing the tokenizer and the preprocessor:-
  - Tested with Different forms of Arabic text:
    - <div dir="rtl"> العربية الفصحى </div>
    - <div dir="rtl"> الْعَرَبِيَّةِ الْفُصْحَى </div> Using Shakkala.
    - Egyptian Arabic text.


[COLAB]: https://colab.research.google.com/assets/colab-badge.svg

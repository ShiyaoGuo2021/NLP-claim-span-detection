# NLP-claim-span-detection


We fine-tuned encoder and encoder-decoder large language models to automatically extract spans of text representing claims in Twitter posts.

The models we tested include the following:

Encoder models: DaBERTa, BERT, DistilBERT, BERT+LSTM
Encoder-Decoder Models: T5, BART
BERT, DaBERTa, and DistilBERT achieved state-of-the-art performance for this task and this dataset.

The encoder-decoder models performed reasonably well, but they were inferior to the encoder models due to the suboptimal text-to-text restructuring of the claim span detection task.

See report.pdf for a detailed discussion of the task, methods, results, and Analysis.

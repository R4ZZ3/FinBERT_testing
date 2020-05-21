# FinBERT_testing
Testing FinBERT model on various datasets


Results on Eduskunta-vkk test.csv below:
(train.csv, dev.csv and test.csvDownloaded with ./scripts/get_data.sh from https://github.com/aajanki/fi-sentence-embeddings-eval)

To preproduce:
Setup conda env from environment file (Windows packages included, For Linux you might need to remove some Win specifig packages)

Download FinBERT model files from (http://dl.turkunlp.org/finbert/bert-base-finnish-cased-v1.zip) 
to {Main-drive}:/{User}/ktrain_data/multi_cased_L-12_H-768_A-12

For me the path is: C:\Users\Admin\ktrain_data\multi_cased_L-12_H-768_A-12
Ktrain-library (Used in notebook)  will use this folder to look up model files

![alt text](https://github.com/R4ZZ3/FinBERT_testing/blob/master/Eduskunta_vkk_FinBert_test_results.JPG)

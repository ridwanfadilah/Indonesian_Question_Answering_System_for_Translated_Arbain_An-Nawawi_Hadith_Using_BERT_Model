# Indonesian_Question_Answering_System_for_Translated_Arbain_An-Nawawi_Hadith_Using_BERT_Model
An Indobert-QA model fine-tuned for trial data on Indonesian translation questions for the Arbain Nawawi Hadith using the BERT model.

The Indobert-QA model will be fine-tuned on Arba'in An-Nawawi Hadith translation data. The process will be carried out on two datasets, one based on publisher and one based on hadith context length.
The publisher dataset consists of four publishers:
* Al-Wafi
* Insan Kamil
* Hikmah
* Islamhouse

And the hadith context length dataset consists of three categories:
* Short Hadith (30-85 words)
* Medium Hadith (91-147 words)
* Long Hadith (154-312 words)

The dataset will be trained using the following hyperparameters:
* Learning Rate : 1e-5, 2e-5, 3e-5, 4e-5, 5e-5
* Batch : 8
* Epoch : 5

Each dataset that has been fine-tuned will produce a Bert model that can be used for QAS.

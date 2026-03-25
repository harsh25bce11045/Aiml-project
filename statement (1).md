Problem Statement: 
Today, users are constantly faced with being inundated by large amounts of unsolicited and often harmful email messages, commonly known as spam. The amount of spam that users receive is a major drain on productivity, consumes computing resources, and also presents the risk of being used to carry out phishing or distribution of malware. Although there are existing email providers that provide filtering services for users, these filtering services rely heavily on a predefined set of filters/rules, which is not adaptive and lead to false positive (acceptable emails often get marked as spam) and false negative (sophisticated spam passes through the filters) rates that will continue to grow over time.

The fundamental issue is a need for an adaptive, intelligent, data-driven filtering mechanism that can accommodate any changes to the way that spam is being perpetrated.

Project Scope:

1. A full, verifiable ML pipeline will be implemented to process text data, including Data Loading, Text Preprocessing (cleaning and tokenization), Feature Extraction, Model Training, and Model Evaluation.

2. The classification technique that will be used for this project is the Multinomial Naive Bayes (MNB) algorithm, which has previously demonstrated success for text data classification in the literature.

3. The application of the TF-IDF vectorization technique will transform raw textual documents into numerical feature vectors based on their term frequency – inverse document frequency (TF-IDF) value; therefore, showing how this widely used technique can be applied for text-based feature extraction using a number of different methods.

4. The data that will be utilized for training and testing purposes, to evaluate the performance of the proposed predictive model, will originate from the static dataset; specifically, the e-mail spam dataset that is being used for the purpose of this assignment.

5. The evaluation of the performance can be performed by performing a complete analysis of the entire machine learning pipeline that was used for constructing the predictive model.
# LING-583 Final Project
# Intent Recognition: Customer Service Domain

INTRO:
<br>
Virtual assistants have become integral to the way that customers interact with their smart devices, providing human-like responses to commands, information, and often paired with other connected electronics in the home. In 2020, an estimated 4.2 billion digital voice assistants were being used around the world and is expected to reach 8.4 billion units by 2024 (Statista, 2022). One significant application of a text mining system is intent recognition of spoken customer utterances that can be used in virtual assistant technology to handle basic customer service tasks.


DATA:
<br>
The dataset, collected from Kaggle’s “Training Dataset for chatbot/Virtual Assistants,” contains 20,000 example utterances and their corresponding intents from the Customer Support domain. It consists of 11 categories (“ACCOUNT”, “CANCELLATION_FEE”, “PAYMENT”, etc.) that are further split into 27 intent groupings (“cancelorder”, “complaint”, “contactcustomerservice” etc.) which represent the actionable steps to be conducted by the system to help customers with their orders.

METHODS:
<br>
The goal of this project is to create a model that can accurately predict the categorization of utterances spoken by customers. Since there are more than two possible class outcomes (i.e. the intents), we will be using multinomial classification. We’ll begin by conducting text cleaning/preprocessing where we will remove unnecessary characters, and then split the data into 80% training set and 20% test set. Next, we’ll apply classifier techniques to include Naive Bayes and Multiclass Support Vector Machine. Model performance will be evaluated using the accuracy scores (f1-scores) from our test set. Finally, we’ll discuss actionable intelligence that virtual assistant companies should consider based on our findings.


For the full report, please contact Joseline at @jayala21452sdsu.edu

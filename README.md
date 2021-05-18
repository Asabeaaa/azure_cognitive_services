# azure_cognitive_services
Making api calls to Azure Cognitive Services to gain insight from text data mixed with both english and swahili.

Library needed to be installed: 
pip install --upgrade azure-ai-textanalytics

Libraries needed to be imported:
from azure.ai.textanalytics import TextAnalyticsClient
from azure.core.credentials import AzureKeyCredential

Azure cognitive service used was the text translator which supports Swahili translation. 
Actions performed on data :
1. Sentiment Analysis- helps check sentiment behind a given text, whether positive,negative or neutral.
2.Language Detection- helps detect the language the text data has been written in.
3.Key phrase extraction- helps check the important phrases in a piece of text and returns it.

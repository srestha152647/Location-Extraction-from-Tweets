# Location-Extraction-from-Tweets

At the onset of a disaster, Twitter messages with critical information such as medical assistance, food or shelter needs, reports of trapped people, and severely damaged infrastructure, are not useful for response authorities if they are not geotagged. While tweets with exact GPS coordinates are usually scarce, often they contain toponyms (i.e., place/area/street names), which can be helpful for authorities to estimate the location. However, due to the high volume of Twitter messages, manual extraction of location cues cannot scale. An automated process is required for the recognition and geo localization of location mentions in tweets.

This NLP model trained on the IDRISI-R dataset, the largest-scale publicly-available Twitter Location Mention Prediction (LMP) dataset, uses the Flair library built on PyTorch and its Name-Entity Recognition(NER) utility for training with BiLSTM and GloVe embedding.

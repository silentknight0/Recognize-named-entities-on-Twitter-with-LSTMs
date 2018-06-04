# Recognize-named-entities-on-Twitter-with-LSTMs
NER is a common task in natural language processing systems. It serves for extraction such entities from the text as persons, organizations, locations, etc. In this task I experimented to recognize named entities from Twitter.

For example, we want to extract persons' and organizations' names from the text. Than for the input text:

Ian Goodfellow works for Google Brain

a NER model needs to provide the following sequence of tags:

B-PER I-PER    O     O   B-ORG  I-ORG

Where B- and I- prefixes stand for the beginning and inside of the entity, while O stands for out of tag or no tag. Markup with the prefix scheme is called BIO markup. This markup is introduced for distinguishing of consequent entities with similar types.

A solution of the task will be based on neural networks, particularly, on Bi-Directional Long Short-Term Memory Networks (Bi-LSTMs).
# Libraries
* tensorflow
* numpy

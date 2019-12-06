# Ita-Lip

In this work we accomplish the task of lipreading 100 words selected from the 1000 most common
words in the Italian language through deep learning. We create our own dataset by recording a person
pronouncing words facing a camera. The chosen set of words consists of nouns, adjectives and verbs
and can possibly be extended to the whole dictionary.
We use an adapted version of GCNet [3] for our purpose, which we explain in detail in section 5. The
model we present should be taken as a follow up, simplified version of LipNet [2], Deep Speech 2 [1]
and Lip Reading Sentences in the Wild [5], where more complex networks are capable of recognizing
entire sentences coming from different speakers, possibly with different orientations and in various
settings.

This repository provides the evaluation datasets used in our paper "Comparison of the Intimacy Process between Real and Acting-based Long-term Text Chats" (LREC-COLING2024).

This repository provides two datasets.

## Long-term Asynchrnous Chat (Section 3.1.1)
We are releasing three weeks' worth of chat logs for four pairs.

### Summary
|label|value|
|--|--|
|Male pair id| 1, 13 |
|Female pair id|  42, 52|
|Num of utterance| 815|

### lac-public-dialogue.tsv

|key|value|
|---|---|
|room| pair id (unique value for each pair)|
|dayid| date number on which the utterance was posted|
|speaker|speaker id (unique value for each speaker)|
|utterance|message|

## Japanese version of Multi-Session Chat (Section 3.1.2)
We release part of our Japanese Multi-Session Chat. 
We excluded some pairs for several reasons.

### Summary
|label|value|
|--|--|
|Num of 5 session pair| 72|
|Num of 3 session pair| 125|
|Num of utterance| 8820|


### jmsc-public-dialogue.tsv
|key|value|
|---|---|
|pair_id| persona id|
|sid| session id|
|tid| turn id|
|speaker| speaker id|
|utt| message|
|sum| persona summary|
|interval_sum_label|total interval|
|interval_last_label|interval from last session|

### jmsc-public-persona.tsv
|key|value|
|---|---|
|PersonaID| persona id|
|A| persona for speaker A|
|B| persona for speaker B|

For further details and usage instructions regarding the datasets, please refer to our paper.
# Guinnes
A Transformer model that generates text in a similar writing style as the textual data that was fed into it.

## Context
This model was developed and trained by The Hyperomas as their attempt in ThinkAi Hackathon which was organized by 1337 and UM6P in May 2023, and it falls as a solution under the NLP Challenge category.

## What is it doing?
Guinnes is a decoder-only transformer (a full extention is coming fairly soon - as of 05/16/2023) that generates text that has a similar writing style to whatever textual data that the model has trained on.

## How it was made?
Guinnes is the first transformer model we've ever created; thus, we built it by following the standard paper on transformer models [Attention Is All You Need](https://arxiv.org/abs/1706.03762) and some Youtube Videos.
As for the technical aspects of the model, it was all built using PyTorch.

## Why building a model from scratch in a competition?
Yes we agree, building a model as complicated as a transformer from scratch in a competition can be risky, especially if you didn't know of how it can be implemented, because then you will have
to dig deep into the paper and understand its inner workings. However, there were some reasons for our strategy:
* We wanted to use different components in the transformer model, such as modifying The FFNNs with The [Holistic Robust NNs](https://arxiv.org/abs/2207.09560) as an experimentation of performance (Not yet implemented - as of 05/16/2023).
* Experimenting with different optimizers such as SGD, Adam, and AdamW.
* We love to challenge ourselves.

Our strategy didn't give us the prize, but we learned more than what a prize could buy.

## THE HYPEROMAS
* ADNANE TOUIYATE
* MOHAMED AMINE LAYACHI    
* OMAIMA BINAN 

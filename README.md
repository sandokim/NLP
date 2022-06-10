# NLP (Natural Language Processing)

Transformer - Attention is all you need

### BERT는 Transformer의 Encoder들을 이은 것

BERT는 language를 이해하도록 사전 학습시킨 후 specific한 task를 배우도록 만든다.

<img src="https://github.com/sandokim/NLP/blob/main/images/BERT.PNG" width="60%">

### GPT는 Transformer의 Decoder들을 이은 것

<img src="https://github.com/sandokim/NLP/blob/main/images/BERT_GPT.PNG" width="60%">

#### 벡터의 dot product 내적을 통해 두 단어의 cosine similarity를 구할 수 있다.

덧셈뺄셈을 통해서 임베딩 공간을 확인을 하는 것을 analogy test라고 한다. 

* Semantic analogy 의미 관계 파악
* Syntactic analogy 문법적인 구조도 임베딩이 됐는지 파악

##### Word embedding VS GPT -> Word embedding은 새로운 단어를 파악하지 못한다. GPT는 단어내의 관계를 통해 파악한다.

<img src="https://github.com/sandokim/NLP/blob/main/images/word_embedding_VS_GPT.PNG" width="60%">

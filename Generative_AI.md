# **Generative AI**

It is an AI that can create new content. Models that can create any type of data such as text, images, audio and video etc



##### **How does gen ai works?**

By identifying patterns from the training data it can create new content

Ex: Training data -> Identifies patterns -> Receive any request -> generates new content

It creates a new content based on the patterns identified but doesn't copy 



***Lets compare this with machine learning***

Machine learning has two main concepts Training and Inference

In training, Model is trained with dataset that consists of inputs(features) and labels(correct answer) then we get a trained model.

Inference, is the concept of using the capability of trained model for prediction tasks.



##### **How Gen AI is different from other AI approaches?**

In ML, model is learning from data and labels, it identifies the relationship b/w data and labels, and makes a prediction

In Gen AI, model is trained only on unstructured data, it identifies patterns within the unstructured data and generates new content



##### **Types of Gen AI models:**

1)Text based: that can generate text, code etc. Learns from large collection of data and identifies relationship

2)Multi modal: can generate multiple modals like text, image, videos and audios. learns from large types of data, is capable of processing and generating multiple modalities



##### **Introduction to LLM**



**What is LLM?**

LLM(Large language model) is a probabilistic model of text. It identifies the next possible word in a sentence by observing the previous words based on assigning probability to each word in the vocabulary. It picks the token/word with highest probability



***Examples:***

Can be used to known something, used to write essays or poems, and also to translate b/w languages



LLM is based on the *Transformers(Deep learning architecture)*



**Model size and Parameters**

***Parameters:*** Adjustable weights in the model's neural n/w. Model with large no of parameters has more capacity but sometimes it also causes overfitting problem

***Model size:*** Memory required to store the model's parameter



Understanding a sentence structure is easy for humans but it would be difficult for machines 

So RNNs come into picture which has the capability of handling sequential data, maintains a hidden state, and has a feedback loop through which hidden states are transferred as input to next state. But this is difficult for large sequences.



RNNs has the problem of Vanishing gradient since it takes only one input at a time then it becomes to understand the relationship b/w words/tokens that are far away



##### **How Transformer is different from RNN**

Transformer understands the relationship between each word in a sentence unlike RNN which process the input sequentially one by one

As transformers understand the relationship between every words in a sentence we may have a doubt that how can it understand the correct reference of the word, it is because of its *'Self Attention mechanism*: understands context of the text too'



##### **Encoder Decoder**

**Encoder:** takes the input and encodes it into embeddings that captures meaning of the input text

**Decoder:** uses this embeddings to generate the output text



###### **Tokens**

Transformers understand tokens not words

You may think that a token is a word, but its not just a word it may be a part of word, a word or a punctuation mark

so in *simple text*, one token per word

&nbsp;  in *complex text*, 2-3 tokens per word



##### **Embeddings**

Embeddings are *numerical representation* of piece of a word. The piece of text may be word, phrase, sentence or paragraphs. So these make machines easy to understand the relationship between each piece of text.



*For example* if there are 4 tokens then 5 embeddings will be generated where 4 are for tokens and 1 for the entire text/sentence



So these embeddings are achieved by using the encoder 



##### **Retrieval Augment Generation(RAG)**

1)Vector database: it stores all the knowledge base or corpus in the form if embeddings

2)User queries for any content which is matched with any of the document in the vector database by converting into embeddings(machine understands only embeddings)

3)Private documents are returned and are given as input to LLM

4)LLM uses the content and general knowledge to provide answer for user queries



Everything here happens by embeddings(numerical representation of the text) because machines can only understand by this



##### **Decoder:** 

takes sequence of tokens and generates only a single token at a time. It can have self references (arrows) because it generates only one token at a time 



##### **Transformer model types:**

***1)Encoder:*** to convert input into sequence of embeddings(search related tasks)

***2)Decoder:*** To convert sequence of tokens into a single token( Text generation)

***3)Encoder-Decoder:*** Entire process of converting input into embeddings and then output(Machine Translation)


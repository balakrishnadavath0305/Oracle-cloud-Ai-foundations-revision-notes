##### **Prompt:**

the input provided to the model



##### **Prompt Engineering:** The process of refining the input/prompt to get a particular response



Since LLM is trained on a large set of Internet text, it becomes difficult to get exactly what a user needs, so in that finetuning the model for a particular purpose is essential



**RLHF(Reinforcement learning from Human Feedback)** is also used to finetune LLMs to perform as per the user feedback because these LLMs are completion LLMs.

##### 

##### **Incontext learning:**

Prompting an LLM with instruction or demonstration of task it is meant to complete

##### 

##### **K-shot prompting:**

Providing k no of examples of an intended task in the prompt 



##### **Chain of Thought prompting:**

Breaking a complex task into steps and providing prompt with an example. The example answer must include the reasoning steps and calculation logic.



**Hallucination:** Confidently providing information which is not factual. To overcome Hallucination RAG(Retrieval Augmented Systems) is used





##### **Customizing LLM with your own data**

1)Prompt engineering

2)Retrieval Augmented Generation

3)Fine tuning

###### 

###### **RAG implementation:**

It involves two major steps retrieval of information from corpus/ vector databases then using that information for generating responses. Fine tuning is not required for RAG

###### 

###### **Fine Tuning:**

Taking a pretrained model and training again with new data to get a custom model and then using this custom model to generate new responses for any input data is Inference 


# GPT, ChatGPT, InstructGPT
![image](https://user-images.githubusercontent.com/129742046/236900096-c38791b3-498e-4abb-85b4-277924d4a3bd.png)

![image](https://user-images.githubusercontent.com/129742046/236911422-d85a9d3e-ea46-4cf7-9fa1-dac4c0e3b4d3.png)




### 1. ChatGPT


![image](https://user-images.githubusercontent.com/129742046/236999448-5a359429-6276-4396-91c1-27334d1e1e6e.png)

- ChatGPT is a sibling model to InstructGPT, which is trained to follow an instruction in a prompt and provide a detailed response
- ChatGPT finetuned on GPT-3.5 and InstructGPT fine-tuned on GPT-3
- trained using Supervised Learning + RLHF 
- **Dataset :** The primary source of data for ChatGPT is the WebText dataset, which consists of approximately 8 million web pages collected from the internet. This dataset is publicly available and was created by OpenAI specifically for training language models.
    - A massive corpus of text data, around 570GB of data sourced from books, wikipedia, research articles, webtexts, websites and other forms of content and writing on the net - Approximately 300 billion words were fed into the system.
    - Another advantage of using the WebText dataset is that it is constantly updated with new data. As new web pages are added to the internet, they are included in the dataset, which helps to ensure that the model is trained on the most recent and relevant language data.
- The model works on probability as a result of which it is able to predict the next word/prompt in a sentence.
- While training, if the model gets output wrong, the correct answer is fed back into the model thereby training it to the right responses and also helping it build on its knowledge bank.
- It then goes through the next stage where it offers diverse responses and a human annotator ranks it from the most appropriate to wrong—training the system to compare.

##### Limitations
- ChatGPT sometimes writes plausible-sounding but incorrect or nonsensical answers.
- ChatGPT is sensitive to tweaks to the input phrasing or attempting the same prompt multiple times.
- It will sometimes respond to harmful instructions or exhibit biased behavior - Moderation API is used to warn or block certain types of unsafe content, but expected to have some false negatives and positives for now

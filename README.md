# INT426 ANSWERS

## Link of Courses For Week 1:- https://www.coursera.org/programs/int426-generative-ai-8n6df/learn/introduction-to-generative-ai<br><br>https://coursera.org/programs/int426-generative-ai-8n6df/learn/generative-ai-for-everyone

## Week 1 Solution

## Note:-  
```bash 
If anyone facing any doubts in these answers then he/she can refer to the images uploaded in the week-wise folder
```

# Introduction to Generative AI: Quiz

### Q.1 What is Generative AI?
```Answer:- Generative AI is a type of artificial intelligence (AI) that can create new content, such as text, images, audio, and video. It does this by learning from existing data and then using that knowledge to generate new and unique outputs.```

### Q.2 What is an example of both a generative AI model and a discriminative AI model?
```Answer:- A generative AI model could be trained on a dataset of images of cats and then used to generate new images of cats. A discriminative AI model could be trained on a dataset of images of cats and dogs and then used to classify new images as either cats or dogs.```

### Q.3 What are foundation models in Generative AI?
```Answer:- A foundation model is a large AI model pretrained on a vast quantity of data that was "designed to be adapted” (or fine-tuned) to a wide range of downstream tasks, such as sentiment analysis, image captioning, and object recognition.```

### Q.4 Hallucinations are words or phrases that are generated by the model that are often nonsensical or grammatically incorrect. What are some factors that can cause hallucinations? Select three options.
```Answer:- The model is trained on noisy or dirty data.```<br>```The model is not given enough context.```<br>```The model is not trained on enough data```

### Q.5 What is a prompt?
```Answer A prompt is a short piece of text that is given to the large language model as input, and it can be used to control the output of the model in many ways. ```

# Generative AI for Everyone

## Week 1: What is Generative AI? (Graded Quiz)

### Q.1 Which of these is the best definition of “Generative AI”?
```Answer:- AI that can produce high quality content, such as text, images, and audio.```

### Q.2 Which of these is the most accurate description of an LLM?
```Answer:- It generates text by repeatedly predicting the next word.```

### Q.3 True or False. Because an LLM has learned from web pages on the internet, its answers are always more trustworthy than what you will find on the internet. 
```Answer:- False```

### Q.4 Why do we call AI a general purpose technology?
```Answer:- Because it is useful for many different tasks.```

### Q.5 You hear of a company using an LLM to automatically route emails to the right department. Which of these use cases is it most likely to be?
```Answer:- The company has a software-based application that uses an LLM to automatically route emails.```

## Week 1: Generative AI applications

### Q.1 A friend writes the following prompt to a web-based LLM: “Write a description of our new dog food product.” 
```Answer:- All of the above.```

### Q.2 Which of the following are tasks that LLMs can do? (Check all that apply)
```Answer:- Summarize articles```<br>```Proofread text that you’re writing.```<br>```Translate text between languages.```

### Q.3 Someone prompts an LLM as follows: “Please summarize each of this morning’s top 10 news stories in 100 words per story, in a manner suitable for a newsletter.” What is the main reason this is unlikely to work?
```Answer:- Because of the knowledge cutoff, the LLM will not have access to the latest news.```

### Q.4 You’re preparing a presentation about technology, and ask an LLM to help you find an inspirational quote. It comes up with this:<br><br>**And that’s what a computer is to me. What a computer is to me is it’s the most remarkable tool that we’ve ever come up with, and it’s the equivalent of a bicycle for our minds. -Steve Jobs**<br><br>How should you proceed?
```Answer:- Because LLMs hallucinate, double-check this quote by searching other sources (such as the web) to verify if Steve Jobs really said this.```

### Q.5 You want an LLM to help check your writing for grammar and style. Which of these is the better approach for creating a prompt?
```Answer:- Don’t overthink the initial prompt -- quickly give it some context, then prompt the LLM to get its response, see what you get and iteratively refine your prompt from there.```

# Generative AI for Everyone

## Week 2: Software Applications

### Q.1 In the videos, we described using either supervised learning or a prompt-based development process to build a restaurant review sentiment classifier. Which of the following statements about prompt-based development is correct?
```Answer:- Prompt-based development is generally much faster than supervised learning.```

### Q.2 What is a token in the context of a large language model (LLM)?
```Answer:- A word or part of a word in either the input prompt or LLM output.```

### Q.3 What are the major steps of the lifecycle of a Generative AI project? 
```Answer:- Scope project → Build/improve system → Internal evaluation → Deploy and monitor ```

### Q.4 You are building a customer service chatbot. Why is it important to monitor the performance of the system after it is deployed?
```Answer:- In case customers say something that causes the chatbot to respond in an unexpected way, monitoring lets you discover problems and fix them.```

### Q.5 You are working on using an LLM to summarize research reports. Suppose an average report contains roughly 6,000 words. Approximately how many tokens would it take an LLM to process 6,000 input words? (Assume 1 token = 3/4 words, or equivalently, 1 word \approx 1.333 tokens).
```Answer:- 8,000 tokens (about 6000 * 1.333) ```


## Week 2: Advanced technologies: Beyond prompting

### Q.1 True or False. Because of the knowledge cut-off, an LLM cannot answer questions about today’s news. But with RAG to supply it articles from the news, it would be able to.
```Answer:- True```

### Q.2 You want to build an application to answer questions based on information found in your emails. Which of the following is the most appropriate technique?
```Answer:- RAG, where the LLM is provided additional context based on retrieving emails relevant to your question.```

### Q.3 What does the idea of using an LLM as a reasoning engine refer to?
```Answer:- This refers to the idea of using an LLM not as a source of information, but to process information (wherein we provide it the context it needs, through techniques like RAG).```

### Q.4 True or False. By making trusted sources of information available to an LLM via RAG, we can reduce the risk of hallucination.
```Answer:- True, because RAG allows the LLM to reason through accurate information retrieved from a trusted source to arrive at the correct answer.```

### Q.5 An ecommerce company is building a software application to route emails to the right department (Apparel, Electronics, Home Appliances, etc.) It wants to do so with a small, 1 billion parameter model, and needs high accuracy. Which of these is an appropriate technique?
```Answer:- Fine-tune a 1 billion parameter model on around 1,000 examples of emails and the appropriate department.```

# Generative AI for Everyone

## Week 3: Generative AI and business

### Q.1 Which of these job roles are unlikely to find any use for web UI LLMs?
```Answer:- None of the above```

### Q.2 What is the relation between AI, tasks, and jobs?
```Answer:- Jobs are comprised of many tasks. AI automates tasks, rather than jobs.```

### Q.3 Here are some of the tasks of a retail salesperson from O*NET. (We encourage you to check out the page yourself.)<br><br> ![image](https://github.com/Bhanupriya-art/INT426-Coursera-Answers/assets/120407422/ec06a622-3370-4db7-a6b0-c26f21855254) <br>Say we decide to use AI to augment (rather than automate) a salesperson's task of recommending merchandise to customers. Which of the following would be an example of this?
```Answer:- Build an AI system to suggest products to the salesperson, who then decides what to recommend to the customer. ```

### Q.4 When looking for augmentation or automation opportunities, what are the two primary criteria by which to evaluate tasks for generative AI potential? (Check the two that apply.) 
```Answer:- Business value (how valuable is it to automate?).```<br>```Technical feasibility (can AI do it?).```

### Q.5 What is a quick way to start experimenting with an LLM application development project?
```Answer:- Try experimenting and prototyping with a web-based LLM to assess feasibility.```

## Week 3: Generative AI and society

### Q.1 Which of the following statements about Reinforcement Learning from Human Feedback (RLHF) are true? 
```Answer:- RLHF helps to align an LLM to human preferences, and can reduce the bias of an LLM’s output.```

### Q.2 True or False. Because AI automates tasks, not jobs, absolutely no jobs will disappear because of AI. 
```Answer:- False```

### Q.3 If we manage to build Artificial General Intelligence (AGI) some day, which tasks should AI be capable of performing? (Check all that apply.)
```Answer:- Compose the music for a movie soundtrack.```<br>```Write a software application to let users manage their household spending budgets.```<br>```Learn to drive a car in roughly 20 hours of practice.```

### Q.4 You are working on a chatbot to serve as a career coach for recent college graduates. Which of the following steps could you take to ensure that your project follows responsible AI? (Check all that apply.)
```Answer:- Engage diverse recent college graduates and ask them to offer feedback on the output of your chatbot.```<br>```Organize a brainstorming session to identify problems that could arise for users chatting with the career coach```<br>```Engage employers (because they are a key stakeholder group) and ask them to offer feedback on the output of your chatbot.```

### Q.5 Now that you’ve made it to the end of the course, which of these statements are true? (Please check all, because all apply!) 
```Answer:- All are correct```
















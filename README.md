# Google-Gen-AI-Leader 

Notes from the reference FreeCodeCamp in the link [link](https://www.youtube.com/watch?v=30diF8dKpAY).

AI -> Machine performs like human behavior.
ML -> Machine get better at a task with no explicit programming..
DL -> Machine has an artificial neural network to solve complex problem inspired by human brain.
Gen AI -> Subset of AI, it generates out content like image, video, text and audio.


## Difference between AI vs Generative AI

### AI
- Perform tasks requiring human intelligence that include: problem solving, understanding natural language, decision-making and recognizing speech annd images.
- The goal is to analyze, interpret, and respond humam actions.
- AI can be applicated in diverse areas like: natural language processing, expert systems, speech recognition, robotics.
- It is used in a lot of industries for tasks like:
  - B2C -> Chatbots for customer service.
  - Ecommerce -> Recommendation systems.
  - Auto: Autonomous vehicles.
  - Medical: Medical diagnosis.

## Gen AI

Subset of AI focused on creating new content or data. It can interpret and analyze data but generates new datta itself.
- It generates text, images, music, speech and others.

Machine learning techniques:
- Transform models like GPT.
- Generating Adversatial Networks (GANs).
- Variational Autoencoders (VAEs).

  Modalities
  - Text -> human-like text.
  - Molecular -> Drug discovery through genomic data.
  - Audio -> music.
  - Vision -> realistic images and videos.
 
LLMs generates human-like text that is a subset of GenAI and often conflating with being AI

AI x Generative AI
Understand and decision-making x Creates new, original outputs (Functionality).
Analyzes and make decisiong through existing data x Uses existing data in order to generate new unseen content (Data Handling).
Spans across diverse sectors, data analysis, NLP, automation and healthcare x Content creation, deepfakes, design, synthetic data generation (Applications).


## NLP 

Natural Language Processing -> Machine learning technique

It understands the context of a body related text

It:
- Interprets and analyzes text inside email messages and documents.
- Contextualises and interprets spoken sentiment analysis.
- Sythesizes speech like voice assistance that talk with a person.
- Translates spoken or writtenn phrases and sentences between laguages.
- Interpret spoken and writtend commands, determines apropriate actions.

Text wrangling and Pre-Processing -> Conversion, sanitiation, tokenization, streamming, lemmatization
Language Understanding (structure/syntax) -> Parts of speech (POS) tagging, chunking, dependencyy parsing, constituency parsing
Processing annd Functionality -> Named entity recognition (NER), n-gram identification, sentiment analysis, information exttraction, information retrieval, question and answering, topic modeling.

## Supervised and Unsupervised learning

### Supervised

- A machine learning task/function that needs a training data, which is provided the labeled data (correct answer) and machine learning learns from the results.
  - Classification
  - Regression

### Unsupervised 

- Task/function does not need a training data, it will take unlabeled data and discover its patterns, applying its own labels.
  - Clusterig
  - Association
  - Dimentionality reduction
 
Supervised learning tends to be more accurate than Unsupervised, but it requires more upfront work. On the other hand, unsupervised requires more human intervention in order to validate the results.

## ML Model

It is an informative representation of an object, person or system. It can be:
- concrete -> physical form (design for vehicle, person posing for a painting)
- abstract -> behavioural patters (mathematical, compute code, written words)

Function which takes data, peforms ML algorithm to produce a prediction, which is trained.

## Feature

Charactheristic extracted from unstructured dataset, it's being prepared to be ingested by ML model to infer prediction
Generally, models only accept numerical data, but data is prepared into a machine-readable format y encoding)

Feature Engineering

- Extract features from provided data sources.

## Inference

Resquest and get a prediction.
- Input model inside a ML model which has been deployed for production use to outputt a prediction.
Examples:

- banana picture -> What is this ML model -> Class: Yellow Banana, Confidence: 0,9%.

## Foundational Model (FM)

- Trained on vast amounts of data. FM is pretrained due to fine tuned for specific tasks.

Data
- Text                                                                                                                         
- Images                                                                                    
- Videos                                                         
- Structured data                                               
- Prediction
- Text Generation
- Classification
- Video Generation
- Audio Generation
- Image Generation
                                                                

LLMs are specialized subset of FMs, they use transformer architecture.

## LLM

- Transformer architecture

<img width="553" height="190" alt="image" src="https://github.com/user-attachments/assets/60eaba60-a1b7-4fd4-ab98-21cb3f12d62a" />


Source: https://www.youtube.com/watch?v=30diF8dKpAY

Training fhase, the model learns semantics (patterns) of language, like: gramar, sentence structure, word usage, style and tone.

## Tokens and Capaticy

Transformer decoder the sequence of tokens back.

Encoder - Decoder

Memory -> Each token requires memory.
Compute -> Model performs more operations for each additional token, which longer senquences require more compute.

## Prompt tuning

LLMs follow parameters like temperature, output token limit, seed, top-p.

- Temperature - control randommness in the output, which low value is more deterministic and low value is more creative.
- Output token limit - Limit the in output response, that low value is shorter responses and it has lower cost. On the other hand, ligh value is longer responses and higher cost.
- Seed - Initializes the model's randon generator
- Top P - Theshold for sample output tokens. Low value is more conservative sampling and high value is more variety (creative).

Recommendation: Run Temperature or Top-P and not both at the same time.

## Zero Shot

Model peforms the expected task with **no prior knowledge or examples*** which is provided during prompting.
Example:

- Classify the text into positive or negative.
  - Text: She is a excellente teacher. She's happy for it.
  -  Sentiment: Positive

## Few Shot

Model peforms the expected task **with examples** in prompts input
  
- Tweet: "I don't like my phone.": Sentiment: Negative
- Tweet: "I love my day, he's great.": Sentiment: Positive
- Tweet: "This is the link to the website": Sentiment: Neutral

Input
- Tweet: " This music is amazing". Sentiment: Positive
Output: Positive

## Prompt Chaining 

**Output of one LLM prompt is used as input for next prompt.**
The context window of the prompt is too small to complete a single large or complex task.

Complex Prompt
- Google Cloud has a GenAI certification, which helps people to gain more knowledge in google tools about Generative AI. This certification is amazing for the professional resume.

Simple prompy
- (Iterative over each line) Translate the text from Spanish to English.
- (List) Give the grocery shopping list.
- (Iterative over list) Provide 5 examples os this grammar rule and explain it.

## Chain-of-Thought (CoT) Prompting

Tell the model to do step-by-step to produces more accurate results.






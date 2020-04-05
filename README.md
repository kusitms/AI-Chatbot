# AI-Chatbot
### 1. Introduction
         그동안 의견 나온 것들!
         특정인의 말투를 따라하는 chatbot 만들기, 혹은 유명인의 말투 따라하기(text), 10대 말투, 아재 말투로 대화하는 챗봇
         
         ++다운) 자료 조사해 보니 대화에서 특정 사실을 추출하는 챗봇 연구도 있더라구요!
### 2. Members
        송형라, 신재욱, 이다빈, 전다운 
### 3. Precedent Research
|Paper Title|Description|Author|
|:---:|:---:|:---:|
|Personazing Dialogue agents: I have a dog, Do you have pets too?|서로 알지 못하는 대화 상대 간 persona dataset을 이용하여 자연스러운 대화 가능|SAIZHENG ZHANG, EMILY DINAN, JACK URBANEK, ARTHUR SZLAM, DOUWE KIELA, JASON WESTON|
|Designing dialogue systems: A mean, grumpy, sarcastic chatbot in the browser|유머러스한 반응을 보이는 딥러닝 대화 시스템에 대한 연구. 관련한 데이터셋에 대해 seq2seq model을 학습시켰고, user간 대화 시 LSTM based encoder decoder model 배포|Suzana Ilić, Reiichiro Nakano, Ivo Hajnal|
|A Personal Conversation Assistant Based on Seq2seq with Word2vec Cognitive Map|WeChat의 대화 기록을 활용해 개인화된 챗봇을 개발하는 방법에 대해 설명함. 단어의 관계를 배우고 저장하는데 word2vect model에 기초한 cognitive map 사용. 그 후 seq2seq를 채택하여 챗봇 설계|Shen Maoyuan, Huang Runhe|     
1.	Feedback-Based Self-Learning in Large-Scale Conversational AI Agents/ Pragaash Ponnusamy, Alireza Roshan Ghias, Chenlei Guo, Ruhi Sarikaya
2.	Learning from Dialogue after Deployment: Feed Yourself, Chatbot!/ Braden Hancock, Antoine Bordes, Pierre-Emmanuel Mazaré, Jason Weston
3.	Sounding Board: A User-Centric and Content-Driven Social Chatbot/ Hao Fang, Hao Cheng, Maarten Sap, Elizabeth Clark, Ari Holtzman, Yejin Choi, Noah A. Smith, Mari Ostendorf



챗봇을 만들기 위해 seq2seq , rnn -> LSTM , word2vec.. 와 관련한 학습이 필요하다는 것을 알았습니다.

### 4. Available Dataset
         한국어 문장과 관련된 dataset : https://lionbridge.ai/datasets/10-best-korean-language-datasets-for-machine-learning/
         Chatscript(규칙기반의 인공지능 개발툴 이용한 챗봇 만들기 - 구체적 챗봇 구현 방법 및 순서 제시되어 있음) : https://exagen.tistory.com/notice/63
         ChatterBot(machine-learning based conversational dialog engine build in Python which makes it possible to generate responses based on collections of known conversations) : https://github.com/gunthercox/ChatterBot/blob/master/README.md
         
         
 chatter bot 이용하여 챗봇 만들기:https://blog.naver.com/naininfo/221565586081
->ChatterBot는 pip 를 사용하여 설치 할 수 있습니다.
(onebook) > pip install chatterbot

(onebook) > pip install --upgrade chatterbot_corpus korean

(onebook) > pip install --upgrade chatterbot

​
한국어 코퍼스 다운:
https://github.com/gunthercox/chatterbot-corpus/tree/master/chatterbot_corpus/data

한국어 질문 답변 데이터셋 코쿼드:https://korquad.github.io/





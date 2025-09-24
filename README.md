# Empowering-CTI-with-AI-in-practice

<img src="https://github.com/fboldewin/Empowering-CTI-with-AI-in-practice/blob/main/Title.PNG" height="272" width="483">

This presentation is the result of my personal learning journey on AI and RAG applications, which I worked on for two weeks in fall 2024.
I was curious to find out how AI can help me to complete tasks faster and more efficiently in cyber threat intelligence analysis.

For this purpose, I developed four use cases.

 1. A simple russian->english translator with Pytorch to analyze the Conti leaks logs, as well as a Deepl translator for comparsion.
     A RAG bot to analyze the content of the Conti leaks.

 2. A CTI chatbot with which a user can interact, e.g. to ask specific questions about threat actors, their TTPs, malware usage etc.
    For the showcase, the freely available threat intelligence articles from the Mandiant blog served as source.

 3. A PDF content summarizer, to get a quick overview what's inside a CTI report.
    For this purpose, the Ollama platform was used, which enables the execution of AI models on local devices.
    As LLM I used the freely available Mistral model (7,2 billion params.)

 4. A PDF IoC-extractor based on an IDP called extract thinker.
    Big thanx to its developer Julio Almeida for fixing several issues in the IDP engine I noticed while building the IoC-extractor.
    In early 2025 I switched to the model Gemini Flash 2.5, as it delivered even better visioning results than its predecessor.

Make sure to also checkout the demo videos for the use cases 1,2 and 4.

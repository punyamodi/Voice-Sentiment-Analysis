# Voice-Sentiment-Analysis

The provided code constitutes a comprehensive audio analysis system designed for applications in telemarketing and the service industry. The system leverages Gradio, a user-friendly interface for machine learning models, to create an interactive and efficient solution. This audio analysis system is capable of extracting valuable insights from spoken language, catering to various aspects of communication in customer service and telemarketing scenarios.

At its core, the system utilizes automatic speech recognition through the Whisper ASR model, allowing it to transcribe spoken audio into textual format. This transcription forms the basis for a multi-faceted analysis that includes sentiment analysis, emotion detection, profanity checking, and summarization.

The sentiment analysis module employs diverse natural language processing techniques, incorporating both TextBlob and VADER sentiment analysis tools. These tools evaluate the polarity and intensity of sentiments within the transcribed text, providing a nuanced understanding of the speaker's emotional tone.

Emotion detection is facilitated through a machine learning model trained for classifying emotions in text. This feature is invaluable for discerning the emotional nuances within spoken language, which is particularly crucial in customer interactions where understanding customer sentiment is paramount.

Profanity checking is integrated using the Better Profanity library, allowing the system to identify and flag instances of profane language in the transcribed text. This ensures a respectful and professional interaction, aligning with the standards of customer service.

Additionally, the system incorporates a summarization component utilizing the Facebook BART model. This feature condenses lengthy transcriptions into concise summaries, enabling quick comprehension of the main points discussed during the conversation.

The entire system is encapsulated in a Gradio interface, making it accessible and user-friendly. The interface allows users to interact with the model using their microphone, providing a seamless experience for real-time audio analysis.

In essence, this audio analysis system serves as a valuable tool for businesses engaged in telemarketing and customer service, enhancing their capabilities to understand and respond effectively to customer needs. Its versatility, accuracy, and ease of use make it a valuable asset for applications where insightful analysis of spoken language is paramount.

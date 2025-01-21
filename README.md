# SpeechAnalytics
A RealTime speech Analytics with Voice to Voice Communication. Websocket,Fastapi,GENAI,TTS,STT.

STT: whisper-large-v3-turbo from Groq
LLM: llama-3.3–70b-versatile from Groq
TTS: tts-1 from OpenAI


 we don’t want to store all the user inputs on disk — which can be inefficient and pose security concerns — we can utilize BytesIO to handle the audio data in memory, making the process more efficient

 we collect the audio bytes from the user, assign a filename to mimic an on-disk file, and send it directly to the Groq API to obtain the transcription
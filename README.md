# lazzy.ai
This repository contains the code files for the Lecture Note Generator
Lazzy is an automatic lecture note generator, which takes in an audio input of class lecture and generates a well written lecture note. \

## Technologies Used
- HTML, CSS, Javascript
- Python, Flask
- HuggingFace Transformers
- OpenAI Whisper API
- Facebook's BART LLM
- ReportLab PDF Toolkit
- 
## Architecture
The simplified architecture of the system is given below. The three major sub processes of the system are:
- Converting the input MP3 Audio File into a Text Transcript 
- Summarising this Transcript
- Converting to Bullet Points.
![seq](https://github.com/yoonus47/lazzy.ai/assets/57011711/0a9d8ceb-63ed-433f-8747-6ea475a857e9)
- In addition, making the PDF available for download

For converting the audio input MP3 file into text, we have utilized OpenAI’s open sourced Whisper model, a state-of-the-art speech recognition system. \
For text summarisation, we have incorporated Facebook’s open sourced BART model. BART, short for Bidirectional and Auto-Regressive Transformers, is renowned for its impressive ability to generate concise and coherent summaries from longer texts. \
The summary generated is thenbroken down and displayed in bullet points for easier accesibility. \
Finally we use Python ReportLab Toolkit to design and generate a professional-looking PDF document that encapsulates the Lecture Notes. \
![Lazzy-Website](https://github.com/yoonus47/lazzy.ai/assets/57011711/837cb1f0-dab6-4109-a3fb-44ce3e12c341) 

---
..

## Demo Screenshots
<img width="1680" alt="Screenshot 2023-06-24 at 4 59 39 PM" src="https://github.com/yoonus47/lazzy.ai/assets/57011711/1f1cafe5-cd9f-464f-8855-1f001b4cecf3">
<img width="1680" alt="Screenshot 2023-06-24 at 4 59 48 PM" src="https://github.com/yoonus47/lazzy.ai/assets/57011711/12c3bb56-3a69-4990-972b-415705347060">
<img width="1680" alt="Screenshot 2023-06-24 at 5 00 00 PM" src="https://github.com/yoonus47/lazzy.ai/assets/57011711/50a54a46-d2ea-4e5b-9642-00cf163b8432">
<img width="1680" alt="Screenshot 2023-06-24 at 5 02 07 PM" src="https://github.com/yoonus47/lazzy.ai/assets/57011711/be928e09-b7ee-4c0c-a635-acad42f28299">
<img width="1680" alt="Screenshot 2023-06-24 at 5 02 29 PM" src="https://github.com/yoonus47/lazzy.ai/assets/57011711/286a242d-695f-4e9e-8a2e-e829df7fd752">

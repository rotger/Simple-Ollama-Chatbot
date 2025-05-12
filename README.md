# Simple Ollama Chatbot
A simple Ollama chatbot that is easy to install and use.

### Instructions
1. Install Ollama.
1. Install your favorite model. For example, you can use the following command to install the qwen3 model: ```ollama pull qwen3```.
1. Set environment variable ```OLLAMA_ORIGINS=*```. On windows, you can set it simply by running this powershell command: ```[Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS","*","User")```.
1. Make sure Ollama is running. Either by doing ```ollama serve``` in a terminal or by opening ollama.exe.
1. Copy the file ```simple_chatbot.html``` to your disk.
1. Open the file ```simple_chatbot.html``` in a web browser.

If you want to modify the chatbot, you can edit the file ```simple_chatbot.html``` in a text editor. The chatbot is written in HTML and JavaScript, so you can easily change the code to suit your needs.
Also, you can copy the code in the chatbot interface and ask your favorite ai model to make it better! In fact, the entire code was created by an AI.

### Support
Support the following features:
- Markdown
- Mathjax
- Code bloc synthax highlighting
- Attaching files (including pdf)
- Attaching images
- Scrape URL content found in the user input and send it to the model
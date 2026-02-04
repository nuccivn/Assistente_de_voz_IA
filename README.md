# 🎙️ Assistente de Voz Inteligente (Gemini + Whisper)

Este projeto é um assistente virtual capaz de ouvir, processar e responder comandos de voz. Desenvolvido no Google Colab, ele utiliza tecnologias de ponta para transcrição e inteligência artificial generativa.

## 🛠️ Como o projeto funciona:
1.  **Captura de Áudio:** Um script em **JavaScript** acessa o microfone pelo navegador.
2.  **Transcrição (STT):** O modelo **Whisper (OpenAI)** converte o áudio gravado em texto.
3.  **Processamento (LLM):** O texto é enviado para a API do **Google Gemini**, que gera uma resposta inteligente.
4.  **Sintetização de Voz (TTS):** A biblioteca **gTTS** transforma o texto da IA em um arquivo de áudio.

## 🚀 Tecnologias Utilizadas
* **Python** (Lógica principal)
* **JavaScript** (Interface de microfone)
* **Google Gemini API** (Cérebro da IA)
* **Whisper** (Reconhecimento de fala)
* **gTTS** (Voz do Google)

## 📋 Como utilizar
1. Abra o arquivo `.ipynb` no Google Colab.
2. Obtenha sua chave de API no [Google AI Studio](https://aistudio.google.com/).
3. Insira sua chave na célula de configuração.
4. Execute as células e fale com seu assistente!

---
✨ *Projeto desenvolvido para fins de estudo em Inteligência Artificial.*

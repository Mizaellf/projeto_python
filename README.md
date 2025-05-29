# projeto_python
Projeto em python de Transcrição por Video por meio de IA


DESCRIÇÃO GERAL

O projeto consiste em uma aplicação web com backend em Flask, que permite aos usuários enviar vídeos, transcrevê-los automaticamente com a biblioteca Whisper da OpenAI, e substituir trechos do áudio com conteúdo gerado via Google Generative AI.
Além disso, o sistema utiliza o FFmpeg para manipulação dos vídeos e audios.



FUNCIONALIDADES PRINCIPAIS

•	Upload de vídeos via interface web.
•	Transcrição automática do áudio do vídeo usando Whisper.
•	Edição automatizada de falas com IA generativa.
•	Substituição e renderização de vídeos com novo áudio com FFmpeg.
•	API com rotas para:
o	/ → Página inicial.
o	/process → Processamento do vídeo via POST.



TECNOLOGIAS UTILIZADAS

•	Python 3.10.9
•	Flask (servidor web)
•	Whisper (OpenAI) (transcrição de áudio)
•	Google Generative AI (geração de texto/áudio)
•	FFmpeg (manipulação de vídeo)
•	validators, dotenv, flask-cors
•	HTML (interface web)



REQUISITOS DO SISTEMA

•	Python 3.10.9
•	Dependências Python listadas em requirements.txt:
o	flask
o	flask-cors
o	python-dotenv
o	openai-whisper
o	google-generativeai
o	validators
•	FFmpeg instalado (incluso na pasta ffmpeg-7.1.1-essentials_build)



ARQUITETURA DO PROJETO

•	Backend em Flask, interface web servida diretamente pelo servidor.
•	Processamento local de vídeos com chamadas para APIs de IA.


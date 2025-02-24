# 🎙️ Discord AI Bot

Um bot do Discord capaz de **ouvir e responder em chamadas de voz**, utilizando inteligência artificial para conversas dinâmicas. O bot integra a **API do Character AI** para interações realistas e a **API do discord-ext** para captura de áudio.

## 🚀 Funcionalidades
- 🎤 **Captura de áudio** em chamadas do Discord
- 🧠 **Responde com IA** utilizando a API do Character AI
- 🔊 **Transforma texto em fala** para interagir com os usuários
- ⚡ **Comandos personalizáveis** para gestão do bot
- 📜 **Salva histórico de conversas** em JSON

## 🛠️ Tecnologias Utilizadas
- **Python**
- **discord.py** + **discord.ext.voice_recv** (para coleta de áudio)
- **Character AI API** (para IA do personagem)
- **speech_recognition** (para transcrição de áudio)
- **pyttsx3** (para conversão de texto em fala)
- **dotenv** (para gerenciamento de credenciais)
- **FFmpeg** (para processamento de áudio)
- **NumPy e SciPy** (para manipulação de áudio)

## 📦 Instalação e Uso
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie um ambiente virtual e instale as dependências:
   ```sh
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Baixe e instale o **FFmpeg**:
   - Baixe o FFmpeg no site oficial: [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)
   - Extraia os arquivos e copie o caminho do diretório `bin`
   - Adicione esse caminho à variável de ambiente `PATH` do sistema
   - Para verificar a instalação, execute:
     ```sh
     ffmpeg -version
     ```

4. Configure o arquivo `.env` com as credenciais:
   ```sh
   DISCORD_TOKEN=seu_token_aqui
   CHAR_TOKEN=sua_chave_character_ai_aqui
   ```

5. Execute o bot:
   ```sh
   python main.py
   ```

## 🤖 Comandos Disponíveis
- `entrai` - Faz o bot entrar na call
- `sai` - Faz o bot sair da call
- **Canais suportados:** `geral` (modificavel)
- O bot processa mensagens de texto e áudio automaticamente

## 🛠️ Contribuição
Sinta-se livre para abrir issues e enviar PRs para melhorias! 😊


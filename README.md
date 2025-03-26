🛠️ Tecnologias Utilizadas
Azure Speech-to-Text → Para converter os áudios em texto.

Git/GitHub → Para versionamento e compartilhamento do projeto.

📌 Como Utilizar
1️⃣ Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/azure-speech-poems.git
cd azure-speech-poems
2️⃣ Certifique-se de ter o SDK do Azure instalado:

bash
Copiar
Editar
pip install azure-cognitiveservices-speech
3️⃣ Execute o script de transcrição (se aplicável):

bash
Copiar
Editar
python script/transcribe.py
4️⃣ Verifique as transcrições geradas na pasta transcriptions/.

📊 Insights Obtidos
📌 Precisão da Transcrição: A tecnologia Azure Speech-to-Text demonstrou uma boa precisão, mas alguns trechos apresentaram pequenos erros devido à dicção e ruídos no áudio.

📌 Ajustes Necessários: Para melhorar os resultados, seria interessante treinar o modelo com mais amostras de voz ou utilizar pós-processamento para correção ortográfica.

📌 Possibilidades Futuras:
✔️ Aplicação em legendagem automática.
✔️ Conversão de palestras e entrevistas para texto.
✔️ Análise de sentimentos baseada em textos transcritos.

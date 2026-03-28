1️⃣ Monitoramento de Faltas de Funcionários
Monitora automaticamente uma aba do Google Sheets.
Detecta atualizações de linhas.
Envia um e-mail automático avisando quando não há faltas registradas no dia.
2️⃣ Classificação de Produtos da API DummyJSON
Busca produtos da API pública DummyJSON.
Divide os itens individualmente com Split Out.
Formata os campos (Nome, Categoria, Preço).
Classifica em:
🟥 Produtos Caros (>= 50)
🟩 Produtos Baratos (< 50)
Envia automaticamente para duas abas diferentes no Google Sheets.
🧠 Funcionalidades Principais

✔️ Integração com API externa (DummyJSON)
✔️ Processamento e transformação de dados
✔️ Lógica condicional com If (Preço >= 50)
✔️ Automação completa de Google Sheets
✔️ Envio automático de e-mails pelo Gmail OAuth2
✔️ Trigger para monitorar updates na planilha
✔️ Workflow contínuo e encadeado

🛠️ Tecnologias Utilizadas
n8n
Google Sheets API
Gmail OAuth2
DummyJSON API
Low-Code / No-Code Automation
📂 Estrutura do Workflow
Google Sheets Trigger ───► Send Email ───► HTTP Request
                                             │
                                             ▼
                                        Split Out
                                             │
                                             ▼
                                        Edit Fields
                                             │
                                             ▼
                                            IF
                           ┌──────────────────┴───────────────────┐
                           ▼                                      ▼
                Append Row (Produtos Caros)        Append Row (Produtos Baratos)

📊 Exemplo de Decisão do IF

Produto:

Nome: IPhone 9
Categoria: smartphones
Preço: 549

Decisão:
👉 Vai para Produtos Caros

▶️ Como Executar
Importe o arquivo .json do workflow no n8n.
Configure suas credenciais:
Google Sheets
Gmail OAuth2
Atualize os IDs das planilhas se necessário.
Clique em Execute Workflow.
Veja:
o e-mail de alerta sendo enviado
os produtos entrando automaticamente nas abas
o fluxo rodando redondinho ⭐
🎯 Objetivo do Projeto

Criar um fluxo completo que demonstra:

domínio de lógica de automação
integração entre plataformas
uso profissional do n8n
organização de dados
experiência real aplicável em empresas

Perfeito para compor portfólio profissional.

📝 Autor

Felipe Yan
Automação | n8n | RPA | Integrações | Sistemas
GitHub: adicione seu link aqui

📊 Automação de Separação de Produtos por Preço (n8n)

Esse workflow faz uma requisição para a API pública DummyJSON, pega os produtos, separa um por um, formata os campos e envia automaticamente para duas abas diferentes de uma planilha do Google Sheets:

Produtos Caros (preço maior que 50)
Produtos Baratos (preço menor ou igual a 50)

É uma automação útil para organização de dados, testes, estudo de APIs e integração entre n8n + Google Sheets.

Funcionalidades
🔄 Trigger manual para executar o workflow
🌐 HTTP Request para buscar produtos (limit = 10)
📦 Split Out para quebrar os itens da API
✏️ Set para deixar só Nome, Categoria e Preço
🧠 IF para separar produtos acima de 50
📑 Append Row automatizado em duas abas diferentes do Google Sheets
Tecnologias usadas
n8n
Google Sheets API
DummyJSON API
No-code/low-code
Workflow Orchestration
Como executar
Importe o arquivo .json no n8n
Conecte sua credencial do Google Sheets
Clique em Execute Workflow
Veja os dados entrando na planilha em tempo real ⭐

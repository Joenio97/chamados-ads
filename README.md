# chamados-ads

# API de Chamados de Suporte

## 1. Estudante
Joenio Borges de Araujo

## 2. Objetivo do Projeto
Criar a estrutura inicial da API de chamados de suporte utilizando Python e Flask, com gerenciamento de ambiente e dependências realizado pelo `uv`.

## 3. Instalação das Dependências
Na raiz do projeto, execute o comando abaixo para instalar as dependências exatamente conforme definidas no arquivo `uv.lock`:

```bash
uv sync --locked
4. Execução da Aplicação
Para executar a aplicação no GitHub Codespaces, utilize o comando:

Bash
uv run flask --app app run --host=0.0.0.0 --port=5000
5. Acesso à Rota Inicial e Resposta Esperada
Com o servidor em execução, acesse a rota GET / pelo navegador (utilizando o endereço gerado na aba Portas para a porta 5000) ou via terminal com:

Bash
curl -i http://localhost:5000/
A resposta esperada deve conter:

Código de status HTTP: 200 OK

Cabeçalho: Content-Type: application/json

Corpo (JSON):

JSON
{
  "mensagem": "API de chamados em funcionamento"
}


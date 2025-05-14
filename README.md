💱 Currency Converter - Conversor de Moedas em Java
Este é um projeto simples de console em Java que permite converter valores entre diferentes moedas utilizando a API pública ExchangeRate-API. O sistema também mantém um histórico das conversões realizadas.

🛠 Tecnologias utilizadas
Java 17+

Biblioteca Gson para desserialização de JSON

API pública ExchangeRate-API

Console (entrada e saída via terminal)

📦 Estrutura do Projeto
bash
Copiar
Editar
currencyconverter/
│
├── app/                    # Classe principal para execução
│   └── CurrencyConverterApp.java
│
├── service/                # Lógica de negócio
│   ├── CurrencyService.java
│   └── ConversionHistory.java
│
├── util/                   # Utilitários
│   └── LoggerUtil.java
│
├── model/                  # Modelos de dados
│   └── ExchageResponse.java
🚀 Como executar


💡 Funcionalidades
Conversão de moedas:

USD ↔ BRL

EUR ↔ BRL

USD ↔ EUR

USD → JPY

BRL → CAD

Histórico de conversões com data e hora

Tratamento de erros simples (API, entrada inválida, moeda não encontrada)

🔐 Observações
A chave de API (API_KEY) está embutida no código para fins educacionais. Em projetos reais, armazene informações sensíveis de forma segura.

Para obter sua própria chave de API gratuita, acesse: https://www.exchangerate-api.com/

📋 Exemplo de uso
python-repl
Copiar
Editar
=== Conversor de Moedas ===
1 - USD para BRL
2 - EUR para BRL
...
Escolha uma opção: 1
Digite o valor a converter: 100
100.00 USD = 508.20 BRL
🧠 Aprendizados
Este projeto tem como objetivo reforçar os seguintes conceitos:

Requisições HTTP em Java

Manipulação de JSON com Gson

Boas práticas de organização de pacotes

Registro de logs e histórico

Interação com o usuário via terminal

👨‍💻 Autor
Kayo Alves
LinkedIn | Estudante de Análise e Desenvolvimento de Sistemas
Atualmente desenvolvendo habilidades em Java, Spring Boot e back-end.

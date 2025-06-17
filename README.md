# Agentes Autônomos – Análise de CSV

Subindo o projeto:

- Necessario uma conta de google;
- Acessar o Colab;
- Fazer import do .ipynb;
- Ter uma chave GROQ_API_KEY; (acessar o portas do <https://groq.com/>)
- Cadastrar essa chave no secret do Colab com o nome GROQ_API
- Executar Run_all

# Testando app;

- baixar o arquivo do assets;
- fazer upload desse modelo;
- Perguntar para a LLM sobre esse arquiv fiscal;

## Exemplo de pergunas :

1. Qual a origem que tem mais itens?
2. Qual o valor total das notas fiscais ?
3. Qual é a origem que mais faturou em notas fiscais?
4. Qual a maior notas fiscais e que itens foram comprados?




RESPOSATAS PARA O TRABALHO:
```text
1. A framework escolhida
- Llamaindex

2. Como a solução foi estruturada
Devido à necessidade de uma solução sem custos, optamos por usar o Google Colab para desenvolver e implantar o aplicativo. Criamos uma página web com Gradio, que permite o deploy direto do Colab.

Funcionalidades do Aplicativo
O aplicativo permite aos usuários carregar arquivos de dados, sejam eles CSV ou ZIP contendo múltiplos CSVs. Uma vez carregados, o aplicativo processa o arquivo e responde às perguntas do usuário.

Tecnologia Utilizada
Para o processamento das perguntas, utilizamos o modelo de linguagem grande (LLM) Llama3-70b-8192 gratuitamente através da API da Groq. Este LLM, integrado a um pipeline de consulta, traduz as perguntas do usuário para código Pandas, executa o código e, em seguida, sintetiza uma resposta compreensível.

3. Pelo menos 4 perguntas com as respectivas respostas.
```text
    1. Qual a origem que tem mais itens?
    2. Qual o valor total das notas fiscais ?
    3. Qual é a origem que mais faturou em notas fiscais?
    4. Qual a maior notas fiscais e que itens foram comprados?
```        

4. Link para a pasta do Github contendo os códigos fonte ou um link para acessar seu agente.
- https://github.com/ge-i2a2-maverick/I2a2

5. Não se esqueçam de ocultar chaves utilizadas nos softwares.
- Chave não expostas
```
